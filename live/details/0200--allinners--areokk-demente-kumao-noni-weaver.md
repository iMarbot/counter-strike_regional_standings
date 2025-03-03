### Roster Details<br />
Team Name: ALLINNERS<br />
Roster: areokk, demente, kumao, noni, weaveR<br />
Global Rank: [200](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [143]( ../standings_europe.md)<br />
<br />
Final Rank Value:  711.5<br />
<br />
Final Rank Value (711.5) = Starting Rank Value (702.9) + Head To Head Adjustments (8.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.078[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 702.9
- 400 + ( ( 0.151 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 702.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     1274 | 2024-12-29 | Temp                            | L   | 0.776      | -            | -                | -                | -         |   -14.84 | areokk, demente, kumao, noni, weaveR  |
|           14 |     1740 | 2024-12-13 | Mix52                           | L   | 0.675      | -            | -                | -                | -         |    -9.98 | areokk, demente, kumao, noni, weaveR  |
|           13 |     1819 | 2024-12-13 | AimAssassins                    | L   | 0.669      | -            | -                | -                | -         |    -4.98 | areokk, demente, kumao, noni, weaveR  |
|           12 |     1826 | 2024-12-12 | Blaze (Uzbek team)              | W   | 0.668      | 0.333        | 0.005 (0.001)    | 0.069 (0.015)    | 1 (0.668) |    10.38 | areokk, demente, kumao, noni, weaveR  |
|           11 |     2415 | 2024-12-01 | Team Novaq                      | W   | 0.592      | 0.143        | 0.030 (0.003)    | 0.393 (0.033)    | 0 (0.000) |    16.84 | areokk, demente, kumao, noni, weaveR  |
|           10 |     2439 | 2024-12-01 | AK BARS                         | W   | 0.591      | 0.143        | 0.008 (0.001)    | 0.209 (0.018)    | 0 (0.000) |    12.38 | areokk, demente, kumao, noni, weaveR  |
|            9 |     2494 | 2024-11-30 | Cerberus eSports (Russian team) | L   | 0.586      | -            | -                | -                | -         |   -12.45 | Areokk, demente, kumao, Noni, weaveR  |
|            8 |     2635 | 2024-11-28 | Metizport X                     | L   | 0.572      | -            | -                | -                | -         |   -10.45 | Areokk, demente, kumao, Noni, weaveR  |
|            7 |     3274 | 2024-11-17 | DEPO                            | L   | 0.497      | -            | -                | -                | -         |    -7.08 | areokk, noni, plushax, tasman, weaveR |
|            6 |     3295 | 2024-11-17 | MYSKILL                         | L   | 0.496      | -            | -                | -                | -         |    -9.14 | areokk, noni, plushax, tasman, weaveR |
|            5 |     3350 | 2024-11-16 | Yamato Esports                  | W   | 0.490      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     3.42 | areokk, noni, plushax, tasman, weaveR |
|            4 |     3729 | 2024-11-09 | AK BARS                         | W   | 0.445      | 0.143        | 0.008 (0.001)    | 0.209 (0.013)    | 0 (0.000) |     9.06 | areokk, demente, noni, rinn, weaveR   |
|            3 |     3807 | 2024-11-08 | AK BARS                         | W   | 0.438      | 0.143        | 0.008 (0.001)    | 0.209 (0.013)    | 0 (0.000) |     9.14 | areokk, demente, noni, rinn, weaveR   |
|            2 |     3898 | 2024-11-06 | DEPO                            | W   | 0.425      | 0.143        | 0.006 (0.000)    | 0.291 (0.018)    | 0 (0.000) |     7.75 | areokk, demente, noni, rinn, weaveR   |
|            1 |     4075 | 2024-11-03 | RAGE (Kazakh team)              | W   | 0.404      | 0.143        | 0.005 (0.000)    | 0.179 (0.010)    | 0 (0.000) |     8.53 | areokk, demente, noni, rinn, weaveR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($823.57)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-17 |      0.497 | $100.31        | $49.89          |
| 2024-11-09 |      0.445 | $1,740.06      | $773.68         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
