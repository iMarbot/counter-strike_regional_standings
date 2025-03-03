### Roster Details<br />
Team Name: HOTU<br />
Roster: kade0, lampada, mizu, Re1GN, youka<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [95]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.1<br />
<br />
Final Rank Value (786.1) = Starting Rank Value (728.7) + Head To Head Adjustments (57.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 728.7
- 400 + ( ( 0.164 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 728.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           80 |       31 | 2025-02-27 | ATOX Esports               | L   | 1.000      | -            | -                | -                | -         |    -4.53 | kade0, lampada, mizu, Re1GN, youka      |
|           79 |       44 | 2025-02-26 | Chinggis Warriors          | L   | 1.000      | -            | -                | -                | -         |   -11.74 | kade0, lampada, mizu, Re1GN, youka      |
|           78 |       62 | 2025-02-25 | Nomads (Mongolian team)    | W   | 1.000      | 0.143        | -                | 0.407 (0.058)    | 0 (0.000) |     8.12 | kade0, lampada, mizu, Re1GN, youka      |
|           77 |       91 | 2025-02-23 | ATOX Esports               | W   | 1.000      | 0.143        | 0.064 (0.009)    | 0.601 (0.086)    | 0 (0.000) |    26.94 | kade0, lampada, mizu, Re1GN, youka      |
|           76 |      366 | 2025-02-16 | Nomads (Mongolian team)    | W   | 1.000      | 0.143        | -                | 0.407 (0.058)    | 0 (0.000) |     8.76 | kade0, lampada, mizu, Re1GN, youka      |
|           75 |      370 | 2025-02-16 | ShamanKings                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.96 | kade0, lampada, mizu, Re1GN, youka      |
|           74 |      377 | 2025-02-16 | Vizora Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.40 | kade0, lampada, mizu, Re1GN, youka      |
|           73 |      387 | 2025-02-16 | Flashback Gaming           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.35 | kade0, lampada, mizu, Re1GN, youka      |
|           72 |      496 | 2025-02-14 | Eruption                   | L   | 1.000      | -            | -                | -                | -         |    -8.62 | kade0, lampada, mizu, Re1GN, youka      |
|           71 |      506 | 2025-02-14 | IHC Esports                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.22 | kade0, lampada, mizu, Re1GN, youka      |
|           70 |     1442 | 2024-12-21 | Avtostopom Po Galaktike    | L   | 0.726      | -            | -                | -                | -         |   -14.47 | kade0, lampada, mizu, Re1GN, youka      |
|           69 |     1447 | 2024-12-21 | ICE SPIRITS                | W   | 0.726      | -            | -                | -                | 0 (0.000) |     3.01 | kade0, lampada, mizu, Re1GN, youka      |
|           68 |     1498 | 2024-12-20 | Nuclear TigeRES            | L   | 0.720      | -            | -                | -                | -         |   -10.03 | kade0, lampada, mizu, Re1GN, youka      |
|           67 |     1502 | 2024-12-20 | Soul's Heart Esport        | W   | 0.719      | -            | -                | -                | 0 (0.000) |     2.89 | kade0, lampada, mizu, Re1GN, youka      |
|           66 |     2511 | 2024-11-30 | K27                        | L   | 0.585      | -            | -                | -                | -         |    -6.30 | kade0, lampada, mizu, Pumpkin66, Re1GN  |
|           65 |     2795 | 2024-11-24 | ARCRED                     | W   | 0.545      | 0.262        | 0.018 (0.003)    | 0.480 (0.068)    | 0 (0.000) |     9.81 | fineshine, kade0, lampada, mizu, Re1GN  |
|           64 |     2802 | 2024-11-24 | NEVERMORE (Ukrainian team) | W   | 0.544      | 0.262        | 0.010 (0.001)    | 0.904 (0.129)    | -         |     9.45 | fineshine, kade0, lampada, mizu, Re1GN  |
|           63 |     2824 | 2024-11-24 | K27                        | L   | 0.543      | -            | -                | -                | -         |    -5.68 | fineshine, kade0, lampada, mizu, Re1GN  |
|           62 |     2849 | 2024-11-23 | CS2NEWS                    | W   | 0.539      | -            | -                | -                | -         |     4.37 | kade0, lampada, mizu, Re1GN, youka      |
|           61 |     2867 | 2024-11-23 | VP.Prodigy                 | W   | 0.538      | -            | -                | -                | -         |     3.37 | kade0, lampada, mizu, Re1GN, youka      |
|           60 |     2956 | 2024-11-22 | GamerLegion Academy        | W   | 0.532      | -            | -                | -                | -         |     5.23 | fineshine, kade0, lampada, mizu, Re1GN  |
|           59 |     3021 | 2024-11-21 | The Suspect                | W   | 0.525      | -            | -                | -                | -         |     8.49 | fineshine, kade0, lampada, mizu, Re1GN  |
|           58 |     3035 | 2024-11-21 | GTZ.ESPORTS                | W   | 0.525      | 0.372        | 0.080 (0.016)    | 0.557 (0.109)    | -         |    15.30 | fineshine, kade0, lampada, mizu, Re1GN  |
|           57 |     3106 | 2024-11-20 | Ex-9INE Academy            | W   | 0.519      | -            | -                | -                | -         |     4.86 | fineshine, kade0, lampada, mizu, Re1GN  |
|           56 |     3257 | 2024-11-17 | VP.Prodigy                 | W   | 0.497      | -            | -                | -                | -         |     3.73 | fineshine, kade0, lampada, mizu, Re1GN  |
|           55 |     3271 | 2024-11-17 | Hyuga                      | L   | 0.497      | -            | -                | -                | -         |   -11.27 | fineshine, kade0, lampada, mizu, Re1GN  |
|           54 |     3285 | 2024-11-17 | Donstu Esports             | W   | 0.496      | -            | -                | -                | -         |     3.93 | fineshine, kade0, lampada, mizu, Re1GN  |
|           53 |     3366 | 2024-11-16 | Chimera Esports            | L   | 0.489      | -            | -                | -                | -         |    -4.33 | fineshine, kade0, lampada, mizu, Re1GN  |
|           52 |     3424 | 2024-11-15 | WOPA Esport                | W   | 0.483      | 0.143        | 0.032 (0.002)    | 0.777 (0.054)    | -         |    10.66 | fineshine, kade0, lampada, mizu, Re1GN  |
|           51 |     3488 | 2024-11-14 | Daystar                    | W   | 0.476      | -            | -                | -                | -         |     6.08 | fineshine, kade0, lampada, mizu, Re1GN  |
|           50 |     3533 | 2024-11-13 | WOPA Esport                | L   | 0.469      | -            | -                | -                | -         |    -4.34 | fineshine, kade0, lampada, mizu, Re1GN  |
|           49 |     3603 | 2024-11-11 | Ex-Soul's Heart Esport     | W   | 0.459      | -            | -                | -                | -         |     6.12 | anttzz, fineshine, lampada, mizu, Re1GN |
|           48 |     3911 | 2024-11-06 | Zero Tenacity              | L   | 0.423      | -            | -                | -                | -         |    -3.67 | anttzz, fineshine, lampada, mizu, Re1GN |
|           47 |     3997 | 2024-11-04 | Soul's Heart Esport        | L   | 0.412      | -            | -                | -                | -         |    -9.03 | anttzz, fineshine, lampada, mizu, Re1GN |
|           46 |     4017 | 2024-11-04 | Johnny Speeds              | L   | 0.411      | -            | -                | -                | -         |    -2.81 | anttzz, fineshine, lampada, mizu, Re1GN |
|           45 |     4082 | 2024-11-03 | VP.Prodigy                 | W   | 0.404      | -            | -                | -                | -         |     2.79 | anttzz, fineshine, lampada, mizu, Re1GN |
|           44 |     4089 | 2024-11-03 | MOLEGAN                    | W   | 0.403      | -            | -                | -                | -         |     2.06 | anttzz, fineshine, lampada, mizu, Re1GN |
|           43 |     4211 | 2024-11-01 | Chimera Esports            | L   | 0.391      | -            | -                | -                | -         |    -3.63 | anttzz, fineshine, lampada, mizu, Re1GN |
|           42 |     4218 | 2024-11-01 | Tricked Esport             | L   | 0.390      | -            | -                | -                | -         |    -3.55 | anttzz, fineshine, lampada, mizu, Re1GN |
|           41 |     4258 | 2024-10-31 | Lausanne-Sport Esports     | L   | 0.385      | -            | -                | -                | -         |    -8.40 | anttzz, fineshine, lampada, mizu, Re1GN |
|           40 |     4396 | 2024-10-29 | SINNERS Esports            | W   | 0.370      | 0.384        | 0.027 (0.004)    | 0.446 (0.063)    | -         |     8.90 | anttzz, fineshine, lampada, mizu, Re1GN |
|           39 |     4448 | 2024-10-28 | TEAM NEXT LEVEL            | L   | 0.365      | -            | -                | -                | -         |    -6.07 | anttzz, fineshine, lampada, mizu, Re1GN |
|           38 |     4482 | 2024-10-27 | 1win                       | L   | 0.358      | -            | -                | -                | -         |    -5.26 | anttzz, fineshine, lampada, mizu, Re1GN |
|           37 |     4491 | 2024-10-27 | 9INE                       | L   | 0.357      | -            | -                | -                | -         |    -4.51 | anttzz, fineshine, lampada, mizu, Re1GN |
|           36 |     4639 | 2024-10-24 | UNiTY esports              | W   | 0.337      | 0.384        | 0.025 (0.003)    | 0.403 (0.052)    | -         |     7.28 | anttzz, fineshine, lampada, mizu, Re1GN |
|           35 |     4667 | 2024-10-23 | Passion UA                 | L   | 0.332      | -            | -                | -                | -         |    -1.46 | anttzz, fineshine, lampada, mizu, Re1GN |
|           34 |     4768 | 2024-10-21 | 9INE                       | L   | 0.315      | -            | -                | -                | -         |    -4.14 | anttzz, fineshine, lampada, mizu, Re1GN |
|           33 |     4782 | 2024-10-20 | K27                        | L   | 0.311      | -            | -                | -                | -         |    -2.40 | anttzz, fineshine, lampada, mizu, Re1GN |
|           32 |     4793 | 2024-10-20 | QUAZAR Academy             | W   | 0.311      | -            | -                | -                | -         |     1.43 | anttzz, fineshine, lampada, mizu, Re1GN |
|           31 |     4961 | 2024-10-17 | TSM                        | W   | 0.290      | 0.384        | 0.009 (0.001)    | -                | -         |     5.13 | anttzz, fineshine, lampada, mizu, Re1GN |
|           30 |     5013 | 2024-10-16 | THE SPELLS                 | L   | 0.284      | -            | -                | -                | -         |    -6.50 | anttzz, fineshine, lampada, mizu, Re1GN |
|           29 |     5091 | 2024-10-15 | ALTERNATE aTTaX            | W   | 0.276      | 0.384        | 0.021 (0.002)    | 0.552 (0.059)    | -         |     6.66 | anttzz, fineshine, lampada, mizu, Re1GN |
|           28 |     5166 | 2024-10-13 | RUSTEC                     | L   | 0.263      | -            | -                | -                | -         |    -4.58 | anttzz, fineshine, lampada, mizu, Re1GN |
|           27 |     5254 | 2024-10-12 | NO BYSTANDERS              | L   | 0.256      | -            | -                | -                | -         |    -6.31 | anttzz, fineshine, lampada, mizu, Re1GN |
|           26 |     5280 | 2024-10-11 | Tricked Esport             | L   | 0.250      | -            | -                | -                | -         |    -2.77 | anttzz, fineshine, lampada, mizu, Re1GN |
|           25 |     5350 | 2024-10-09 | Daystar                    | L   | 0.238      | -            | -                | -                | -         |    -4.58 | anttzz, fineshine, lampada, mizu, Re1GN |
|           24 |     5382 | 2024-10-09 | 500                        | L   | 0.235      | -            | -                | -                | -         |    -1.39 | anttzz, fineshine, lampada, mizu, Re1GN |
|           23 |     5477 | 2024-10-07 | UNiTY esports              | L   | 0.225      | -            | -                | -                | -         |    -2.42 | anttzz, fineshine, lampada, mizu, Re1GN |
|           22 |     5555 | 2024-10-06 | CYBERSHOKE Esports         | L   | 0.216      | -            | -                | -                | -         |    -2.31 | anttzz, fineshine, lampada, mizu, Re1GN |
|           21 |     5788 | 2024-10-02 | FAVBET Team                | L   | 0.190      | -            | -                | -                | -         |    -2.23 | anttzz, fineshine, lampada, mizu, Re1GN |
|           20 |     5812 | 2024-10-02 | Tricked Esport             | W   | 0.189      | 0.384        | 0.034 (0.002)    | -                | -         |     3.79 | anttzz, fineshine, lampada, mizu, Re1GN |
|           19 |     5882 | 2024-10-01 | GUN5 Esports               | L   | 0.183      | -            | -                | -                | -         |    -1.44 | anttzz, fineshine, lampada, mizu, Re1GN |
|           18 |     5893 | 2024-10-01 | ALTERNATE aTTaX            | L   | 0.182      | -            | -                | -                | -         |    -1.50 | anttzz, fineshine, lampada, mizu, Re1GN |
|           17 |     5999 | 2024-09-29 | AMKAL ESPORTS              | W   | 0.169      | -            | -                | -                | -         |     3.04 | anttzz, fineshine, lampada, mizu, Re1GN |
|           16 |     6082 | 2024-09-28 | ENCE Academy               | W   | 0.163      | -            | -                | -                | -         |     3.13 | anttzz, fineshine, lampada, mizu, Re1GN |
|           15 |     6324 | 2024-09-25 | Daystar                    | W   | 0.143      | -            | -                | -                | -         |     1.76 | anttzz, fineshine, lampada, mizu, Re1GN |
|           14 |     6403 | 2024-09-24 | ENCE Academy               | L   | 0.137      | -            | -                | -                | -         |    -1.68 | anttzz, fineshine, lampada, mizu, Re1GN |
|           13 |     6532 | 2024-09-22 | ARCRED                     | W   | 0.124      | -            | -                | -                | -         |     2.10 | anttzz, fineshine, lampada, mizu, Re1GN |
|           12 |     6545 | 2024-09-22 | WW Team                    | L   | 0.122      | -            | -                | -                | -         |    -3.00 | anttzz, fineshine, lampada, mizu, Re1GN |
|           11 |     6645 | 2024-09-20 | AMKAL ESPORTS              | L   | 0.111      | -            | -                | -                | -         |    -1.59 | anttzz, fineshine, lampada, mizu, Re1GN |
|           10 |     6710 | 2024-09-19 | CYBERSHOKE Esports         | L   | 0.104      | -            | -                | -                | -         |    -1.07 | anttzz, fineshine, lampada, mizu, Re1GN |
|            9 |     6725 | 2024-09-19 | GenOne                     | W   | 0.102      | -            | -                | -                | -         |     2.05 | anttzz, fineshine, lampada, mizu, Re1GN |
|            8 |     7097 | 2024-09-13 | FAVBET Team                | L   | 0.064      | -            | -                | -                | -         |    -0.71 | anttzz, fineshine, lampada, mizu, Re1GN |
|            7 |     7113 | 2024-09-13 | Ex-ENTERPRISE esports      | W   | 0.063      | -            | -                | -                | -         |     0.97 | anttzz, fineshine, lampada, mizu, Re1GN |
|            6 |     7199 | 2024-09-11 | Passion UA                 | W   | 0.051      | -            | -                | -                | -         |     1.36 | anttzz, fineshine, lampada, mizu, Re1GN |
|            5 |     7357 | 2024-09-08 | Team Spirit Academy        | L   | 0.031      | -            | -                | -                | -         |    -0.25 | anttzz, fineshine, lampada, mizu, Re1GN |
|            4 |     7509 | 2024-09-06 | FLuffy Gangsters           | L   | 0.018      | -            | -                | -                | -         |    -0.24 | anttzz, fineshine, lampada, mizu, Re1GN |
|            3 |     7528 | 2024-09-06 | FORZE Reload               | W   | 0.018      | -            | -                | -                | -         |     0.37 | anttzz, fineshine, lampada, mizu, Re1GN |
|            2 |     7584 | 2024-09-05 | MOUZ NXT                   | W   | 0.012      | -            | -                | -                | -         |     0.08 | anttzz, fineshine, lampada, mizu, Re1GN |
|            1 |     7616 | 2024-09-05 | RUSH B (Russian team)      | W   | 0.011      | -            | -                | -                | -         |     0.24 | anttzz, fineshine, lampada, mizu, Re1GN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,046.25)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.545 | $1,000.00      | $544.70         |
| 2024-11-03 |      0.405 | $1,021.74      | $413.95         |
| 2024-09-21 |      0.117 | $750.00        | $87.60          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
