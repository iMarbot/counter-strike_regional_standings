### Roster Details<br />
Team Name: Rhyno Esports<br />
Roster: aragornN, Icarus, krazy, P3R3IIRA, seabraez<br />
Global Rank: [173](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [128]( ../standings_europe.md)<br />
<br />
Final Rank Value:  735.5<br />
<br />
Final Rank Value (735.5) = Starting Rank Value (852.4) + Head To Head Adjustments (-116.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.066[<sup>2</sup>](#table1)
- LAN Wins: 0.232[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 852.4
- 400 + ( ( 0.226 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 852.4


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
|           33 |       18 | 2025-02-27 | BC.Game Esports                | L   | 1.000      | -            | -                | -                | -         |    -3.09 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           32 |       28 | 2025-02-26 | Alliance                       | L   | 1.000      | -            | -                | -                | -         |   -11.34 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           31 |      130 | 2025-02-22 | TEAM NEXT LEVEL                | L   | 1.000      | -            | -                | -                | -         |   -14.80 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           30 |      252 | 2025-02-20 | Betclic Apogee Esports         | L   | 1.000      | -            | -                | -                | -         |   -10.13 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           29 |      262 | 2025-02-19 | PARIVISION                     | L   | 1.000      | -            | -                | -                | -         |   -14.09 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           28 |      300 | 2025-02-17 | Mercenaires                    | L   | 1.000      | -            | -                | -                | -         |   -25.43 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           27 |      339 | 2025-02-16 | Abyss team                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.82 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           26 |      764 | 2025-02-07 | 1win                           | L   | 1.000      | -            | -                | -                | -         |   -17.61 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           25 |      990 | 2025-02-04 | Informmix                      | L   | 1.000      | -            | -                | -                | -         |   -27.00 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           24 |     1209 | 2025-01-09 | Insilio                        | L   | 0.859      | -            | -                | -                | -         |   -18.10 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           23 |     1216 | 2025-01-06 | FLuffy Gangsters               | W   | 0.840      | 0.417        | 0.014 (0.005)    | 0.925 (0.324)    | 0 (0.000) |    12.61 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           22 |     1225 | 2025-01-04 | CS2NEWS                        | W   | 0.824      | 0.417        | -                | 0.062 (0.021)    | 0 (0.000) |     3.87 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           21 |     1227 | 2025-01-03 | KONO.ECF                       | L   | 0.819      | -            | -                | -                | -         |   -21.02 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           20 |     1308 | 2024-12-28 | BRUTE                          | W   | 0.777      | 0.417        | 0.004 (0.001)    | 0.345 (0.112)    | 0 (0.000) |     7.01 | aragornN, Icarus, krazy, P3R3IIRA, seabraez |
|           19 |     1978 | 2024-12-08 | ZennoX                         | L   | 0.647      | -            | -                | -                | -         |   -15.85 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           18 |     2125 | 2024-12-06 | Ex-UHKA eSports                | W   | 0.634      | 0.333        | -                | 0.271 (0.057)    | 0 (0.000) |     2.44 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           17 |     2205 | 2024-12-04 | Maestro Esports (Belgian team) | W   | 0.620      | 0.333        | -                | 0.100 (0.021)    | -         |     2.12 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           16 |     2329 | 2024-12-02 | Team M33                       | W   | 0.607      | -            | -                | -                | -         |     1.19 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           15 |     2485 | 2024-11-30 | NIP Svea                       | W   | 0.594      | 0.333        | -                | 0.048 (0.009)    | -         |     1.25 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           14 |     2609 | 2024-11-28 | BRUTE                          | L   | 0.580      | -            | -                | -                | -         |   -13.45 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           13 |     2977 | 2024-11-22 | GTZ.ESPORTS                    | W   | 0.539      | 0.143        | 0.080 (0.006)    | 0.563 (0.043)    | 1 (0.539) |    13.67 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           12 |     3244 | 2024-11-17 | Iberian Soul                   | W   | 0.506      | 0.143        | 0.015 (0.001)    | 0.553 (0.040)    | 1 (0.506) |     7.10 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           11 |     3339 | 2024-11-16 | The Agency Clan                | W   | 0.498      | 0.143        | 0.006 (0.000)    | 0.295 (0.021)    | 1 (0.498) |     7.26 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|           10 |     3715 | 2024-11-09 | Rhyno Youngsters               | W   | 0.453      | 0.143        | 0.003 (0.000)    | -                | -         |     4.85 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|            9 |     4523 | 2024-10-26 | GOOFYBOYZ                      | W   | 0.359      | 0.143        | 0.003 (0.000)    | 0.183 (0.009)    | -         |     4.06 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|            8 |     4534 | 2024-10-26 | SQUAD (Portuguese team)        | W   | 0.358      | -            | -                | -                | -         |     0.81 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|            7 |     4573 | 2024-10-25 | Coxos                          | W   | 0.353      | -            | -                | -                | -         |     0.80 | aragornN, Icarus, P3R3IIRA, seabraez, shr   |
|            6 |     5532 | 2024-10-06 | Rhyno Esports                  | W   | 0.225      | 0.143        | 0.002 (0.000)    | -                | 1 (0.225) |     2.08 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            5 |     5593 | 2024-10-05 | Rhyno Youngsters               | W   | 0.219      | 0.143        | 0.003 (0.000)    | -                | 1 (0.219) |     2.56 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            4 |     6054 | 2024-09-28 | Rhyno Esports                  | L   | 0.172      | -            | -                | -                | -         |    -3.92 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            3 |     6075 | 2024-09-28 | Impulse GW                     | W   | 0.171      | 0.143        | 0.006 (0.000)    | -                | -         |     1.80 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            2 |     6813 | 2024-09-17 | SQUAD (Portuguese team)        | W   | 0.100      | -            | -                | -                | -         |     0.35 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |
|            1 |     6869 | 2024-09-16 | Turritos                       | W   | 0.094      | -            | -                | -                | -         |     0.22 | aragornN, Icarus, P3R3IIRA, SeabraEZ, shr   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,465.31)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-22 |      0.539 | $1,047.10      | $564.42         |
| 2024-11-17 |      0.506 | $5,272.32      | $2,665.45       |
| 2024-10-06 |      0.225 | $5,490.86      | $1,235.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
