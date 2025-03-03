### Roster Details<br />
Team Name: Bounty Hunters Esports<br />
Roster: Bruninho, KAISER, meyern, Tuurtle, zock<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [27]( ../standings_americas.md)<br />
<br />
Final Rank Value:  790.7<br />
<br />
Final Rank Value (790.7) = Starting Rank Value (711.4) + Head To Head Adjustments (79.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.299[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.156<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.4
- 400 + ( ( 0.156 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 711.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      238 | 2025-02-20 | Sharks Esports  | L   | 1.000      | -            | -                | -                | -         |    -7.52 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           25 |      286 | 2025-02-17 | Galorys         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.94 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           24 |      290 | 2025-02-17 | Seleção do BT   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.26 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           23 |      295 | 2025-02-17 | Fake do Biru    | W   | 1.000      | 0.143        | -                | 0.292 (0.042)    | 0 (0.000) |     8.08 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           22 |      406 | 2025-02-15 | Dusty Roots     | W   | 1.000      | 0.371        | 0.009 (0.003)    | 0.366 (0.136)    | 0 (0.000) |    14.80 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           21 |      486 | 2025-02-14 | KRÜ Esports     | W   | 1.000      | 0.371        | 0.001 (0.001)    | 0.131 (0.049)    | 0 (0.000) |    11.69 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           20 |      561 | 2025-02-11 | AdalYamigos     | W   | 1.000      | 0.371        | 0.004 (0.002)    | 0.193 (0.072)    | 0 (0.000) |    13.97 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           19 |      581 | 2025-02-10 | UNO MILLE       | L   | 1.000      | -            | -                | -                | -         |   -15.63 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           18 |      840 | 2025-02-06 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |    -7.75 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           17 |      884 | 2025-02-05 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -11.47 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           16 |      905 | 2025-02-05 | BESTIA          | W   | 1.000      | 0.143        | 0.069 (0.010)    | 0.472 (0.067)    | 0 (0.000) |    23.73 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           15 |      943 | 2025-02-04 | W7m esports     | W   | 1.000      | 0.143        | -                | 0.234 (0.033)    | 0 (0.000) |     6.83 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           14 |      950 | 2025-02-04 | Yawara E-Sports | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.448 (0.064)    | 0 (0.000) |    13.00 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           13 |     1619 | 2024-12-15 | Game Hunters    | W   | 0.686      | 0.143        | 0.003 (0.000)    | 0.392 (0.038)    | 0 (0.000) |    10.60 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|           12 |     1677 | 2024-12-14 | TROPA DO TACO   | L   | 0.680      | -            | -                | -                | -         |    -8.81 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|           11 |     1769 | 2024-12-13 | Hype Esports    | W   | 0.673      | -            | -                | -                | -         |     9.11 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|           10 |     1833 | 2024-12-12 | Yawara E-Sports | W   | 0.666      | 0.143        | 0.002 (0.000)    | 0.448 (0.043)    | -         |     9.73 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            9 |     1874 | 2024-12-11 | TROPA DO TACO   | L   | 0.660      | -            | -                | -                | -         |    -8.77 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            8 |     1920 | 2024-12-10 | Yawara E-Sports | W   | 0.653      | 0.143        | 0.002 (0.000)    | 0.448 (0.042)    | -         |     9.60 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            7 |     3926 | 2024-11-05 | Sharks Esports  | L   | 0.420      | -            | -                | -                | -         |    -2.13 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            6 |     3930 | 2024-11-05 | Fluxo           | L   | 0.419      | -            | -                | -                | -         |    -2.95 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            5 |     3980 | 2024-11-04 | América eSports | W   | 0.413      | -            | -                | -                | -         |     4.47 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            4 |     4036 | 2024-11-03 | AdalYamigos     | W   | 0.407      | 0.143        | 0.004 (0.000)    | -                | -         |     7.01 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            3 |     4123 | 2024-11-02 | UNO MILLE       | L   | 0.399      | -            | -                | -                | -         |    -5.80 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            2 |     4176 | 2024-11-01 | UNO MILLE       | W   | 0.394      | 0.143        | 0.010 (0.001)    | -                | -         |     6.83 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            1 |     4183 | 2024-11-01 | Intense Game    | L   | 0.393      | -            | -                | -                | -         |    -6.57 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,494.45)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-05 |      0.421 | $2,589.73      | $1,089.31       |
| 2024-11-03 |      0.405 | $1,000.00      | $405.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
