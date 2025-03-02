### Roster Details<br />
Team Name: PaiN Gaming<br />
Roster: biguzera, dav1deuS, kauez, nqz, snow<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1604.1<br />
<br />
Final Rank Value (1604.1) = Starting Rank Value (1656.2) + Head To Head Adjustments (-52.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.668[<sup>1</sup>](#table2)
- Bounty Collected: 0.634[<sup>2</sup>](#table1)
- Opponent Network: 0.354[<sup>2</sup>](#table1)
- LAN Wins: 0.860[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1656.2
- 400 + ( ( 0.629 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1656.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |      220 | 2025-02-21 | MOUZ             | L   | 1.000      | -            | -                | -                | -         |    -6.18 | biguzera, dav1deuS, kauez, nqz, snow |
|           59 |      287 | 2025-02-17 | Virtus.pro       | W   | 1.000      | 1.000        | 0.268 (0.268)    | 0.439 (0.439)    | 1 (1.000) |    15.92 | biguzera, dav1deuS, kauez, nqz, snow |
|           58 |      350 | 2025-02-16 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -4.17 | biguzera, dav1deuS, kauez, nqz, snow |
|           57 |      409 | 2025-02-15 | Team Falcons     | W   | 1.000      | 1.000        | 0.927 (0.927)    | 0.613 (0.613)    | 1 (1.000) |    24.65 | biguzera, dav1deuS, kauez, nqz, snow |
|           56 |      483 | 2025-02-14 | Astralis         | W   | 1.000      | 1.000        | 0.609 (0.609)    | 0.787 (0.787)    | 1 (1.000) |    21.87 | biguzera, dav1deuS, kauez, nqz, snow |
|           55 |      632 | 2025-02-09 | Imperial Esports | L   | 1.000      | -            | -                | -                | -         |   -29.88 | biguzera, dav1deuS, kauez, nqz, snow |
|           54 |      668 | 2025-02-08 | RED Canids       | W   | 1.000      | -            | -                | -                | -         |     0.53 | biguzera, dav1deuS, kauez, nqz, snow |
|           53 |     1089 | 2025-01-31 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -8.35 | biguzera, dav1deuS, kauez, nqz, snow |
|           52 |     1101 | 2025-01-30 | GamerLegion      | L   | 0.998      | -            | -                | -                | -         |   -17.28 | biguzera, dav1deuS, kauez, nqz, snow |
|           51 |     1113 | 2025-01-29 | Virtus.pro       | W   | 0.991      | 1.000        | 0.268 (0.266)    | 0.439 (0.435)    | 1 (0.991) |    14.59 | biguzera, dav1deuS, kauez, nqz, snow |
|           50 |     1138 | 2025-01-24 | Natus Vincere    | L   | 0.960      | -            | -                | -                | -         |    -9.96 | biguzera, dav1deuS, kauez, nqz, snow |
|           49 |     1165 | 2025-01-18 | FaZe Clan        | W   | 0.919      | 0.363        | 0.744 (0.248)    | 0.482 (0.161)    | -         |    24.36 | biguzera, dav1deuS, kauez, nqz, snow |
|           48 |     1176 | 2025-01-17 | GamerLegion      | W   | 0.911      | 0.363        | 0.127 (0.042)    | 0.493 (0.163)    | -         |    13.76 | biguzera, dav1deuS, kauez, nqz, snow |
|           47 |     2097 | 2024-12-07 | FURIA            | L   | 0.637      | -            | -                | -                | -         |   -12.98 | biguzera, kauez, lux, nqz, snow      |
|           46 |     2143 | 2024-12-06 | BIG              | W   | 0.631      | 1.000        | 0.246 (0.155)    | 0.579 (0.365)    | 1 (0.631) |     7.26 | biguzera, kauez, lux, nqz, snow      |
|           45 |     2166 | 2024-12-05 | 3DMAX            | L   | 0.625      | -            | -                | -                | -         |    -9.76 | biguzera, kauez, lux, nqz, snow      |
|           44 |     2187 | 2024-12-04 | MOUZ             | L   | 0.623      | -            | -                | -                | -         |    -1.91 | biguzera, kauez, lux, nqz, snow      |
|           43 |     2372 | 2024-12-01 | FlyQuest         | W   | 0.603      | 1.000        | 0.105 (0.063)    | 0.239 (0.144)    | 1 (0.603) |     1.42 | biguzera, kauez, lux, nqz, snow      |
|           42 |     2452 | 2024-11-30 | Cloud9           | W   | 0.596      | -            | -                | -                | 1 (0.596) |     0.49 | biguzera, kauez, lux, nqz, snow      |
|           41 |     2534 | 2024-11-30 | GamerLegion      | L   | 0.592      | -            | -                | -                | -         |    -9.69 | biguzera, kauez, lux, nqz, snow      |
|           40 |     2554 | 2024-11-29 | Imperial Esports | W   | 0.590      | 1.000        | 0.091 (0.054)    | 0.564 (0.333)    | 1 (0.590) |     0.66 | biguzera, kauez, lux, nqz, snow      |
|           39 |     3481 | 2024-11-13 | 9z Team          | W   | 0.483      | -            | -                | -                | 1 (0.483) |     0.18 | biguzera, kauez, lux, nqz, snow      |
|           38 |     3526 | 2024-11-12 | Imperial Esports | W   | 0.476      | -            | -                | -                | 1 (0.476) |     0.52 | biguzera, kauez, lux, nqz, snow      |
|           37 |     3560 | 2024-11-12 | Wildcard         | L   | 0.471      | -            | -                | -                | -         |   -12.25 | biguzera, kauez, lux, nqz, snow      |
|           36 |     3577 | 2024-11-11 | Nouns Esports    | W   | 0.470      | -            | -                | -                | -         |     0.13 | biguzera, kauez, lux, nqz, snow      |
|           35 |     4471 | 2024-10-27 | B8               | L   | 0.366      | -            | -                | -                | -         |   -10.71 | biguzera, kauez, lux, nqz, snow      |
|           34 |     4590 | 2024-10-25 | Legacy           | W   | 0.353      | 0.500        | -                | 0.554 (0.098)    | -         |     0.21 | biguzera, kauez, lux, nqz, snow      |
|           33 |     4603 | 2024-10-25 | Monte            | W   | 0.352      | -            | -                | -                | -         |     0.16 | biguzera, kauez, lux, nqz, snow      |
|           32 |     4761 | 2024-10-20 | MIBR             | W   | 0.320      | 0.450        | 0.141 (0.020)    | -                | -         |     2.57 | biguzera, kauez, lux, nqz, snow      |
|           31 |     4915 | 2024-10-17 | MIBR             | W   | 0.301      | -            | -                | -                | -         |     2.46 | biguzera, kauez, lux, nqz, snow      |
|           30 |     4969 | 2024-10-16 | AdalYamigos      | W   | 0.294      | -            | -                | -                | -         |     0.09 | biguzera, kauez, lux, nqz, snow      |
|           29 |     5315 | 2024-10-09 | AdalYamigos      | L   | 0.248      | -            | -                | -                | -         |    -7.74 | biguzera, kauez, lux, nqz, snow      |
|           28 |     5323 | 2024-10-09 | AdalYamigos      | L   | 0.247      | -            | -                | -                | -         |    -7.74 | biguzera, kauez, lux, nqz, snow      |
|           27 |     5391 | 2024-10-08 | Imperial Esports | L   | 0.241      | -            | -                | -                | -         |    -7.39 | biguzera, kauez, lux, nqz, snow      |
|           26 |     5402 | 2024-10-08 | Imperial Esports | W   | 0.241      | -            | -                | -                | -         |     0.20 | biguzera, kauez, lux, nqz, snow      |
|           25 |     5411 | 2024-10-08 | MIBR             | W   | 0.240      | -            | -                | -                | -         |     1.80 | biguzera, kauez, lux, nqz, snow      |
|           24 |     5414 | 2024-10-08 | MIBR             | W   | 0.240      | -            | -                | -                | -         |     1.83 | biguzera, kauez, lux, nqz, snow      |
|           23 |     5460 | 2024-10-07 | FaZe Clan        | L   | 0.233      | -            | -                | -                | -         |    -1.25 | biguzera, kauez, lux, nqz, snow      |
|           22 |     5488 | 2024-10-07 | MOUZ             | L   | 0.232      | -            | -                | -                | -         |    -0.83 | biguzera, kauez, lux, nqz, snow      |
|           21 |     5664 | 2024-10-04 | BESTIA           | L   | 0.213      | -            | -                | -                | -         |    -6.57 | biguzera, kauez, lux, nqz, snow      |
|           20 |     5748 | 2024-10-02 | Fluxo            | L   | 0.201      | -            | -                | -                | -         |    -6.21 | biguzera, kauez, lux, nqz, snow      |
|           19 |     5754 | 2024-10-02 | Fluxo            | L   | 0.201      | -            | -                | -                | -         |    -6.21 | biguzera, kauez, lux, nqz, snow      |
|           18 |     5760 | 2024-10-02 | RED Canids       | W   | 0.200      | -            | -                | -                | -         |     0.07 | biguzera, kauez, lux, nqz, snow      |
|           17 |     5765 | 2024-10-02 | RED Canids       | L   | 0.200      | -            | -                | -                | -         |    -6.22 | biguzera, kauez, lux, nqz, snow      |
|           16 |     5823 | 2024-10-01 | Hype Esports     | W   | 0.194      | -            | -                | -                | -         |     0.03 | biguzera, kauez, lux, nqz, snow      |
|           15 |     5828 | 2024-10-01 | Hype Esports     | W   | 0.194      | -            | -                | -                | -         |     0.03 | biguzera, kauez, lux, nqz, snow      |
|           14 |     5943 | 2024-09-29 | Fluxo            | W   | 0.181      | -            | -                | -                | -         |     0.10 | biguzera, kauez, lux, nqz, snow      |
|           13 |     5946 | 2024-09-29 | Team Solid       | W   | 0.180      | -            | -                | -                | -         |     0.06 | biguzera, kauez, lux, nqz, snow      |
|           12 |     5996 | 2024-09-28 | RED Canids       | W   | 0.175      | -            | -                | -                | -         |     0.06 | biguzera, kauez, lux, nqz, snow      |
|           11 |     6004 | 2024-09-28 | Team Solid       | L   | 0.173      | -            | -                | -                | -         |    -5.41 | biguzera, kauez, lux, nqz, snow      |
|           10 |     6251 | 2024-09-25 | ODDIK            | W   | 0.155      | -            | -                | -                | -         |     0.04 | biguzera, kauez, lux, nqz, snow      |
|            9 |     6256 | 2024-09-25 | ODDIK            | W   | 0.154      | -            | -                | -                | -         |     0.04 | biguzera, kauez, lux, nqz, snow      |
|            8 |     6343 | 2024-09-24 | Sharks Esports   | W   | 0.148      | -            | -                | -                | -         |     0.13 | biguzera, kauez, lux, nqz, snow      |
|            7 |     6349 | 2024-09-24 | Sharks Esports   | W   | 0.147      | -            | -                | -                | -         |     0.13 | biguzera, kauez, lux, nqz, snow      |
|            6 |     6437 | 2024-09-23 | RED Canids       | W   | 0.140      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, snow      |
|            5 |     6475 | 2024-09-23 | InSanitY Sports  | W   | 0.139      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, snow      |
|            4 |     6670 | 2024-09-19 | KRÜ Esports      | W   | 0.114      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, snow      |
|            3 |     6673 | 2024-09-19 | KRÜ Esports      | W   | 0.114      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, snow      |
|            2 |     6732 | 2024-09-18 | BESTIA           | W   | 0.108      | -            | -                | -                | -         |     0.05 | biguzera, kauez, lux, nqz, snow      |
|            1 |     6736 | 2024-09-18 | BESTIA           | W   | 0.107      | -            | -                | -                | -         |     0.05 | biguzera, kauez, lux, nqz, snow      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,967.97)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2025-01-26 |      0.973 | $15,000.00     | $14,587.50      |
| 2024-12-15 |      0.691 | $20,000.00     | $13,818.98      |
| 2024-10-27 |      0.367 | $10,000.00     | $3,665.74       |
| 2024-10-20 |      0.320 | $20,000.00     | $6,402.78       |
| 2024-10-13 |      0.273 | $4,000.00      | $1,091.11       |
| 2024-10-05 |      0.219 | $1,832.41      | $401.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
