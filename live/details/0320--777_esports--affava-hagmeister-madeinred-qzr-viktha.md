### Roster Details<br />
Team Name: 777 Esports<br />
Roster: Affava, Hagmeister, MadeInRed, qzr, Viktha<br />
Global Rank: [320](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [210]( ../standings_europe.md)<br />
<br />
Final Rank Value:  639.3<br />
<br />
Final Rank Value (639.3) = Starting Rank Value (645.9) + Head To Head Adjustments (-6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 645.9
- 400 + ( ( 0.123 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 645.9


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
|           26 |      990 | 2025-02-04 | Preasy Esport       | L   | 1.000      | -            | -                | -                | -         |   -10.22 | Affava, Hagmeister, MadeInRed, qzr, Viktha |
|           25 |     1016 | 2025-02-04 | Viperio             | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.404 (0.058)    | 0 (0.000) |    18.70 | Affava, Hagmeister, MadeInRed, qzr, Viktha |
|           24 |     1249 | 2024-12-30 | Preasy Esport       | L   | 0.785      | -            | -                | -                | -         |    -8.77 | Hagmeister, MadeInRed, qzr, Viktha, wenba  |
|           23 |     2100 | 2024-12-07 | NewBALLS            | L   | 0.631      | -            | -                | -                | -         |    -9.35 | Cruxey, Hagmeister, qzr, Viktha, wenba     |
|           22 |     2218 | 2024-12-04 | BRODA               | W   | 0.612      | 0.333        | -                | 0.056 (0.011)    | 0 (0.000) |     6.27 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           21 |     2347 | 2024-12-02 | Ex-ESC Gaming       | L   | 0.598      | -            | -                | -                | -         |    -8.92 | Affava, H4RR3, Hagmeister, qzr, Viktha     |
|           20 |     2491 | 2024-11-30 | XI Esport           | L   | 0.586      | -            | -                | -                | -         |    -8.23 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           19 |     2597 | 2024-11-29 | Split ESC           | W   | 0.578      | -            | -                | -                | 0 (0.000) |     3.47 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           18 |     2633 | 2024-11-28 | The Last Resort     | W   | 0.572      | 0.333        | 0.001 (0.000)    | 0.159 (0.030)    | 0 (0.000) |    10.83 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           17 |     2764 | 2024-11-25 | G2 Ares             | L   | 0.551      | -            | -                | -                | -         |    -7.76 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           16 |     2906 | 2024-11-23 | ADEPTS              | L   | 0.537      | -            | -                | -                | -         |    -9.52 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           15 |     3000 | 2024-11-22 | Preasy Esport       | L   | 0.530      | -            | -                | -                | -         |    -6.26 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           14 |     3806 | 2024-11-08 | Monte               | L   | 0.438      | -            | -                | -                | -         |    -2.83 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           13 |     3815 | 2024-11-08 | GenOne              | L   | 0.437      | -            | -                | -                | -         |    -3.95 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           12 |     3912 | 2024-11-06 | Devils.one          | W   | 0.423      | 0.333        | 0.001 (0.000)    | 0.068 (0.010)    | 0 (0.000) |     6.23 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           11 |     4160 | 2024-11-02 | GenOne              | L   | 0.397      | -            | -                | -                | -         |    -3.55 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|           10 |     4850 | 2024-10-19 | ALTERNATE aTTaX Evo | W   | 0.305      | 0.278        | 0.001 (0.000)    | 0.178 (0.015)    | 0 (0.000) |     4.15 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            9 |     4950 | 2024-10-17 | ALTERNATE aTTaX Evo | W   | 0.290      | 0.278        | 0.001 (0.000)    | 0.178 (0.014)    | 0 (0.000) |     3.97 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            8 |     5085 | 2024-10-15 | Team Czech Republic | W   | 0.277      | 0.278        | 0.000 (0.000)    | 0.092 (0.007)    | 0 (0.000) |     5.10 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            7 |     5221 | 2024-10-12 | Daystar             | W   | 0.257      | 0.278        | 0.000 (0.000)    | 0.131 (0.009)    | 0 (0.000) |     3.97 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            6 |     5267 | 2024-10-11 | ENTERPRISE Genesis  | W   | 0.251      | 0.278        | 0.001 (0.000)    | 0.175 (0.012)    | 0 (0.000) |     3.89 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            5 |     5439 | 2024-10-08 | Devils.one          | L   | 0.230      | -            | -                | -                | -         |    -3.56 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            4 |     5610 | 2024-10-05 | SINNERS Academy     | W   | 0.210      | 0.278        | 0.001 (0.000)    | 0.101 (0.006)    | -         |     4.07 | H4RR3, Hagmeister, qzr, Viktha, wenba      |
|            3 |     5716 | 2024-10-03 | POOHANK             | W   | 0.200      | 0.215        | 0.000 (0.000)    | -                | -         |     2.55 | Chrysus, Hagmeister, qzr, Viktha, wenba    |
|            2 |     6055 | 2024-09-28 | Kay Team            | W   | 0.164      | -            | -                | -                | -         |     1.63 | Chrysus, Hagmeister, qzr, Viktha, wenba    |
|            1 |     6068 | 2024-09-28 | Inroads Esports     | W   | 0.164      | -            | -                | -                | -         |     1.48 | Chrysus, Hagmeister, qzr, Viktha, wenba    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($775.18)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-07 |      0.631 | $99.15         | $62.56          |
| 2024-11-10 |      0.452 | $500.00        | $225.76         |
| 2024-10-19 |      0.305 | $1,500.00      | $456.88         |
| 2024-10-03 |      0.200 | $150.00        | $29.98          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
