### Roster Details<br />
Team Name: ADEPTS<br />
Roster: cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky<br />
Global Rank: [267](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [186]( ../standings_europe.md)<br />
<br />
Final Rank Value:  668.7<br />
<br />
Final Rank Value (668.7) = Starting Rank Value (679.3) + Head To Head Adjustments (-10.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.175[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.095[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.3
- 400 + ( ( 0.140 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 679.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |     1398 | 2024-12-22 | WOPA Esport         | L   | 0.739      | -            | -                | -                | -         |    -6.01 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           58 |     1466 | 2024-12-21 | KONO.ECF            | L   | 0.732      | -            | -                | -                | -         |    -5.76 | cHeuuuuk, Chuckyy, SBT, Tarkky, xReal    |
|           57 |     1541 | 2024-12-19 | Preasy Esport       | W   | 0.718      | 0.333        | 0.012 (0.003)    | 0.710 (0.170)    | 0 (0.000) |    13.78 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           56 |     1592 | 2024-12-16 | Heimo Esports       | W   | 0.698      | 0.333        | 0.004 (0.001)    | 0.658 (0.153)    | 0 (0.000) |    13.19 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           55 |     1811 | 2024-12-13 | ENCE Academy        | L   | 0.677      | -            | -                | -                | -         |    -6.91 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           54 |     1824 | 2024-12-12 | Dark Cloud Esports  | L   | 0.674      | -            | -                | -                | -         |    -6.20 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           53 |     1839 | 2024-12-12 | GODSENT             | L   | 0.672      | -            | -                | -                | -         |   -10.49 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           52 |     1880 | 2024-12-11 | Illuminar Gaming    | L   | 0.666      | -            | -                | -                | -         |    -6.55 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           51 |     1958 | 2024-12-09 | Heimo Esports       | W   | 0.652      | 0.333        | 0.004 (0.001)    | 0.658 (0.143)    | 0 (0.000) |    11.19 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           50 |     1985 | 2024-12-08 | Astralis Talent     | L   | 0.647      | -            | -                | -                | -         |    -7.24 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           49 |     2415 | 2024-12-01 | Kubix Esports       | L   | 0.600      | -            | -                | -                | -         |    -4.11 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           48 |     2575 | 2024-11-29 | FLuffy Gangsters    | L   | 0.587      | -            | -                | -                | -         |    -5.19 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           47 |     2668 | 2024-11-27 | Preasy Esport       | L   | 0.573      | -            | -                | -                | -         |    -7.37 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           46 |     2700 | 2024-11-26 | JANO Esports        | W   | 0.567      | 0.333        | 0.022 (0.004)    | 0.442 (0.084)    | 0 (0.000) |    13.61 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           45 |     2894 | 2024-11-23 | 777 Esports         | W   | 0.545      | 0.333        | -                | 0.239 (0.043)    | 0 (0.000) |     8.22 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           44 |     3007 | 2024-11-21 | Monte               | L   | 0.534      | -            | -                | -                | -         |    -3.31 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           43 |     3046 | 2024-11-21 | Nexus Gaming        | L   | 0.532      | -            | -                | -                | -         |    -1.31 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           42 |     3086 | 2024-11-20 | Lilmix              | W   | 0.527      | -            | -                | -                | 0 (0.000) |     6.83 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           41 |     3167 | 2024-11-19 | Preasy Esport       | L   | 0.517      | -            | -                | -                | -         |    -6.67 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           40 |     3186 | 2024-11-18 | XP Academy          | L   | 0.514      | -            | -                | -                | -         |   -10.00 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           39 |     3439 | 2024-11-14 | Infinite Gaming     | W   | 0.486      | -            | -                | -                | 0 (0.000) |     4.21 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           38 |     3483 | 2024-11-13 | GODSENT             | L   | 0.480      | -            | -                | -                | -         |    -7.79 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           37 |     3494 | 2024-11-13 | ROUNDS              | W   | 0.480      | -            | -                | -                | 0 (0.000) |     4.11 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           36 |     3651 | 2024-11-10 | Permitta Esports    | W   | 0.460      | 0.372        | 0.013 (0.002)    | 0.494 (0.085)    | 0 (0.000) |     9.64 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           35 |     3927 | 2024-11-05 | GTZ.ESPORTS         | W   | 0.427      | 0.372        | 0.080 (0.013)    | 0.563 (0.089)    | 0 (0.000) |    12.68 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           34 |     3954 | 2024-11-05 | Astralis Talent     | L   | 0.425      | -            | -                | -                | -         |    -5.17 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           33 |     4214 | 2024-11-01 | Heimo Esports       | L   | 0.398      | -            | -                | -                | -         |    -4.76 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           32 |     4312 | 2024-10-30 | ALTERNATE aTTaX     | W   | 0.386      | 0.372        | 0.021 (0.003)    | 0.564 (0.081)    | -         |     9.67 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           31 |     4370 | 2024-10-29 | THE SPELLS          | L   | 0.380      | -            | -                | -                | -         |    -7.81 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           30 |     4859 | 2024-10-19 | Viperio             | L   | 0.311      | -            | -                | -                | -         |    -4.02 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           29 |     4990 | 2024-10-16 | Partizan Esports    | L   | 0.293      | -            | -                | -                | -         |    -0.91 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           28 |     5062 | 2024-10-15 | HyperSpirit         | W   | 0.286      | -            | -                | -                | -         |     4.39 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           27 |     5156 | 2024-10-13 | KONO.ECF            | W   | 0.271      | 0.333        | 0.045 (0.004)    | 0.757 (0.068)    | -         |     6.82 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           26 |     5284 | 2024-10-10 | Viperio             | L   | 0.253      | -            | -                | -                | -         |    -3.04 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           25 |     5362 | 2024-10-09 | Ex-9INE Academy     | W   | 0.244      | -            | -                | -                | -         |     3.06 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           24 |     5854 | 2024-10-01 | Underrated          | L   | 0.192      | -            | -                | -                | -         |    -2.85 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           23 |     5903 | 2024-09-30 | Ex-9INE Academy     | W   | 0.187      | -            | -                | -                | -         |     2.36 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           22 |     6132 | 2024-09-27 | Underrated          | L   | 0.166      | -            | -                | -                | -         |    -2.43 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           21 |     6229 | 2024-09-26 | ALASKA              | L   | 0.157      | -            | -                | -                | -         |    -0.32 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           20 |     6273 | 2024-09-25 | GameAgents          | L   | 0.154      | -            | -                | -                | -         |    -2.30 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           19 |     6314 | 2024-09-25 | WOPA Esport         | L   | 0.151      | -            | -                | -                | -         |    -1.28 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           18 |     6322 | 2024-09-25 | Alliance            | L   | 0.151      | -            | -                | -                | -         |    -1.07 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           17 |     6400 | 2024-09-24 | RUBY                | L   | 0.145      | -            | -                | -                | -         |    -2.17 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           16 |     6418 | 2024-09-24 | Partizan Esports    | L   | 0.144      | -            | -                | -                | -         |    -0.40 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           15 |     6481 | 2024-09-23 | FLuffy Gangsters    | L   | 0.138      | -            | -                | -                | -         |    -1.52 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           14 |     6491 | 2024-09-23 | Preasy Esport       | W   | 0.137      | 0.333        | 0.012 (0.001)    | -                | -         |     2.91 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           13 |     6523 | 2024-09-22 | Partizan Esports    | W   | 0.132      | 0.333        | 0.082 (0.004)    | 0.768 (0.034)    | -         |     3.79 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           12 |     6579 | 2024-09-21 | Viperio             | L   | 0.126      | -            | -                | -                | -         |    -1.52 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           11 |     6599 | 2024-09-21 | Viperio             | L   | 0.124      | -            | -                | -                | -         |    -1.51 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           10 |     6621 | 2024-09-20 | Preasy Esport       | L   | 0.120      | -            | -                | -                | -         |    -1.24 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            9 |     6715 | 2024-09-19 | Partizan Esports    | L   | 0.110      | -            | -                | -                | -         |    -0.30 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            8 |     6770 | 2024-09-18 | Ex-9INE Academy     | W   | 0.105      | -            | -                | -                | -         |     1.31 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            7 |     6837 | 2024-09-17 | GODSENT             | L   | 0.099      | -            | -                | -                | -         |    -1.60 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            6 |     6872 | 2024-09-16 | Leo Team            | L   | 0.093      | -            | -                | -                | -         |    -0.87 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            5 |     7032 | 2024-09-14 | Astralis Talent     | L   | 0.078      | -            | -                | -                | -         |    -0.89 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            4 |     7106 | 2024-09-13 | Team Spirit Academy | L   | 0.070      | -            | -                | -                | -         |    -0.46 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            3 |     7260 | 2024-09-10 | Ex-9INE Academy     | W   | 0.051      | -            | -                | -                | -         |     0.64 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            2 |     7624 | 2024-09-05 | Dark Cloud Esports  | W   | 0.018      | -            | -                | -                | -         |     0.40 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            1 |     7742 | 2024-09-03 | FLuffy Gangsters    | L   | 0.005      | -            | -                | -                | -         |    -0.06 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6.39)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-04 |      0.013 | $500.00        | $6.39           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
