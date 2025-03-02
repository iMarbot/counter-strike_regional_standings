### Roster Details<br />
Team Name: Just Swing (Chinese team)<br />
Roster: gas, Marek, Purely, qqGOD, VanceKK<br />
Global Rank: [310](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [46]( ../standings_asia.md)<br />
<br />
Final Rank Value:  644.5<br />
<br />
Final Rank Value (644.5) = Starting Rank Value (701.4) + Head To Head Adjustments (-56.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.303[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.054[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.4
- 400 + ( ( 0.151 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 701.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |       48 | 2025-02-24 | Unsettled Resentment    | L   | 1.000      | -            | -                | -                | -         |   -11.92 | gas, Marek, Purely, qqGOD, VanceKK |
|           28 |       64 | 2025-02-24 | Shika                   | L   | 1.000      | -            | -                | -                | -         |   -18.23 | gas, Marek, Purely, qqGOD, VanceKK |
|           27 |      606 | 2025-02-09 | Rooster                 | L   | 1.000      | -            | -                | -                | -         |   -15.41 | gas, Marek, Purely, qqGOD, VanceKK |
|           26 |      643 | 2025-02-08 | SemperFi Esports        | L   | 1.000      | -            | -                | -                | -         |   -17.95 | gas, Marek, Purely, qqGOD, VanceKK |
|           25 |      724 | 2025-02-07 | DXA Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.76 | gas, Marek, Purely, qqGOD, VanceKK |
|           24 |     1233 | 2024-12-30 | Shika                   | L   | 0.797      | -            | -                | -                | -         |   -18.07 | gas, Marek, Purely, qqGOD, VanceKK |
|           23 |     1352 | 2024-12-25 | TREMOR-                 | L   | 0.759      | -            | -                | -                | -         |   -15.25 | gas, Marek, Purely, qqGOD, VanceKK |
|           22 |     1361 | 2024-12-24 | OverWhelMing eSport     | L   | 0.752      | -            | -                | -                | -         |   -15.03 | gas, Marek, Purely, qqGOD, VanceKK |
|           21 |     1513 | 2024-12-20 | Last Dance 4.0          | W   | 0.725      | -            | -                | -                | 0 (0.000) |     2.81 | gas, Marek, Purely, qqGOD, VanceKK |
|           20 |     1894 | 2024-12-11 | Nalakuvara Gaming       | L   | 0.665      | -            | -                | -                | -         |   -16.20 | gas, Marek, Purely, qqGOD, VanceKK |
|           19 |     1965 | 2024-12-09 | FengDa Gaming           | W   | 0.651      | 0.250        | 0.008 (0.001)    | 0.553 (0.090)    | 0 (0.000) |     8.72 | gas, Marek, Purely, qqGOD, VanceKK |
|           18 |     2228 | 2024-12-04 | ATOX Esports            | L   | 0.618      | -            | -                | -                | -         |    -2.55 | gas, Marek, Purely, qqGOD, VanceKK |
|           17 |     2234 | 2024-12-04 | IHC Esports             | L   | 0.617      | -            | -                | -                | -         |   -10.82 | gas, Marek, Purely, qqGOD, VanceKK |
|           16 |     2235 | 2024-12-03 | Nomads (Mongolian team) | W   | 0.617      | 0.333        | -                | 0.407 (0.084)    | 0 (0.000) |     4.13 | gas, Marek, Purely, qqGOD, VanceKK |
|           15 |     2272 | 2024-12-03 | FengDa Gaming           | W   | 0.612      | 0.250        | 0.008 (0.001)    | 0.553 (0.085)    | 0 (0.000) |     8.19 | gas, Marek, Purely, qqGOD, VanceKK |
|           14 |     2347 | 2024-12-02 | Nalakuvara Gaming       | W   | 0.605      | 0.250        | 0.000 (0.000)    | 0.057 (0.009)    | 0 (0.000) |     5.53 | gas, Marek, Purely, qqGOD, VanceKK |
|           13 |     2531 | 2024-11-30 | The Main F              | W   | 0.592      | -            | -                | -                | 0 (0.000) |     2.29 | gas, Marek, Purely, qqGOD, VanceKK |
|           12 |     2904 | 2024-11-23 | ATOX Esports            | L   | 0.544      | -            | -                | -                | -         |    -2.02 | gas, Marek, Purely, qqGOD, VanceKK |
|           11 |     2910 | 2024-11-22 | IHC Esports             | W   | 0.544      | 0.333        | 0.002 (0.000)    | 0.248 (0.045)    | 0 (0.000) |     7.72 | gas, Marek, Purely, qqGOD, VanceKK |
|           10 |     3060 | 2024-11-20 | Harizma                 | W   | 0.531      | 0.333        | 0.002 (0.000)    | 0.433 (0.076)    | 0 (0.000) |     8.56 | gas, Marek, Purely, qqGOD, VanceKK |
|            9 |     3063 | 2024-11-20 | The Huns Esports        | W   | 0.530      | 0.333        | 0.025 (0.004)    | 0.557 (0.098)    | 0 (0.000) |    12.38 | gas, Marek, Purely, qqGOD, VanceKK |
|            8 |     3348 | 2024-11-16 | CatEvil                 | W   | 0.498      | 0.143        | 0.000 (0.000)    | 0.093 (0.007)    | -         |     6.51 | gas, Marek, Purely, qqGOD, VanceKK |
|            7 |     3357 | 2024-11-16 | SUBUTAI                 | W   | 0.497      | 0.143        | 0.001 (0.000)    | 0.051 (0.004)    | -         |     4.09 | gas, Marek, Purely, qqGOD, VanceKK |
|            6 |     3364 | 2024-11-15 | Eruption                | W   | 0.497      | 0.143        | 0.014 (0.001)    | 0.552 (0.039)    | -         |    12.26 | gas, Marek, Purely, qqGOD, VanceKK |
|            5 |     6704 | 2024-09-19 | Chinggis Warriors       | L   | 0.112      | -            | -                | -                | -         |    -2.09 | gas, Marek, Purely, qqGOD, risk    |
|            4 |     6843 | 2024-09-17 | Oni CLAN                | W   | 0.098      | 0.250        | 0.000 (0.000)    | -                | -         |     0.84 | gas, Marek, Purely, qqGOD, risk    |
|            3 |     6942 | 2024-09-15 | THE (Russian team)      | W   | 0.085      | -            | -                | -                | -         |     0.60 | gas, Marek, Purely, qqGOD, risk    |
|            2 |     7311 | 2024-09-09 | Chinggis Warriors       | L   | 0.045      | -            | -                | -                | -         |    -0.84 | gas, Marek, Purely, qqGOD, risk    |
|            1 |     7450 | 2024-09-07 | SUBUTAI                 | W   | 0.032      | -            | -                | -                | -         |     0.15 | gas, Marek, Purely, qqGOD, risk    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,699.01)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-09 |      0.651 | $500.00        | $325.42         |
| 2024-11-23 |      0.544 | $2,500.00      | $1,361.11       |
| 2024-09-21 |      0.125 | $100.00        | $12.49          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
