### Roster Details<br />
Team Name: WOPA Esport<br />
Roster: Gnøffe, n1Xen, PR1mE, sL1m3, Vster<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  803.9<br />
<br />
Final Rank Value (803.9) = Starting Rank Value (858.0) + Head To Head Adjustments (-54.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.399[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.159[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 858.0
- 400 + ( ( 0.229 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 858.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           69 |      328 | 2025-02-16 | GenOne                    | L   | 1.000      | -            | -                | -                | -         |   -14.12 | Gnøffe, n1Xen, PR1mE, sL1m3, Vster |
|           68 |     1218 | 2025-01-06 | BadGuys                   | L   | 0.838      | -            | -                | -                | -         |   -18.89 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           67 |     1222 | 2025-01-05 | Wu-Tang Clan              | W   | 0.831      | -            | -                | -                | 0 (0.000) |     7.28 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           66 |     1259 | 2024-12-29 | CS2NEWS                   | L   | 0.785      | -            | -                | -                | -         |   -20.95 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           65 |     1302 | 2024-12-28 | EYEBALLERS                | L   | 0.778      | -            | -                | -                | -         |   -15.22 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           64 |     1354 | 2024-12-25 | KONO.ECF                  | L   | 0.758      | -            | -                | -                | -         |   -10.14 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           63 |     1362 | 2024-12-24 | ENCE Academy              | W   | 0.752      | 0.333        | 0.009 (0.002)    | 0.655 (0.164)    | 0 (0.000) |     9.71 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           62 |     1366 | 2024-12-24 | ALASKA                    | L   | 0.751      | -            | -                | -                | -         |   -10.39 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           61 |     1377 | 2024-12-23 | ESC Gaming                | W   | 0.745      | -            | -                | -                | 0 (0.000) |     4.22 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           60 |     1379 | 2024-12-23 | Heimo Esports             | W   | 0.744      | 0.333        | 0.004 (0.001)    | 0.658 (0.163)    | 0 (0.000) |     7.68 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           59 |     1398 | 2024-12-22 | ADEPTS                    | W   | 0.739      | -            | -                | -                | 0 (0.000) |     6.01 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           58 |     1420 | 2024-12-22 | Astralis Talent           | W   | 0.738      | 0.333        | -                | 0.733 (0.180)    | 0 (0.000) |     9.58 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           57 |     1456 | 2024-12-21 | ALASKA                    | W   | 0.732      | 0.333        | 0.030 (0.007)    | 0.875 (0.214)    | 0 (0.000) |    13.90 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           56 |     1483 | 2024-12-21 | KONO.ECF                  | W   | 0.731      | 0.333        | 0.045 (0.011)    | 0.757 (0.184)    | 0 (0.000) |    13.24 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           55 |     1517 | 2024-12-20 | Heimo Esports             | L   | 0.725      | -            | -                | -                | -         |   -14.28 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           54 |     1557 | 2024-12-18 | Viperio                   | W   | 0.712      | 0.333        | -                | 0.411 (0.097)    | 0 (0.000) |     8.23 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           53 |     1562 | 2024-12-18 | ESC Gaming                | L   | 0.711      | -            | -                | -                | -         |   -18.14 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           52 |     1591 | 2024-12-16 | Lilmix                    | W   | 0.698      | -            | -                | -                | -         |     4.03 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           51 |     1766 | 2024-12-13 | LEON Esports              | L   | 0.680      | -            | -                | -                | -         |   -13.20 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           50 |     1825 | 2024-12-12 | AMKAL ESPORTS             | W   | 0.674      | 0.333        | -                | 0.681 (0.153)    | -         |    10.28 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           49 |     1849 | 2024-12-12 | GenOne                    | W   | 0.671      | 0.333        | 0.012 (0.003)    | 0.848 (0.190)    | -         |    11.48 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           48 |     1872 | 2024-12-11 | XPERION NXT               | W   | 0.667      | -            | -                | -                | -         |     6.16 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           47 |     1882 | 2024-12-11 | BRUTE                     | W   | 0.666      | -            | -                | -                | -         |     7.53 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           46 |     2014 | 2024-12-08 | Lilmix                    | W   | 0.645      | -            | -                | -                | -         |     4.36 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           45 |     2084 | 2024-12-07 | Lilmix                    | L   | 0.639      | -            | -                | -                | -         |   -16.17 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           44 |     2208 | 2024-12-04 | LEON Esports              | L   | 0.620      | -            | -                | -                | -         |   -11.39 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           43 |     2324 | 2024-12-02 | XI Esport                 | W   | 0.607      | -            | -                | -                | -         |     5.79 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           42 |     2408 | 2024-12-01 | Dragon Esports Club       | W   | 0.600      | 0.333        | 0.007 (0.001)    | -                | -         |     6.03 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           41 |     2576 | 2024-11-29 | Betclic Apogee Esports    | L   | 0.587      | -            | -                | -                | -         |    -7.96 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           40 |     2616 | 2024-11-28 | Team Genesium             | W   | 0.580      | -            | -                | -                | -         |     5.46 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           39 |     2681 | 2024-11-27 | Dark Cloud Esports        | L   | 0.571      | -            | -                | -                | -         |    -8.74 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           38 |     2717 | 2024-11-26 | Insilio                   | W   | 0.567      | 0.354        | -                | 0.504 (0.101)    | -         |     4.48 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           37 |     2728 | 2024-11-26 | 9INE                      | W   | 0.566      | 0.354        | 0.011 (0.002)    | -                | -         |     7.43 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           36 |     2729 | 2024-11-26 | Betclic Apogee Esports    | L   | 0.566      | -            | -                | -                | -         |    -7.86 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           35 |     2755 | 2024-11-25 | Natus Vincere Junior      | L   | 0.559      | -            | -                | -                | -         |    -4.96 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           34 |     2845 | 2024-11-23 | Astralis Talent           | W   | 0.547      | -            | -                | -                | 1 (0.547) |     7.75 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           33 |     3128 | 2024-11-20 | Dark Cloud Esports        | W   | 0.525      | 0.333        | 0.038 (0.007)    | 0.828 (0.145)    | -         |     8.56 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           32 |     3353 | 2024-11-16 | G2 Ares                   | L   | 0.497      | -            | -                | -                | -         |   -10.67 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           31 |     3412 | 2024-11-15 | HOTU                      | L   | 0.491      | -            | -                | -                | -         |   -10.85 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           30 |     3428 | 2024-11-14 | Astralis Talent           | W   | 0.487      | -            | -                | -                | -         |     6.45 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           29 |     3448 | 2024-11-14 | Denial (Danish team)      | W   | 0.486      | -            | -                | -                | -         |     4.18 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           28 |     3451 | 2024-11-14 | G2 Ares                   | L   | 0.486      | -            | -                | -                | -         |   -10.81 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           27 |     3521 | 2024-11-13 | HOTU                      | W   | 0.477      | -            | -                | -                | -         |     4.40 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           26 |     3563 | 2024-11-12 | GenOne                    | L   | 0.471      | -            | -                | -                | -         |    -7.63 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           25 |     3600 | 2024-11-11 | Astralis Talent           | L   | 0.467      | -            | -                | -                | -         |    -9.18 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           24 |     3607 | 2024-11-11 | MASONIC                   | W   | 0.466      | -            | -                | -                | -         |     3.40 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           23 |     3932 | 2024-11-05 | Preasy Esport             | W   | 0.427      | -            | -                | -                | -         |     5.42 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           22 |     3996 | 2024-11-04 | XI Esport                 | W   | 0.420      | -            | -                | -                | -         |     1.92 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           21 |     4403 | 2024-10-28 | Copenhagen Wolves Academy | W   | 0.374      | -            | -                | -                | -         |     0.82 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           20 |     4418 | 2024-10-28 | XI Esport                 | W   | 0.374      | -            | -                | -                | -         |     3.40 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           19 |     4631 | 2024-10-24 | Leo Team                  | L   | 0.344      | -            | -                | -                | -         |    -5.70 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           18 |     4675 | 2024-10-23 | Natus Vincere Junior      | L   | 0.339      | -            | -                | -                | -         |    -3.59 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           17 |     4734 | 2024-10-21 | Denial (Danish team)      | W   | 0.326      | -            | -                | -                | -         |     2.57 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           16 |     4813 | 2024-10-20 | ALASKA                    | W   | 0.318      | 0.333        | 0.030 (0.003)    | -                | -         |     8.18 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           15 |     4849 | 2024-10-19 | Ex-9INE Academy           | W   | 0.312      | -            | -                | -                | -         |     1.94 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           14 |     5019 | 2024-10-16 | Chimera Esports           | L   | 0.291      | -            | -                | -                | -         |    -4.71 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           13 |     5023 | 2024-10-16 | UNiTY esports             | W   | 0.290      | 0.333        | 0.025 (0.002)    | -                | -         |     4.70 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           12 |     5116 | 2024-10-14 | Lilmix                    | W   | 0.278      | -            | -                | -                | -         |     2.17 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           11 |     5444 | 2024-10-08 | Chimera Esports           | L   | 0.237      | -            | -                | -                | -         |    -3.75 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           10 |     5467 | 2024-10-07 | Copenhagen Wolves Academy | W   | 0.233      | -            | -                | -                | -         |     0.55 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            9 |     5472 | 2024-10-07 | Preasy Esport             | W   | 0.233      | -            | -                | -                | -         |     3.23 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            8 |     5481 | 2024-10-07 | Denial (Danish team)      | L   | 0.233      | -            | -                | -                | -         |    -5.51 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            7 |     5898 | 2024-09-30 | MASONIC                   | L   | 0.187      | -            | -                | -                | -         |    -4.36 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            6 |     5912 | 2024-09-30 | Astralis Talent           | L   | 0.186      | -            | -                | -                | -         |    -3.59 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            5 |     6314 | 2024-09-25 | ADEPTS                    | W   | 0.151      | -            | -                | -                | -         |     1.28 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            4 |     6466 | 2024-09-23 | XI Esport                 | L   | 0.139      | -            | -                | -                | -         |    -3.19 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            3 |     6470 | 2024-09-23 | XI Esport                 | W   | 0.139      | -            | -                | -                | -         |     0.54 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            2 |     6480 | 2024-09-23 | Dark Cloud Esports        | L   | 0.138      | -            | -                | -                | -         |    -2.30 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            1 |     7733 | 2024-09-03 | Viperio                   | L   | 0.006      | -            | -                | -                | -         |    -0.12 | Gnøffe, Leakz, sL1m3, Vster, zEden |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,536.22)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-25 |      0.758 | $3,000.00      | $2,274.79       |
| 2024-12-24 |      0.751 | $3,000.00      | $2,252.50       |
| 2024-12-15 |      0.692 | $1,500.00      | $1,038.33       |
| 2024-11-23 |      0.547 | $9,080.87      | $4,964.21       |
| 2024-09-04 |      0.013 | $500.00        | $6.39           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
