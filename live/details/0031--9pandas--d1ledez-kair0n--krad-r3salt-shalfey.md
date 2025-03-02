### Roster Details<br />
Team Name: 9Pandas<br />
Roster: d1Ledez, KaiR0N-, Krad, r3salt, shalfey<br />
Global Rank: [31](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1052.8<br />
<br />
Final Rank Value (1052.8) = Starting Rank Value (979.8) + Head To Head Adjustments (73.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.483[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.179[<sup>2</sup>](#table1)
- LAN Wins: 0.125[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 979.8
- 400 + ( ( 0.290 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 979.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |      107 | 2025-02-23 | B8                                        | L   | 1.000      | -            | -                | -                | -         |   -12.82 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           49 |      170 | 2025-02-22 | Dynamo Eclot                              | W   | 1.000      | 0.435        | 0.127 (0.055)    | 0.703 (0.306)    | 0 (0.000) |    14.62 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           48 |      251 | 2025-02-20 | Sashi Esport                              | W   | 1.000      | 0.435        | -                | 0.503 (0.218)    | 0 (0.000) |    11.21 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           47 |      506 | 2025-02-13 | 500                                       | L   | 1.000      | -            | -                | -                | -         |   -13.66 | d1Ledez, Krad, mo0N, r3salt, shalfey            |
|           46 |     1186 | 2025-01-14 | Team Liquid                               | L   | 0.893      | -            | -                | -                | -         |    -1.71 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           45 |     1190 | 2025-01-12 | Wildcard                                  | L   | 0.879      | -            | -                | -                | -         |    -4.71 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           44 |     1194 | 2025-01-11 | EYEBALLERS                                | W   | 0.872      | 0.417        | 0.019 (0.007)    | 0.356 (0.129)    | 0 (0.000) |     6.24 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           43 |     1201 | 2025-01-10 | GenOne                                    | W   | 0.865      | 0.417        | -                | 0.848 (0.306)    | 0 (0.000) |     6.56 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           42 |     2819 | 2024-11-23 | Ninjas in Pyjamas                         | L   | 0.549      | -            | -                | -                | -         |   -12.32 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           41 |     2921 | 2024-11-22 | Aurora Gaming                             | W   | 0.543      | -            | -                | -                | 1 (0.543) |     3.83 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           40 |     3002 | 2024-11-21 | Virtus.pro                                | L   | 0.536      | -            | -                | -                | -         |    -0.67 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           39 |     3052 | 2024-11-21 | G2 Esports                                | L   | 0.531      | -            | -                | -                | -         |    -0.22 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           38 |     3064 | 2024-11-20 | Astralis                                  | W   | 0.530      | 0.143        | 0.609 (0.046)    | -                | 1 (0.530) |    16.51 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           37 |     3631 | 2024-11-11 | Dynamo Eclot                              | W   | 0.464      | 0.371        | 0.127 (0.022)    | -                | 0 (0.000) |     8.12 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           36 |     3653 | 2024-11-10 | Dynamo Eclot                              | W   | 0.460      | 0.384        | 0.127 (0.022)    | 0.703 (0.124)    | 0 (0.000) |     8.37 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           35 |     3675 | 2024-11-10 | 500                                       | L   | 0.458      | -            | -                | -                | -         |    -7.52 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           34 |     3724 | 2024-11-09 | Tricked Esport                            | W   | 0.453      | 0.384        | 0.033 (0.006)    | 0.696 (0.121)    | 0 (0.000) |     4.19 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           33 |     3737 | 2024-11-09 | Natus Vincere Junior                      | W   | 0.452      | 0.371        | 0.091 (0.015)    | 0.878 (0.147)    | 0 (0.000) |     6.80 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           32 |     3806 | 2024-11-08 | Fire Flux Esports                         | W   | 0.445      | 0.384        | -                | 1.000 (0.171)    | -         |     4.87 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           31 |     3843 | 2024-11-07 | Aurora Gaming                             | L   | 0.439      | -            | -                | -                | -         |   -10.52 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           30 |     3852 | 2024-11-07 | Dynamo Eclot                              | W   | 0.438      | 0.371        | 0.127 (0.021)    | -                | -         |     7.83 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           29 |     3935 | 2024-11-05 | Insilio                                   | W   | 0.427      | -            | -                | -                | -         |     1.43 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           28 |     3955 | 2024-11-05 | Los kogutos                               | W   | 0.425      | -            | -                | -                | -         |     4.63 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           27 |     4072 | 2024-11-03 | Tricked Esport                            | W   | 0.412      | -            | -                | -                | -         |     3.99 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           26 |     4139 | 2024-11-02 | Endpoint                                  | W   | 0.406      | -            | -                | -                | -         |     2.89 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           25 |     4207 | 2024-11-01 | Natus Vincere Junior                      | W   | 0.398      | 0.371        | 0.091 (0.013)    | 0.878 (0.129)    | -         |     6.23 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           24 |     4264 | 2024-10-31 | 9INE                                      | W   | 0.391      | -            | -                | -                | -         |     3.17 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           23 |     4325 | 2024-10-30 | Johnny Speeds                             | W   | 0.385      | 0.384        | 0.039 (0.006)    | -                | -         |     4.90 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           22 |     4442 | 2024-10-28 | ALASKA                                    | W   | 0.372      | -            | -                | -                | -         |     7.62 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           21 |     4600 | 2024-10-25 | Fire Flux Esports                         | W   | 0.352      | 0.384        | -                | 1.000 (0.135)    | -         |     4.18 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           20 |     4809 | 2024-10-20 | Dynamo Eclot                              | L   | 0.318      | -            | -                | -                | -         |    -3.97 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           19 |     4927 | 2024-10-17 | SAW                                       | L   | 0.299      | -            | -                | -                | -         |    -1.20 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           18 |     4996 | 2024-10-16 | TSM                                       | W   | 0.293      | -            | -                | -                | -         |     2.06 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           17 |     5059 | 2024-10-15 | Zero Tenacity                             | W   | 0.286      | -            | -                | -                | -         |     3.16 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           16 |     5205 | 2024-10-12 | NewBALLS                                  | W   | 0.265      | -            | -                | -                | -         |     1.22 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           15 |     5526 | 2024-10-06 | GamerLegion                               | L   | 0.225      | -            | -                | -                | -         |    -0.23 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           14 |     5589 | 2024-10-05 | ECSTATIC                                  | W   | 0.219      | -            | -                | -                | -         |     2.66 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           13 |     5667 | 2024-10-04 | AMKAL ESPORTS                             | W   | 0.212      | -            | -                | -                | -         |     1.71 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           12 |     6534 | 2024-09-22 | Nemiga Gaming                             | L   | 0.131      | -            | -                | -                | -         |    -1.81 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           11 |     6577 | 2024-09-21 | Nexus Gaming                              | L   | 0.126      | -            | -                | -                | -         |    -0.96 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           10 |     6590 | 2024-09-21 | Devils.one                                | W   | 0.125      | -            | -                | -                | -         |     0.57 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            9 |     6624 | 2024-09-20 | Wild Lotus                                | W   | 0.120      | -            | -                | -                | -         |     0.82 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            8 |     6690 | 2024-09-19 | Copenhagen Wolves (American organization) | L   | 0.113      | -            | -                | -                | -         |    -3.28 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            7 |     6706 | 2024-09-19 | Nemiga Gaming                             | L   | 0.111      | -            | -                | -                | -         |    -1.56 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            6 |     6831 | 2024-09-17 | The Suspect                               | W   | 0.100      | -            | -                | -                | -         |     0.62 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            5 |     6894 | 2024-09-16 | Los kogutos                               | L   | 0.092      | -            | -                | -                | -         |    -1.31 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            4 |     6929 | 2024-09-15 | K27                                       | W   | 0.086      | -            | -                | -                | -         |     1.17 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            3 |     6941 | 2024-09-15 | Johnny Speeds                             | L   | 0.085      | -            | -                | -                | -         |    -1.65 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            2 |     6953 | 2024-09-15 | Underrated                                | W   | 0.084      | -            | -                | -                | -         |     0.45 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            1 |     7499 | 2024-09-06 | B8                                        | W   | 0.026      | -            | -                | -                | -         |     0.56 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,512.41)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $5,000.00      | $5,000.00       |
| 2025-01-12 |      0.879 | $10,000.00     | $8,788.89       |
| 2024-11-12 |      0.473 | $500.00        | $236.31         |
| 2024-11-11 |      0.464 | $11,000.00     | $5,105.83       |
| 2024-11-10 |      0.460 | $12,500.00     | $5,750.00       |
| 2024-11-09 |      0.452 | $15.18         | $6.87           |
| 2024-10-20 |      0.319 | $6,000.00      | $1,913.33       |
| 2024-10-06 |      0.226 | $5,000.00      | $1,132.29       |
| 2024-09-24 |      0.145 | $4,000.00      | $578.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
