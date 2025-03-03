### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: ariucle, controlez, efire, NEUZ, ROUX<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  895.2<br />
<br />
Final Rank Value (895.2) = Starting Rank Value (928.5) + Head To Head Adjustments (-33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.374[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 928.5
- 400 + ( ( 0.264 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 928.5


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
|           55 |       44 | 2025-02-26 | HOTU                          | W   | 1.000      | 0.143        | -                | 0.768 (0.110)    | -         |    11.74 | ariucle, controlez, efire, NEUZ, ROUX   |
|           54 |       57 | 2025-02-25 | The Huns Esports              | W   | 1.000      | 0.143        | 0.025 (0.004)    | 0.553 (0.079)    | -         |    17.01 | ariucle, controlez, efire, NEUZ, ROUX   |
|           53 |       78 | 2025-02-24 | The QUBE Esports              | W   | 1.000      | -            | -                | -                | -         |     2.03 | ariucle, controlez, efire, NEUZ, ROUX   |
|           52 |      553 | 2025-02-11 | The Huns Esports              | L   | 1.000      | -            | -                | -                | -         |   -14.62 | ariucle, controlez, efire, NEUZ, ROUX   |
|           51 |      615 | 2025-02-09 | Eruption                      | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.551 (0.079)    | -         |    17.51 | ariucle, controlez, efire, NEUZ, ROUX   |
|           50 |      617 | 2025-02-09 | Believe.                      | W   | 1.000      | 0.143        | -                | 0.188 (0.027)    | -         |     4.87 | ariucle, controlez, efire, NEUZ, ROUX   |
|           49 |      658 | 2025-02-08 | Mindfreak (Australian team)   | W   | 1.000      | -            | -                | -                | -         |     8.64 | ariucle, controlez, efire, NEUZ, ROUX   |
|           48 |      808 | 2025-02-07 | Nomads (Mongolian team)       | L   | 1.000      | -            | -                | -                | -         |   -27.13 | ariucle, controlez, efire, NEUZ, ROUX   |
|           47 |      820 | 2025-02-06 | Eruption                      | L   | 1.000      | -            | -                | -                | -         |   -14.63 | ariucle, controlez, efire, NEUZ, ROUX   |
|           46 |     1328 | 2024-12-27 | ATOX Esports                  | L   | 0.769      | -            | -                | -                | -         |    -5.85 | ariucle, controlez, efire, NEUZ, ROUX   |
|           45 |     1353 | 2024-12-26 | The Huns Esports              | L   | 0.762      | -            | -                | -                | -         |   -13.60 | ariucle, controlez, efire, NEUZ, ROUX   |
|           44 |     1367 | 2024-12-25 | Eruption                      | W   | 0.750      | 0.143        | 0.014 (0.002)    | 0.551 (0.059)    | 1 (0.750) |    10.45 | ariucle, controlez, efire, NEUZ, ROUX   |
|           43 |     1370 | 2024-12-24 | The QUBE Esports              | W   | 0.748      | -            | -                | -                | 1 (0.748) |     2.77 | ariucle, controlez, efire, NEUZ, ROUX   |
|           42 |     1380 | 2024-12-23 | Eruption                      | W   | 0.742      | 0.143        | 0.014 (0.001)    | 0.551 (0.058)    | -         |    10.63 | ariucle, controlez, efire, NEUZ, ROUX   |
|           41 |     1382 | 2024-12-23 | Nomads (Mongolian team)       | W   | 0.741      | 0.143        | -                | 0.407 (0.043)    | -         |     2.81 | ariucle, controlez, efire, NEUZ, ROUX   |
|           40 |     2145 | 2024-12-06 | ATOX Esports                  | L   | 0.624      | -            | -                | -                | -         |    -4.56 | ariucle, controlez, efire, NEUZ, ROUX   |
|           39 |     2149 | 2024-12-06 | IHC Esports                   | W   | 0.623      | 0.333        | -                | 0.247 (0.051)    | -         |     5.87 | ariucle, controlez, efire, NEUZ, ROUX   |
|           38 |     2180 | 2024-12-05 | Harizma                       | L   | 0.617      | -            | -                | -                | -         |   -12.86 | ariucle, controlez, efire, NEUZ, ROUX   |
|           37 |     2183 | 2024-12-05 | Ex-GR Gaming                  | W   | 0.616      | 0.333        | 0.012 (0.002)    | -                | -         |     4.81 | ariucle, controlez, efire, NEUZ, ROUX   |
|           36 |     2194 | 2024-12-04 | Harizma                       | L   | 0.615      | -            | -                | -                | -         |   -13.15 | ariucle, controlez, efire, NEUZ, ROUX   |
|           35 |     2374 | 2024-12-02 | Nomads (Mongolian team)       | W   | 0.596      | 0.143        | -                | 0.407 (0.035)    | -         |     2.20 | ariucle, controlez, efire, NEUZ, ROUX   |
|           34 |     2380 | 2024-12-01 | SUBUTAI                       | W   | 0.595      | -            | -                | -                | -         |     1.99 | ariucle, controlez, efire, NEUZ, ROUX   |
|           33 |     2385 | 2024-12-01 | The Huns Esports              | W   | 0.595      | 0.143        | 0.025 (0.002)    | 0.553 (0.047)    | -         |     9.42 | ariucle, controlez, efire, NEUZ, ROUX   |
|           32 |     3143 | 2024-11-20 | CatEvil                       | L   | 0.516      | -            | -                | -                | -         |   -12.92 | ariucle, controlez, efire, NEUZ, ROUX   |
|           31 |     3145 | 2024-11-19 | ATOX Esports                  | L   | 0.515      | -            | -                | -                | -         |    -4.07 | ariucle, controlez, efire, NEUZ, ROUX   |
|           30 |     3824 | 2024-11-07 | Ex-GR Gaming                  | L   | 0.436      | -            | -                | -                | -         |   -10.24 | ariucle, controlez, me1o, NEUZ, Tugu    |
|           29 |     3867 | 2024-11-07 | DEWA United                   | W   | 0.429      | -            | -                | -                | -         |     1.66 | ariucle, controlez, me1o, NEUZ, Tugu    |
|           28 |     3971 | 2024-11-05 | NOVA Esports (Mongolian team) | W   | 0.416      | -            | -                | -                | -         |     0.73 | ariucle, controlez, me1o, NEUZ, Tugu    |
|           27 |     3974 | 2024-11-04 | Ex-GR Gaming                  | L   | 0.415      | -            | -                | -                | -         |   -10.07 | ariucle, controlez, me1o, NEUZ, Tugu    |
|           26 |     4646 | 2024-10-24 | Clutch Gaming                 | W   | 0.335      | -            | -                | -                | -         |     1.18 | ariucle, controlez, fury5k, me1o, NEUZ  |
|           25 |     4648 | 2024-10-23 | The Huns Esports              | L   | 0.335      | -            | -                | -                | -         |    -5.28 | ariucle, controlez, fury5k, me1o, NEUZ  |
|           24 |     4650 | 2024-10-23 | The QUBE Esports              | W   | 0.335      | -            | -                | -                | -         |     0.51 | ariucle, controlez, fury5k, me1o, NEUZ  |
|           23 |     4913 | 2024-10-18 | Unsettled Resentment          | L   | 0.297      | -            | -                | -                | -         |    -7.00 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           22 |     4921 | 2024-10-17 | ATOX Esports                  | W   | 0.295      | 0.333        | 0.008 (0.001)    | -                | 1 (0.295) |     2.20 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           21 |     5027 | 2024-10-16 | Ex-GR Gaming                  | W   | 0.283      | 0.417        | 0.012 (0.001)    | -                | -         |     1.97 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           20 |     5034 | 2024-10-16 | ATOX Esports                  | W   | 0.282      | -            | -                | -                | 1 (0.282) |     2.08 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           19 |     5086 | 2024-10-15 | ATOX Esports                  | L   | 0.277      | -            | -                | -                | -         |    -6.77 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           18 |     5094 | 2024-10-15 | Clutch Gaming                 | W   | 0.276      | -            | -                | -                | 1 (0.276) |     0.92 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           17 |     5361 | 2024-10-09 | -72C                          | W   | 0.237      | -            | -                | -                | -         |     0.71 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           16 |     5367 | 2024-10-09 | -72C                          | W   | 0.237      | -            | -                | -                | -         |     0.72 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           15 |     5441 | 2024-10-08 | DEWA United                   | W   | 0.230      | -            | -                | -                | -         |     0.70 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           14 |     5447 | 2024-10-08 | DEWA United                   | W   | 0.230      | -            | -                | -                | -         |     0.70 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           13 |     5703 | 2024-10-03 | ATOX Esports                  | L   | 0.202      | -            | -                | -                | -         |    -1.83 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           12 |     5745 | 2024-10-03 | The Huns Esports              | W   | 0.196      | -            | -                | -                | 1 (0.196) |     3.15 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           11 |     5752 | 2024-10-02 | The QUBE Esports              | W   | 0.194      | -            | -                | -                | 1 (0.194) |     0.87 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|           10 |     5795 | 2024-10-02 | Ex-GR Gaming                  | W   | 0.190      | 0.417        | 0.012 (0.001)    | -                | -         |     1.32 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            9 |     5800 | 2024-10-02 | Ex-GR Gaming                  | W   | 0.190      | 0.417        | 0.012 (0.001)    | -                | -         |     1.33 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            8 |     5870 | 2024-10-01 | Lynn Vision Gaming            | L   | 0.183      | -            | -                | -                | -         |    -3.46 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            7 |     5876 | 2024-10-01 | Lynn Vision Gaming            | L   | 0.183      | -            | -                | -                | -         |    -3.51 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            6 |     6161 | 2024-09-27 | Chinggis Warriors             | W   | 0.156      | -            | -                | -                | 1 (0.156) |     0.78 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            5 |     6174 | 2024-09-26 | The Huns Esports              | W   | 0.154      | -            | -                | -                | 1 (0.154) |     2.55 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            4 |     6327 | 2024-09-25 | Chinggis Warriors             | W   | 0.143      | -            | -                | -                | 1 (0.143) |     0.73 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            3 |     6343 | 2024-09-24 | Nomads (Mongolian team)       | W   | 0.142      | -            | -                | -                | -         |     0.22 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            2 |     6408 | 2024-09-24 | KENLA Gaming                  | W   | 0.137      | -            | -                | -                | -         |     0.21 | AccuracyTG, ariucle, efire, ROUX, Zesta |
|            1 |     6415 | 2024-09-24 | KENLA Gaming                  | W   | 0.137      | -            | -                | -                | -         |     0.21 | AccuracyTG, ariucle, efire, ROUX, Zesta |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,352.20)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.776 | $1,000.00      | $775.83         |
| 2024-12-06 |      0.624 | $2,500.00      | $1,559.72       |
| 2024-11-03 |      0.403 | $2,000.00      | $805.19         |
| 2024-10-17 |      0.295 | $7,500.00      | $2,211.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
