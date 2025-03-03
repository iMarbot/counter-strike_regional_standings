### Roster Details<br />
Team Name: Dragon Esports Club<br />
Roster: Kiy0o, Matheos, milky, rafftu, Shlyaperson<br />
Global Rank: [243](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [168]( ../standings_europe.md)<br />
<br />
Final Rank Value:  681.8<br />
<br />
Final Rank Value (681.8) = Starting Rank Value (689.5) + Head To Head Adjustments (-7.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.5
- 400 + ( ( 0.145 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 689.5


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
|           26 |     1345 | 2024-12-27 | Preasy Esport                             | L   | 0.763      | -            | -                | -                | -         |    -9.96 | Kiy0o, Matheos, milky, rafftu, Shlyaperson       |
|           25 |     1375 | 2024-12-24 | Soul's Heart Esport                       | W   | 0.743      | 0.333        | 0.000 (0.000)    | 0.035 (0.009)    | 0 (0.000) |     4.00 | Kiy0o, Matheos, milky, rafftu, Shlyaperson       |
|           24 |     1386 | 2024-12-23 | BMTH (Ukrainian team)                     | L   | 0.737      | -            | -                | -                | -         |   -16.82 | Kiy0o, Matheos, milky, rafftu, Shlyaperson       |
|           23 |     1398 | 2024-12-22 | Soul's Heart Esport                       | W   | 0.732      | 0.333        | 0.000 (0.000)    | 0.035 (0.008)    | 0 (0.000) |     3.52 | Kiy0o, Matheos, milky, rafftu, Shlyaperson       |
|           22 |     1404 | 2024-12-22 | C.S.D.E                                   | W   | 0.731      | 0.143        | 0.006 (0.001)    | 0.153 (0.016)    | 0 (0.000) |    11.47 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           21 |     1423 | 2024-12-22 | SkyFury                                   | W   | 0.730      | 0.143        | 0.004 (0.000)    | 0.338 (0.035)    | 0 (0.000) |    11.45 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           20 |     1467 | 2024-12-21 | NEVERMORE (Ukrainian team)                | W   | 0.724      | 0.143        | 0.010 (0.001)    | 0.904 (0.094)    | 0 (0.000) |    15.86 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           19 |     1479 | 2024-12-21 | Lazer Cats                                | L   | 0.723      | -            | -                | -                | -         |    -9.30 | 3ippoch, Kiy0o, milky, rafftu, Shlyaperson       |
|           18 |     1484 | 2024-12-21 | GUESS                                     | W   | 0.723      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     6.10 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           17 |     1488 | 2024-12-21 | 0to100                                    | L   | 0.723      | -            | -                | -                | -         |    -8.36 | 3ippoch, Kiy0o, milky, rafftu, Shlyaperson       |
|           16 |     1514 | 2024-12-20 | BadGuys                                   | L   | 0.719      | -            | -                | -                | -         |   -13.69 | kiy0o, milky, rafftu, Shlyaperson, Зippoch       |
|           15 |     1571 | 2024-12-18 | TEAM NEXT LEVEL                           | L   | 0.703      | -            | -                | -                | -         |    -6.47 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           14 |     1588 | 2024-12-17 | Copenhagen Wolves (American organization) | L   | 0.696      | -            | -                | -                | -         |    -5.80 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           13 |     1600 | 2024-12-16 | TEAM NEXT LEVEL                           | L   | 0.691      | -            | -                | -                | -         |    -6.54 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           12 |     1608 | 2024-12-16 | Astralis Talent                           | W   | 0.689      | 0.371        | 0.002 (0.001)    | 0.724 (0.185)    | 0 (0.000) |    13.52 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           11 |     2172 | 2024-12-05 | Chroma                                    | W   | 0.618      | 0.143        | 0.005 (0.000)    | 0.091 (0.008)    | 0 (0.000) |     9.93 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|           10 |     2231 | 2024-12-04 | NewBALLS                                  | L   | 0.612      | -            | -                | -                | -         |   -10.53 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|            9 |     2418 | 2024-12-01 | WOPA Esport                               | L   | 0.592      | -            | -                | -                | -         |    -5.97 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|            8 |     2634 | 2024-11-28 | Reveal (German team)                      | W   | 0.572      | 0.333        | 0.001 (0.000)    | 0.187 (0.036)    | 0 (0.000) |     7.92 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|            7 |     2730 | 2024-11-26 | NIP Svea                                  | W   | 0.559      | 0.333        | -                | 0.047 (0.009)    | 0 (0.000) |     3.09 | fakerealityy, Kiy0o, milky, rafftu, Shlyaperson  |
|            6 |     5025 | 2024-10-16 | Tibian Soldiers                           | W   | 0.283      | -            | -                | -                | -         |     1.47 | auth0ri, fakerealityy, kiy0o, milky, Shlyaperson |
|            5 |     5146 | 2024-10-13 | Tibian Soldiers                           | W   | 0.264      | -            | -                | -                | -         |     1.40 | auth0ri, fakerealityy, kiy0o, milky, Shlyaperson |
|            4 |     5236 | 2024-10-12 | LEON Esports                              | L   | 0.257      | -            | -                | -                | -         |    -3.14 | auth0ri, fakerealityy, Kiy0o, milky, Shlyaperson |
|            3 |     5303 | 2024-10-10 | Illuminar Gaming                          | L   | 0.243      | -            | -                | -                | -         |    -2.05 | auth0ri, fakerealityy, kiy0o, milky, Shlyaperson |
|            2 |     5589 | 2024-10-05 | ENRAGE                                    | W   | 0.211      | 0.143        | 0.000 (0.000)    | 0.094 (0.003)    | -         |     2.85 | auth0ri, fakerealityy, kiy0o, milky, Shlyaperson |
|            1 |     7036 | 2024-09-14 | Inroads Esports                           | L   | 0.070      | -            | -                | -                | -         |    -1.67 | Kiy0o, milky, rafftu, tripex17, xxlafy           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,197.35)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.731 | $718.19        | $525.26         |
| 2024-12-17 |      0.698 | $2,395.34      | $1,672.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
