### Roster Details<br />
Team Name: Heimo Esports<br />
Roster: arvid, japE, oopee, Welho, ykis<br />
Global Rank: [170](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [125]( ../standings_europe.md)<br />
<br />
Final Rank Value:  737.5<br />
<br />
Final Rank Value (737.5) = Starting Rank Value (746.8) + Head To Head Adjustments (-9.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.282[<sup>2</sup>](#table1)
- Opponent Network: 0.115[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 746.8
- 400 + ( ( 0.174 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 746.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           62 |      201 | 2025-02-21 | JANO Esports                              | L   | 1.000      | -            | -                | -                | -         |   -14.33 | arvid, japE, oopee, Welho, ykis   |
|           61 |      286 | 2025-02-17 | HAVU                                      | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.378 (0.054)    | 0 (0.000) |    14.43 | arvid, japE, oopee, Welho, ykis   |
|           60 |      510 | 2025-02-13 | ENCE Academy                              | L   | 1.000      | -            | -                | -                | -         |   -12.64 | arvid, japE, oopee, Welho, ykis   |
|           59 |      640 | 2025-02-09 | Ex-UHKA eSports                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.18 | arvid, japE, oopee, Welho, ykis   |
|           58 |      762 | 2025-02-07 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |    -9.01 | arvid, japE, oopee, Welho, ykis   |
|           57 |     1032 | 2025-02-02 | SAUCEMEN                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.60 | arvid, japE, oopee, Welho, ykis   |
|           56 |     1066 | 2025-02-01 | JANO Esports                              | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.442 (0.063)    | 0 (0.000) |    19.09 | arvid, japE, oopee, Welho, ykis   |
|           55 |     1128 | 2025-01-26 | FCottoNd                                  | W   | 0.971      | -            | -                | -                | 0 (0.000) |     4.87 | arvid, japE, oopee, Welho, ykis   |
|           54 |     1133 | 2025-01-25 | Smuuttikusilkki                           | W   | 0.965      | -            | -                | -                | 0 (0.000) |     6.77 | arvid, japE, oopee, Welho, ykis   |
|           53 |     1168 | 2025-01-17 | Smuuttikusilkki                           | W   | 0.914      | -            | -                | -                | 0 (0.000) |     6.11 | arvid, japE, oopee, Welho, ykis   |
|           52 |     1171 | 2025-01-17 | Myllysuola                                | W   | 0.913      | -            | -                | -                | 0 (0.000) |     4.29 | arvid, japE, oopee, Welho, ykis   |
|           51 |     1224 | 2025-01-04 | BRUTE                                     | L   | 0.825      | -            | -                | -                | -         |   -13.35 | arvid, japE, oopee, spargo, Welho |
|           50 |     1247 | 2024-12-29 | Insilio                                   | L   | 0.787      | -            | -                | -                | -         |   -13.81 | arvid, japE, oopee, spargo, Welho |
|           49 |     1379 | 2024-12-23 | WOPA Esport                               | L   | 0.744      | -            | -                | -                | -         |    -7.68 | arvid, japE, oopee, spargo, Welho |
|           48 |     1408 | 2024-12-22 | ALASKA                                    | L   | 0.738      | -            | -                | -                | -         |    -6.69 | arvid, japE, oopee, spargo, Welho |
|           47 |     1517 | 2024-12-20 | WOPA Esport                               | W   | 0.725      | 0.333        | 0.031 (0.008)    | 0.785 (0.190)    | 0 (0.000) |    14.28 | arvid, japE, oopee, spargo, Welho |
|           46 |     1561 | 2024-12-18 | Astralis Talent                           | W   | 0.711      | 0.333        | 0.002 (0.001)    | 0.733 (0.174)    | 0 (0.000) |    12.72 | arvid, japE, oopee, spargo, Welho |
|           45 |     1592 | 2024-12-16 | ADEPTS                                    | L   | 0.698      | -            | -                | -                | -         |   -13.19 | arvid, japE, oopee, spargo, Welho |
|           44 |     1777 | 2024-12-13 | Dark Cloud Esports                        | W   | 0.680      | 0.333        | 0.038 (0.009)    | 0.828 (0.188)    | -         |    13.52 | arvid, japE, oopee, spargo, Welho |
|           43 |     1802 | 2024-12-13 | Mission Possible                          | W   | 0.678      | 0.333        | -                | 0.295 (0.067)    | -         |     5.97 | arvid, japE, oopee, spargo, Welho |
|           42 |     1949 | 2024-12-09 | Copenhagen Wolves (American organization) | W   | 0.653      | 0.333        | 0.016 (0.003)    | 1.000 (0.218)    | -         |    14.71 | arvid, japE, oopee, spargo, Welho |
|           41 |     1958 | 2024-12-09 | ADEPTS                                    | L   | 0.652      | -            | -                | -                | -         |   -11.19 | arvid, japE, oopee, spargo, Welho |
|           40 |     2803 | 2024-11-24 | Dark Cloud Esports                        | L   | 0.551      | -            | -                | -                | -         |    -5.52 | arvid, japE, oopee, spargo, Welho |
|           39 |     3090 | 2024-11-20 | Daystar                                   | L   | 0.527      | -            | -                | -                | -         |   -10.77 | arvid, japE, oopee, spargo, Welho |
|           38 |     3190 | 2024-11-18 | Ex-Soul's Heart Esport                    | W   | 0.514      | -            | -                | -                | -         |     5.87 | arvid, japE, oopee, spargo, Welho |
|           37 |     3277 | 2024-11-17 | Endpoint                                  | L   | 0.504      | -            | -                | -                | -         |    -6.85 | arvid, japE, oopee, spargo, Welho |
|           36 |     3513 | 2024-11-13 | Viperio                                   | L   | 0.478      | -            | -                | -                | -         |    -7.50 | arvid, japE, spargo, Welho, xartE |
|           35 |     3811 | 2024-11-08 | Astralis Talent                           | L   | 0.444      | -            | -                | -                | -         |    -6.67 | japE, m0n0xx, oopee, Welho, xartE |
|           34 |     3848 | 2024-11-07 | GenOne                                    | L   | 0.439      | -            | -                | -                | -         |    -5.26 | arvid, japE, oopee, spargo, Welho |
|           33 |     3870 | 2024-11-06 | KONO.ECF                                  | L   | 0.434      | -            | -                | -                | -         |    -4.04 | arvid, japE, oopee, spargo, Welho |
|           32 |     3939 | 2024-11-05 | Nexus Gaming                              | L   | 0.426      | -            | -                | -                | -         |    -1.75 | arvid, japE, oopee, spargo, Welho |
|           31 |     3958 | 2024-11-05 | Viperio                                   | L   | 0.424      | -            | -                | -                | -         |    -7.09 | arvid, japE, oopee, spargo, Welho |
|           30 |     3995 | 2024-11-04 | FAVBET Team                               | L   | 0.420      | -            | -                | -                | -         |    -4.93 | arvid, japE, oopee, spargo, Welho |
|           29 |     4214 | 2024-11-01 | ADEPTS                                    | W   | 0.398      | -            | -                | -                | -         |     4.76 | arvid, japE, m0n0xx, oopee, Welho |
|           28 |     4364 | 2024-10-29 | 1win                                      | L   | 0.380      | -            | -                | -                | -         |    -6.42 | arvid, japE, oopee, spargo, Welho |
|           27 |     4421 | 2024-10-28 | Ex-9INE Academy                           | W   | 0.373      | -            | -                | -                | -         |     3.18 | arvid, japE, oopee, spargo, Welho |
|           26 |     4620 | 2024-10-24 | Viperio                                   | W   | 0.346      | 0.372        | 0.002 (0.000)    | 0.411 (0.053)    | -         |     5.04 | arvid, japE, oopee, spargo, Welho |
|           25 |     4623 | 2024-10-24 | Lausanne-Sport Esports                    | W   | 0.346      | -            | -                | -                | -         |     2.67 | arvid, japE, oopee, spargo, Welho |
|           24 |     4717 | 2024-10-22 | ALASKA                                    | W   | 0.330      | 0.333        | 0.030 (0.003)    | 0.875 (0.096)    | -         |     9.15 | arvid, japE, oopee, spargo, Welho |
|           23 |     4821 | 2024-10-20 | Natus Vincere Junior                      | L   | 0.317      | -            | -                | -                | -         |    -2.12 | arvid, japE, oopee, spargo, Welho |
|           22 |     4860 | 2024-10-19 | Lilmix                                    | W   | 0.311      | -            | -                | -                | -         |     3.56 | arvid, japE, oopee, spargo, Welho |
|           21 |     4955 | 2024-10-17 | Anonymo Esports                           | L   | 0.297      | -            | -                | -                | -         |    -7.15 | arvid, japE, oopee, spargo, Welho |
|           20 |     5064 | 2024-10-15 | GODSENT                                   | W   | 0.286      | -            | -                | -                | -         |     3.48 | arvid, japE, oopee, spargo, Welho |
|           19 |     5084 | 2024-10-15 | KONO.ECF                                  | L   | 0.284      | -            | -                | -                | -         |    -2.58 | arvid, japE, oopee, spargo, Welho |
|           18 |     5160 | 2024-10-13 | Lilmix                                    | W   | 0.270      | -            | -                | -                | -         |     3.06 | arvid, japE, oopee, spargo, Welho |
|           17 |     5220 | 2024-10-12 | Ex-9INE Academy                           | W   | 0.265      | -            | -                | -                | -         |     2.50 | arvid, japE, oopee, spargo, Welho |
|           16 |     5371 | 2024-10-09 | KONO.ECF                                  | L   | 0.244      | -            | -                | -                | -         |    -2.21 | arvid, japE, oopee, spargo, Welho |
|           15 |     5513 | 2024-10-06 | JANO Esports                              | L   | 0.226      | -            | -                | -                | -         |    -2.01 | arvid, japE, oopee, Welho, ykis   |
|           14 |     5539 | 2024-10-06 | Cspojat                                   | W   | 0.224      | -            | -                | -                | -         |     1.33 | arvid, japE, oopee, spargo, Welho |
|           13 |     5547 | 2024-10-06 | Natus Vincere Junior                      | L   | 0.224      | -            | -                | -                | -         |    -1.63 | arvid, japE, oopee, spargo, Welho |
|           12 |     5590 | 2024-10-05 | ENCE Academy                              | L   | 0.219      | -            | -                | -                | -         |    -2.87 | arvid, japE, oopee, spargo, Welho |
|           11 |     5627 | 2024-10-05 | Preasy Esport                             | W   | 0.217      | 0.333        | 0.012 (0.001)    | 0.710 (0.051)    | -         |     3.92 | arvid, japE, oopee, spargo, Welho |
|           10 |     5736 | 2024-10-03 | Anonymo Esports                           | W   | 0.204      | -            | -                | -                | -         |     1.44 | arvid, japE, oopee, Welho, ykis   |
|            9 |     5873 | 2024-10-01 | Leo Team                                  | L   | 0.191      | -            | -                | -                | -         |    -2.28 | arvid, japE, oopee, Welho, ykis   |
|            8 |     5972 | 2024-09-29 | SIUUUUUU                                  | W   | 0.178      | -            | -                | -                | -         |     0.70 | arvid, japE, oopee, Welho, ykis   |
|            7 |     6215 | 2024-09-26 | Ex-9INE Academy                           | W   | 0.158      | -            | -                | -                | -         |     1.53 | arvid, japE, oopee, Welho, ykis   |
|            6 |     6467 | 2024-09-23 | Cspojat                                   | W   | 0.139      | -            | -                | -                | -         |     0.81 | arvid, japE, oopee, Welho, ykis   |
|            5 |     6528 | 2024-09-22 | Preasy Esport                             | W   | 0.131      | 0.333        | 0.012 (0.001)    | -                | -         |     2.42 | arvid, japE, oopee, Welho, ykis   |
|            4 |     6951 | 2024-09-15 | JANO Esports                              | L   | 0.084      | -            | -                | -                | -         |    -0.73 | arvid, japE, oopee, Welho, ykis   |
|            3 |     7293 | 2024-09-09 | KUUSAMO.gg                                | W   | 0.046      | -            | -                | -                | -         |     0.31 | arvid, japE, oopee, Welho, ykis   |
|            2 |     7445 | 2024-09-07 | Team Spirit Academy                       | L   | 0.032      | -            | -                | -                | -         |    -0.28 | arvid, japE, oopee, Welho, ykis   |
|            1 |     7752 | 2024-09-03 | Copenhagen Wolves (American organization) | L   | 0.004      | -            | -                | -                | -         |    -0.10 | arvid, japE, oopee, Welho, ykis   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,446.80)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $523.23        | $523.23         |
| 2024-12-24 |      0.751 | $1,000.00      | $750.83         |
| 2024-10-20 |      0.318 | $543.71        | $172.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
