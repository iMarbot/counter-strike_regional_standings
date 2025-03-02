### Roster Details<br />
Team Name: 777 Esports<br />
Roster: Affava, Hagmeister, MadeInRed, qzr, Viktha<br />
Global Rank: [314](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [209]( ../standings_europe.md)<br />
<br />
Final Rank Value:  641.3<br />
<br />
Final Rank Value (641.3) = Starting Rank Value (646.2) + Head To Head Adjustments (-4.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.2
- 400 + ( ( 0.123 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 646.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      978 | 2025-02-04 | Preasy Esport       | L   | 1.000      | -            | -                | -                | -         |   -10.15 | Affava, Hagmeister, MadeInRed, qzr, Viktha |
|           25 |     1004 | 2025-02-04 | Viperio             | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.411 (0.059)    | 0 (0.000) |    18.69 | Affava, Hagmeister, MadeInRed, qzr, Viktha |
|           24 |     1237 | 2024-12-30 | Preasy Esport       | L   | 0.793      | -            | -                | -                | -         |    -8.81 | Hagmeister, MadeInRed, qzr, Viktha, wenba  |
|           23 |     2088 | 2024-12-07 | NewBALLS            | L   | 0.639      | -            | -                | -                | -         |    -9.51 | Cruxey, Hagmeister, qzr, Viktha, wenba     |
|           22 |     2206 | 2024-12-04 | BRODA               | W   | 0.620      | 0.333        | -                | 0.056 (0.012)    | 0 (0.000) |     6.31 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           21 |     2335 | 2024-12-02 | Ex-ESC Gaming       | L   | 0.606      | -            | -                | -                | -         |    -9.09 | Affava, H4RR3, Hagmeister, qzr, Viktha     |
|           20 |     2479 | 2024-11-30 | XI Esport           | L   | 0.594      | -            | -                | -                | -         |    -8.38 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           19 |     2585 | 2024-11-29 | Split ESC           | W   | 0.586      | -            | -                | -                | 0 (0.000) |     3.48 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           18 |     2621 | 2024-11-28 | The Last Resort     | W   | 0.580      | 0.333        | 0.001 (0.000)    | 0.161 (0.031)    | 0 (0.000) |    10.93 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           17 |     2752 | 2024-11-25 | G2 Ares             | L   | 0.560      | -            | -                | -                | -         |    -7.90 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           16 |     2894 | 2024-11-23 | ADEPTS              | L   | 0.545      | -            | -                | -                | -         |    -8.22 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           15 |     2988 | 2024-11-22 | Preasy Esport       | L   | 0.538      | -            | -                | -                | -         |    -6.34 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           14 |     3794 | 2024-11-08 | Monte               | L   | 0.446      | -            | -                | -                | -         |    -2.87 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           13 |     3803 | 2024-11-08 | GenOne              | L   | 0.445      | -            | -                | -                | -         |    -4.01 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           12 |     3900 | 2024-11-06 | Devils.one          | W   | 0.432      | 0.333        | 0.001 (0.000)    | 0.073 (0.011)    | 0 (0.000) |     6.38 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           11 |     4148 | 2024-11-02 | GenOne              | L   | 0.405      | -            | -                | -                | -         |    -3.61 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           10 |     4838 | 2024-10-19 | ALTERNATE aTTaX Evo | W   | 0.313      | 0.278        | 0.001 (0.000)    | 0.184 (0.016)    | 0 (0.000) |     4.26 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            9 |     4938 | 2024-10-17 | ALTERNATE aTTaX Evo | W   | 0.299      | 0.278        | 0.001 (0.000)    | 0.184 (0.015)    | 0 (0.000) |     4.07 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            8 |     5073 | 2024-10-15 | Team Czech Republic | W   | 0.285      | 0.278        | 0.000 (0.000)    | 0.094 (0.007)    | 0 (0.000) |     5.25 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            7 |     5209 | 2024-10-12 | Daystar             | W   | 0.265      | 0.278        | 0.000 (0.000)    | 0.135 (0.010)    | 0 (0.000) |     4.12 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            6 |     5255 | 2024-10-11 | ENTERPRISE Genesis  | W   | 0.259      | 0.278        | 0.001 (0.000)    | 0.178 (0.013)    | 0 (0.000) |     4.01 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            5 |     5427 | 2024-10-08 | Devils.one          | L   | 0.239      | -            | -                | -                | -         |    -3.66 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            4 |     5602 | 2024-10-05 | SINNERS Academy     | W   | 0.219      | 0.278        | 0.001 (0.000)    | 0.102 (0.006)    | -         |     4.23 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            3 |     5704 | 2024-10-03 | POOHANK             | W   | 0.208      | 0.215        | 0.000 (0.000)    | -                | -         |     2.65 | Chrysus, Hagmeister, qzr, Viktha, wenba    |
|            2 |     6043 | 2024-09-28 | Kay Team            | W   | 0.172      | -            | -                | -                | -         |     1.71 | Chrysus, Hagmeister, qzr, Viktha, wenba    |
|            1 |     6056 | 2024-09-28 | Inroads Esports     | W   | 0.172      | -            | -                | -                | -         |     1.56 | Chrysus, Hagmeister, qzr, Viktha, wenba    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($793.61)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-07 |      0.639 | $99.15         | $63.37          |
| 2024-11-10 |      0.460 | $500.00        | $229.86         |
| 2024-10-19 |      0.313 | $1,500.00      | $469.17         |
| 2024-10-03 |      0.208 | $150.00        | $31.21          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
