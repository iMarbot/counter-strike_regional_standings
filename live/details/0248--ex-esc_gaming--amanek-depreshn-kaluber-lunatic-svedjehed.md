### Roster Details<br />
Team Name: Ex-ESC Gaming<br />
Roster: AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed<br />
Global Rank: [248](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [172]( ../standings_europe.md)<br />
<br />
Final Rank Value:  680.5<br />
<br />
Final Rank Value (680.5) = Starting Rank Value (650.4) + Head To Head Adjustments (30.1)<br />

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
- 400 + ( ( 0.125 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 650.4


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
|           20 |     2097 | 2024-12-07 | Metizport X                    | W   | 0.631      | 0.143        | 0.001 (0.000)    | 0.218 (0.020)    | 0 (0.000) |     9.43 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           19 |     2229 | 2024-12-04 | BRUTE                          | L   | 0.612      | -            | -                | -                | -         |    -8.78 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           18 |     2327 | 2024-12-02 | BAKS Esports                   | W   | 0.599      | 0.333        | 0.000 (0.000)    | 0.151 (0.030)    | 0 (0.000) |     5.63 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           17 |     2347 | 2024-12-02 | 777 Esports                    | W   | 0.598      | 0.143        | 0.002 (0.000)    | 0.235 (0.020)    | 0 (0.000) |     8.92 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           16 |     2478 | 2024-11-30 | Sissi State Punks              | W   | 0.586      | 0.333        | 0.000 (0.000)    | 0.066 (0.013)    | 0 (0.000) |     7.39 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           15 |     2551 | 2024-11-30 | DEPO                           | L   | 0.583      | -            | -                | -                | -         |    -6.30 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           14 |     2629 | 2024-11-28 | Maestro Esports (Belgian team) | L   | 0.572      | -            | -                | -                | -         |   -12.81 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           13 |     2630 | 2024-11-28 | Impulse GW                     | W   | 0.572      | 0.284        | 0.006 (0.001)    | 0.169 (0.027)    | 0 (0.000) |    10.92 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           12 |     2676 | 2024-11-27 | SAUCEMEN                       | W   | 0.565      | 0.143        | 0.000 (0.000)    | 0.086 (0.007)    | 0 (0.000) |     3.30 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           11 |     3438 | 2024-11-14 | Onyx Ravens                    | W   | 0.479      | 0.284        | 0.019 (0.003)    | 0.156 (0.021)    | 0 (0.000) |     8.07 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|           10 |     3453 | 2024-11-14 | TGD Pro                        | W   | 0.478      | 0.284        | 0.000 (0.000)    | 0.046 (0.006)    | 0 (0.000) |     3.06 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            9 |     5241 | 2024-10-12 | Nexus Gaming                   | L   | 0.257      | -            | -                | -                | -         |    -0.45 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            8 |     5902 | 2024-09-30 | GameAgents                     | L   | 0.179      | -            | -                | -                | -         |    -3.21 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            7 |     5916 | 2024-09-30 | LEON Esports                   | W   | 0.178      | 0.143        | 0.010 (0.000)    | 0.271 (0.007)    | 0 (0.000) |     3.72 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            6 |     5971 | 2024-09-29 | Fire Flux Esports              | L   | 0.171      | -            | -                | -                | -         |    -1.28 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            5 |     6018 | 2024-09-28 | Nuclear TigeRES                | W   | 0.165      | 0.143        | 0.004 (0.000)    | 0.580 (0.014)    | 0 (0.000) |     3.81 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            4 |     6040 | 2024-09-28 | Oshikousei                     | W   | 0.165      | -            | -                | -                | -         |     1.02 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            3 |     6572 | 2024-09-21 | Illuminar Gaming               | L   | 0.119      | -            | -                | -                | -         |    -0.88 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            2 |     6822 | 2024-09-17 | Sampi NEXT                     | L   | 0.092      | -            | -                | -                | -         |    -2.02 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |
|            1 |     6835 | 2024-09-17 | Naaaa                          | W   | 0.092      | -            | -                | -                | -         |     0.57 | AMANEK, DEPRESHN, KalubeR, lunAtic, Svedjehed |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($397.68)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-07 |      0.631 | $396.59        | $250.24         |
| 2024-12-01 |      0.590 | $250.00        | $147.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
