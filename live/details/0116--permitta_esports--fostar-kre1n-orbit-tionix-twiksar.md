### Roster Details<br />
Team Name: Permitta Esports<br />
Roster: fostar, Kre1N, Orbit, Tionix, Twiksar<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  810.9<br />
<br />
Final Rank Value (810.9) = Starting Rank Value (800.0) + Head To Head Adjustments (10.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.346[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.066[<sup>2</sup>](#table1)
- LAN Wins: 0.079[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 800.0
- 400 + ( ( 0.200 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 800.0


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
|           38 |      483 | 2025-02-14 | BAKS Esports                              | L   | 1.000      | -            | -                | -                | -         |   -26.38 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           37 |      788 | 2025-02-07 | Fnatic                                    | L   | 1.000      | -            | -                | -                | -         |    -6.35 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           36 |      984 | 2025-02-04 | GardenGarage                              | L   | 1.000      | -            | -                | -                | -         |   -19.57 | fostar, Kre1N, Spexy, Tionix, Twiksar  |
|           35 |      995 | 2025-02-04 | Ex-Daystar                                | W   | 1.000      | 0.143        | -                | 0.141 (0.020)    | 0 (0.000) |     4.25 | fostar, Kre1N, Spexy, Tionix, Twiksar  |
|           34 |     1500 | 2024-12-20 | Mission Possible                          | W   | 0.719      | 0.143        | -                | 0.292 (0.030)    | 0 (0.000) |     3.83 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           33 |     1505 | 2024-12-20 | HyperSpirit                               | W   | 0.719      | -            | -                | -                | 0 (0.000) |     2.82 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           32 |     1512 | 2024-12-20 | Maestro Esports (Belgian team)            | W   | 0.719      | -            | -                | -                | 0 (0.000) |     2.85 | fostar, Kre1N, Orbit, Tionix, Twiksar  |
|           31 |     1703 | 2024-12-14 | BIG                                       | W   | 0.678      | 0.143        | 0.248 (0.024)    | 0.572 (0.055)    | 1 (0.678) |    20.74 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           30 |     2328 | 2024-12-02 | Partizan Esports                          | L   | 0.599      | -            | -                | -                | -         |    -4.17 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           29 |     2537 | 2024-11-30 | Kubix Esports                             | W   | 0.584      | 0.372        | 0.045 (0.010)    | 0.487 (0.106)    | 0 (0.000) |    11.52 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           28 |     2737 | 2024-11-26 | 1win                                      | L   | 0.558      | -            | -                | -                | -         |   -10.09 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           27 |     2887 | 2024-11-23 | UNiTY esports                             | W   | 0.538      | 0.372        | 0.025 (0.005)    | 0.403 (0.081)    | 0 (0.000) |     9.06 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           26 |     3089 | 2024-11-20 | Grindas                                   | W   | 0.519      | -            | -                | -                | 0 (0.000) |     3.11 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           25 |     3123 | 2024-11-20 | ALASKA                                    | W   | 0.518      | 0.372        | 0.031 (0.006)    | 0.867 (0.167)    | 0 (0.000) |    12.11 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           24 |     3163 | 2024-11-19 | Haspers Team                              | W   | 0.512      | 0.372        | 0.013 (0.003)    | 0.171 (0.033)    | 0 (0.000) |     6.00 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           23 |     3392 | 2024-11-15 | Kay Team                                  | W   | 0.485      | -            | -                | -                | -         |     2.42 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           22 |     3442 | 2024-11-14 | Passion UA                                | W   | 0.478      | 0.372        | 0.044 (0.008)    | 0.545 (0.097)    | -         |    11.25 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           21 |     3600 | 2024-11-11 | Reveal (German team)                      | L   | 0.459      | -            | -                | -                | -         |   -10.02 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           20 |     3620 | 2024-11-11 | BIG SELECTA                               | W   | 0.458      | -            | -                | -                | -         |     3.11 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           19 |     3663 | 2024-11-10 | ADEPTS                                    | L   | 0.452      | -            | -                | -                | -         |   -10.64 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           18 |     3884 | 2024-11-06 | Kubix Esports                             | L   | 0.425      | -            | -                | -                | -         |    -4.54 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           17 |     4058 | 2024-11-03 | ALTERNATE aTTaX                           | W   | 0.405      | 0.143        | 0.021 (0.001)    | 0.552 (0.032)    | -         |     8.22 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           16 |     4073 | 2024-11-03 | XPERION NXT                               | W   | 0.404      | 0.143        | 0.002 (0.000)    | -                | -         |     3.82 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           15 |     4152 | 2024-11-02 | Wave Esports                              | W   | 0.397      | -            | -                | -                | -         |     3.69 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           14 |     4192 | 2024-11-01 | ALTERNATE aTTaX                           | L   | 0.392      | -            | -                | -                | -         |    -4.32 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           13 |     4424 | 2024-10-28 | Wave Esports                              | W   | 0.365      | -            | -                | -                | -         |     3.29 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           12 |     4446 | 2024-10-28 | PCIFIC Espor                              | W   | 0.365      | 0.372        | 0.004 (0.001)    | 0.251 (0.034)    | -         |     5.41 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           11 |     4670 | 2024-10-23 | MYinsanity                                | W   | 0.332      | 0.143        | 0.002 (0.000)    | -                | -         |     3.40 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|           10 |     4679 | 2024-10-23 | Endpoint                                  | L   | 0.331      | -            | -                | -                | -         |    -5.37 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            9 |     4744 | 2024-10-21 | XPERION NXT                               | W   | 0.318      | -            | -                | -                | -         |     3.13 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            8 |     4935 | 2024-10-17 | QUAZAR                                    | L   | 0.291      | -            | -                | -                | -         |    -5.62 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            7 |     5001 | 2024-10-16 | Copenhagen Wolves (American organization) | L   | 0.285      | -            | -                | -                | -         |    -3.77 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            6 |     5109 | 2024-10-14 | ALTERNATE aTTaX                           | L   | 0.272      | -            | -                | -                | -         |    -2.89 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            5 |     5348 | 2024-10-09 | ESports Cologne                           | W   | 0.238      | -            | -                | -                | -         |     1.02 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            4 |     5775 | 2024-10-02 | Regnum4Games                              | W   | 0.192      | -            | -                | -                | -         |     1.66 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            3 |     6043 | 2024-09-28 | Betera Esports                            | L   | 0.165      | -            | -                | -                | -         |    -3.05 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            2 |     6774 | 2024-09-18 | Sissi State Punks                         | W   | 0.098      | -            | -                | -                | -         |     0.75 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |
|            1 |     7284 | 2024-09-09 | SNOGARD Dragons                           | W   | 0.038      | -            | -                | -                | -         |     0.29 | Kre1N, Orbit, P4TriCK, Tionix, Twiksar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,275.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.678 | $6,302.85      | $4,275.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
