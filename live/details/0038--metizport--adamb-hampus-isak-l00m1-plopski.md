### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, hampus, isak, L00m1, Plopski<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1015.7<br />
<br />
Final Rank Value (1015.7) = Starting Rank Value (1094.6) + Head To Head Adjustments (-79.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.469[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.147[<sup>2</sup>](#table1)
- LAN Wins: 0.442[<sup>2</sup>](#table1)

The average of these factors is 0.348<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1094.6
- 400 + ( ( 0.348 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1094.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |      554 | 2025-02-11 | HEROIC                      | L   | 1.000      | -            | -                | -                | -         |    -9.58 | adamb, hampus, isak, L00m1, Plopski |
|           41 |      563 | 2025-02-11 | Nemiga Gaming               | W   | 1.000      | 0.143        | 0.177 (0.025)    | -                | 0 (0.000) |    14.54 | adamb, hampus, isak, L00m1, Plopski |
|           40 |      581 | 2025-02-10 | GamerLegion                 | L   | 1.000      | -            | -                | -                | -         |    -1.23 | adamb, hampus, isak, L00m1, Plopski |
|           39 |      592 | 2025-02-10 | Nexus Gaming                | W   | 1.000      | 0.143        | 0.186 (0.027)    | 0.808 (0.115)    | 0 (0.000) |    13.83 | adamb, hampus, isak, L00m1, Plopski |
|           38 |      910 | 2025-02-05 | Ninjas in Pyjamas           | L   | 1.000      | -            | -                | -                | -         |   -27.45 | adamb, hampus, isak, L00m1, Plopski |
|           37 |      919 | 2025-02-05 | Passion UA                  | L   | 1.000      | -            | -                | -                | -         |   -14.98 | adamb, hampus, isak, L00m1, Plopski |
|           36 |     1181 | 2025-01-15 | Team Vitality               | L   | 0.900      | -            | -                | -                | -         |    -0.22 | adamb, hampus, isak, L00m1, Plopski |
|           35 |     1382 | 2024-12-22 | P0RTUGAL                    | L   | 0.741      | -            | -                | -                | -         |   -17.59 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           34 |     1387 | 2024-12-22 | Zero Tenacity               | W   | 0.740      | 0.143        | 0.028 (0.003)    | 0.692 (0.073)    | -         |     7.17 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           33 |     1441 | 2024-12-21 | Insilio                     | W   | 0.733      | -            | -                | -                | -         |     2.71 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           32 |     1700 | 2024-12-14 | 9INE                        | L   | 0.686      | -            | -                | -                | -         |   -14.72 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           31 |     1799 | 2024-12-13 | Monte                       | W   | 0.678      | 0.435        | 0.029 (0.009)    | 0.242 (0.071)    | -         |     6.45 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           30 |     1895 | 2024-12-11 | Insilio                     | W   | 0.665      | 0.435        | -                | 0.504 (0.146)    | -         |     2.36 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           29 |     1932 | 2024-12-10 | Chimera Esports             | L   | 0.658      | -            | -                | -                | -         |   -14.30 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           28 |     2022 | 2024-12-08 | FLuffy Gangsters            | W   | 0.644      | 0.435        | 0.014 (0.004)    | 0.925 (0.259)    | -         |     4.91 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           27 |     2164 | 2024-12-05 | Fire Flux Esports           | W   | 0.625      | 0.435        | -                | 1.000 (0.272)    | -         |     6.20 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           26 |     2286 | 2024-12-03 | Wild Lotus                  | L   | 0.611      | -            | -                | -                | -         |   -15.94 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           25 |     3249 | 2024-11-17 | Partizan Esports            | L   | 0.505      | -            | -                | -                | -         |    -8.26 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           24 |     3279 | 2024-11-17 | Nexus Gaming                | L   | 0.504      | -            | -                | -                | -         |    -7.68 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           23 |     3332 | 2024-11-16 | The Huns Esports            | W   | 0.499      | 0.617        | 0.025 (0.008)    | 0.557 (0.172)    | 1 (0.499) |     4.46 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           22 |     3401 | 2024-11-15 | Homyno                      | W   | 0.492      | -            | -                | -                | 1 (0.492) |     1.55 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           21 |     3409 | 2024-11-15 | Team Norway                 | W   | 0.491      | -            | -                | -                | 1 (0.491) |     1.10 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           20 |     3423 | 2024-11-14 | Los kogutos                 | W   | 0.487      | 0.617        | 0.032 (0.010)    | 0.527 (0.159)    | 1 (0.487) |     4.06 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           19 |     3504 | 2024-11-13 | PCIFIC Espor                | L   | 0.479      | -            | -                | -                | -         |   -13.02 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           18 |     3510 | 2024-11-13 | Mindfreak (Australian team) | W   | 0.479      | -            | -                | -                | 1 (0.479) |     1.72 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           17 |     3720 | 2024-11-09 | Ninjas in Pyjamas           | W   | 0.453      | -            | -                | -                | 1 (0.453) |     3.40 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           16 |     3779 | 2024-11-08 | Johnny Speeds               | W   | 0.447      | 0.143        | 0.039 (0.003)    | -                | 1 (0.447) |     4.04 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           15 |     3818 | 2024-11-07 | Kappa Bar                   | W   | 0.441      | -            | -                | -                | 1 (0.441) |     1.59 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           14 |     4248 | 2024-10-31 | Johnny Speeds               | L   | 0.393      | -            | -                | -                | -         |    -8.89 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           13 |     4304 | 2024-10-30 | ECSTATIC                    | W   | 0.386      | 0.333        | 0.033 (0.004)    | 0.828 (0.107)    | -         |     3.02 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           12 |     4317 | 2024-10-30 | Iberian Soul                | W   | 0.386      | -            | -                | -                | -         |     2.38 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           11 |     5230 | 2024-10-12 | Aurora Gaming               | L   | 0.265      | -            | -                | -                | -         |    -6.83 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           10 |     5294 | 2024-10-10 | Fnatic                      | W   | 0.251      | 0.435        | 0.072 (0.008)    | -                | -         |     3.69 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            9 |     5441 | 2024-10-08 | ALTERNATE aTTaX             | W   | 0.237      | -            | -                | -                | -         |     2.08 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            8 |     5497 | 2024-10-07 | Monte                       | L   | 0.231      | -            | -                | -                | -         |    -5.70 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            7 |     5661 | 2024-10-04 | CYBERSHOKE Esports          | W   | 0.213      | 0.435        | -                | 1.000 (0.092)    | -         |     1.41 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            6 |     5845 | 2024-10-01 | G2 Ares                     | W   | 0.193      | -            | -                | -                | -         |     0.59 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            5 |     6490 | 2024-09-23 | Wild Lotus                  | L   | 0.137      | -            | -                | -                | -         |    -3.77 | adamb, L00m1, nilo, Plopski, Sapec  |
|            4 |     6901 | 2024-09-16 | 9INE                        | W   | 0.091      | -            | -                | -                | -         |     0.39 | adamb, L00m1, nilo, Plopski, Sapec  |
|            3 |     7194 | 2024-09-11 | Zero Tenacity               | L   | 0.058      | -            | -                | -                | -         |    -1.43 | adamb, L00m1, nilo, Plopski, Sapec  |
|            2 |     7313 | 2024-09-09 | Zero Tenacity               | L   | 0.044      | -            | -                | -                | -         |    -1.09 | adamb, L00m1, nilo, Plopski, Sapec  |
|            1 |     7674 | 2024-09-04 | Team Sampi                  | W   | 0.012      | -            | -                | -                | -         |     0.06 | adamb, L00m1, nilo, Plopski, Sapec  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,939.71)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.741 | $6,518.90      | $4,827.61       |
| 2024-12-15 |      0.693 | $2,000.00      | $1,385.83       |
| 2024-11-17 |      0.506 | $15,000.00     | $7,593.75       |
| 2024-11-09 |      0.453 | $23,119.67     | $10,468.07      |
| 2024-10-13 |      0.273 | $2,000.00      | $545.23         |
| 2024-09-26 |      0.159 | $500.00        | $79.49          |
| 2024-09-14 |      0.079 | $500.00        | $39.72          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
