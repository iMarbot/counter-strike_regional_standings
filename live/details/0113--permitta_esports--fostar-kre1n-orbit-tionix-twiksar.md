### Roster Details<br />
Team Name: Permitta Esports<br />
Roster: fostar, Kre1N, Orbit, Tionix, Twiksar<br />
Global Rank: [113](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  813.2<br />
<br />
Final Rank Value (813.2) = Starting Rank Value (800.7) + Head To Head Adjustments (12.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.346[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.068[<sup>2</sup>](#table1)
- LAN Wins: 0.080[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 800.7
- 400 + ( ( 0.201 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 800.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |      471 | 2025-02-14 | BAKS Esports                              | L   | 1.000      | -            | -                | -                | -         |   -26.43 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           37 |      776 | 2025-02-07 | Fnatic                                    | L   | 1.000      | -            | -                | -                | -         |    -6.35 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           36 |      972 | 2025-02-04 | GardenGarage                              | L   | 1.000      | -            | -                | -                | -         |   -19.65 | fostar, Kre1N, Spexy, Tionix, Twiksar  |
|           35 |      983 | 2025-02-04 | Ex-Daystar                                | W   | 1.000      | 0.143        | -                | 0.140 (0.020)    | 0 (0.000) |     4.20 | fostar, Kre1N, Spexy, Tionix, Twiksar  |
|           34 |     1488 | 2024-12-20 | Mission Possible                          | W   | 0.728      | 0.143        | -                | 0.295 (0.031)    | 0 (0.000) |     3.86 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           33 |     1493 | 2024-12-20 | HyperSpirit                               | W   | 0.727      | -            | -                | -                | 0 (0.000) |     2.82 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           32 |     1500 | 2024-12-20 | Maestro Esports (Belgian team)            | W   | 0.727      | -            | -                | -                | 0 (0.000) |     2.85 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           31 |     1691 | 2024-12-14 | BIG                                       | W   | 0.686      | 0.143        | 0.246 (0.024)    | 0.579 (0.057)    | 1 (0.686) |    20.99 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           30 |     2316 | 2024-12-02 | Partizan Esports                          | L   | 0.607      | -            | -                | -                | -         |    -4.24 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           29 |     2525 | 2024-11-30 | Kubix Esports                             | W   | 0.593      | 0.372        | 0.045 (0.010)    | 0.496 (0.109)    | 0 (0.000) |    11.66 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           28 |     2725 | 2024-11-26 | 1win                                      | L   | 0.566      | -            | -                | -                | -         |   -10.26 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           27 |     2875 | 2024-11-23 | UNiTY esports                             | W   | 0.546      | 0.372        | 0.025 (0.005)    | 0.412 (0.084)    | 0 (0.000) |     9.21 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           26 |     3077 | 2024-11-20 | Grindas                                   | W   | 0.527      | -            | -                | -                | 0 (0.000) |     3.14 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           25 |     3111 | 2024-11-20 | ALASKA                                    | W   | 0.526      | 0.372        | 0.030 (0.006)    | 0.875 (0.171)    | 0 (0.000) |    12.20 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           24 |     3151 | 2024-11-19 | Haspers Team                              | W   | 0.520      | 0.372        | 0.013 (0.003)    | 0.174 (0.034)    | 0 (0.000) |     6.07 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           23 |     3380 | 2024-11-15 | Kay Team                                  | W   | 0.493      | -            | -                | -                | -         |     2.45 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           22 |     3430 | 2024-11-14 | Passion UA                                | W   | 0.487      | 0.372        | 0.044 (0.008)    | 0.557 (0.101)    | -         |    11.43 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           21 |     3588 | 2024-11-11 | Reveal (German team)                      | L   | 0.467      | -            | -                | -                | -         |   -10.22 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           20 |     3608 | 2024-11-11 | BIG SELECTA                               | W   | 0.466      | -            | -                | -                | -         |     3.13 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           19 |     3651 | 2024-11-10 | ADEPTS                                    | L   | 0.460      | -            | -                | -                | -         |    -9.64 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           18 |     3872 | 2024-11-06 | Kubix Esports                             | L   | 0.434      | -            | -                | -                | -         |    -4.62 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           17 |     4046 | 2024-11-03 | ALTERNATE aTTaX                           | W   | 0.413      | 0.143        | 0.021 (0.001)    | 0.564 (0.033)    | -         |     8.41 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           16 |     4061 | 2024-11-03 | XPERION NXT                               | W   | 0.412      | 0.143        | 0.002 (0.000)    | -                | -         |     3.89 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           15 |     4140 | 2024-11-02 | Wave Esports                              | W   | 0.406      | -            | -                | -                | -         |     3.77 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           14 |     4180 | 2024-11-01 | ALTERNATE aTTaX                           | L   | 0.400      | -            | -                | -                | -         |    -4.38 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           13 |     4412 | 2024-10-28 | Wave Esports                              | W   | 0.374      | -            | -                | -                | -         |     3.36 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           12 |     4434 | 2024-10-28 | PCIFIC Espor                              | W   | 0.373      | 0.372        | 0.004 (0.001)    | 0.254 (0.035)    | -         |     5.53 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           11 |     4658 | 2024-10-23 | MYinsanity                                | W   | 0.340      | 0.143        | 0.002 (0.000)    | -                | -         |     3.48 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           10 |     4667 | 2024-10-23 | Endpoint                                  | L   | 0.339      | -            | -                | -                | -         |    -5.50 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            9 |     4732 | 2024-10-21 | XPERION NXT                               | W   | 0.326      | -            | -                | -                | -         |     3.20 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            8 |     4923 | 2024-10-17 | QUAZAR                                    | L   | 0.299      | -            | -                | -                | -         |    -5.77 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            7 |     4989 | 2024-10-16 | Copenhagen Wolves (American organization) | L   | 0.293      | -            | -                | -                | -         |    -3.88 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            6 |     5097 | 2024-10-14 | ALTERNATE aTTaX                           | L   | 0.280      | -            | -                | -                | -         |    -2.97 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            5 |     5336 | 2024-10-09 | ESports Cologne                           | W   | 0.246      | -            | -                | -                | -         |     1.05 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            4 |     5763 | 2024-10-02 | Regnum4Games                              | W   | 0.200      | -            | -                | -                | -         |     1.72 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            3 |     6031 | 2024-09-28 | Betera Esports                            | L   | 0.173      | -            | -                | -                | -         |    -3.20 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            2 |     6762 | 2024-09-18 | Sissi State Punks                         | W   | 0.106      | -            | -                | -                | -         |     0.81 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            1 |     7272 | 2024-09-09 | SNOGARD Dragons                           | W   | 0.047      | -            | -                | -                | -         |     0.35 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,326.65)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.686 | $6,302.85      | $4,326.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
