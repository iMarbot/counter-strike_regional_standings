### Roster Details<br />
Team Name: GameAgents<br />
Roster: nestee, POLO, Qlocuu, swiz, virtuoso<br />
Global Rank: [285](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [192]( ../standings_europe.md)<br />
<br />
Final Rank Value:  659.3<br />
<br />
Final Rank Value (659.3) = Starting Rank Value (679.4) + Head To Head Adjustments (-20.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.4
- 400 + ( ( 0.140 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 679.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      998 | 2025-02-04 | GardenGarage                              | L   | 1.000      | -            | -                | -                | -         |   -12.10 | nestee, POLO, Qlocuu, swiz, virtuoso |
|           45 |     4453 | 2024-10-28 | ARCRED                                    | L   | 0.364      | -            | -                | -                | -         |    -4.20 | Demho, Prism, Qlocuu, swiz, virtuoso |
|           44 |     4914 | 2024-10-18 | NewBALLS                                  | L   | 0.296      | -            | -                | -                | -         |    -4.90 | Demho, Prism, Qlocuu, swiz, virtuoso |
|           43 |     5080 | 2024-10-15 | Haspers Team                              | L   | 0.278      | -            | -                | -                | -         |    -5.47 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           42 |     5121 | 2024-10-14 | Dynamo Eclot                              | L   | 0.270      | -            | -                | -                | -         |    -0.92 | Demho, Prism, Qlocuu, swiz, virtuoso |
|           41 |     5220 | 2024-10-12 | AgenciUSB                                 | L   | 0.257      | -            | -                | -                | -         |    -6.14 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           40 |     5233 | 2024-10-12 | Haspers Team                              | L   | 0.257      | -            | -                | -                | -         |    -5.19 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           39 |     5273 | 2024-10-11 | Ins (Polish team)                         | L   | 0.251      | -            | -                | -                | -         |    -4.28 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           38 |     5298 | 2024-10-10 | 500 Rush                                  | L   | 0.244      | -            | -                | -                | -         |    -4.44 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           37 |     5433 | 2024-10-08 | ENTERPRISE Genesis                        | L   | 0.231      | -            | -                | -                | -         |    -4.36 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           36 |     5702 | 2024-10-04 | TSM                                       | L   | 0.202      | -            | -                | -                | -         |    -2.78 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           35 |     5742 | 2024-10-03 | Passion UA                                | L   | 0.196      | -            | -                | -                | -         |    -0.89 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           34 |     5776 | 2024-10-02 | Betera Esports                            | W   | 0.192      | 0.500        | 0.006 (0.001)    | 0.295 (0.028)    | 0 (0.000) |     3.24 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           33 |     5854 | 2024-10-01 | Rebels Gaming                             | W   | 0.185      | 0.500        | 0.009 (0.001)    | 0.298 (0.028)    | 0 (0.000) |     3.15 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           32 |     5888 | 2024-10-01 | TSM                                       | W   | 0.183      | 0.371        | 0.009 (0.001)    | -                | 0 (0.000) |     3.28 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           31 |     5911 | 2024-09-30 | MADNESS (Kosovar team)                    | W   | 0.178      | -            | -                | -                | 0 (0.000) |     1.60 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           30 |     6000 | 2024-09-29 | ALTERNATE aTTaX                           | W   | 0.169      | 0.371        | 0.021 (0.001)    | 0.552 (0.035)    | 0 (0.000) |     4.18 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           29 |     6065 | 2024-09-28 | 9z Team                                   | L   | 0.164      | -            | -                | -                | -         |    -2.01 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           28 |     6125 | 2024-09-27 | OG                                        | W   | 0.158      | 0.143        | 0.062 (0.001)    | 1.000 (0.023)    | 0 (0.000) |     3.81 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           27 |     6153 | 2024-09-27 | SAW                                       | L   | 0.157      | -            | -                | -                | -         |    -0.13 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           26 |     6163 | 2024-09-27 | ALASKA                                    | W   | 0.156      | 0.371        | 0.031 (0.002)    | 0.867 (0.050)    | 0 (0.000) |     4.57 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           25 |     6203 | 2024-09-26 | ARCRED                                    | W   | 0.151      | 0.143        | 0.018 (0.000)    | -                | 0 (0.000) |     2.84 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           24 |     6209 | 2024-09-26 | Tricked Esport                            | W   | 0.151      | 0.143        | 0.034 (0.001)    | 0.687 (0.015)    | 0 (0.000) |     3.31 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           23 |     6235 | 2024-09-26 | Preasy Esport                             | L   | 0.149      | -            | -                | -                | -         |    -1.61 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           22 |     6285 | 2024-09-25 | ADEPTS                                    | W   | 0.145      | -            | -                | -                | 0 (0.000) |     1.68 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           21 |     6372 | 2024-09-24 | Dark Cloud Esports                        | L   | 0.138      | -            | -                | -                | -         |    -1.34 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           20 |     6388 | 2024-09-24 | Monte                                     | L   | 0.138      | -            | -                | -                | -         |    -1.26 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           19 |     6399 | 2024-09-24 | Kubix Esports                             | L   | 0.138      | -            | -                | -                | -         |    -0.89 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           18 |     6453 | 2024-09-23 | Illuminar Gaming                          | W   | 0.132      | 0.143        | -                | 0.581 (0.011)    | -         |     3.02 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           17 |     6466 | 2024-09-23 | AgenciUSB                                 | W   | 0.132      | -            | -                | -                | -         |     1.02 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           16 |     6496 | 2024-09-23 | Johnny Speeds                             | L   | 0.130      | -            | -                | -                | -         |    -0.96 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           15 |     6547 | 2024-09-22 | Ex-9INE Academy                           | L   | 0.122      | -            | -                | -                | -         |    -2.40 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           14 |     6728 | 2024-09-19 | ALASKA                                    | W   | 0.102      | 0.371        | 0.031 (0.001)    | 0.867 (0.033)    | -         |     3.01 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           13 |     6919 | 2024-09-16 | Natus Vincere Junior                      | L   | 0.082      | -            | -                | -                | -         |    -0.46 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           12 |     6969 | 2024-09-15 | Astralis Talent                           | W   | 0.075      | 0.333        | -                | 0.724 (0.018)    | -         |     1.50 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           11 |     7059 | 2024-09-14 | ENCE Academy                              | W   | 0.069      | 0.333        | -                | 0.649 (0.015)    | -         |     1.47 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           10 |     7101 | 2024-09-13 | Natus Vincere Junior                      | L   | 0.064      | -            | -                | -                | -         |    -0.36 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            9 |     7110 | 2024-09-13 | UNiTY esports                             | W   | 0.063      | 0.333        | 0.025 (0.001)    | -                | -         |     1.39 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            8 |     7154 | 2024-09-12 | Natus Vincere Junior                      | L   | 0.057      | -            | -                | -                | -         |    -0.32 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            7 |     7179 | 2024-09-11 | Haspers Team                              | W   | 0.052      | -            | -                | -                | -         |     0.62 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            6 |     7207 | 2024-09-11 | JiJieHao                                  | W   | 0.050      | -            | -                | -                | -         |     0.70 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            5 |     7243 | 2024-09-10 | WiLD MultiGaming                          | W   | 0.045      | -            | -                | -                | -         |     0.57 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            4 |     7277 | 2024-09-10 | Copenhagen Wolves (American organization) | W   | 0.042      | -            | -                | -                | -         |     0.40 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            3 |     7326 | 2024-09-09 | Preasy Esport                             | W   | 0.036      | -            | -                | -                | -         |     0.77 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            2 |     7334 | 2024-09-09 | ALASKA                                    | W   | 0.035      | -            | -                | -                | -         |     1.05 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            1 |     7591 | 2024-09-05 | Team Space                                | W   | 0.012      | -            | -                | -                | -         |     0.09 | POLO, Prism, Qlocuu, swiz, virtuoso  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,025.69)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.311 | $1,000.00      | $310.69         |
| 2024-10-05 |      0.209 | $3,000.00      | $626.25         |
| 2024-09-17 |      0.089 | $1,000.00      | $88.75          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
