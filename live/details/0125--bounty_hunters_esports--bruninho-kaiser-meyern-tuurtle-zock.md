### Roster Details<br />
Team Name: Bounty Hunters Esports<br />
Roster: Bruninho, KAISER, meyern, Tuurtle, zock<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  792.1<br />
<br />
Final Rank Value (792.1) = Starting Rank Value (711.3) + Head To Head Adjustments (80.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.299[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.156<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.3
- 400 + ( ( 0.156 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 711.3


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
|           26 |      226 | 2025-02-20 | Sharks Esports  | L   | 1.000      | -            | -                | -                | -         |    -7.79 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           25 |      274 | 2025-02-17 | Galorys         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.06 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           24 |      278 | 2025-02-17 | Seleção do BT   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.25 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           23 |      283 | 2025-02-17 | Fake do Biru    | W   | 1.000      | 0.143        | -                | 0.292 (0.042)    | 0 (0.000) |     8.10 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           22 |      394 | 2025-02-15 | Dusty Roots     | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.371 (0.138)    | 0 (0.000) |    14.80 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           21 |      474 | 2025-02-14 | KRÜ Esports     | W   | 1.000      | 0.371        | 0.001 (0.001)    | 0.132 (0.049)    | 0 (0.000) |    11.72 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           20 |      549 | 2025-02-11 | AdalYamigos     | W   | 1.000      | 0.371        | 0.004 (0.002)    | 0.194 (0.072)    | 0 (0.000) |    13.98 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           19 |      569 | 2025-02-10 | UNO MILLE       | L   | 1.000      | -            | -                | -                | -         |   -15.58 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           18 |      828 | 2025-02-06 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |    -7.80 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           17 |      872 | 2025-02-05 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -11.40 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           16 |      893 | 2025-02-05 | BESTIA          | W   | 1.000      | 0.143        | 0.069 (0.010)    | 0.478 (0.068)    | 0 (0.000) |    23.68 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           15 |      931 | 2025-02-04 | W7m esports     | W   | 1.000      | 0.143        | -                | 0.234 (0.033)    | 0 (0.000) |     6.81 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           14 |      938 | 2025-02-04 | Yawara E-Sports | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.454 (0.065)    | 0 (0.000) |    13.03 | Bruninho, KAISER, meyern, Tuurtle, zock  |
|           13 |     1607 | 2024-12-15 | Game Hunters    | W   | 0.694      | 0.143        | 0.002 (0.000)    | 0.396 (0.039)    | 0 (0.000) |    10.74 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|           12 |     1665 | 2024-12-14 | TROPA DO TACO   | L   | 0.688      | -            | -                | -                | -         |    -8.87 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|           11 |     1757 | 2024-12-13 | Hype Esports    | W   | 0.681      | -            | -                | -                | -         |     9.26 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|           10 |     1821 | 2024-12-12 | Yawara E-Sports | W   | 0.674      | 0.143        | 0.002 (0.000)    | 0.454 (0.044)    | -         |     9.88 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            9 |     1862 | 2024-12-11 | TROPA DO TACO   | L   | 0.668      | -            | -                | -                | -         |    -8.83 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            8 |     1908 | 2024-12-10 | Yawara E-Sports | W   | 0.661      | 0.143        | 0.002 (0.000)    | 0.454 (0.043)    | -         |     9.76 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            7 |     3914 | 2024-11-05 | Sharks Esports  | L   | 0.428      | -            | -                | -                | -         |    -2.19 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            6 |     3918 | 2024-11-05 | Fluxo           | L   | 0.427      | -            | -                | -                | -         |    -2.98 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            5 |     3968 | 2024-11-04 | América eSports | W   | 0.421      | -            | -                | -                | -         |     4.56 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            4 |     4024 | 2024-11-03 | AdalYamigos     | W   | 0.415      | 0.143        | 0.004 (0.000)    | -                | -         |     7.17 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            3 |     4111 | 2024-11-02 | UNO MILLE       | L   | 0.407      | -            | -                | -                | -         |    -5.89 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            2 |     4164 | 2024-11-01 | UNO MILLE       | W   | 0.402      | 0.143        | 0.010 (0.001)    | -                | -         |     7.00 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |
|            1 |     4171 | 2024-11-01 | Intense Game    | L   | 0.401      | -            | -                | -                | -         |    -6.69 | bnc, Bruninho, KAISER, meyern, SHOOWTiME |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,523.86)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-05 |      0.429 | $2,589.73      | $1,110.53       |
| 2024-11-03 |      0.413 | $1,000.00      | $413.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
