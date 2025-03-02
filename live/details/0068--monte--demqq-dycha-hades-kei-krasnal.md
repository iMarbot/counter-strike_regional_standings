### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, KEi, kRaSnaL<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  898.6<br />
<br />
Final Rank Value (898.6) = Starting Rank Value (842.4) + Head To Head Adjustments (56.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.395[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.083[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 842.4
- 400 + ( ( 0.221 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 842.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |     1584 | 2024-12-16 | Dynamo Eclot        | L   | 0.699      | -            | -                | -                | -         |    -6.43 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           30 |     1799 | 2024-12-13 | Metizport           | L   | 0.678      | -            | -                | -                | -         |    -6.45 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           29 |     1925 | 2024-12-10 | Aurora Gaming       | W   | 0.659      | 0.435        | 0.019 (0.006)    | 0.516 (0.148)    | 0 (0.000) |     8.59 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           28 |     1953 | 2024-12-09 | GUN5 Esports        | W   | 0.653      | 0.435        | 0.102 (0.029)    | 0.515 (0.146)    | 0 (0.000) |    11.95 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           27 |     2793 | 2024-11-24 | ENCE                | L   | 0.552      | -            | -                | -                | -         |    -5.55 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           26 |     2887 | 2024-11-23 | Johnny Speeds       | W   | 0.546      | 0.143        | 0.039 (0.003)    | 0.355 (0.028)    | 0 (0.000) |     9.64 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           25 |     3667 | 2024-11-10 | FAVBET Team         | W   | 0.459      | 0.143        | 0.032 (0.002)    | 0.814 (0.053)    | 0 (0.000) |     6.92 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           24 |     3851 | 2024-11-07 | 500                 | L   | 0.439      | -            | -                | -                | -         |    -4.56 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           23 |     3896 | 2024-11-06 | Team Spirit Academy | W   | 0.432      | 0.143        | 0.068 (0.004)    | 0.714 (0.044)    | 0 (0.000) |     8.14 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           22 |     4478 | 2024-10-27 | SAW                 | L   | 0.365      | -            | -                | -                | -         |    -0.84 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           21 |     4531 | 2024-10-26 | Legacy              | W   | 0.358      | 0.500        | 0.036 (0.006)    | 0.554 (0.099)    | 1 (0.358) |     6.09 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           20 |     4587 | 2024-10-25 | MIBR                | W   | 0.353      | 0.500        | 0.141 (0.025)    | 0.471 (0.083)    | 1 (0.353) |    10.60 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           19 |     4603 | 2024-10-25 | PaiN Gaming         | L   | 0.352      | -            | -                | -                | -         |    -0.16 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           18 |     5251 | 2024-10-11 | SINNERS Esports     | L   | 0.260      | -            | -                | -                | -         |    -3.58 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           17 |     5497 | 2024-10-07 | Metizport           | W   | 0.231      | 0.435        | 0.074 (0.007)    | 0.513 (0.051)    | 0 (0.000) |     5.70 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           16 |     5611 | 2024-10-05 | Adventurers         | W   | 0.218      | -            | -                | -                | 0 (0.000) |     2.78 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           15 |     5723 | 2024-10-03 | Team Spirit Academy | L   | 0.205      | -            | -                | -                | -         |    -2.61 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           14 |     5920 | 2024-09-30 | ECSTATIC            | W   | 0.185      | 0.435        | 0.033 (0.003)    | 0.828 (0.067)    | 0 (0.000) |     3.17 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           13 |     6233 | 2024-09-26 | 3DMAX               | L   | 0.157      | -            | -                | -                | -         |    -0.07 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           12 |     6372 | 2024-09-24 | Rebels Gaming       | W   | 0.146      | -            | -                | -                | -         |     1.60 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           11 |     6375 | 2024-09-24 | GameAgents          | W   | 0.146      | -            | -                | -                | -         |     1.34 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           10 |     6409 | 2024-09-24 | BIG                 | W   | 0.145      | 0.384        | 0.246 (0.014)    | 0.579 (0.032)    | -         |     4.45 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            9 |     6436 | 2024-09-23 | 4wb                 | W   | 0.141      | -            | -                | -                | -         |     0.34 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            8 |     6462 | 2024-09-23 | Ins (Polish team)   | W   | 0.140      | -            | -                | -                | -         |     1.20 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            7 |     6485 | 2024-09-23 | PARIVISION          | W   | 0.138      | -            | -                | -                | -         |     1.43 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            6 |     6710 | 2024-09-19 | Sashi Esport        | W   | 0.111      | -            | -                | -                | -         |     2.28 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            5 |     6847 | 2024-09-17 | EYEBALLERS          | W   | 0.098      | -            | -                | -                | -         |     1.38 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            4 |     7143 | 2024-09-12 | Nemiga Gaming       | L   | 0.065      | -            | -                | -                | -         |    -0.56 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            3 |     7478 | 2024-09-07 | GamerLegion         | L   | 0.030      | -            | -                | -                | -         |    -0.66 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            2 |     7627 | 2024-09-05 | SINNERS Esports     | W   | 0.017      | -            | -                | -                | -         |     0.33 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            1 |     7682 | 2024-09-04 | PARIVISION          | L   | 0.011      | -            | -                | -                | -         |    -0.23 | DemQQ, dycha, hades, KEi, kRaSnaL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,876.65)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.707 | $5,000.00      | $3,533.33       |
| 2024-11-24 |      0.552 | $4,262.60      | $2,353.90       |
| 2024-11-09 |      0.452 | $15.18         | $6.87           |
| 2024-10-27 |      0.367 | $10,000.00     | $3,665.74       |
| 2024-09-26 |      0.159 | $1,500.00      | $238.47         |
| 2024-09-08 |      0.039 | $2,000.00      | $78.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
