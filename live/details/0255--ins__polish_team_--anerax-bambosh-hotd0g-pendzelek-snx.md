### Roster Details<br />
Team Name: Ins (Polish team)<br />
Roster: ANeraX, Bambosh, hotd0g, pendzelek, sNx<br />
Global Rank: [255](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [178]( ../standings_europe.md)<br />
<br />
Final Rank Value:  675.8<br />
<br />
Final Rank Value (675.8) = Starting Rank Value (668.7) + Head To Head Adjustments (7.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 668.7
- 400 + ( ( 0.135 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 668.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |     2000 | 2024-12-08 | REDPack Esports        | L   | 0.646      | -            | -                | -                | -         |   -12.38 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           34 |     2117 | 2024-12-06 | YoCrew                 | W   | 0.634      | 0.310        | 0.001 (0.000)    | 0.029 (0.006)    | 0 (0.000) |     5.68 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           33 |     2197 | 2024-12-04 | YENKEE Academy         | W   | 0.620      | -            | -                | -                | 0 (0.000) |     3.51 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           32 |     2474 | 2024-11-30 | QMISTRY                | L   | 0.594      | -            | -                | -                | -         |   -11.00 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           31 |     2548 | 2024-11-30 | 500 Rush               | L   | 0.591      | -            | -                | -                | -         |    -9.81 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           30 |     2667 | 2024-11-27 | KUUSAMO.gg             | W   | 0.573      | 0.284        | -                | 0.164 (0.027)    | 0 (0.000) |     5.00 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           29 |     3107 | 2024-11-20 | Lazer Cats             | L   | 0.527      | -            | -                | -                | -         |    -6.79 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           28 |     3148 | 2024-11-19 | ENTERPRISE Genesis     | W   | 0.520      | 0.278        | 0.001 (0.000)    | 0.178 (0.026)    | 0 (0.000) |     7.32 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           27 |     3202 | 2024-11-18 | Lazer Cats             | L   | 0.513      | -            | -                | -                | -         |    -6.61 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           26 |     3322 | 2024-11-16 | BRUTE                  | W   | 0.499      | 0.278        | 0.004 (0.001)    | 0.345 (0.048)    | 0 (0.000) |     8.38 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           25 |     3485 | 2024-11-13 | Onyx Ravens            | W   | 0.480      | 0.284        | 0.018 (0.003)    | 0.158 (0.021)    | 0 (0.000) |     7.61 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           24 |     3507 | 2024-11-13 | DUSTY                  | W   | 0.479      | 0.278        | 0.001 (0.000)    | 0.140 (0.019)    | 0 (0.000) |     9.95 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           23 |     3845 | 2024-11-07 | XI Esport              | W   | 0.439      | 0.278        | -                | 0.127 (0.015)    | 0 (0.000) |     4.29 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           22 |     4056 | 2024-11-03 | KUUSAMO.gg             | W   | 0.412      | 0.278        | -                | 0.164 (0.019)    | 0 (0.000) |     3.76 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           21 |     4483 | 2024-10-27 | Illuminar Gaming       | L   | 0.364      | -            | -                | -                | -         |    -2.81 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           20 |     4541 | 2024-10-26 | GardenGarage           | L   | 0.358      | -            | -                | -                | -         |    -4.58 | ANeraX, Bambosh, hotd0g, pendzel, sNx   |
|           19 |     4553 | 2024-10-26 | Ex-ENTERPRISE esports  | L   | 0.357      | -            | -                | -                | -         |    -4.91 | ANeraX, Bambosh, hotd0g, pendzel, sNx   |
|           18 |     4783 | 2024-10-20 | ROUNDS                 | L   | 0.319      | -            | -                | -                | -         |    -7.15 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           17 |     5106 | 2024-10-14 | Ex-Soul's Heart Esport | W   | 0.279      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.83 | ANeraX, Bambosh, hotd0g, pendzel, sNx   |
|           16 |     5187 | 2024-10-12 | Los kogutos            | L   | 0.267      | -            | -                | -                | -         |    -1.36 | ANeraX, Bambosh, hotd0g, pendzel, sNx   |
|           15 |     5196 | 2024-10-12 | Ex-Soul's Heart Esport | W   | 0.266      | -            | -                | -                | -         |     3.63 | ANeraX, Bambosh, hotd0g, pendzel, sNx   |
|           14 |     5249 | 2024-10-11 | 500 Rush               | W   | 0.260      | 0.143        | 0.002 (0.000)    | -                | -         |     3.84 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           13 |     5261 | 2024-10-11 | GameAgents             | W   | 0.259      | 0.143        | 0.003 (0.000)    | -                | -         |     4.46 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           12 |     5280 | 2024-10-10 | Los kogutos            | L   | 0.253      | -            | -                | -                | -         |    -1.21 | ANeraX, Bambosh, hotd0g, pendzelek, sNx |
|           11 |     5583 | 2024-10-05 | Team ESKYY             | W   | 0.219      | -            | -                | -                | -         |     1.24 | ANeraX, Bambosh, hotd0g, pendzel, sNx   |
|           10 |     5851 | 2024-10-01 | GardenGarage           | W   | 0.193      | 0.143        | 0.001 (0.000)    | 0.413 (0.011)    | -         |     3.72 | ANeraX, Bambosh, CheDzik, hotd0g, sNx   |
|            9 |     5892 | 2024-09-30 | Ogurkiii               | W   | 0.187      | -            | -                | -                | -         |     1.09 | ANeraX, Bambosh, CheDzik, hotd0g, sNx   |
|            8 |     5896 | 2024-09-30 | Widelec                | W   | 0.187      | -            | -                | -                | -         |     1.07 | ANeraX, Bambosh, CheDzik, hotd0g, sNx   |
|            7 |     6033 | 2024-09-28 | Ex-Soul's Heart Esport | L   | 0.173      | -            | -                | -                | -         |    -2.98 | ANeraX, Bambosh, hotd0g, pendzel, sNx   |
|            6 |     6462 | 2024-09-23 | Monte                  | L   | 0.140      | -            | -                | -                | -         |    -1.20 | ANeraX, Bambosh, hotd0g, morelz, sNx    |
|            5 |     6808 | 2024-09-17 | Dark Cloud Esports     | L   | 0.100      | -            | -                | -                | -         |    -0.89 | ANeraX, Bambosh, hotd0g, OXYGEN, sNx    |
|            4 |     6824 | 2024-09-17 | Illuminar Gaming       | W   | 0.100      | 0.143        | 0.007 (0.000)    | 0.593 (0.008)    | -         |     2.36 | ANeraX, Bambosh, hotd0g, OXYGEN, sNx    |
|            3 |     7237 | 2024-09-10 | Zero Tenacity          | L   | 0.053      | -            | -                | -                | -         |    -0.41 | ANeraX, Bambosh, CheDzik, hotd0g, sNx   |
|            2 |     7471 | 2024-09-07 | AgenciUSB              | W   | 0.031      | -            | -                | -                | -         |     0.18 | ANeraX, Bambosh, CheDzik, hotd0g, sNx   |
|            1 |     7480 | 2024-09-07 | EMERITOS BANDITOS      | W   | 0.030      | -            | -                | -                | -         |     0.26 | ANeraX, Bambosh, CheDzik, hotd0g, sNx   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,242.97)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.694 | $350.00        | $242.81         |
| 2024-12-01 |      0.598 | $250.00        | $149.48         |
| 2024-11-20 |      0.527 | $750.00        | $394.90         |
| 2024-10-27 |      0.366 | $1,244.91      | $455.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
