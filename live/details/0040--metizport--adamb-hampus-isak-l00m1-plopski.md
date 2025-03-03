### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, hampus, isak, L00m1, Plopski<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1013.4<br />
<br />
Final Rank Value (1013.4) = Starting Rank Value (1090.8) + Head To Head Adjustments (-77.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.470[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.143[<sup>2</sup>](#table1)
- LAN Wins: 0.436[<sup>2</sup>](#table1)

The average of these factors is 0.345<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1090.8
- 400 + ( ( 0.345 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1090.8


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
|           42 |      566 | 2025-02-11 | HEROIC                      | L   | 1.000      | -            | -                | -                | -         |    -9.63 | adamb, hampus, isak, L00m1, Plopski |
|           41 |      575 | 2025-02-11 | Nemiga Gaming               | W   | 1.000      | 0.143        | 0.176 (0.025)    | -                | 0 (0.000) |    14.50 | adamb, hampus, isak, L00m1, Plopski |
|           40 |      593 | 2025-02-10 | GamerLegion                 | L   | 1.000      | -            | -                | -                | -         |    -1.22 | adamb, hampus, isak, L00m1, Plopski |
|           39 |      604 | 2025-02-10 | Nexus Gaming                | W   | 1.000      | 0.143        | 0.187 (0.027)    | 0.795 (0.114)    | 0 (0.000) |    13.92 | adamb, hampus, isak, L00m1, Plopski |
|           38 |      922 | 2025-02-05 | Ninjas in Pyjamas           | L   | 1.000      | -            | -                | -                | -         |   -27.42 | adamb, hampus, isak, L00m1, Plopski |
|           37 |      931 | 2025-02-05 | Passion UA                  | L   | 1.000      | -            | -                | -                | -         |   -14.96 | adamb, hampus, isak, L00m1, Plopski |
|           36 |     1193 | 2025-01-15 | Team Vitality               | L   | 0.892      | -            | -                | -                | -         |    -0.21 | adamb, hampus, isak, L00m1, Plopski |
|           35 |     1394 | 2024-12-22 | P0RTUGAL                    | L   | 0.732      | -            | -                | -                | -         |   -17.36 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           34 |     1399 | 2024-12-22 | Zero Tenacity               | W   | 0.732      | 0.143        | 0.028 (0.003)    | 0.684 (0.072)    | -         |     7.08 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           33 |     1453 | 2024-12-21 | Insilio                     | W   | 0.725      | -            | -                | -                | -         |     2.68 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           32 |     1712 | 2024-12-14 | 9INE                        | L   | 0.678      | -            | -                | -                | -         |   -14.52 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           31 |     1811 | 2024-12-13 | Monte                       | W   | 0.670      | 0.435        | 0.029 (0.009)    | -                | -         |     6.36 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           30 |     1907 | 2024-12-11 | Insilio                     | W   | 0.656      | 0.435        | -                | 0.500 (0.143)    | -         |     2.33 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           29 |     1944 | 2024-12-10 | Chimera Esports             | L   | 0.650      | -            | -                | -                | -         |   -14.13 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           28 |     2034 | 2024-12-08 | FLuffy Gangsters            | W   | 0.636      | 0.435        | 0.014 (0.004)    | 0.909 (0.251)    | -         |     4.83 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           27 |     2176 | 2024-12-05 | Fire Flux Esports           | W   | 0.617      | 0.435        | -                | 1.000 (0.268)    | -         |     6.11 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           26 |     2298 | 2024-12-03 | Wild Lotus                  | L   | 0.603      | -            | -                | -                | -         |   -15.74 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           25 |     3261 | 2024-11-17 | Partizan Esports            | L   | 0.497      | -            | -                | -                | -         |    -8.11 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           24 |     3291 | 2024-11-17 | Nexus Gaming                | L   | 0.496      | -            | -                | -                | -         |    -7.49 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           23 |     3344 | 2024-11-16 | The Huns Esports            | W   | 0.490      | 0.617        | 0.025 (0.008)    | 0.553 (0.167)    | 1 (0.490) |     4.42 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           22 |     3413 | 2024-11-15 | Homyno                      | W   | 0.484      | -            | -                | -                | 1 (0.484) |     1.55 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           21 |     3421 | 2024-11-15 | Team Norway                 | W   | 0.483      | -            | -                | -                | 1 (0.483) |     1.09 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           20 |     3435 | 2024-11-14 | Los kogutos                 | W   | 0.479      | 0.617        | 0.032 (0.009)    | 0.515 (0.152)    | 1 (0.479) |     4.03 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           19 |     3516 | 2024-11-13 | PCIFIC Espor                | L   | 0.471      | -            | -                | -                | -         |   -12.78 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           18 |     3522 | 2024-11-13 | Mindfreak (Australian team) | W   | 0.470      | -            | -                | -                | 1 (0.470) |     1.70 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           17 |     3732 | 2024-11-09 | Ninjas in Pyjamas           | W   | 0.445      | -            | -                | -                | 1 (0.445) |     3.33 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           16 |     3791 | 2024-11-08 | Johnny Speeds               | W   | 0.439      | 0.143        | 0.039 (0.002)    | -                | 1 (0.439) |     3.97 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           15 |     3830 | 2024-11-07 | Kappa Bar                   | W   | 0.433      | -            | -                | -                | 1 (0.433) |     1.58 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           14 |     4260 | 2024-10-31 | Johnny Speeds               | L   | 0.385      | -            | -                | -                | -         |    -8.71 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           13 |     4316 | 2024-10-30 | ECSTATIC                    | W   | 0.378      | 0.333        | 0.033 (0.004)    | 0.820 (0.103)    | -         |     2.97 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           12 |     4329 | 2024-10-30 | Iberian Soul                | W   | 0.378      | 0.333        | -                | 0.551 (0.069)    | -         |     2.35 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           11 |     5242 | 2024-10-12 | Aurora Gaming               | L   | 0.256      | -            | -                | -                | -         |    -6.60 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           10 |     5306 | 2024-10-10 | Fnatic                      | W   | 0.243      | 0.435        | 0.072 (0.008)    | -                | -         |     3.57 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            9 |     5453 | 2024-10-08 | ALTERNATE aTTaX             | W   | 0.229      | -            | -                | -                | -         |     2.02 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            8 |     5509 | 2024-10-07 | Monte                       | L   | 0.223      | -            | -                | -                | -         |    -5.50 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            7 |     5673 | 2024-10-04 | CYBERSHOKE Esports          | W   | 0.205      | 0.435        | -                | 1.000 (0.089)    | -         |     1.37 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            6 |     5857 | 2024-10-01 | G2 Ares                     | W   | 0.185      | -            | -                | -                | -         |     0.57 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            5 |     6502 | 2024-09-23 | Wild Lotus                  | L   | 0.129      | -            | -                | -                | -         |    -3.54 | adamb, L00m1, nilo, Plopski, Sapec  |
|            4 |     6913 | 2024-09-16 | 9INE                        | W   | 0.083      | -            | -                | -                | -         |     0.35 | adamb, L00m1, nilo, Plopski, Sapec  |
|            3 |     7206 | 2024-09-11 | Zero Tenacity               | L   | 0.050      | -            | -                | -                | -         |    -1.23 | adamb, L00m1, nilo, Plopski, Sapec  |
|            2 |     7325 | 2024-09-09 | Zero Tenacity               | L   | 0.036      | -            | -                | -                | -         |    -0.89 | adamb, L00m1, nilo, Plopski, Sapec  |
|            1 |     7686 | 2024-09-04 | Team Sampi                  | W   | 0.004      | -            | -                | -                | -         |     0.02 | adamb, L00m1, nilo, Plopski, Sapec  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,532.95)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.732 | $6,518.90      | $4,774.19       |
| 2024-12-15 |      0.685 | $2,000.00      | $1,369.44       |
| 2024-11-17 |      0.498 | $15,000.00     | $7,470.83       |
| 2024-11-09 |      0.445 | $23,119.67     | $10,278.62      |
| 2024-10-13 |      0.264 | $2,000.00      | $528.84         |
| 2024-09-26 |      0.151 | $500.00        | $75.39          |
| 2024-09-14 |      0.071 | $500.00        | $35.63          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
