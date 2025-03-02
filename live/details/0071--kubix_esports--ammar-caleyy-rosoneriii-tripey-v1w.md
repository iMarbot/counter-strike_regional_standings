### Roster Details<br />
Team Name: Kubix Esports<br />
Roster: ammar, Caleyy, rosoneriii, tripey, v1w<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  894.1<br />
<br />
Final Rank Value (894.1) = Starting Rank Value (936.5) + Head To Head Adjustments (-42.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.426[<sup>1</sup>](#table2)
- Bounty Collected: 0.260[<sup>2</sup>](#table1)
- Opponent Network: 0.052[<sup>2</sup>](#table1)
- LAN Wins: 0.336[<sup>2</sup>](#table1)

The average of these factors is 0.269<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 936.5
- 400 + ( ( 0.269 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 936.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |     1301 | 2024-12-28 | KONO.ECF                    | L   | 0.779      | -            | -                | -                | -         |   -11.02 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           41 |     1350 | 2024-12-26 | BMTH (Ukrainian team)       | W   | 0.765      | -            | -                | -                | 0 (0.000) |     2.73 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           40 |     1385 | 2024-12-22 | M1X                         | W   | 0.740      | 0.143        | 0.008 (0.001)    | -                | 1 (0.740) |     8.13 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           39 |     1410 | 2024-12-22 | The Suspect                 | W   | 0.738      | 0.143        | 0.003 (0.000)    | 0.220 (0.023)    | 1 (0.738) |     6.22 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           38 |     1428 | 2024-12-21 | Onlineheroes                | W   | 0.734      | -            | -                | -                | 1 (0.734) |     2.71 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           37 |     1995 | 2024-12-08 | P0RTUGAL                    | L   | 0.647      | -            | -                | -                | -         |   -13.30 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           36 |     2411 | 2024-12-01 | Insilio                     | L   | 0.600      | -            | -                | -                | -         |   -15.23 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           35 |     2415 | 2024-12-01 | ADEPTS                      | W   | 0.600      | 0.143        | -                | 0.292 (0.025)    | 0 (0.000) |     4.11 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           34 |     2525 | 2024-11-30 | Permitta Esports            | L   | 0.593      | -            | -                | -                | -         |   -11.66 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           33 |     2638 | 2024-11-28 | Fire Flux Esports           | L   | 0.579      | -            | -                | -                | -         |    -9.23 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           32 |     2724 | 2024-11-26 | GenOne                      | W   | 0.566      | 0.372        | 0.012 (0.003)    | 0.848 (0.179)    | 0 (0.000) |     6.62 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           31 |     2791 | 2024-11-24 | FLuffy Gangsters            | L   | 0.552      | -            | -                | -                | -         |   -10.64 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           30 |     2893 | 2024-11-23 | PCIFIC Espor                | L   | 0.545      | -            | -                | -                | -         |   -12.96 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           29 |     2950 | 2024-11-22 | Underrated                  | W   | 0.540      | 0.372        | 0.002 (0.000)    | 0.271 (0.055)    | 0 (0.000) |     2.81 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           28 |     2974 | 2024-11-22 | Anonymo Esports             | W   | 0.539      | 0.372        | -                | 0.101 (0.020)    | 0 (0.000) |     1.52 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           27 |     3184 | 2024-11-18 | RUSTEC                      | W   | 0.514      | 0.372        | -                | 0.217 (0.042)    | -         |     1.61 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           26 |     3329 | 2024-11-16 | Dark Cloud Esports          | W   | 0.499      | 0.143        | 0.038 (0.003)    | 0.828 (0.059)    | 1 (0.499) |     6.11 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           25 |     3583 | 2024-11-11 | Daystar                     | W   | 0.467      | 0.372        | -                | 0.135 (0.023)    | -         |     2.26 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           24 |     3872 | 2024-11-06 | Permitta Esports            | W   | 0.434      | 0.372        | 0.013 (0.002)    | 0.494 (0.080)    | -         |     4.62 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           23 |     3937 | 2024-11-05 | Kyoto (European mix-team)   | W   | 0.427      | 0.143        | 0.013 (0.001)    | -                | -         |     2.74 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           22 |     4006 | 2024-11-04 | ROUNDS                      | W   | 0.419      | -            | -                | -                | -         |     1.26 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           21 |     4055 | 2024-11-03 | MADNESS (Kosovar team)      | W   | 0.413      | 0.143        | 0.003 (0.000)    | -                | -         |     1.35 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           20 |     4238 | 2024-10-31 | Grindas                     | W   | 0.394      | -            | -                | -                | -         |     1.28 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           19 |     4432 | 2024-10-28 | ENTERPRISE Genesis          | W   | 0.373      | -            | -                | -                | -         |     1.97 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           18 |     4475 | 2024-10-27 | Juggernauts                 | L   | 0.365      | -            | -                | -                | -         |    -9.45 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           17 |     4591 | 2024-10-25 | Nuclear TigeRES             | L   | 0.352      | -            | -                | -                | -         |    -6.97 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           16 |     4598 | 2024-10-25 | 500                         | L   | 0.352      | -            | -                | -                | -         |    -4.47 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           15 |     4645 | 2024-10-23 | Poslednii3ae3d              | W   | 0.340      | -            | -                | -                | -         |     1.65 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           14 |     5147 | 2024-10-13 | Baklava Gaming              | W   | 0.271      | -            | -                | -                | -         |     1.11 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           13 |     5850 | 2024-10-01 | Dynamo Eclot                | W   | 0.193      | 0.143        | 0.127 (0.003)    | 0.703 (0.019)    | -         |     4.21 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           12 |     6011 | 2024-09-28 | M1X                         | L   | 0.173      | -            | -                | -                | -         |    -3.90 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           11 |     6046 | 2024-09-28 | The Suspect                 | W   | 0.172      | -            | -                | -                | 1 (0.172) |     1.28 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           10 |     6366 | 2024-09-24 | Los kogutos                 | W   | 0.146      | 0.143        | 0.032 (0.001)    | -                | -         |     2.71 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            9 |     6387 | 2024-09-24 | GameAgents                  | W   | 0.146      | -            | -                | -                | -         |     0.95 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            8 |     6809 | 2024-09-17 | Team Secret (Croatian team) | W   | 0.100      | -            | -                | -                | -         |     0.23 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            7 |     6818 | 2024-09-17 | SINNERS Academy             | W   | 0.100      | -            | -                | -                | -         |     0.79 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            6 |     6892 | 2024-09-16 | THE GENTLEMEN ESPORTS       | L   | 0.092      | -            | -                | -                | -         |    -2.32 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            5 |     6915 | 2024-09-15 | NOM Esports                 | W   | 0.087      | -            | -                | -                | -         |     0.13 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            4 |     7094 | 2024-09-13 | QUAZAR                      | L   | 0.072      | -            | -                | -                | -         |    -1.77 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            3 |     7295 | 2024-09-09 | XPERION NXT                 | W   | 0.046      | -            | -                | -                | -         |     0.24 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            2 |     7444 | 2024-09-07 | Grannys Knockers            | L   | 0.032      | -            | -                | -                | -         |    -0.86 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            1 |     7589 | 2024-09-05 | TOOMUCHVIDEOGAMES           | W   | 0.019      | -            | -                | -                | -         |     0.04 | ammar, gejmzilla, rosoneriii, tripey, v1w |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,091.92)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.740 | $5,736.64      | $4,246.97       |
| 2024-11-16 |      0.499 | $21,089.26     | $10,517.29      |
| 2024-09-28 |      0.173 | $1,675.22      | $289.91         |
| 2024-09-21 |      0.126 | $300.00        | $37.75          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
