### Roster Details<br />
Team Name: SAW<br />
Roster: Ag1l, MUTiRiS, rmn, shr, story<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1283.1<br />
<br />
Final Rank Value (1283.1) = Starting Rank Value (1340.8) + Head To Head Adjustments (-57.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.635[<sup>1</sup>](#table2)
- Bounty Collected: 0.448[<sup>2</sup>](#table1)
- Opponent Network: 0.141[<sup>2</sup>](#table1)
- LAN Wins: 0.657[<sup>2</sup>](#table1)

The average of these factors is 0.470<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1340.8
- 400 + ( ( 0.470 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1340.8


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
|           35 |      209 | 2025-02-21 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |    -1.01 | Ag1l, MUTiRiS, rmn, shr, story          |
|           34 |      281 | 2025-02-18 | 3DMAX           | W   | 1.000      | 1.000        | 0.298 (0.298)    | 0.528 (0.528)    | 1 (1.000) |    26.57 | Ag1l, MUTiRiS, rmn, shr, story          |
|           33 |      296 | 2025-02-17 | Complexity      | W   | 1.000      | 1.000        | 0.098 (0.098)    | 0.226 (0.226)    | 1 (1.000) |     9.99 | Ag1l, MUTiRiS, rmn, shr, story          |
|           32 |      367 | 2025-02-16 | FlyQuest        | W   | 1.000      | 1.000        | 0.105 (0.105)    | 0.235 (0.235)    | 1 (1.000) |    10.87 | Ag1l, MUTiRiS, rmn, shr, story          |
|           31 |      423 | 2025-02-15 | Astralis        | L   | 1.000      | -            | -                | -                | -         |    -2.18 | Ag1l, MUTiRiS, rmn, shr, story          |
|           30 |      505 | 2025-02-14 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |    -0.94 | Ag1l, MUTiRiS, rmn, shr, story          |
|           29 |      860 | 2025-02-06 | 500             | L   | 1.000      | -            | -                | -                | -         |   -24.48 | Ag1l, MUTiRiS, rmn, shr, story          |
|           28 |      919 | 2025-02-05 | Eco Warriors    | W   | 1.000      | 0.143        | -                | 0.241 (0.034)    | -         |     2.40 | Ag1l, MUTiRiS, rmn, shr, story          |
|           27 |      928 | 2025-02-05 | BC.Game Esports | L   | 1.000      | -            | -                | -                | -         |   -24.49 | Ag1l, MUTiRiS, rmn, shr, story          |
|           26 |     1114 | 2025-01-30 | Virtus.pro      | L   | 0.990      | -            | -                | -                | -         |    -5.28 | Ag1l, MUTiRiS, rmn, shr, story          |
|           25 |     1122 | 2025-01-29 | GamerLegion     | L   | 0.983      | -            | -                | -                | -         |    -5.98 | Ag1l, MUTiRiS, rmn, shr, story          |
|           24 |     1195 | 2025-01-15 | BIG             | L   | 0.891      | -            | -                | -                | -         |    -8.49 | Ag1l, MUTiRiS, rmn, shr, story          |
|           23 |     3148 | 2024-11-19 | BetBoom Team    | L   | 0.514      | -            | -                | -                | -         |   -13.35 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           22 |     3185 | 2024-11-18 | Natus Vincere   | L   | 0.508      | -            | -                | -                | -         |    -1.62 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           21 |     3229 | 2024-11-17 | Team Falcons    | W   | 0.502      | -            | -                | -                | 1 (0.502) |     0.60 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           20 |     3262 | 2024-11-17 | UNiTY esports   | W   | 0.497      | 0.143        | -                | 0.403 (0.029)    | 1 (0.497) |     0.99 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           19 |     3305 | 2024-11-16 | SINNERS Esports | L   | 0.495      | -            | -                | -                | -         |   -14.23 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           18 |     4469 | 2024-10-27 | B8              | W   | 0.358      | 0.500        | 0.126 (0.022)    | 0.586 (0.105)    | 1 (0.358) |     3.02 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           17 |     4490 | 2024-10-27 | Monte           | W   | 0.357      | 0.500        | 0.029 (0.005)    | 0.235 (0.042)    | 1 (0.357) |     0.81 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           16 |     4608 | 2024-10-25 | B8              | W   | 0.344      | 0.500        | 0.126 (0.022)    | 0.586 (0.101)    | 1 (0.344) |     2.73 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           15 |     4616 | 2024-10-25 | Team Falcons    | W   | 0.343      | -            | -                | -                | 1 (0.343) |     0.37 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           14 |     4901 | 2024-10-18 | 3DMAX           | L   | 0.298      | -            | -                | -                | -         |    -1.92 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           13 |     4939 | 2024-10-17 | 9Pandas         | W   | 0.291      | 0.500        | 0.085 (0.012)    | 0.477 (0.070)    | -         |     1.16 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           12 |     5007 | 2024-10-16 | HEROIC          | L   | 0.285      | -            | -                | -                | -         |    -7.22 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           11 |     5524 | 2024-10-06 | BIG             | L   | 0.218      | -            | -                | -                | -         |    -1.96 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|           10 |     5573 | 2024-10-05 | BetBoom Team    | W   | 0.212      | 0.500        | 0.104 (0.011)    | 0.379 (0.040)    | 1 (0.212) |     1.01 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            9 |     5662 | 2024-10-04 | FlyQuest        | L   | 0.205      | -            | -                | -                | -         |    -5.12 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            8 |     5678 | 2024-10-04 | Rooster         | W   | 0.204      | -            | -                | -                | -         |     0.15 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            7 |     5980 | 2024-09-29 | 3DMAX           | W   | 0.170      | 0.143        | 0.298 (0.007)    | -                | -         |     4.35 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            6 |     6033 | 2024-09-28 | 9z Team         | W   | 0.165      | -            | -                | -                | -         |     0.22 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            5 |     6064 | 2024-09-28 | Nemiga Gaming   | W   | 0.164      | 0.143        | 0.176 (0.004)    | -                | -         |     0.74 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            4 |     6127 | 2024-09-27 | B8              | L   | 0.158      | -            | -                | -                | -         |    -3.90 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            3 |     6153 | 2024-09-27 | GameAgents      | W   | 0.157      | -            | -                | -                | -         |     0.13 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            2 |     7160 | 2024-09-12 | Insilio         | L   | 0.056      | -            | -                | -                | -         |    -1.73 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            1 |     7270 | 2024-09-10 | TSM             | W   | 0.043      | -            | -                | -                | -         |     0.05 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($87,750.86)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.27) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-10-27 |      0.358 | $50,000.00     | $17,918.98      |
| 2024-10-20 |      0.311 | $8,500.00      | $2,640.90       |
| 2024-10-06 |      0.219 | $10,000.00     | $2,190.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
