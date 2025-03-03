### Roster Details<br />
Team Name: Just Swing (Chinese team)<br />
Roster: gas, Marek, Purely, qqGOD, VanceKK<br />
Global Rank: [311](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [46]( ../standings_asia.md)<br />
<br />
Final Rank Value:  644.3<br />
<br />
Final Rank Value (644.3) = Starting Rank Value (701.3) + Head To Head Adjustments (-56.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.053[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.3
- 400 + ( ( 0.151 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 701.3


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
|           29 |       63 | 2025-02-24 | Unsettled Resentment    | L   | 1.000      | -            | -                | -                | -         |   -11.92 | gas, Marek, Purely, qqGOD, VanceKK |
|           28 |       79 | 2025-02-24 | Shika                   | L   | 1.000      | -            | -                | -                | -         |   -18.23 | gas, Marek, Purely, qqGOD, VanceKK |
|           27 |      618 | 2025-02-09 | Rooster                 | L   | 1.000      | -            | -                | -                | -         |   -15.43 | gas, Marek, Purely, qqGOD, VanceKK |
|           26 |      655 | 2025-02-08 | SemperFi Esports        | L   | 1.000      | -            | -                | -                | -         |   -17.96 | gas, Marek, Purely, qqGOD, VanceKK |
|           25 |      736 | 2025-02-07 | DXA Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.77 | gas, Marek, Purely, qqGOD, VanceKK |
|           24 |     1245 | 2024-12-30 | Shika                   | L   | 0.789      | -            | -                | -                | -         |   -17.88 | gas, Marek, Purely, qqGOD, VanceKK |
|           23 |     1364 | 2024-12-25 | TREMOR-                 | L   | 0.751      | -            | -                | -                | -         |   -15.06 | gas, Marek, Purely, qqGOD, VanceKK |
|           22 |     1373 | 2024-12-24 | OverWhelMing eSport     | L   | 0.744      | -            | -                | -                | -         |   -14.84 | gas, Marek, Purely, qqGOD, VanceKK |
|           21 |     1525 | 2024-12-20 | Last Dance 4.0          | W   | 0.717      | -            | -                | -                | 0 (0.000) |     2.79 | gas, Marek, Purely, qqGOD, VanceKK |
|           20 |     1906 | 2024-12-11 | Nalakuvara Gaming       | L   | 0.657      | -            | -                | -                | -         |   -16.00 | gas, Marek, Purely, qqGOD, VanceKK |
|           19 |     1977 | 2024-12-09 | FengDa Gaming           | W   | 0.643      | 0.250        | 0.008 (0.001)    | 0.550 (0.088)    | 0 (0.000) |     8.64 | gas, Marek, Purely, qqGOD, VanceKK |
|           18 |     2240 | 2024-12-04 | ATOX Esports            | L   | 0.610      | -            | -                | -                | -         |    -2.55 | gas, Marek, Purely, qqGOD, VanceKK |
|           17 |     2246 | 2024-12-04 | IHC Esports             | L   | 0.609      | -            | -                | -                | -         |   -10.67 | gas, Marek, Purely, qqGOD, VanceKK |
|           16 |     2247 | 2024-12-03 | Nomads (Mongolian team) | W   | 0.609      | 0.333        | -                | 0.407 (0.083)    | 0 (0.000) |     4.09 | gas, Marek, Purely, qqGOD, VanceKK |
|           15 |     2284 | 2024-12-03 | FengDa Gaming           | W   | 0.604      | 0.250        | 0.008 (0.001)    | 0.550 (0.083)    | 0 (0.000) |     8.12 | gas, Marek, Purely, qqGOD, VanceKK |
|           14 |     2359 | 2024-12-02 | Nalakuvara Gaming       | W   | 0.597      | 0.250        | 0.000 (0.000)    | 0.057 (0.008)    | 0 (0.000) |     5.48 | gas, Marek, Purely, qqGOD, VanceKK |
|           13 |     2543 | 2024-11-30 | The Main F              | W   | 0.584      | -            | -                | -                | 0 (0.000) |     2.27 | gas, Marek, Purely, qqGOD, VanceKK |
|           12 |     2916 | 2024-11-23 | ATOX Esports            | L   | 0.536      | -            | -                | -                | -         |    -2.02 | gas, Marek, Purely, qqGOD, VanceKK |
|           11 |     2922 | 2024-11-22 | IHC Esports             | W   | 0.536      | 0.333        | 0.002 (0.000)    | 0.247 (0.044)    | 0 (0.000) |     7.62 | gas, Marek, Purely, qqGOD, VanceKK |
|           10 |     3072 | 2024-11-20 | Harizma                 | W   | 0.522      | 0.333        | 0.002 (0.000)    | 0.428 (0.074)    | 0 (0.000) |     8.40 | gas, Marek, Purely, qqGOD, VanceKK |
|            9 |     3075 | 2024-11-20 | The Huns Esports        | W   | 0.522      | 0.333        | 0.025 (0.004)    | 0.553 (0.096)    | 0 (0.000) |    12.18 | gas, Marek, Purely, qqGOD, VanceKK |
|            8 |     3360 | 2024-11-16 | CatEvil                 | W   | 0.489      | 0.143        | 0.000 (0.000)    | 0.091 (0.006)    | -         |     6.39 | gas, Marek, Purely, qqGOD, VanceKK |
|            7 |     3369 | 2024-11-16 | SUBUTAI                 | W   | 0.489      | 0.143        | 0.001 (0.000)    | 0.051 (0.004)    | -         |     4.03 | gas, Marek, Purely, qqGOD, VanceKK |
|            6 |     3376 | 2024-11-15 | Eruption                | W   | 0.489      | 0.143        | 0.014 (0.001)    | 0.551 (0.038)    | -         |    12.05 | gas, Marek, Purely, qqGOD, VanceKK |
|            5 |     6716 | 2024-09-19 | Chinggis Warriors       | L   | 0.103      | -            | -                | -                | -         |    -1.94 | gas, Marek, Purely, qqGOD, risk    |
|            4 |     6855 | 2024-09-17 | Oni CLAN                | W   | 0.090      | 0.250        | 0.000 (0.000)    | -                | -         |     0.77 | gas, Marek, Purely, qqGOD, risk    |
|            3 |     6954 | 2024-09-15 | THE (Russian team)      | W   | 0.077      | -            | -                | -                | -         |     0.54 | gas, Marek, Purely, qqGOD, risk    |
|            2 |     7323 | 2024-09-09 | Chinggis Warriors       | L   | 0.037      | -            | -                | -                | -         |    -0.69 | gas, Marek, Purely, qqGOD, risk    |
|            1 |     7462 | 2024-09-07 | SUBUTAI                 | W   | 0.023      | -            | -                | -                | -         |     0.12 | gas, Marek, Purely, qqGOD, risk    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,673.61)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-09 |      0.643 | $500.00        | $321.32         |
| 2024-11-23 |      0.536 | $2,500.00      | $1,340.63       |
| 2024-09-21 |      0.117 | $100.00        | $11.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
