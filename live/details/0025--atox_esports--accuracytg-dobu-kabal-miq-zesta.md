### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: AccuracyTG, dobu, kabal, MiQ, Zesta<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1111.6<br />
<br />
Final Rank Value (1111.6) = Starting Rank Value (1103.2) + Head To Head Adjustments (8.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.456[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.481[<sup>2</sup>](#table1)

The average of these factors is 0.352<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1103.2
- 400 + ( ( 0.352 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1103.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |       16 | 2025-02-27 | HOTU                      | W   | 1.000      | 0.143        | -                | 0.777 (0.111)    | -         |     4.49 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           40 |       21 | 2025-02-26 | Eruption                  | W   | 1.000      | -            | -                | -                | -         |     7.73 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           39 |       35 | 2025-02-25 | The Huns Esports          | W   | 1.000      | 0.143        | 0.025 (0.004)    | -                | -         |     7.63 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           38 |       53 | 2025-02-24 | Gods Reign                | W   | 1.000      | -            | -                | -                | -         |     6.17 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           37 |       76 | 2025-02-23 | HOTU                      | L   | 1.000      | -            | -                | -                | -         |   -26.98 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           36 |      518 | 2025-02-13 | The Huns Esports          | W   | 1.000      | 0.143        | 0.025 (0.004)    | -                | -         |     7.48 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           35 |      521 | 2025-02-12 | Rare Atom                 | W   | 1.000      | 0.143        | 0.063 (0.009)    | -                | -         |    11.19 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           34 |      534 | 2025-02-12 | Lynn Vision Gaming        | L   | 1.000      | -            | -                | -                | -         |   -24.18 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           33 |      557 | 2025-02-11 | The Huns Esports          | W   | 1.000      | -            | -                | -                | -         |     7.10 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           32 |      565 | 2025-02-11 | TYLOO                     | W   | 1.000      | -            | -                | -                | -         |     5.41 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           31 |      568 | 2025-02-10 | Rooster                   | W   | 1.000      | -            | -                | -                | -         |     3.12 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           30 |     1245 | 2024-12-29 | DogEvil                   | L   | 0.790      | -            | -                | -                | -         |   -20.38 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           29 |     1266 | 2024-12-29 | Eruption                  | W   | 0.784      | 0.384        | 0.014 (0.004)    | 0.552 (0.166)    | 1 (0.784) |     5.46 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           28 |     1268 | 2024-12-28 | Rare Atom                 | W   | 0.783      | 0.384        | 0.063 (0.019)    | 0.581 (0.175)    | 1 (0.783) |     7.81 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           27 |     1309 | 2024-12-28 | The Huns Esports          | W   | 0.777      | 0.384        | 0.025 (0.007)    | 0.557 (0.166)    | 1 (0.777) |     4.98 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           26 |     1316 | 2024-12-27 | Chinggis Warriors         | W   | 0.777      | 0.384        | 0.016 (0.005)    | 0.567 (0.169)    | 1 (0.777) |     5.88 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           25 |     1328 | 2024-12-27 | Rare Atom                 | W   | 0.772      | 0.396        | 0.063 (0.019)    | 0.581 (0.178)    | -         |     9.05 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           24 |     1334 | 2024-12-27 | IHC Esports               | W   | 0.771      | -            | -                | -                | -         |     2.72 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           23 |     1340 | 2024-12-26 | Eruption                  | L   | 0.770      | -            | -                | -                | -         |   -19.01 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           22 |     2133 | 2024-12-06 | Chinggis Warriors         | W   | 0.632      | 0.333        | -                | 0.567 (0.119)    | -         |     4.60 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           21 |     2141 | 2024-12-06 | DogEvil                   | W   | 0.631      | 0.333        | 0.024 (0.005)    | 0.896 (0.188)    | -         |     3.66 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           20 |     2228 | 2024-12-04 | Just Swing (Chinese team) | W   | 0.618      | -            | -                | -                | -         |     2.55 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           19 |     2231 | 2024-12-04 | Nomads (Mongolian team)   | W   | 0.618      | 0.333        | -                | 0.407 (0.084)    | -         |     0.79 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           18 |     2236 | 2024-12-03 | IHC Esports               | L   | 0.617      | -            | -                | -                | -         |   -17.52 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           17 |     2904 | 2024-11-23 | Just Swing (Chinese team) | W   | 0.544      | -            | -                | -                | -         |     2.02 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           16 |     2913 | 2024-11-22 | CatEvil                   | W   | 0.543      | -            | -                | -                | -         |     1.40 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           15 |     3132 | 2024-11-19 | IHC Esports               | W   | 0.524      | -            | -                | -                | -         |     1.54 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           14 |     3133 | 2024-11-19 | Chinggis Warriors         | W   | 0.523      | 0.333        | -                | 0.567 (0.099)    | -         |     4.12 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           13 |     3272 | 2024-11-17 | Nomads (Mongolian team)   | W   | 0.504      | -            | -                | -                | -         |     0.59 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           12 |     3286 | 2024-11-16 | FengDa Gaming             | W   | 0.504      | -            | -                | -                | -         |     1.56 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           11 |     3289 | 2024-11-16 | MOLEGAN                   | W   | 0.503      | -            | -                | -                | -         |     0.31 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           10 |     5682 | 2024-10-04 | Clutch Gaming             | W   | 0.211      | -            | -                | -                | 1 (0.211) |     0.30 | cool4st, dobu, kabal, MiQ, yAmi      |
|            9 |     5691 | 2024-10-03 | Chinggis Warriors         | W   | 0.210      | -            | -                | -                | 1 (0.210) |     1.91 | cool4st, dobu, kabal, MiQ, yAmi      |
|            8 |     5795 | 2024-10-02 | Chinggis Warriors         | L   | 0.198      | -            | -                | -                | -         |    -5.81 | cool4st, dobu, kabal, MiQ, yAmi      |
|            7 |     5806 | 2024-10-01 | Clutch Gaming             | W   | 0.196      | -            | -                | -                | 1 (0.196) |     0.26 | cool4st, dobu, kabal, MiQ, yAmi      |
|            6 |     6224 | 2024-09-26 | The Huns Esports          | W   | 0.158      | -            | -                | -                | 1 (0.158) |     1.49 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            5 |     6236 | 2024-09-25 | The QUBE Esports          | W   | 0.157      | -            | -                | -                | 1 (0.157) |     0.30 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            4 |     7002 | 2024-09-14 | FURIA                     | L   | 0.079      | -            | -                | -                | -         |    -0.33 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            3 |     7077 | 2024-09-13 | ENCE                      | W   | 0.073      | 0.889        | 0.136 (0.009)    | -                | 1 (0.073) |     0.84 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            2 |     7146 | 2024-09-12 | Team Falcons              | L   | 0.065      | -            | -                | -                | -         |    -1.81 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            1 |     7203 | 2024-09-11 | Team Vitality             | L   | 0.058      | -            | -                | -                | -         |    -0.02 | ANNIHILATION, dobu, kabal, MiQ, yAmi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,528.33)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.791 | $2,500.00      | $1,978.47       |
| 2024-12-29 |      0.784 | $12,500.00     | $9,800.35       |
| 2024-12-06 |      0.632 | $7,500.00      | $4,740.63       |
| 2024-11-23 |      0.544 | $7,500.00      | $4,083.33       |
| 2024-09-22 |      0.132 | $7,000.00      | $925.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
