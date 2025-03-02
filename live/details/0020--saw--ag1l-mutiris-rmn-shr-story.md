### Roster Details<br />
Team Name: SAW<br />
Roster: Ag1l, MUTiRiS, rmn, shr, story<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1283.2<br />
<br />
Final Rank Value (1283.2) = Starting Rank Value (1341.5) + Head To Head Adjustments (-58.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.633[<sup>1</sup>](#table2)
- Bounty Collected: 0.448[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.662[<sup>2</sup>](#table1)

The average of these factors is 0.471<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1341.5
- 400 + ( ( 0.471 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1341.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      197 | 2025-02-21 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |    -1.02 | Ag1l, MUTiRiS, rmn, shr, story          |
|           34 |      269 | 2025-02-18 | 3DMAX           | W   | 1.000      | 1.000        | 0.295 (0.295)    | 0.535 (0.535)    | 1 (1.000) |    26.57 | Ag1l, MUTiRiS, rmn, shr, story          |
|           33 |      284 | 2025-02-17 | Complexity      | W   | 1.000      | 1.000        | 0.097 (0.097)    | 0.229 (0.229)    | 1 (1.000) |    10.06 | Ag1l, MUTiRiS, rmn, shr, story          |
|           32 |      355 | 2025-02-16 | FlyQuest        | W   | 1.000      | 1.000        | 0.105 (0.105)    | 0.239 (0.239)    | 1 (1.000) |    11.03 | Ag1l, MUTiRiS, rmn, shr, story          |
|           31 |      411 | 2025-02-15 | Astralis        | L   | 1.000      | -            | -                | -                | -         |    -2.21 | Ag1l, MUTiRiS, rmn, shr, story          |
|           30 |      493 | 2025-02-14 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |    -0.95 | Ag1l, MUTiRiS, rmn, shr, story          |
|           29 |      848 | 2025-02-06 | 500             | L   | 1.000      | -            | -                | -                | -         |   -24.45 | Ag1l, MUTiRiS, rmn, shr, story          |
|           28 |      907 | 2025-02-05 | Eco Warriors    | W   | 1.000      | 0.143        | -                | 0.244 (0.035)    | -         |     2.41 | Ag1l, MUTiRiS, rmn, shr, story          |
|           27 |      916 | 2025-02-05 | BC.Game Esports | L   | 1.000      | -            | -                | -                | -         |   -24.47 | Ag1l, MUTiRiS, rmn, shr, story          |
|           26 |     1102 | 2025-01-30 | Virtus.pro      | L   | 0.998      | -            | -                | -                | -         |    -5.36 | Ag1l, MUTiRiS, rmn, shr, story          |
|           25 |     1110 | 2025-01-29 | GamerLegion     | L   | 0.992      | -            | -                | -                | -         |    -6.00 | Ag1l, MUTiRiS, rmn, shr, story          |
|           24 |     1183 | 2025-01-15 | BIG             | L   | 0.899      | -            | -                | -                | -         |    -8.56 | Ag1l, MUTiRiS, rmn, shr, story          |
|           23 |     3136 | 2024-11-19 | BetBoom Team    | L   | 0.522      | -            | -                | -                | -         |   -13.53 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           22 |     3173 | 2024-11-18 | Natus Vincere   | L   | 0.516      | -            | -                | -                | -         |    -1.62 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           21 |     3217 | 2024-11-17 | Team Falcons    | W   | 0.510      | -            | -                | -                | 1 (0.510) |     0.62 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           20 |     3250 | 2024-11-17 | UNiTY esports   | W   | 0.505      | 0.143        | -                | 0.412 (0.030)    | 1 (0.505) |     1.02 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           19 |     3293 | 2024-11-16 | SINNERS Esports | L   | 0.503      | -            | -                | -                | -         |   -14.45 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           18 |     4457 | 2024-10-27 | B8              | W   | 0.367      | 0.500        | 0.124 (0.023)    | 0.590 (0.108)    | 1 (0.367) |     3.12 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           17 |     4478 | 2024-10-27 | Monte           | W   | 0.365      | 0.500        | 0.029 (0.005)    | 0.242 (0.044)    | 1 (0.365) |     0.84 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           16 |     4596 | 2024-10-25 | B8              | W   | 0.352      | 0.500        | 0.124 (0.022)    | 0.590 (0.104)    | 1 (0.352) |     2.82 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           15 |     4604 | 2024-10-25 | Team Falcons    | W   | 0.351      | -            | -                | -                | 1 (0.351) |     0.38 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           14 |     4889 | 2024-10-18 | 3DMAX           | L   | 0.306      | -            | -                | -                | -         |    -1.97 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           13 |     4927 | 2024-10-17 | 9Pandas         | W   | 0.299      | 0.500        | 0.085 (0.013)    | 0.485 (0.073)    | -         |     1.20 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           12 |     4995 | 2024-10-16 | HEROIC          | L   | 0.293      | -            | -                | -                | -         |    -7.40 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           11 |     5512 | 2024-10-06 | BIG             | L   | 0.226      | -            | -                | -                | -         |    -2.03 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|           10 |     5561 | 2024-10-05 | BetBoom Team    | W   | 0.220      | 0.500        | 0.103 (0.011)    | 0.382 (0.042)    | 1 (0.220) |     1.05 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            9 |     5650 | 2024-10-04 | FlyQuest        | L   | 0.214      | -            | -                | -                | -         |    -5.29 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            8 |     5666 | 2024-10-04 | Rooster         | W   | 0.212      | -            | -                | -                | -         |     0.16 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            7 |     5968 | 2024-09-29 | 3DMAX           | W   | 0.178      | 0.143        | 0.295 (0.008)    | -                | -         |     4.57 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            6 |     6021 | 2024-09-28 | 9z Team         | W   | 0.173      | -            | -                | -                | -         |     0.24 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            5 |     6052 | 2024-09-28 | Nemiga Gaming   | W   | 0.172      | 0.143        | 0.177 (0.004)    | -                | -         |     0.78 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            4 |     6115 | 2024-09-27 | B8              | L   | 0.166      | -            | -                | -                | -         |    -4.10 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            3 |     6141 | 2024-09-27 | GameAgents      | W   | 0.165      | -            | -                | -                | -         |     0.14 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            2 |     7148 | 2024-09-12 | Insilio         | L   | 0.064      | -            | -                | -                | -         |    -1.98 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            1 |     7258 | 2024-09-10 | TSM             | W   | 0.051      | -            | -                | -                | -         |     0.06 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($88,312.18)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.26) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-10-27 |      0.367 | $50,000.00     | $18,328.70      |
| 2024-10-20 |      0.319 | $8,500.00      | $2,710.56       |
| 2024-10-06 |      0.227 | $10,000.00     | $2,272.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
