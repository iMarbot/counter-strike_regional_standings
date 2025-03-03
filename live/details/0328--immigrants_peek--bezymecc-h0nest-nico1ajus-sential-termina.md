### Roster Details<br />
Team Name: Immigrants Peek<br />
Roster: bezymecc, H0NeST, nico1ajus, sential, Termina<br />
Global Rank: [328](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [213]( ../standings_europe.md)<br />
<br />
Final Rank Value:  635.4<br />
<br />
Final Rank Value (635.4) = Starting Rank Value (648.5) + Head To Head Adjustments (-13.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.261[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 648.5
- 400 + ( ( 0.124 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 648.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |      186 | 2025-02-21 | Wanted Goons        | L   | 1.000      | -            | -                | -                | -         |   -17.70 | bezymecc, H0NeST, nico1ajus, sential, Termina   |
|           18 |      236 | 2025-02-20 | Vireo.pro           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.14 | bezymecc, H0NeST, nico1ajus, sential, Termina   |
|           17 |      329 | 2025-02-16 | Straight2Killin     | L   | 1.000      | -            | -                | -                | -         |   -22.59 | bezymecc, H0NeST, nico1ajus, sential, Termina   |
|           16 |      517 | 2025-02-13 | BLUEJAYS            | L   | 1.000      | -            | -                | -                | -         |    -3.27 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|           15 |      585 | 2025-02-10 | Vagrants            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.276 (0.039)    | 0 (0.000) |    17.49 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|           14 |      589 | 2025-02-10 | SUPER EVIL GANG     | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.352 (0.050)    | 0 (0.000) |    18.63 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|           13 |      621 | 2025-02-09 | Mythic              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     9.75 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|           12 |      684 | 2025-02-08 | Vagrants            | L   | 1.000      | -            | -                | -                | -         |   -12.97 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|           11 |      744 | 2025-02-07 | Chill Guys          | L   | 1.000      | -            | -                | -                | -         |   -13.31 | bezymecc, H0NeST, myline, nico1ajus, sential    |
|           10 |      829 | 2025-02-06 | Blahaj              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.144 (0.021)    | 0 (0.000) |    11.62 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|            9 |      831 | 2025-02-06 | Team Aether         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.094 (0.013)    | 0 (0.000) |     9.54 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|            8 |     1765 | 2024-12-13 | MarcaRegistrada     | L   | 0.674      | -            | -                | -                | -         |   -11.31 | bezymecc, H0NeST, marekiew, nico1ajus, Valter0k |
|            7 |     2204 | 2024-12-04 | SUPER EVIL GANG     | L   | 0.614      | -            | -                | -                | -         |    -8.14 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            6 |     2254 | 2024-12-03 | MIGHT               | W   | 0.608      | 0.372        | 0.002 (0.000)    | 0.489 (0.111)    | 0 (0.000) |    13.05 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            5 |     2322 | 2024-12-02 | Orbital vsat online | W   | 0.601      | 0.372        | 0.000 (0.000)    | 0.028 (0.006)    | 0 (0.000) |     4.02 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            4 |     2395 | 2024-12-01 | LOSTHILLS           | W   | 0.594      | 0.372        | 0.000 (0.000)    | 0.026 (0.006)    | 0 (0.000) |     4.10 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            3 |     2700 | 2024-11-26 | MCS Gaming          | L   | 0.561      | -            | -                | -                | -         |    -8.57 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            2 |     2945 | 2024-11-22 | Make Your Mind      | L   | 0.534      | -            | -                | -                | -         |    -6.91 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            1 |     6625 | 2024-09-20 | Kinship             | L   | 0.113      | -            | -                | -                | -         |    -2.58 | bezymecc, H0NeST, nakaznyi, nico1ajus, Rulik    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($480.63)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.641 | $750.00        | $480.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
