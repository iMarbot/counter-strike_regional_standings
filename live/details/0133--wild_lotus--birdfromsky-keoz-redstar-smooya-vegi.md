### Roster Details<br />
Team Name: Wild Lotus<br />
Roster: birdfromsky, Keoz, REDSTAR, smooya, Vegi<br />
Global Rank: [133](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [94]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.8<br />
<br />
Final Rank Value (786.8) = Starting Rank Value (738.5) + Head To Head Adjustments (48.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.255[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 738.5
- 400 + ( ( 0.169 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 738.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       56 | 2025-02-25 | Fire Flux Esports                         | L   | 1.000      | -            | -                | -                | -         |   -10.23 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           54 |       71 | 2025-02-24 | Aurora Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -14.40 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           53 |      148 | 2025-02-22 | Alliance                                  | L   | 1.000      | -            | -                | -                | -         |   -13.31 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           52 |      211 | 2025-02-21 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |   -11.18 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           51 |      222 | 2025-02-21 | GhoulsW                                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.83 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           50 |      247 | 2025-02-20 | Nordix Esport                             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.56 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           49 |     1118 | 2025-01-29 | Copenhagen Wolves (American organization) | W   | 0.985      | 0.143        | -                | 1.000 (0.141)    | 0 (0.000) |    18.32 | Keoz, REDSTAR, reiko, sinnopsyy, smooya       |
|           48 |     1127 | 2025-01-28 | Zero Tenacity                             | W   | 0.979      | 0.143        | 0.028 (0.004)    | 0.684 (0.096)    | 0 (0.000) |    18.60 | Keoz, REDSTAR, reiko, sinnopsyy, smooya       |
|           47 |     1131 | 2025-01-27 | AMKAL ESPORTS                             | L   | 0.972      | -            | -                | -                | -         |   -13.13 | Keoz, REDSTAR, reiko, sinnopsyy, smooya       |
|           46 |     1786 | 2024-12-13 | AMKAL ESPORTS                             | L   | 0.672      | -            | -                | -                | -         |    -9.91 | hAdji, Keoz, REDSTAR, sinnopsyy, smooya       |
|           45 |     1998 | 2024-12-08 | 9INE                                      | W   | 0.638      | 0.435        | 0.037 (0.010)    | 0.837 (0.232)    | 0 (0.000) |    13.17 | Keoz, REDSTAR, reiko, sinnopsyy, smooya       |
|           44 |     2142 | 2024-12-06 | Endpoint                                  | W   | 0.624      | 0.435        | -                | 0.377 (0.102)    | 0 (0.000) |     8.46 | hAdji, Keoz, REDSTAR, sinnopsyy, smooya       |
|           43 |     2298 | 2024-12-03 | Metizport                                 | W   | 0.603      | 0.435        | 0.074 (0.019)    | 0.507 (0.133)    | 0 (0.000) |    15.74 | hAdji, Keoz, REDSTAR, sinnopsyy, smooya       |
|           42 |     3740 | 2024-11-09 | ENCE                                      | L   | 0.444      | -            | -                | -                | -         |    -2.85 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           41 |     3821 | 2024-11-08 | Dynamo Eclot                              | L   | 0.436      | -            | -                | -                | -         |    -2.41 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           40 |     3902 | 2024-11-06 | 9INE                                      | L   | 0.424      | -            | -                | -                | -         |    -6.70 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           39 |     3910 | 2024-11-06 | 9INE                                      | W   | 0.423      | 0.371        | -                | 0.217 (0.034)    | 0 (0.000) |     6.80 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           38 |     3961 | 2024-11-05 | Nemiga Gaming                             | L   | 0.418      | -            | -                | -                | -         |    -2.59 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           37 |     4023 | 2024-11-04 | Rebels Gaming                             | L   | 0.410      | -            | -                | -                | -         |    -7.54 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           36 |     4099 | 2024-11-03 | AMKAL ESPORTS                             | L   | 0.403      | -            | -                | -                | -         |    -6.25 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           35 |     4138 | 2024-11-02 | 500                                       | W   | 0.398      | 0.143        | 0.093 (0.005)    | 1.000 (0.057)    | 0 (0.000) |     9.73 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           34 |     4156 | 2024-11-02 | Sashi Esport                              | W   | 0.397      | -            | -                | -                | 0 (0.000) |     8.74 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           33 |     4165 | 2024-11-02 | Los kogutos                               | W   | 0.396      | -            | -                | -                | -         |     8.65 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           32 |     4216 | 2024-11-01 | Insilio                                   | L   | 0.391      | -            | -                | -                | -         |    -8.76 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           31 |     4225 | 2024-11-01 | Dynamo Eclot                              | L   | 0.389      | -            | -                | -                | -         |    -2.16 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           30 |     4331 | 2024-10-30 | Los kogutos                               | W   | 0.378      | 0.384        | 0.032 (0.005)    | 0.515 (0.075)    | -         |     8.40 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           29 |     4338 | 2024-10-30 | GUN5 Esports                              | W   | 0.377      | 0.371        | 0.103 (0.014)    | 0.505 (0.070)    | -         |     8.57 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           28 |     4555 | 2024-10-26 | Chimera Esports                           | W   | 0.350      | 0.371        | -                | 0.586 (0.076)    | -         |     6.91 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           27 |     4802 | 2024-10-20 | Johnny Speeds                             | W   | 0.311      | -            | -                | -                | -         |     6.89 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           26 |     5154 | 2024-10-13 | GUN5 Esports                              | L   | 0.264      | -            | -                | -                | -         |    -2.17 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           25 |     5543 | 2024-10-06 | Nexus Gaming                              | W   | 0.217      | 0.143        | 0.187 (0.006)    | -                | -         |     6.21 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           24 |     5805 | 2024-10-02 | Illuminar Gaming                          | L   | 0.190      | -            | -                | -                | -         |    -2.00 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           23 |     5894 | 2024-10-01 | Passion UA                                | L   | 0.182      | -            | -                | -                | -         |    -1.01 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           22 |     5978 | 2024-09-29 | Copenhagen Wolves (American organization) | L   | 0.170      | -            | -                | -                | -         |    -4.05 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           21 |     6070 | 2024-09-28 | Team Sampi                                | W   | 0.163      | -            | -                | -                | -         |     2.92 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           20 |     6084 | 2024-09-28 | Johnny Speeds                             | W   | 0.163      | -            | -                | -                | -         |     3.52 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           19 |     6130 | 2024-09-27 | ALTERNATE aTTaX                           | L   | 0.158      | -            | -                | -                | -         |    -1.33 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           18 |     6154 | 2024-09-27 | UNiTY esports                             | W   | 0.157      | -            | -                | -                | -         |     3.10 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           17 |     6197 | 2024-09-26 | ECSTATIC                                  | L   | 0.152      | -            | -                | -                | -         |    -1.51 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           16 |     6233 | 2024-09-26 | Aurora Gaming                             | L   | 0.150      | -            | -                | -                | -         |    -1.95 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           15 |     6382 | 2024-09-24 | Endpoint                                  | W   | 0.138      | -            | -                | -                | -         |     2.35 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           14 |     6405 | 2024-09-24 | Fnatic                                    | W   | 0.137      | 0.384        | 0.072 (0.004)    | -                | -         |     3.70 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           13 |     6425 | 2024-09-24 | ALTERNATE aTTaX                           | L   | 0.136      | -            | -                | -                | -         |    -1.13 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           12 |     6502 | 2024-09-23 | Metizport                                 | W   | 0.129      | 0.384        | 0.074 (0.004)    | -                | -         |     3.54 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           11 |     6636 | 2024-09-20 | 9Pandas                                   | L   | 0.112      | -            | -                | -                | -         |    -0.76 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           10 |     6659 | 2024-09-20 | Dark Cloud Esports                        | W   | 0.109      | -            | -                | -                | -         |     2.18 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            9 |     6666 | 2024-09-20 | 9INE                                      | L   | 0.109      | -            | -                | -                | -         |    -1.64 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            8 |     6706 | 2024-09-19 | Team Sampi                                | W   | 0.105      | -            | -                | -                | -         |     1.93 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            7 |     6784 | 2024-09-18 | AMKAL ESPORTS                             | L   | 0.096      | -            | -                | -                | -         |    -1.29 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            6 |     6854 | 2024-09-17 | Sashi Esport                              | W   | 0.090      | -            | -                | -                | -         |     2.19 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            5 |     6865 | 2024-09-17 | GUN5 Esports                              | W   | 0.089      | 0.443        | 0.103 (0.004)    | -                | -         |     2.10 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            4 |     7203 | 2024-09-11 | EYEBALLERS                                | W   | 0.050      | -            | -                | -                | -         |     0.94 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            3 |     7223 | 2024-09-11 | Rebels Gaming                             | L   | 0.049      | -            | -                | -                | -         |    -0.80 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            2 |     7627 | 2024-09-05 | TEAM NEXT LEVEL                           | W   | 0.010      | -            | -                | -                | -         |     0.14 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            1 |     7640 | 2024-09-05 | GamerLegion                               | W   | 0.009      | -            | -                | -                | -         |     0.12 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($398.33)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-26 |      0.151 | $1,500.00      | $226.18         |
| 2024-09-24 |      0.137 | $1,000.00      | $136.53         |
| 2024-09-14 |      0.071 | $500.00        | $35.63          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
