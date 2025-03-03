### Roster Details<br />
Team Name: Kubix Esports<br />
Roster: ammar, Caleyy, rosoneriii, tripey, v1w<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  892.4<br />
<br />
Final Rank Value (892.4) = Starting Rank Value (934.6) + Head To Head Adjustments (-42.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.426[<sup>1</sup>](#table2)
- Bounty Collected: 0.259[<sup>2</sup>](#table1)
- Opponent Network: 0.051[<sup>2</sup>](#table1)
- LAN Wins: 0.333[<sup>2</sup>](#table1)

The average of these factors is 0.267<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 934.6
- 400 + ( ( 0.267 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 934.6


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
|           42 |     1313 | 2024-12-28 | KONO.ECF                    | L   | 0.770      | -            | -                | -                | -         |   -10.95 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           41 |     1362 | 2024-12-26 | BMTH (Ukrainian team)       | W   | 0.757      | -            | -                | -                | 0 (0.000) |     2.72 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           40 |     1397 | 2024-12-22 | M1X                         | W   | 0.732      | 0.143        | 0.008 (0.001)    | -                | 1 (0.732) |     8.05 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           39 |     1422 | 2024-12-22 | The Suspect                 | W   | 0.730      | 0.143        | 0.003 (0.000)    | 0.216 (0.023)    | 1 (0.730) |     6.17 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           38 |     1440 | 2024-12-21 | Onlineheroes                | W   | 0.726      | -            | -                | -                | 1 (0.726) |     2.71 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           37 |     2007 | 2024-12-08 | P0RTUGAL                    | L   | 0.638      | -            | -                | -                | -         |   -13.09 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           36 |     2423 | 2024-12-01 | Insilio                     | L   | 0.592      | -            | -                | -                | -         |   -15.03 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           35 |     2430 | 2024-12-01 | ADEPTS                      | W   | 0.592      | 0.143        | -                | 0.287 (0.024)    | 0 (0.000) |     3.15 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           34 |     2537 | 2024-11-30 | Permitta Esports            | L   | 0.584      | -            | -                | -                | -         |   -11.52 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           33 |     2650 | 2024-11-28 | Fire Flux Esports           | L   | 0.571      | -            | -                | -                | -         |    -9.14 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           32 |     2736 | 2024-11-26 | GenOne                      | W   | 0.558      | 0.372        | 0.012 (0.003)    | 0.837 (0.174)    | 0 (0.000) |     6.52 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           31 |     2803 | 2024-11-24 | FLuffy Gangsters            | L   | 0.544      | -            | -                | -                | -         |   -10.51 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           30 |     2905 | 2024-11-23 | PCIFIC Espor                | L   | 0.537      | -            | -                | -                | -         |   -12.75 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           29 |     2962 | 2024-11-22 | Underrated                  | W   | 0.532      | 0.372        | 0.002 (0.000)    | 0.268 (0.053)    | 0 (0.000) |     2.79 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           28 |     2986 | 2024-11-22 | Anonymo Esports             | W   | 0.531      | 0.372        | -                | 0.099 (0.020)    | 0 (0.000) |     1.51 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           27 |     3196 | 2024-11-18 | RUSTEC                      | W   | 0.505      | 0.372        | -                | 0.216 (0.041)    | -         |     1.59 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           26 |     3341 | 2024-11-16 | Dark Cloud Esports          | W   | 0.491      | 0.143        | 0.039 (0.003)    | 0.819 (0.057)    | 1 (0.491) |     6.03 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           25 |     3595 | 2024-11-11 | Daystar                     | W   | 0.459      | 0.372        | -                | 0.131 (0.022)    | -         |     2.21 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           24 |     3884 | 2024-11-06 | Permitta Esports            | W   | 0.425      | 0.372        | 0.013 (0.002)    | 0.487 (0.077)    | -         |     4.54 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           23 |     3949 | 2024-11-05 | Kyoto (European mix-team)   | W   | 0.418      | 0.143        | 0.013 (0.001)    | -                | -         |     2.70 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           22 |     4018 | 2024-11-04 | ROUNDS                      | W   | 0.411      | -            | -                | -                | -         |     1.24 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           21 |     4067 | 2024-11-03 | MADNESS (Kosovar team)      | W   | 0.404      | 0.143        | 0.003 (0.000)    | -                | -         |     1.33 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           20 |     4250 | 2024-10-31 | Grindas                     | W   | 0.385      | -            | -                | -                | -         |     1.26 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           19 |     4444 | 2024-10-28 | ENTERPRISE Genesis          | W   | 0.365      | -            | -                | -                | -         |     1.94 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           18 |     4487 | 2024-10-27 | Juggernauts                 | L   | 0.357      | -            | -                | -                | -         |    -9.23 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           17 |     4603 | 2024-10-25 | Nuclear TigeRES             | L   | 0.344      | -            | -                | -                | -         |    -6.79 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           16 |     4610 | 2024-10-25 | 500                         | L   | 0.344      | -            | -                | -                | -         |    -4.34 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           15 |     4657 | 2024-10-23 | Poslednii3ae3d              | W   | 0.332      | -            | -                | -                | -         |     1.62 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           14 |     5159 | 2024-10-13 | Baklava Gaming              | W   | 0.263      | -            | -                | -                | -         |     1.08 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           13 |     5862 | 2024-10-01 | Dynamo Eclot                | W   | 0.184      | 0.143        | 0.128 (0.003)    | 0.692 (0.018)    | -         |     4.02 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           12 |     6023 | 2024-09-28 | M1X                         | L   | 0.165      | -            | -                | -                | -         |    -3.71 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           11 |     6058 | 2024-09-28 | The Suspect                 | W   | 0.164      | -            | -                | -                | 1 (0.164) |     1.22 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           10 |     6378 | 2024-09-24 | Los kogutos                 | W   | 0.138      | 0.143        | 0.032 (0.001)    | -                | -         |     2.55 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            9 |     6399 | 2024-09-24 | GameAgents                  | W   | 0.138      | -            | -                | -                | -         |     0.89 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            8 |     6821 | 2024-09-17 | Team Secret (Croatian team) | W   | 0.092      | -            | -                | -                | -         |     0.22 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            7 |     6830 | 2024-09-17 | SINNERS Academy             | W   | 0.092      | -            | -                | -                | -         |     0.73 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            6 |     6904 | 2024-09-16 | THE GENTLEMEN ESPORTS       | L   | 0.084      | -            | -                | -                | -         |    -2.11 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            5 |     6927 | 2024-09-15 | NOM Esports                 | W   | 0.078      | -            | -                | -                | -         |     0.12 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            4 |     7106 | 2024-09-13 | QUAZAR                      | L   | 0.063      | -            | -                | -                | -         |    -1.56 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            3 |     7307 | 2024-09-09 | XPERION NXT                 | W   | 0.038      | -            | -                | -                | -         |     0.20 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            2 |     7456 | 2024-09-07 | Grannys Knockers            | L   | 0.024      | -            | -                | -                | -         |    -0.64 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            1 |     7601 | 2024-09-05 | TOOMUCHVIDEOGAMES           | W   | 0.011      | -            | -                | -                | -         |     0.03 | ammar, gejmzilla, rosoneriii, tripey, v1w |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,855.91)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.732 | $5,736.64      | $4,199.96       |
| 2024-11-16 |      0.491 | $21,089.26     | $10,344.48      |
| 2024-09-28 |      0.165 | $1,675.22      | $276.18         |
| 2024-09-21 |      0.118 | $300.00        | $35.29          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
