### Roster Details<br />
Team Name: Dragon Esports Club<br />
Roster: Kiy0o, Matheos, milky, rafftu, Shlyaperson<br />
Global Rank: [241](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [170]( ../standings_europe.md)<br />
<br />
Final Rank Value:  682.0<br />
<br />
Final Rank Value (682.0) = Starting Rank Value (689.4) + Head To Head Adjustments (-7.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.4
- 400 + ( ( 0.145 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 689.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     1333 | 2024-12-27 | Preasy Esport                             | L   | 0.771      | -            | -                | -                | -         |    -9.95 | Kiy0o, Matheos, milky, rafftu, Shlyaperson       |
|           25 |     1363 | 2024-12-24 | Soul's Heart Esport                       | W   | 0.751      | 0.333        | 0.000 (0.000)    | 0.035 (0.009)    | 0 (0.000) |     4.04 | Kiy0o, Matheos, milky, rafftu, Shlyaperson       |
|           24 |     1374 | 2024-12-23 | BMTH (Ukrainian team)                     | L   | 0.745      | -            | -                | -                | -         |   -17.01 | Kiy0o, Matheos, milky, rafftu, Shlyaperson       |
|           23 |     1386 | 2024-12-22 | Soul's Heart Esport                       | W   | 0.740      | 0.333        | 0.000 (0.000)    | 0.035 (0.009)    | 0 (0.000) |     3.56 | Kiy0o, Matheos, milky, rafftu, Shlyaperson       |
|           22 |     1392 | 2024-12-22 | C.S.D.E                                   | W   | 0.740      | 0.143        | 0.006 (0.001)    | 0.154 (0.016)    | 0 (0.000) |    11.60 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           21 |     1411 | 2024-12-22 | SkyFury                                   | W   | 0.738      | 0.143        | 0.004 (0.000)    | 0.342 (0.036)    | 0 (0.000) |    11.58 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           20 |     1455 | 2024-12-21 | NEVERMORE (Ukrainian team)                | W   | 0.732      | 0.143        | 0.010 (0.001)    | 0.911 (0.095)    | 0 (0.000) |    16.06 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           19 |     1467 | 2024-12-21 | Lazer Cats                                | L   | 0.732      | -            | -                | -                | -         |    -9.36 | 3ippoch, Kiy0o, milky, rafftu, Shlyaperson       |
|           18 |     1472 | 2024-12-21 | GUESS                                     | W   | 0.731      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     6.17 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           17 |     1476 | 2024-12-21 | 0to100                                    | L   | 0.731      | -            | -                | -                | -         |    -8.43 | 3ippoch, Kiy0o, milky, rafftu, Shlyaperson       |
|           16 |     1502 | 2024-12-20 | BadGuys                                   | L   | 0.727      | -            | -                | -                | -         |   -13.80 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           15 |     1559 | 2024-12-18 | TEAM NEXT LEVEL                           | L   | 0.711      | -            | -                | -                | -         |    -6.51 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           14 |     1576 | 2024-12-17 | Copenhagen Wolves (American organization) | L   | 0.704      | -            | -                | -                | -         |    -5.83 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           13 |     1588 | 2024-12-16 | TEAM NEXT LEVEL                           | L   | 0.699      | -            | -                | -                | -         |    -6.59 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           12 |     1596 | 2024-12-16 | Astralis Talent                           | W   | 0.698      | 0.371        | 0.002 (0.001)    | 0.733 (0.189)    | 0 (0.000) |    13.76 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           11 |     2160 | 2024-12-05 | Chroma                                    | W   | 0.626      | 0.143        | 0.005 (0.000)    | 0.094 (0.008)    | 0 (0.000) |    10.06 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           10 |     2219 | 2024-12-04 | NewBALLS                                  | L   | 0.620      | -            | -                | -                | -         |   -10.65 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|            9 |     2408 | 2024-12-01 | WOPA Esport                               | L   | 0.600      | -            | -                | -                | -         |    -6.03 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|            8 |     2622 | 2024-11-28 | Reveal (German team)                      | W   | 0.580      | 0.333        | 0.001 (0.000)    | 0.192 (0.037)    | 0 (0.000) |     8.04 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|            7 |     2718 | 2024-11-26 | NIP Svea                                  | W   | 0.567      | 0.333        | -                | 0.048 (0.009)    | 0 (0.000) |     3.14 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|            6 |     5013 | 2024-10-16 | Tibian Soldiers                           | W   | 0.292      | -            | -                | -                | -         |     1.51 | auth0ri, fakerealityy, kiy0o, milky, Shlyaperson |
|            5 |     5134 | 2024-10-13 | Tibian Soldiers                           | W   | 0.273      | -            | -                | -                | -         |     1.44 | auth0ri, fakerealityy, kiy0o, milky, Shlyaperson |
|            4 |     5224 | 2024-10-12 | LEON Esports                              | L   | 0.265      | -            | -                | -                | -         |    -3.24 | auth0ri, fakerealityy, Kiy0o, milky, Shlyaperson |
|            3 |     5291 | 2024-10-10 | Illuminar Gaming                          | L   | 0.252      | -            | -                | -                | -         |    -2.09 | auth0ri, fakerealityy, kiy0o, milky, Shlyaperson |
|            2 |     5577 | 2024-10-05 | ENRAGE                                    | W   | 0.220      | 0.143        | 0.000 (0.000)    | 0.093 (0.003)    | -         |     2.96 | auth0ri, fakerealityy, kiy0o, milky, Shlyaperson |
|            1 |     7024 | 2024-09-14 | Inroads Esports                           | L   | 0.078      | -            | -                | -                | -         |    -1.87 | Kiy0o, milky, rafftu, tripex17, xxlafy           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,222.86)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.740 | $718.19        | $531.15         |
| 2024-12-17 |      0.706 | $2,395.34      | $1,691.71       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
