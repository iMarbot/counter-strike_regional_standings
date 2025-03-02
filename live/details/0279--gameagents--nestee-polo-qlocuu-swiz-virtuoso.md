### Roster Details<br />
Team Name: GameAgents<br />
Roster: nestee, POLO, Qlocuu, swiz, virtuoso<br />
Global Rank: [279](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [192]( ../standings_europe.md)<br />
<br />
Final Rank Value:  662.2<br />
<br />
Final Rank Value (662.2) = Starting Rank Value (681.1) + Head To Head Adjustments (-19.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.1
- 400 + ( ( 0.141 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 681.1


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
|           46 |      986 | 2025-02-04 | GardenGarage                              | L   | 1.000      | -            | -                | -                | -         |   -12.21 | nestee, POLO, Qlocuu, swiz, virtuoso |
|           45 |     4441 | 2024-10-28 | ARCRED                                    | L   | 0.372      | -            | -                | -                | -         |    -4.33 | Demho, Prism, Qlocuu, swiz, virtuoso |
|           44 |     4902 | 2024-10-18 | NewBALLS                                  | L   | 0.304      | -            | -                | -                | -         |    -5.08 | Demho, Prism, Qlocuu, swiz, virtuoso |
|           43 |     5068 | 2024-10-15 | Haspers Team                              | L   | 0.286      | -            | -                | -                | -         |    -5.64 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           42 |     5109 | 2024-10-14 | Dynamo Eclot                              | L   | 0.279      | -            | -                | -                | -         |    -0.96 | Demho, Prism, Qlocuu, swiz, virtuoso |
|           41 |     5208 | 2024-10-12 | AgenciUSB                                 | L   | 0.265      | -            | -                | -                | -         |    -6.36 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           40 |     5222 | 2024-10-12 | Haspers Team                              | L   | 0.265      | -            | -                | -                | -         |    -5.37 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           39 |     5261 | 2024-10-11 | Ins (Polish team)                         | L   | 0.259      | -            | -                | -                | -         |    -4.46 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           38 |     5286 | 2024-10-10 | 500 Rush                                  | L   | 0.252      | -            | -                | -                | -         |    -4.62 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           37 |     5421 | 2024-10-08 | ENTERPRISE Genesis                        | L   | 0.239      | -            | -                | -                | -         |    -4.57 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           36 |     5690 | 2024-10-04 | TSM                                       | L   | 0.210      | -            | -                | -                | -         |    -2.91 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           35 |     5730 | 2024-10-03 | Passion UA                                | L   | 0.204      | -            | -                | -                | -         |    -0.94 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           34 |     5764 | 2024-10-02 | Betera Esports                            | W   | 0.200      | 0.500        | 0.006 (0.001)    | 0.299 (0.030)    | 0 (0.000) |     3.35 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           33 |     5842 | 2024-10-01 | Rebels Gaming                             | W   | 0.193      | 0.500        | 0.009 (0.001)    | 0.301 (0.029)    | 0 (0.000) |     3.27 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           32 |     5876 | 2024-10-01 | TSM                                       | W   | 0.191      | 0.371        | 0.009 (0.001)    | -                | 0 (0.000) |     3.41 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           31 |     5899 | 2024-09-30 | MADNESS (Kosovar team)                    | W   | 0.187      | -            | -                | -                | 0 (0.000) |     1.64 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           30 |     5988 | 2024-09-29 | ALTERNATE aTTaX                           | W   | 0.177      | 0.371        | 0.021 (0.001)    | 0.564 (0.037)    | 0 (0.000) |     4.38 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           29 |     6053 | 2024-09-28 | 9z Team                                   | L   | 0.172      | -            | -                | -                | -         |    -2.11 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           28 |     6113 | 2024-09-27 | OG                                        | W   | 0.166      | 0.143        | 0.062 (0.001)    | 1.000 (0.024)    | 0 (0.000) |     3.99 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           27 |     6141 | 2024-09-27 | SAW                                       | L   | 0.165      | -            | -                | -                | -         |    -0.14 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           26 |     6151 | 2024-09-27 | ALASKA                                    | W   | 0.164      | 0.371        | 0.030 (0.002)    | 0.875 (0.053)    | 0 (0.000) |     4.80 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           25 |     6191 | 2024-09-26 | ARCRED                                    | W   | 0.160      | -            | -                | -                | 0 (0.000) |     2.98 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           24 |     6197 | 2024-09-26 | Tricked Esport                            | W   | 0.159      | 0.143        | 0.033 (0.001)    | 0.696 (0.016)    | 0 (0.000) |     3.48 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           23 |     6223 | 2024-09-26 | Preasy Esport                             | L   | 0.158      | -            | -                | -                | -         |    -1.71 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           22 |     6273 | 2024-09-25 | ADEPTS                                    | W   | 0.154      | -            | -                | -                | 0 (0.000) |     2.30 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           21 |     6360 | 2024-09-24 | Dark Cloud Esports                        | L   | 0.147      | -            | -                | -                | -         |    -1.44 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           20 |     6375 | 2024-09-24 | Monte                                     | L   | 0.146      | -            | -                | -                | -         |    -1.34 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           19 |     6387 | 2024-09-24 | Kubix Esports                             | L   | 0.146      | -            | -                | -                | -         |    -0.95 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           18 |     6441 | 2024-09-23 | Illuminar Gaming                          | W   | 0.140      | -            | -                | -                | -         |     3.21 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           17 |     6454 | 2024-09-23 | AgenciUSB                                 | W   | 0.140      | -            | -                | -                | -         |     1.07 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           16 |     6484 | 2024-09-23 | Johnny Speeds                             | L   | 0.138      | -            | -                | -                | -         |    -1.02 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           15 |     6535 | 2024-09-22 | Ex-9INE Academy                           | L   | 0.130      | -            | -                | -                | -         |    -2.57 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           14 |     6716 | 2024-09-19 | ALASKA                                    | W   | 0.110      | 0.371        | 0.030 (0.001)    | 0.875 (0.036)    | -         |     3.25 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           13 |     6907 | 2024-09-16 | Natus Vincere Junior                      | L   | 0.090      | -            | -                | -                | -         |    -0.51 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           12 |     6957 | 2024-09-15 | Astralis Talent                           | W   | 0.084      | 0.333        | -                | 0.733 (0.020)    | -         |     1.66 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           11 |     7047 | 2024-09-14 | ENCE Academy                              | W   | 0.077      | 0.333        | -                | 0.655 (0.017)    | -         |     1.64 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|           10 |     7089 | 2024-09-13 | Natus Vincere Junior                      | L   | 0.072      | -            | -                | -                | -         |    -0.41 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            9 |     7098 | 2024-09-13 | UNiTY esports                             | W   | 0.071      | 0.333        | 0.025 (0.001)    | -                | -         |     1.57 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            8 |     7142 | 2024-09-12 | Natus Vincere Junior                      | L   | 0.065      | -            | -                | -                | -         |    -0.36 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            7 |     7167 | 2024-09-11 | Haspers Team                              | W   | 0.060      | -            | -                | -                | -         |     0.71 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            6 |     7195 | 2024-09-11 | JiJieHao                                  | W   | 0.058      | -            | -                | -                | -         |     0.80 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            5 |     7231 | 2024-09-10 | WiLD MultiGaming                          | W   | 0.053      | -            | -                | -                | -         |     0.67 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            4 |     7265 | 2024-09-10 | Copenhagen Wolves (American organization) | W   | 0.050      | -            | -                | -                | -         |     0.48 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            3 |     7314 | 2024-09-09 | Preasy Esport                             | W   | 0.044      | -            | -                | -                | -         |     0.94 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            2 |     7322 | 2024-09-09 | ALASKA                                    | W   | 0.044      | 0.333        | 0.030 (0.000)    | 0.875 (0.013)    | -         |     1.29 | POLO, Prism, Qlocuu, swiz, virtuoso  |
|            1 |     7579 | 2024-09-05 | Team Space                                | W   | 0.020      | -            | -                | -                | -         |     0.16 | POLO, Prism, Qlocuu, swiz, virtuoso  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,066.67)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.319 | $1,000.00      | $318.89         |
| 2024-10-05 |      0.217 | $3,000.00      | $650.83         |
| 2024-09-17 |      0.097 | $1,000.00      | $96.94          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
