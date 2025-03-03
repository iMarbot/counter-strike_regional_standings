### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: AccuracyTG, dobu, kabal, MiQ, Zesta<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1109.2<br />
<br />
Final Rank Value (1109.2) = Starting Rank Value (1099.1) + Head To Head Adjustments (10.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.456[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.143[<sup>2</sup>](#table1)
- LAN Wins: 0.474[<sup>2</sup>](#table1)

The average of these factors is 0.349<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1099.1
- 400 + ( ( 0.349 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1099.1


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
|           41 |       31 | 2025-02-27 | HOTU                      | W   | 1.000      | 0.143        | -                | 0.768 (0.110)    | -         |     4.53 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           40 |       36 | 2025-02-26 | Eruption                  | W   | 1.000      | -            | -                | -                | -         |     7.80 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           39 |       50 | 2025-02-25 | The Huns Esports          | W   | 1.000      | 0.143        | 0.025 (0.004)    | -                | -         |     7.68 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           38 |       68 | 2025-02-24 | Gods Reign                | W   | 1.000      | -            | -                | -                | -         |     6.29 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           37 |       91 | 2025-02-23 | HOTU                      | L   | 1.000      | -            | -                | -                | -         |   -26.94 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           36 |      530 | 2025-02-13 | The Huns Esports          | W   | 1.000      | 0.143        | 0.025 (0.004)    | -                | -         |     7.55 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           35 |      533 | 2025-02-12 | Rare Atom                 | W   | 1.000      | 0.143        | 0.063 (0.009)    | -                | -         |    11.26 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           34 |      546 | 2025-02-12 | Lynn Vision Gaming        | L   | 1.000      | -            | -                | -                | -         |   -24.12 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           33 |      569 | 2025-02-11 | The Huns Esports          | W   | 1.000      | -            | -                | -                | -         |     7.18 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           32 |      577 | 2025-02-11 | TYLOO                     | W   | 1.000      | -            | -                | -                | -         |     5.45 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           31 |      580 | 2025-02-10 | Rooster                   | W   | 1.000      | -            | -                | -                | -         |     3.16 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           30 |     1257 | 2024-12-29 | DogEvil                   | L   | 0.782      | -            | -                | -                | -         |   -20.12 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           29 |     1278 | 2024-12-29 | Eruption                  | W   | 0.776      | 0.384        | 0.014 (0.004)    | 0.551 (0.164)    | 1 (0.776) |     5.48 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           28 |     1280 | 2024-12-28 | Rare Atom                 | W   | 0.775      | 0.384        | 0.063 (0.019)    | 0.578 (0.172)    | 1 (0.775) |     7.80 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           27 |     1321 | 2024-12-28 | The Huns Esports          | W   | 0.769      | 0.384        | 0.025 (0.007)    | 0.553 (0.163)    | 1 (0.769) |     5.00 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           26 |     1328 | 2024-12-27 | Chinggis Warriors         | W   | 0.769      | 0.384        | 0.016 (0.005)    | 0.563 (0.166)    | 1 (0.769) |     5.85 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           25 |     1340 | 2024-12-27 | Rare Atom                 | W   | 0.764      | 0.396        | 0.063 (0.019)    | 0.578 (0.175)    | -         |     9.02 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           24 |     1346 | 2024-12-27 | IHC Esports               | W   | 0.763      | -            | -                | -                | -         |     2.73 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           23 |     1352 | 2024-12-26 | Eruption                  | L   | 0.762      | -            | -                | -                | -         |   -18.72 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           22 |     2145 | 2024-12-06 | Chinggis Warriors         | W   | 0.624      | 0.333        | -                | 0.563 (0.117)    | -         |     4.56 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           21 |     2153 | 2024-12-06 | DogEvil                   | W   | 0.622      | 0.333        | 0.024 (0.005)    | 0.895 (0.186)    | -         |     3.66 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           20 |     2240 | 2024-12-04 | Just Swing (Chinese team) | W   | 0.610      | -            | -                | -                | -         |     2.55 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           19 |     2243 | 2024-12-04 | Nomads (Mongolian team)   | W   | 0.609      | 0.333        | -                | 0.407 (0.083)    | -         |     0.80 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           18 |     2248 | 2024-12-03 | IHC Esports               | L   | 0.608      | -            | -                | -                | -         |   -17.25 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           17 |     2916 | 2024-11-23 | Just Swing (Chinese team) | W   | 0.536      | -            | -                | -                | -         |     2.02 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           16 |     2925 | 2024-11-22 | CatEvil                   | W   | 0.535      | -            | -                | -                | -         |     1.40 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           15 |     3144 | 2024-11-19 | IHC Esports               | W   | 0.516      | -            | -                | -                | -         |     1.54 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           14 |     3145 | 2024-11-19 | Chinggis Warriors         | W   | 0.515      | 0.333        | -                | 0.563 (0.097)    | -         |     4.07 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           13 |     3284 | 2024-11-17 | Nomads (Mongolian team)   | W   | 0.496      | -            | -                | -                | -         |     0.59 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           12 |     3298 | 2024-11-16 | FengDa Gaming             | W   | 0.496      | -            | -                | -                | -         |     1.56 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           11 |     3301 | 2024-11-16 | MOLEGAN                   | W   | 0.495      | -            | -                | -                | -         |     0.31 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           10 |     5694 | 2024-10-04 | Clutch Gaming             | W   | 0.203      | -            | -                | -                | 1 (0.203) |     0.29 | cool4st, dobu, kabal, MiQ, yAmi      |
|            9 |     5703 | 2024-10-03 | Chinggis Warriors         | W   | 0.202      | -            | -                | -                | 1 (0.202) |     1.83 | cool4st, dobu, kabal, MiQ, yAmi      |
|            8 |     5807 | 2024-10-02 | Chinggis Warriors         | L   | 0.189      | -            | -                | -                | -         |    -5.56 | cool4st, dobu, kabal, MiQ, yAmi      |
|            7 |     5818 | 2024-10-01 | Clutch Gaming             | W   | 0.188      | -            | -                | -                | 1 (0.188) |     0.26 | cool4st, dobu, kabal, MiQ, yAmi      |
|            6 |     6236 | 2024-09-26 | The Huns Esports          | W   | 0.149      | -            | -                | -                | 1 (0.149) |     1.43 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            5 |     6248 | 2024-09-25 | The QUBE Esports          | W   | 0.148      | -            | -                | -                | 1 (0.148) |     0.29 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            4 |     7014 | 2024-09-14 | FURIA                     | L   | 0.071      | -            | -                | -                | -         |    -0.30 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            3 |     7089 | 2024-09-13 | ENCE                      | W   | 0.065      | 0.889        | 0.136 (0.008)    | -                | 1 (0.065) |     0.75 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            2 |     7158 | 2024-09-12 | Team Falcons              | L   | 0.056      | -            | -                | -                | -         |    -1.58 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            1 |     7215 | 2024-09-11 | Team Vitality             | L   | 0.050      | -            | -                | -                | -         |    -0.02 | ANNIHILATION, dobu, kabal, MiQ, yAmi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,225.14)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.783 | $2,500.00      | $1,957.99       |
| 2024-12-29 |      0.776 | $12,500.00     | $9,697.92       |
| 2024-12-06 |      0.624 | $7,500.00      | $4,679.17       |
| 2024-11-23 |      0.536 | $7,500.00      | $4,021.88       |
| 2024-09-22 |      0.124 | $7,000.00      | $868.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
