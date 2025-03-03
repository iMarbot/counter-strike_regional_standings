### Roster Details<br />
Team Name: Rhyno Esports<br />
Roster: aragornN, Icarus, krazy, P3R3IIRA, seabraez<br />
Global Rank: [175](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [128]( ../standings_europe.md)<br />
<br />
Final Rank Value:  733.7<br />
<br />
Final Rank Value (733.7) = Starting Rank Value (850.1) + Head To Head Adjustments (-116.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.260[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.228[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.1
- 400 + ( ( 0.225 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 850.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |       33 | 2025-02-27 | BC.Game Esports                | L   | 1.000      | -            | -                | -                | -         |    -3.07 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           32 |       43 | 2025-02-26 | Alliance                       | L   | 1.000      | -            | -                | -                | -         |   -11.31 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           31 |      145 | 2025-02-22 | TEAM NEXT LEVEL                | L   | 1.000      | -            | -                | -                | -         |   -14.74 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           30 |      264 | 2025-02-20 | Betclic Apogee Esports         | L   | 1.000      | -            | -                | -                | -         |   -10.11 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           29 |      274 | 2025-02-19 | PARIVISION                     | L   | 1.000      | -            | -                | -                | -         |   -14.02 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           28 |      312 | 2025-02-17 | Mercenaires                    | L   | 1.000      | -            | -                | -                | -         |   -25.37 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           27 |      351 | 2025-02-16 | Abyss team                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.85 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           26 |      776 | 2025-02-07 | 1win                           | L   | 1.000      | -            | -                | -                | -         |   -17.57 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           25 |     1002 | 2025-02-04 | Informmix                      | L   | 1.000      | -            | -                | -                | -         |   -26.95 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           24 |     1221 | 2025-01-09 | Insilio                        | L   | 0.850      | -            | -                | -                | -         |   -17.95 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           23 |     1228 | 2025-01-06 | FLuffy Gangsters               | W   | 0.832      | 0.417        | 0.014 (0.005)    | 0.909 (0.315)    | 0 (0.000) |    12.47 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           22 |     1237 | 2025-01-04 | CS2NEWS                        | W   | 0.816      | 0.417        | -                | 0.062 (0.021)    | 0 (0.000) |     3.87 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           21 |     1239 | 2025-01-03 | KONO.ECF                       | L   | 0.811      | -            | -                | -                | -         |   -20.77 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           20 |     1320 | 2024-12-28 | BRUTE                          | W   | 0.769      | 0.417        | 0.004 (0.001)    | 0.341 (0.109)    | 0 (0.000) |     6.99 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           19 |     1990 | 2024-12-08 | ZennoX                         | L   | 0.639      | -            | -                | -                | -         |   -15.60 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           18 |     2137 | 2024-12-06 | Ex-UHKA eSports                | W   | 0.625      | 0.333        | -                | 0.268 (0.056)    | 0 (0.000) |     2.43 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           17 |     2217 | 2024-12-04 | Maestro Esports (Belgian team) | W   | 0.612      | 0.333        | -                | 0.100 (0.020)    | -         |     2.11 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           16 |     2341 | 2024-12-02 | Team M33                       | W   | 0.599      | -            | -                | -                | -         |     1.19 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           15 |     2497 | 2024-11-30 | NIP Svea                       | W   | 0.586      | 0.333        | -                | 0.047 (0.009)    | -         |     1.25 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           14 |     2621 | 2024-11-28 | BRUTE                          | L   | 0.572      | -            | -                | -                | -         |   -13.20 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           13 |     2989 | 2024-11-22 | GTZ.ESPORTS                    | W   | 0.531      | 0.143        | 0.080 (0.006)    | 0.557 (0.042)    | 1 (0.531) |    13.49 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           12 |     3256 | 2024-11-17 | Iberian Soul                   | W   | 0.497      | 0.143        | 0.015 (0.001)    | 0.551 (0.039)    | 1 (0.497) |     7.02 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           11 |     3351 | 2024-11-16 | The Agency Clan                | W   | 0.490      | 0.143        | 0.006 (0.000)    | 0.292 (0.020)    | 1 (0.490) |     7.18 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           10 |     3727 | 2024-11-09 | Rhyno Youngsters               | W   | 0.445      | 0.143        | 0.003 (0.000)    | -                | -         |     4.79 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|            9 |     4535 | 2024-10-26 | GOOFYBOYZ                      | W   | 0.350      | 0.143        | 0.003 (0.000)    | 0.179 (0.009)    | -         |     4.00 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|            8 |     4546 | 2024-10-26 | SQUAD (Portuguese team)        | W   | 0.350      | -            | -                | -                | -         |     0.80 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|            7 |     4585 | 2024-10-25 | Coxos                          | W   | 0.345      | -            | -                | -                | -         |     0.80 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|            6 |     5544 | 2024-10-06 | Rhyno Esports                  | W   | 0.217      | 0.143        | 0.002 (0.000)    | -                | 1 (0.217) |     2.01 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            5 |     5605 | 2024-10-05 | Rhyno Youngsters               | W   | 0.211      | 0.143        | 0.003 (0.000)    | -                | 1 (0.211) |     2.47 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            4 |     6066 | 2024-09-28 | Rhyno Esports                  | L   | 0.164      | -            | -                | -                | -         |    -3.73 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            3 |     6087 | 2024-09-28 | Impulse GW                     | W   | 0.163      | 0.143        | 0.006 (0.000)    | -                | -         |     1.73 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            2 |     6825 | 2024-09-17 | SQUAD (Portuguese team)        | W   | 0.092      | -            | -                | -                | -         |     0.33 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            1 |     6881 | 2024-09-16 | Turritos                       | W   | 0.085      | -            | -                | -                | -         |     0.20 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,368.53)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-22 |      0.531 | $1,047.10      | $555.84         |
| 2024-11-17 |      0.497 | $5,272.32      | $2,622.24       |
| 2024-10-06 |      0.217 | $5,490.86      | $1,190.45       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
