### Roster Details<br />
Team Name: Dark Cloud Esports<br />
Roster: AdrieN, chudy, darchevile, mwlky, Nami<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  839.0<br />
<br />
Final Rank Value (839.0) = Starting Rank Value (841.4) + Head To Head Adjustments (-2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 841.4
- 400 + ( ( 0.221 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 841.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           76 |      147 | 2025-02-22 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -15.39 | AdrieN, chudy, darchevile, mwlky, Nami   |
|           75 |      200 | 2025-02-21 | Tricked Esport                            | L   | 1.000      | -            | -                | -                | -         |   -15.05 | AdrieN, chudy, darchevile, mwlky, Nami   |
|           74 |      212 | 2025-02-21 | 1win                                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.60 | AdrieN, chudy, darchevile, mwlky, Nami   |
|           73 |      239 | 2025-02-20 | SEight                                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.25 | AdrieN, chudy, darchevile, mwlky, Nami   |
|           72 |     1223 | 2025-01-04 | Insilio                                   | L   | 0.826      | -            | -                | -                | -         |   -18.56 | chudy, darchevile, Enzo, Michat, Nami    |
|           71 |     1239 | 2024-12-30 | KONO.ECF                                  | L   | 0.792      | -            | -                | -                | -         |    -9.80 | Bambosh, chudy, darchevile, Melavi, Nami |
|           70 |     1257 | 2024-12-29 | Copenhagen Wolves (American organization) | W   | 0.786      | 0.333        | 0.016 (0.004)    | 1.000 (0.262)    | 0 (0.000) |    13.39 | Bambosh, chudy, darchevile, Melavi, Nami |
|           69 |     1264 | 2024-12-29 | BRUTE                                     | W   | 0.784      | -            | -                | -                | 0 (0.000) |     7.10 | chudy, darchevile, Michat, Nami, next1me |
|           68 |     1287 | 2024-12-28 | Preasy Esport                             | W   | 0.780      | 0.333        | 0.012 (0.003)    | 0.710 (0.185)    | 0 (0.000) |     8.62 | Bambosh, chudy, darchevile, Melavi, Nami |
|           67 |     1337 | 2024-12-27 | 9INE                                      | L   | 0.771      | -            | -                | -                | -         |    -8.66 | chudy, darchevile, Enzo, Michat, Nami    |
|           66 |     1343 | 2024-12-26 | M1Z                                       | W   | 0.767      | -            | -                | -                | 0 (0.000) |     1.98 | Bambosh, chudy, darchevile, Enzo, Nami   |
|           65 |     1344 | 2024-12-26 | BRUTE                                     | W   | 0.767      | -            | -                | -                | 0 (0.000) |     7.39 | Bambosh, chudy, darchevile, Enzo, Nami   |
|           64 |     1470 | 2024-12-21 | Astralis Talent                           | L   | 0.732      | -            | -                | -                | -         |   -14.03 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           63 |     1482 | 2024-12-21 | VOLT (European team)                      | W   | 0.731      | -            | -                | -                | 0 (0.000) |     6.97 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           62 |     1504 | 2024-12-20 | Monte                                     | L   | 0.726      | -            | -                | -                | -         |    -8.02 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           61 |     1510 | 2024-12-20 | XI Esport                                 | W   | 0.726      | -            | -                | -                | 0 (0.000) |     6.55 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           60 |     1521 | 2024-12-20 | ALASKA                                    | L   | 0.724      | -            | -                | -                | -         |   -10.00 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           59 |     1527 | 2024-12-19 | FLuffy Gangsters                          | W   | 0.720      | 0.333        | 0.014 (0.003)    | 0.925 (0.222)    | 0 (0.000) |    10.88 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           58 |     1536 | 2024-12-19 | Wu-Tang Clan                              | W   | 0.719      | -            | -                | -                | -         |     6.21 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           57 |     1568 | 2024-12-17 | KONO.ECF                                  | W   | 0.706      | 0.333        | 0.045 (0.011)    | 0.757 (0.178)    | -         |    11.66 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           56 |     1583 | 2024-12-16 | Viperio                                   | W   | 0.700      | -            | -                | -                | -         |     8.60 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           55 |     1625 | 2024-12-15 | ENCE Academy                              | W   | 0.693      | 0.333        | -                | 0.655 (0.151)    | -         |    10.12 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           54 |     1642 | 2024-12-15 | JANO Esports                              | W   | 0.691      | 0.333        | 0.022 (0.005)    | -                | -         |    12.10 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           53 |     1777 | 2024-12-13 | Heimo Esports                             | L   | 0.680      | -            | -                | -                | -         |   -13.52 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           52 |     1824 | 2024-12-12 | ADEPTS                                    | W   | 0.674      | -            | -                | -                | -         |     6.20 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           51 |     1896 | 2024-12-11 | FORZE Reload                              | L   | 0.665      | -            | -                | -                | -         |    -9.07 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           50 |     1954 | 2024-12-09 | ENCE Academy                              | W   | 0.652      | 0.333        | -                | 0.655 (0.142)    | -         |     9.42 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           49 |     1962 | 2024-12-09 | AMKAL ESPORTS                             | L   | 0.651      | -            | -                | -                | -         |   -10.96 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           48 |     2280 | 2024-12-03 | Illuminar Gaming                          | L   | 0.612      | -            | -                | -                | -         |    -9.96 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           47 |     2343 | 2024-12-02 | Chroma                                    | L   | 0.606      | -            | -                | -                | -         |   -13.46 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           46 |     2351 | 2024-12-02 | Betclic Apogee Esports                    | W   | 0.605      | 0.333        | 0.012 (0.002)    | -                | -         |    10.81 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           45 |     2446 | 2024-12-01 | GenOne                                    | L   | 0.598      | -            | -                | -                | -         |    -9.56 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           44 |     2587 | 2024-11-29 | BC.Game Esports                           | L   | 0.586      | -            | -                | -                | -         |    -8.43 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           43 |     2599 | 2024-11-29 | SkyFury                                   | W   | 0.584      | -            | -                | -                | -         |     5.02 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           42 |     2644 | 2024-11-28 | Illuminar Gaming                          | L   | 0.579      | -            | -                | -                | -         |   -10.21 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           41 |     2648 | 2024-11-28 | ENCE Academy                              | W   | 0.578      | -            | -                | -                | -         |     7.50 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           40 |     2676 | 2024-11-27 | Fragmatic                                 | W   | 0.572      | -            | -                | -                | -         |     2.94 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           39 |     2681 | 2024-11-27 | WOPA Esport                               | W   | 0.571      | 0.333        | 0.031 (0.006)    | 0.785 (0.149)    | -         |     8.74 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           38 |     2761 | 2024-11-25 | FORZE Reload                              | L   | 0.558      | -            | -                | -                | -         |    -8.39 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           37 |     2803 | 2024-11-24 | Heimo Esports                             | W   | 0.551      | -            | -                | -                | -         |     5.52 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           36 |     2832 | 2024-11-23 | Viperio                                   | W   | 0.547      | -            | -                | -                | -         |     6.03 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           35 |     2942 | 2024-11-22 | FLuffy Gangsters                          | W   | 0.540      | 0.333        | 0.014 (0.003)    | 0.925 (0.167)    | -         |     8.88 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           34 |     3128 | 2024-11-20 | WOPA Esport                               | L   | 0.525      | -            | -                | -                | -         |    -8.56 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           33 |     3252 | 2024-11-17 | Leo Team                                  | L   | 0.505      | -            | -                | -                | -         |    -7.44 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           32 |     3329 | 2024-11-16 | Kubix Esports                             | L   | 0.499      | -            | -                | -                | -         |    -6.11 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           31 |     3477 | 2024-11-14 | Leo Team                                  | W   | 0.484      | 0.333        | 0.026 (0.004)    | -                | -         |     7.93 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           30 |     3570 | 2024-11-12 | Astralis Talent                           | W   | 0.471      | -            | -                | -                | -         |     6.16 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           29 |     3682 | 2024-11-10 | GenOne                                    | W   | 0.458      | 0.333        | -                | 0.848 (0.129)    | -         |     7.27 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           28 |     4000 | 2024-11-04 | Haspers Team                              | W   | 0.420      | -            | -                | -                | -         |     4.54 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           27 |     4088 | 2024-11-03 | Copenhagen Wolves (American organization) | W   | 0.411      | 0.333        | 0.016 (0.002)    | 1.000 (0.137)    | -         |     6.93 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           26 |     4327 | 2024-10-30 | Lilmix                                    | W   | 0.385      | -            | -                | -                | -         |     3.29 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           25 |     4369 | 2024-10-29 | Illuminar Gaming                          | W   | 0.380      | -            | -                | -                | -         |     6.82 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           24 |     4719 | 2024-10-21 | Dynamo Eclot                              | L   | 0.327      | -            | -                | -                | -         |    -2.09 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           23 |     5461 | 2024-10-07 | Mission Possible                          | L   | 0.233      | -            | -                | -                | -         |    -6.15 | chudy2k, darchevile, michat, Nami, yvro  |
|           22 |     5483 | 2024-10-07 | Error404                                  | W   | 0.233      | -            | -                | -                | -         |     0.64 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           21 |     5802 | 2024-10-02 | Illuminar Gaming                          | L   | 0.197      | -            | -                | -                | -         |    -2.67 | chudy2k, darchevile, Enzo, morelz, Nami  |
|           20 |     6034 | 2024-09-28 | Tibian Soldiers                           | W   | 0.173      | -            | -                | -                | -         |     0.46 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           19 |     6117 | 2024-09-27 | Haspers Team                              | L   | 0.166      | -            | -                | -                | -         |    -3.46 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           18 |     6159 | 2024-09-27 | The Suspect                               | L   | 0.164      | -            | -                | -                | -         |    -3.32 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           17 |     6235 | 2024-09-26 | AMKAL ESPORTS                             | L   | 0.157      | -            | -                | -                | -         |    -2.88 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           16 |     6360 | 2024-09-24 | GameAgents                                | W   | 0.147      | -            | -                | -                | -         |     1.44 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           15 |     6381 | 2024-09-24 | Los kogutos                               | L   | 0.146      | -            | -                | -                | -         |    -1.31 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           14 |     6420 | 2024-09-24 | UNiTY esports                             | L   | 0.144      | -            | -                | -                | -         |    -2.22 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           13 |     6453 | 2024-09-23 | Ex-Soul's Heart Esport                    | L   | 0.140      | -            | -                | -                | -         |    -3.35 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           12 |     6480 | 2024-09-23 | WOPA Esport                               | W   | 0.138      | -            | -                | -                | -         |     2.30 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           11 |     6647 | 2024-09-20 | Wild Lotus                                | L   | 0.118      | -            | -                | -                | -         |    -2.33 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           10 |     6808 | 2024-09-17 | Ins (Polish team)                         | W   | 0.100      | -            | -                | -                | -         |     0.89 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            9 |     6825 | 2024-09-17 | WiLD MultiGaming                          | W   | 0.100      | -            | -                | -                | -         |     0.69 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            8 |     7321 | 2024-09-09 | Astralis Talent                           | L   | 0.044      | -            | -                | -                | -         |    -0.80 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            7 |     7360 | 2024-09-08 | SINNERS Academy                           | L   | 0.038      | -            | -                | -                | -         |    -0.76 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            6 |     7404 | 2024-09-07 | Daystar                                   | L   | 0.033      | -            | -                | -                | -         |    -0.78 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            5 |     7624 | 2024-09-05 | ADEPTS                                    | L   | 0.018      | -            | -                | -                | -         |    -0.40 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            4 |     7646 | 2024-09-04 | Iuhop (Russian team)                      | L   | 0.013      | -            | -                | -                | -         |    -0.37 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            3 |     7661 | 2024-09-04 | Cerberus eSports (Russian team)           | W   | 0.013      | -            | -                | -                | -         |     0.08 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            2 |     7678 | 2024-09-04 | Natus Vincere Junior                      | L   | 0.011      | -            | -                | -                | -         |    -0.12 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            1 |     7731 | 2024-09-03 | Endpoint                                  | L   | 0.006      | -            | -                | -                | -         |    -0.11 | chudy2k, darchevile, Enzo, Nami, yvro    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,946.92)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.792 | $2,000.00      | $1,583.33       |
| 2024-12-21 |      0.732 | $1,000.00      | $732.08         |
| 2024-12-21 |      0.731 | $2,700.00      | $1,973.25       |
| 2024-12-03 |      0.613 | $500.00        | $306.60         |
| 2024-11-17 |      0.505 | $3,000.00      | $1,515.42       |
| 2024-11-16 |      0.499 | $13,708.02     | $6,836.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
