### Roster Details<br />
Team Name: NEVERMORE (Ukrainian team)<br />
Roster: D0nii, hodix, jackast, MUV, neiter<br />
Global Rank: [110](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
<br />
Final Rank Value:  836.3<br />
<br />
Final Rank Value (836.3) = Starting Rank Value (759.4) + Head To Head Adjustments (76.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.090[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 759.4
- 400 + ( ( 0.180 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 759.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |      595 | 2025-02-10 | Zero Tenacity                             | L   | 1.000      | -            | -                | -                | -         |   -14.52 | D0nii, hodix, jackast, MUV, neiter |
|           41 |      603 | 2025-02-10 | 3DMAX                                     | L   | 1.000      | -            | -                | -                | -         |    -0.56 | D0nii, hodix, jackast, MUV, neiter |
|           40 |      677 | 2025-02-08 | Little Red Door                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.89 | D0nii, hodix, jackast, MUV, neiter |
|           39 |      689 | 2025-02-08 | ToxicAndCritic                            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.74 | D0nii, hodix, jackast, MUV, neiter |
|           38 |      709 | 2025-02-08 | Dynamo Eclot                              | W   | 1.000      | 0.143        | 0.128 (0.018)    | 0.692 (0.099)    | 0 (0.000) |    23.90 | D0nii, hodix, jackast, MUV, neiter |
|           37 |      772 | 2025-02-07 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.143        | 0.016 (0.002)    | 1.000 (0.143)    | 0 (0.000) |    19.87 | D0nii, hodix, jackast, MUV, neiter |
|           36 |     1289 | 2024-12-28 | Copenhagen Wolves (American organization) | L   | 0.772      | -            | -                | -                | -         |    -8.74 | D0nii, hodix, jackast, MUV, neiter |
|           35 |     1301 | 2024-12-28 | Copenhagen Wolves (American organization) | L   | 0.771      | -            | -                | -                | -         |    -9.31 | D0nii, hodix, jackast, MUV, neiter |
|           34 |     1316 | 2024-12-28 | 0to100                                    | W   | 0.770      | 0.303        | 0.007 (0.002)    | 0.174 (0.041)    | 0 (0.000) |    11.37 | D0nii, hodix, jackast, MUV, neiter |
|           33 |     1341 | 2024-12-27 | ALASKA                                    | W   | 0.764      | 0.333        | 0.031 (0.008)    | 0.867 (0.221)    | 0 (0.000) |    16.15 | D0nii, hodix, jackast, MUV, neiter |
|           32 |     1372 | 2024-12-24 | Infinite Gaming                           | W   | 0.744      | -            | -                | -                | 0 (0.000) |     4.04 | D0nii, hodix, jackast, MUV, neiter |
|           31 |     1384 | 2024-12-23 | ROYALS                                    | W   | 0.738      | 0.333        | 0.004 (0.001)    | 0.200 (0.049)    | 0 (0.000) |     8.17 | D0nii, hodix, jackast, MUV, neiter |
|           30 |     1405 | 2024-12-22 | Doge Soldiers                             | W   | 0.731      | -            | -                | -                | 0 (0.000) |     4.30 | D0nii, hodix, jackast, MUV, neiter |
|           29 |     1406 | 2024-12-22 | Infinite Gaming                           | L   | 0.731      | -            | -                | -                | -         |   -19.11 | D0nii, hodix, jackast, MUV, neiter |
|           28 |     1421 | 2024-12-22 | Belfast Storm                             | W   | 0.730      | -            | -                | -                | 0 (0.000) |     9.51 | D0nii, hodix, jackast, MUV, neiter |
|           27 |     1426 | 2024-12-22 | Preasy Esport                             | L   | 0.730      | -            | -                | -                | -         |   -13.24 | D0nii, hodix, jackast, MUV, neiter |
|           26 |     1458 | 2024-12-21 | C.S.D.E                                   | L   | 0.725      | -            | -                | -                | -         |   -15.27 | D0nii, hodix, jackast, MUV, neiter |
|           25 |     1463 | 2024-12-21 | WildHunt                                  | W   | 0.724      | -            | -                | -                | -         |     2.17 | D0nii, hodix, jackast, MUV, neiter |
|           24 |     1467 | 2024-12-21 | Dragon Esports Club                       | L   | 0.724      | -            | -                | -                | -         |   -15.86 | D0nii, hodix, jackast, MUV, neiter |
|           23 |     1485 | 2024-12-21 | C.S.D.E                                   | W   | 0.723      | -            | -                | -                | -         |     6.72 | D0nii, hodix, jackast, MUV, neiter |
|           22 |     1504 | 2024-12-20 | BadGuys                                   | L   | 0.719      | -            | -                | -                | -         |   -17.16 | D0nii, hodix, jackast, MUV, neiter |
|           21 |     1508 | 2024-12-20 | Rejected by all                           | W   | 0.719      | -            | -                | -                | -         |     1.89 | D0nii, hodix, jackast, MUV, neiter |
|           20 |     1543 | 2024-12-19 | SkyFury                                   | L   | 0.712      | -            | -                | -                | -         |   -16.40 | D0nii, hodix, jackast, MUV, neiter |
|           19 |     1776 | 2024-12-13 | Ex-GODSENT                                | W   | 0.672      | -            | -                | -                | -         |     3.56 | D0nii, hodix, jackast, MUV, neiter |
|           18 |     1783 | 2024-12-13 | P0RTUGAL                                  | W   | 0.672      | 0.143        | 0.038 (0.004)    | -                | -         |    10.11 | D0nii, hodix, jackast, MUV, neiter |
|           17 |     1787 | 2024-12-13 | FORZE Reload                              | W   | 0.672      | 0.143        | 0.026 (0.003)    | 0.552 (0.053)    | -         |    12.57 | D0nii, hodix, jackast, MUV, neiter |
|           16 |     1792 | 2024-12-13 | UNiTY esports                             | W   | 0.672      | 0.143        | 0.025 (0.002)    | 0.403 (0.039)    | -         |    11.05 | D0nii, hodix, jackast, MUV, neiter |
|           15 |     1883 | 2024-12-11 | AMKAL ESPORTS                             | L   | 0.659      | -            | -                | -                | -         |    -9.64 | D0nii, hodix, jackast, MUV, neiter |
|           14 |     1934 | 2024-12-10 | BRUTE                                     | W   | 0.652      | 0.333        | 0.004 (0.001)    | 0.341 (0.074)    | -         |     7.82 | D0nii, hodix, jackast, MUV, neiter |
|           13 |     1988 | 2024-12-08 | SINNERS Academy                           | W   | 0.639      | -            | -                | -                | -         |     7.66 | D0nii, hodix, jackast, MUV, neiter |
|           12 |     2131 | 2024-12-06 | GardenGarage                              | W   | 0.626      | 0.333        | -                | 0.408 (0.085)    | -         |     8.18 | D0nii, hodix, jackast, MUV, neiter |
|           11 |     2215 | 2024-12-04 | ENTERPRISE Genesis                        | W   | 0.612      | -            | -                | -                | -         |     6.33 | D0nii, hodix, jackast, MUV, neiter |
|           10 |     2277 | 2024-12-03 | Chroma                                    | W   | 0.605      | 0.303        | 0.005 (0.001)    | -                | -         |     7.39 | D0nii, hodix, jackast, MUV, neiter |
|            9 |     2338 | 2024-12-02 | MYSKILL                                   | W   | 0.599      | -            | -                | -                | -         |     7.10 | D0nii, hodix, jackast, MUV, neiter |
|            8 |     2362 | 2024-12-02 | ROYALS                                    | W   | 0.597      | -            | -                | -                | -         |     7.59 | D0nii, hodix, jackast, MUV, neiter |
|            7 |     2522 | 2024-11-30 | DAViNCi ESPORTS                           | W   | 0.585      | -            | -                | -                | -         |     2.02 | D0nii, hodix, jackast, MUV, neiter |
|            6 |     2609 | 2024-11-29 | Chroma                                    | W   | 0.577      | -            | -                | -                | -         |     7.28 | D0nii, hodix, jackast, MUV, neiter |
|            5 |     2627 | 2024-11-28 | XI Esport                                 | L   | 0.572      | -            | -                | -                | -         |   -10.96 | D0nii, hodix, jackast, MUV, neiter |
|            4 |     2684 | 2024-11-27 | Metizport X                               | W   | 0.564      | -            | -                | -                | -         |     6.27 | D0nii, hodix, jackast, MUV, neiter |
|            3 |     2802 | 2024-11-24 | HOTU                                      | L   | 0.544      | -            | -                | -                | -         |    -9.45 | D0nii, hodix, jackast, MUV, neiter |
|            2 |     2845 | 2024-11-23 | AMKAL ESPORTS                             | W   | 0.539      | 0.262        | -                | 0.674 (0.095)    | -         |     9.46 | D0nii, hodix, jackast, MUV, neiter |
|            1 |     2853 | 2024-11-23 | Ex-DOSKI                                  | W   | 0.539      | -            | -                | -                | -         |     2.01 | D0nii, hodix, jackast, MUV, neiter |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,288.65)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.771 | $1,500.00      | $1,157.19       |
| 2024-12-22 |      0.731 | $119.70        | $87.54          |
| 2024-12-15 |      0.684 | $600.00        | $410.42         |
| 2024-12-03 |      0.605 | $2,700.00      | $1,633.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
