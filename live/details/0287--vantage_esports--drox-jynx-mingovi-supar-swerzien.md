### Roster Details<br />
Team Name: Vantage Esports<br />
Roster: Drox, Jynx, Mingovi, supar, swerzieN<br />
Global Rank: [287](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [39]( ../standings_asia.md)<br />
<br />
Final Rank Value:  658.3<br />
<br />
Final Rank Value (658.3) = Starting Rank Value (651.2) + Head To Head Adjustments (7.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 651.2
- 400 + ( ( 0.126 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 651.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |       49 | 2025-02-25 | Only One Word                    | L   | 1.000      | -            | -                | -                | -         |   -17.44 | Drox, Jynx, Mingovi, supar, swerzieN |
|           17 |       64 | 2025-02-24 | TALON                            | L   | 1.000      | -            | -                | -                | -         |   -18.28 | Drox, Jynx, Mingovi, supar, swerzieN |
|           16 |       95 | 2025-02-23 | Rooster                          | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.220 (0.031)    | 0 (0.000) |    16.35 | Drox, Jynx, Mingovi, supar, swerzieN |
|           15 |      458 | 2025-02-14 | Housebets                        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.122 (0.017)    | 0 (0.000) |    12.68 | Drox, Jynx, Mingovi, supar, swerzieN |
|           14 |      462 | 2025-02-14 | MANTRA                           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.174 (0.025)    | 0 (0.000) |    13.48 | Drox, Jynx, Mingovi, supar, swerzieN |
|           13 |      508 | 2025-02-14 | SemperFi Esports                 | L   | 1.000      | -            | -                | -                | -         |   -15.51 | Drox, Jynx, Mingovi, supar, swerzieN |
|           12 |      512 | 2025-02-13 | CAMO                             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     5.61 | Drox, Jynx, Mingovi, supar, swerzieN |
|           11 |     2040 | 2024-12-08 | Underground Esports Club         | W   | 0.636      | 0.270        | 0.001 (0.000)    | 0.240 (0.041)    | 0 (0.000) |     9.30 | Drox, JiNxZiE, Jynx, Mingovi, supar  |
|           10 |     2294 | 2024-12-03 | Above The Rest (Australian team) | W   | 0.603      | 0.270        | 0.000 (0.000)    | 0.086 (0.014)    | 0 (0.000) |     5.68 | Drox, JiNxZiE, Jynx, Mingovi, supar  |
|            9 |     2370 | 2024-12-02 | Altered Edge                     | W   | 0.596      | 0.270        | 0.000 (0.000)    | 0.027 (0.004)    | 0 (0.000) |     3.95 | Drox, JiNxZiE, Jynx, Mingovi, supar  |
|            8 |     2563 | 2024-11-30 | Larzes Legacy                    | W   | 0.582      | 0.270        | -                | 0.028 (0.004)    | 0 (0.000) |     3.78 | Drox, JiNxZiE, Jynx, Mingovi, supar  |
|            7 |     2829 | 2024-11-23 | Justice For Tomorrow             | L   | 0.542      | -            | -                | -                | -         |    -8.39 | Drox, JiNxZiE, Jynx, Mingovi, supar  |
|            6 |     2929 | 2024-11-22 | Rooster                          | L   | 0.535      | -            | -                | -                | -         |    -7.75 | Drox, JiNxZiE, Jynx, Mingovi, supar  |
|            5 |     2934 | 2024-11-22 | Canon Event                      | W   | 0.534      | 0.264        | 0.000 (0.000)    | -                | 0 (0.000) |     5.23 | Drox, JiNxZiE, Jynx, Mingovi, supar  |
|            4 |     5565 | 2024-10-05 | Only One Word                    | L   | 0.213      | -            | -                | -                | -         |    -3.51 | alecc, Drox, Jynx, Mingovi, supar    |
|            3 |     5646 | 2024-10-04 | MANTRA                           | W   | 0.208      | 0.143        | 0.000 (0.000)    | 0.174 (0.005)    | 0 (0.000) |     2.94 | alecc, Drox, Jynx, Mingovi, supar    |
|            2 |     5649 | 2024-10-04 | SemperFi Esports                 | L   | 0.208      | -            | -                | -                | -         |    -4.18 | alecc, Drox, Jynx, Mingovi, supar    |
|            1 |     5654 | 2024-10-04 | Only One Word                    | W   | 0.207      | 0.143        | 0.001 (0.000)    | 0.190 (0.006)    | -         |     3.09 | alecc, Drox, Jynx, Mingovi, supar    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($995.71)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.636 | $1,400.00      | $889.97         |
| 2024-11-23 |      0.542 | $195.00        | $105.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
