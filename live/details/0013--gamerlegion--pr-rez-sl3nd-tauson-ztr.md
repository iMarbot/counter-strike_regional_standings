### Roster Details<br />
Team Name: GamerLegion<br />
Roster: PR, REZ, sl3nd, Tauson, ztr<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1582.9<br />
<br />
Final Rank Value (1582.9) = Starting Rank Value (1583.7) + Head To Head Adjustments (-0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.529[<sup>1</sup>](#table2)
- Bounty Collected: 0.631[<sup>2</sup>](#table1)
- Opponent Network: 0.341[<sup>2</sup>](#table1)
- LAN Wins: 0.865[<sup>2</sup>](#table1)

The average of these factors is 0.592<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1583.7
- 400 + ( ( 0.592 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1583.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      593 | 2025-02-10 | Metizport       | W   | 1.000      | 0.143        | 0.074 (0.011)    | 0.507 (0.072)    | -         |     1.22 | PR, REZ, sl3nd, Tauson, ztr      |
|           28 |      606 | 2025-02-10 | Hesta           | W   | 1.000      | 0.143        | -                | 0.655 (0.094)    | -         |     0.37 | PR, REZ, sl3nd, Tauson, ztr      |
|           27 |      729 | 2025-02-08 | PARIVISION      | L   | 1.000      | -            | -                | -                | -         |   -31.15 | PR, REZ, sl3nd, Tauson, ztr      |
|           26 |      954 | 2025-02-04 | Team Spirit     | L   | 1.000      | -            | -                | -                | -         |    -3.71 | PR, REZ, sl3nd, Tauson, ztr      |
|           25 |     1008 | 2025-02-04 | Astralis        | W   | 1.000      | 1.000        | 0.619 (0.619)    | 0.786 (0.786)    | 1 (1.000) |    22.26 | PR, REZ, sl3nd, Tauson, ztr      |
|           24 |     1038 | 2025-02-03 | The MongolZ     | L   | 1.000      | -            | -                | -                | -         |    -3.75 | PR, REZ, sl3nd, Tauson, ztr      |
|           23 |     1066 | 2025-02-01 | MOUZ            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.470 (0.470)    | 1 (1.000) |    27.35 | PR, REZ, sl3nd, Tauson, ztr      |
|           22 |     1113 | 2025-01-30 | PaiN Gaming     | W   | 0.990      | 1.000        | 0.323 (0.320)    | 0.549 (0.544)    | 1 (0.990) |    17.27 | PR, REZ, sl3nd, Tauson, ztr      |
|           21 |     1122 | 2025-01-29 | SAW             | W   | 0.983      | 1.000        | 0.266 (0.262)    | 0.326 (0.320)    | 1 (0.983) |     5.98 | PR, REZ, sl3nd, Tauson, ztr      |
|           20 |     1188 | 2025-01-17 | PaiN Gaming     | L   | 0.903      | -            | -                | -                | -         |   -13.51 | PR, REZ, sl3nd, Tauson, ztr      |
|           19 |     2114 | 2024-12-06 | Natus Vincere   | L   | 0.628      | -            | -                | -                | -         |    -6.36 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           18 |     2157 | 2024-12-05 | Wildcard        | W   | 0.622      | 1.000        | 0.178 (0.111)    | 0.422 (0.262)    | 1 (0.622) |     4.37 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           17 |     2192 | 2024-12-05 | Team Liquid     | L   | 0.616      | -            | -                | -                | -         |   -11.07 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           16 |     2200 | 2024-12-04 | Team Vitality   | L   | 0.615      | -            | -                | -                | -         |    -2.52 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           15 |     2373 | 2024-12-02 | Passion UA      | W   | 0.596      | 1.000        | 0.044 (0.026)    | 0.545 (0.325)    | 1 (0.596) |     0.92 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           14 |     2459 | 2024-12-01 | The MongolZ     | L   | 0.589      | -            | -                | -                | -         |    -2.23 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           13 |     2546 | 2024-11-30 | PaiN Gaming     | W   | 0.583      | 1.000        | 0.323 (0.188)    | 0.549 (0.320)    | 1 (0.583) |     9.66 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           12 |     2576 | 2024-11-29 | FURIA           | W   | 0.581      | 1.000        | 0.094 (0.055)    | 0.379 (0.220)    | 1 (0.581) |     5.98 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           11 |     3139 | 2024-11-20 | BetBoom Team    | W   | 0.517      | -            | -                | -                | 1 (0.517) |     0.88 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           10 |     3142 | 2024-11-20 | SINNERS Esports | W   | 0.516      | -            | -                | -                | 1 (0.516) |     0.45 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            9 |     3180 | 2024-11-19 | Team Falcons    | W   | 0.509      | -            | -                | -                | -         |     0.16 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            8 |     3222 | 2024-11-18 | UNiTY esports   | W   | 0.503      | -            | -                | -                | -         |     0.27 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            7 |     3281 | 2024-11-17 | Dynamo Eclot    | L   | 0.496      | -            | -                | -                | -         |   -14.84 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            6 |     3309 | 2024-11-16 | Team Vitality   | L   | 0.495      | -            | -                | -                | -         |    -2.14 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            5 |     5271 | 2024-10-11 | GUN5 Esports    | L   | 0.251      | -            | -                | -                | -         |    -7.70 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            4 |     5521 | 2024-10-06 | Passion UA      | W   | 0.218      | -            | -                | -                | -         |     0.32 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            3 |     5538 | 2024-10-06 | 9Pandas         | W   | 0.217      | -            | -                | -                | -         |     0.22 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            2 |     5579 | 2024-10-05 | B8              | W   | 0.212      | 0.435        | 0.126 (0.012)    | -                | -         |     0.46 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            1 |     5669 | 2024-10-04 | Adventurers     | W   | 0.205      | -            | -                | -                | -         |     0.07 | FL4MUS, sl3nd, Tauson, volt, ztr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,456.90)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $24,000.00     | $24,000.00      |
| 2024-12-15 |      0.683 | $20,000.00     | $13,655.09      |
| 2024-10-06 |      0.218 | $22,000.00     | $4,801.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
