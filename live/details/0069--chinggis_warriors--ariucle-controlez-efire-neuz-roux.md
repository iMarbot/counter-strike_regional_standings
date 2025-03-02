### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: ariucle, controlez, efire, NEUZ, ROUX<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  896.8<br />
<br />
Final Rank Value (896.8) = Starting Rank Value (932.3) + Head To Head Adjustments (-35.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.358[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.382[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 932.3
- 400 + ( ( 0.266 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 932.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       29 | 2025-02-26 | HOTU                          | W   | 1.000      | 0.143        | -                | 0.777 (0.111)    | -         |    11.71 | ariucle, controlez, efire, NEUZ, ROUX   |
|           54 |       42 | 2025-02-25 | The Huns Esports              | W   | 1.000      | 0.143        | 0.025 (0.004)    | 0.557 (0.080)    | -         |    16.96 | ariucle, controlez, efire, NEUZ, ROUX   |
|           53 |       63 | 2025-02-24 | The QUBE Esports              | W   | 1.000      | -            | -                | -                | -         |     2.01 | ariucle, controlez, efire, NEUZ, ROUX   |
|           52 |      541 | 2025-02-11 | The Huns Esports              | L   | 1.000      | -            | -                | -                | -         |   -14.68 | ariucle, controlez, efire, NEUZ, ROUX   |
|           51 |      603 | 2025-02-09 | Eruption                      | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.552 (0.079)    | -         |    17.44 | ariucle, controlez, efire, NEUZ, ROUX   |
|           50 |      605 | 2025-02-09 | Believe.                      | W   | 1.000      | 0.143        | -                | 0.187 (0.027)    | -         |     4.83 | ariucle, controlez, efire, NEUZ, ROUX   |
|           49 |      646 | 2025-02-08 | Mindfreak (Australian team)   | W   | 1.000      | -            | -                | -                | -         |     8.60 | ariucle, controlez, efire, NEUZ, ROUX   |
|           48 |      796 | 2025-02-07 | Nomads (Mongolian team)       | L   | 1.000      | -            | -                | -                | -         |   -27.18 | ariucle, controlez, efire, NEUZ, ROUX   |
|           47 |      808 | 2025-02-06 | Eruption                      | L   | 1.000      | -            | -                | -                | -         |   -14.71 | ariucle, controlez, efire, NEUZ, ROUX   |
|           46 |     1316 | 2024-12-27 | ATOX Esports                  | L   | 0.777      | -            | -                | -                | -         |    -5.88 | ariucle, controlez, efire, NEUZ, ROUX   |
|           45 |     1341 | 2024-12-26 | The Huns Esports              | L   | 0.770      | -            | -                | -                | -         |   -13.81 | ariucle, controlez, efire, NEUZ, ROUX   |
|           44 |     1355 | 2024-12-25 | Eruption                      | W   | 0.758      | 0.143        | 0.014 (0.002)    | 0.552 (0.060)    | 1 (0.758) |    10.47 | ariucle, controlez, efire, NEUZ, ROUX   |
|           43 |     1358 | 2024-12-24 | The QUBE Esports              | W   | 0.756      | -            | -                | -                | 1 (0.756) |     2.78 | ariucle, controlez, efire, NEUZ, ROUX   |
|           42 |     1368 | 2024-12-23 | Eruption                      | W   | 0.750      | 0.143        | 0.014 (0.001)    | 0.552 (0.059)    | -         |    10.65 | ariucle, controlez, efire, NEUZ, ROUX   |
|           41 |     1370 | 2024-12-23 | Nomads (Mongolian team)       | W   | 0.749      | 0.143        | -                | 0.407 (0.044)    | -         |     2.81 | ariucle, controlez, efire, NEUZ, ROUX   |
|           40 |     2133 | 2024-12-06 | ATOX Esports                  | L   | 0.632      | -            | -                | -                | -         |    -4.60 | ariucle, controlez, efire, NEUZ, ROUX   |
|           39 |     2137 | 2024-12-06 | IHC Esports                   | W   | 0.631      | 0.333        | -                | 0.248 (0.052)    | -         |     5.90 | ariucle, controlez, efire, NEUZ, ROUX   |
|           38 |     2168 | 2024-12-05 | Harizma                       | L   | 0.625      | -            | -                | -                | -         |   -13.04 | ariucle, controlez, efire, NEUZ, ROUX   |
|           37 |     2171 | 2024-12-05 | Ex-GR Gaming                  | W   | 0.624      | 0.333        | 0.011 (0.002)    | -                | -         |     4.83 | ariucle, controlez, efire, NEUZ, ROUX   |
|           36 |     2182 | 2024-12-04 | Harizma                       | L   | 0.624      | -            | -                | -                | -         |   -13.35 | ariucle, controlez, efire, NEUZ, ROUX   |
|           35 |     2362 | 2024-12-02 | Nomads (Mongolian team)       | W   | 0.604      | 0.143        | -                | 0.407 (0.035)    | -         |     2.20 | ariucle, controlez, efire, NEUZ, ROUX   |
|           34 |     2368 | 2024-12-01 | SUBUTAI                       | W   | 0.604      | -            | -                | -                | -         |     1.99 | ariucle, controlez, efire, NEUZ, ROUX   |
|           33 |     2373 | 2024-12-01 | The Huns Esports              | W   | 0.603      | 0.143        | 0.025 (0.002)    | 0.557 (0.048)    | -         |     9.49 | ariucle, controlez, efire, NEUZ, ROUX   |
|           32 |     3131 | 2024-11-20 | CatEvil                       | L   | 0.524      | -            | -                | -                | -         |   -13.15 | ariucle, controlez, efire, NEUZ, ROUX   |
|           31 |     3133 | 2024-11-19 | ATOX Esports                  | L   | 0.523      | -            | -                | -                | -         |    -4.12 | ariucle, controlez, efire, NEUZ, ROUX   |
|           30 |     3812 | 2024-11-07 | Ex-GR Gaming                  | L   | 0.444      | -            | -                | -                | -         |   -10.47 | ariucle, controlez, me1o, NEUZ, Tugu    |
|           29 |     3855 | 2024-11-07 | DEWA United                   | W   | 0.438      | -            | -                | -                | -         |     1.68 | ariucle, controlez, me1o, NEUZ, Tugu    |
|           28 |     3959 | 2024-11-05 | NOVA Esports (Mongolian team) | W   | 0.424      | -            | -                | -                | -         |     0.74 | ariucle, controlez, me1o, NEUZ, Tugu    |
|           27 |     3962 | 2024-11-04 | Ex-GR Gaming                  | L   | 0.423      | -            | -                | -                | -         |   -10.31 | ariucle, controlez, me1o, NEUZ, Tugu    |
|           26 |     4634 | 2024-10-24 | Clutch Gaming                 | W   | 0.344      | -            | -                | -                | -         |     1.20 | ariucle, controlez, fury5k, me1o, NEUZ  |
|           25 |     4636 | 2024-10-23 | The Huns Esports              | L   | 0.343      | -            | -                | -                | -         |    -5.44 | ariucle, controlez, fury5k, me1o, NEUZ  |
|           24 |     4638 | 2024-10-23 | The QUBE Esports              | W   | 0.343      | -            | -                | -                | -         |     0.51 | ariucle, controlez, fury5k, me1o, NEUZ  |
|           23 |     4901 | 2024-10-18 | Unsettled Resentment          | L   | 0.305      | -            | -                | -                | -         |    -7.23 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           22 |     4909 | 2024-10-17 | ATOX Esports                  | W   | 0.303      | 0.333        | 0.008 (0.001)    | -                | 1 (0.303) |     2.24 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           21 |     5015 | 2024-10-16 | Ex-GR Gaming                  | W   | 0.291      | 0.417        | 0.011 (0.001)    | -                | -         |     1.99 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           20 |     5022 | 2024-10-16 | ATOX Esports                  | W   | 0.291      | -            | -                | -                | 1 (0.291) |     2.12 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           19 |     5074 | 2024-10-15 | ATOX Esports                  | L   | 0.285      | -            | -                | -                | -         |    -7.00 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           18 |     5082 | 2024-10-15 | Clutch Gaming                 | W   | 0.284      | -            | -                | -                | 1 (0.284) |     0.93 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           17 |     5349 | 2024-10-09 | -72C                          | W   | 0.245      | -            | -                | -                | -         |     0.72 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           16 |     5355 | 2024-10-09 | -72C                          | W   | 0.245      | -            | -                | -                | -         |     0.73 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           15 |     5429 | 2024-10-08 | DEWA United                   | W   | 0.238      | -            | -                | -                | -         |     0.71 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           14 |     5435 | 2024-10-08 | DEWA United                   | W   | 0.238      | -            | -                | -                | -         |     0.72 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           13 |     5691 | 2024-10-03 | ATOX Esports                  | L   | 0.210      | -            | -                | -                | -         |    -1.91 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           12 |     5733 | 2024-10-03 | The Huns Esports              | W   | 0.204      | -            | -                | -                | 1 (0.204) |     3.26 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           11 |     5740 | 2024-10-02 | The QUBE Esports              | W   | 0.203      | -            | -                | -                | 1 (0.203) |     0.89 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           10 |     5783 | 2024-10-02 | Ex-GR Gaming                  | W   | 0.198      | 0.417        | 0.011 (0.001)    | -                | -         |     1.35 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            9 |     5788 | 2024-10-02 | Ex-GR Gaming                  | W   | 0.198      | 0.417        | 0.011 (0.001)    | -                | -         |     1.37 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            8 |     5858 | 2024-10-01 | Lynn Vision Gaming            | L   | 0.192      | -            | -                | -                | -         |    -3.63 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            7 |     5864 | 2024-10-01 | Lynn Vision Gaming            | L   | 0.191      | -            | -                | -                | -         |    -3.69 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            6 |     6149 | 2024-09-27 | Chinggis Warriors             | W   | 0.164      | -            | -                | -                | 1 (0.164) |     0.82 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            5 |     6162 | 2024-09-26 | The Huns Esports              | W   | 0.163      | -            | -                | -                | 1 (0.163) |     2.68 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            4 |     6315 | 2024-09-25 | Chinggis Warriors             | W   | 0.151      | -            | -                | -                | 1 (0.151) |     0.77 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            3 |     6331 | 2024-09-24 | Nomads (Mongolian team)       | W   | 0.150      | -            | -                | -                | -         |     0.23 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            2 |     6396 | 2024-09-24 | KENLA Gaming                  | W   | 0.145      | -            | -                | -                | -         |     0.22 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            1 |     6403 | 2024-09-24 | KENLA Gaming                  | W   | 0.145      | -            | -                | -                | -         |     0.22 | AccuracyTG, ariucle, efire, ROUX, Zesta |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,458.73)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.784 | $1,000.00      | $784.03         |
| 2024-12-06 |      0.632 | $2,500.00      | $1,580.21       |
| 2024-11-03 |      0.411 | $2,000.00      | $821.57         |
| 2024-10-17 |      0.303 | $7,500.00      | $2,272.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
