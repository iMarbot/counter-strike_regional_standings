### Roster Details<br />
Team Name: Ex-ESC Gaming<br />
Roster: AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed<br />
Global Rank: [243](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [172]( ../standings_europe.md)<br />
<br />
Final Rank Value:  681.0<br />
<br />
Final Rank Value (681.0) = Starting Rank Value (650.4) + Head To Head Adjustments (30.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.255[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 650.4
- 400 + ( ( 0.125 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 650.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     2085 | 2024-12-07 | Metizport X                    | W   | 0.639      | 0.143        | 0.001 (0.000)    | 0.221 (0.020)    | 0 (0.000) |     9.55 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           19 |     2217 | 2024-12-04 | BRUTE                          | L   | 0.620      | -            | -                | -                | -         |    -8.90 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           18 |     2315 | 2024-12-02 | BAKS Esports                   | W   | 0.607      | 0.333        | 0.000 (0.000)    | 0.153 (0.031)    | 0 (0.000) |     5.71 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           17 |     2335 | 2024-12-02 | 777 Esports                    | W   | 0.606      | 0.143        | 0.002 (0.000)    | 0.239 (0.021)    | 0 (0.000) |     9.09 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           16 |     2466 | 2024-11-30 | Sissi State Punks              | W   | 0.594      | 0.333        | 0.000 (0.000)    | 0.068 (0.013)    | 0 (0.000) |     7.49 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           15 |     2539 | 2024-11-30 | DEPO                           | L   | 0.592      | -            | -                | -                | -         |    -6.33 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           14 |     2617 | 2024-11-28 | Maestro Esports (Belgian team) | L   | 0.580      | -            | -                | -                | -         |   -12.99 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           13 |     2618 | 2024-11-28 | Impulse GW                     | W   | 0.580      | 0.284        | 0.006 (0.001)    | 0.172 (0.028)    | 0 (0.000) |    11.07 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           12 |     2664 | 2024-11-27 | SAUCEMEN                       | W   | 0.573      | 0.143        | 0.000 (0.000)    | 0.087 (0.007)    | 0 (0.000) |     3.35 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           11 |     3426 | 2024-11-14 | Onyx Ravens                    | W   | 0.487      | 0.284        | 0.018 (0.003)    | 0.158 (0.022)    | 0 (0.000) |     8.19 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           10 |     3441 | 2024-11-14 | TGD Pro                        | W   | 0.486      | 0.284        | 0.000 (0.000)    | 0.047 (0.006)    | 0 (0.000) |     3.12 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            9 |     5229 | 2024-10-12 | Nexus Gaming                   | L   | 0.265      | -            | -                | -                | -         |    -0.47 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            8 |     5890 | 2024-09-30 | GameAgents                     | L   | 0.187      | -            | -                | -                | -         |    -3.35 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            7 |     5904 | 2024-09-30 | LEON Esports                   | W   | 0.187      | 0.143        | 0.010 (0.000)    | 0.275 (0.007)    | 0 (0.000) |     3.89 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            6 |     5959 | 2024-09-29 | Fire Flux Esports              | L   | 0.179      | -            | -                | -                | -         |    -1.33 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            5 |     6006 | 2024-09-28 | Nuclear TigeRES                | W   | 0.173      | 0.143        | 0.004 (0.000)    | 0.586 (0.015)    | 0 (0.000) |     3.99 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            4 |     6028 | 2024-09-28 | Oshikousei                     | W   | 0.173      | -            | -                | -                | -         |     1.08 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            3 |     6560 | 2024-09-21 | Illuminar Gaming               | L   | 0.127      | -            | -                | -                | -         |    -0.93 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            2 |     6810 | 2024-09-17 | Sampi NEXT                     | L   | 0.100      | -            | -                | -                | -         |    -2.20 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            1 |     6823 | 2024-09-17 | Naaaa                          | W   | 0.100      | -            | -                | -                | -         |     0.62 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($402.97)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-07 |      0.639 | $396.59        | $253.49         |
| 2024-12-01 |      0.598 | $250.00        | $149.48         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
