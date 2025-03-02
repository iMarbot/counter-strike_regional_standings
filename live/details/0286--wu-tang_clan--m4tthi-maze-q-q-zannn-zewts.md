### Roster Details<br />
Team Name: Wu-Tang Clan<br />
Roster: m4tthi, Maze, Q-Q, zaNNN, zewts<br />
Global Rank: [286](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [195]( ../standings_europe.md)<br />
<br />
Final Rank Value:  658.2<br />
<br />
Final Rank Value (658.2) = Starting Rank Value (646.7) + Head To Head Adjustments (11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.248[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.7
- 400 + ( ( 0.124 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 646.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     1222 | 2025-01-05 | WOPA Esport            | L   | 0.831      | -            | -                | -                | -         |    -7.28 | m4tthi, Maze, Q-Q, zaNNN, zewts      |
|           13 |     1256 | 2024-12-29 | GenOne                 | L   | 0.786      | -            | -                | -                | -         |    -7.74 | m4tthi, Maze, Q-Q, zaNNN, zewts      |
|           12 |     1296 | 2024-12-28 | FLuffy Gangsters       | L   | 0.779      | -            | -                | -                | -         |    -6.85 | m4tthi, Maze, Q-Q, zaNNN, zewts      |
|           11 |     1536 | 2024-12-19 | Dark Cloud Esports     | L   | 0.719      | -            | -                | -                | -         |    -6.21 | m4tthi, Maze, Q-Q, SeBreeZe, zewts   |
|           10 |     1590 | 2024-12-16 | VOLT (European team)   | W   | 0.699      | 0.303        | 0.003 (0.001)    | 0.163 (0.035)    | 0 (0.000) |    11.60 | m4tthi, Maze, Q-Q, SeBreeZe, zewts   |
|            9 |     1610 | 2024-12-15 | AMKAL ESPORTS          | L   | 0.694      | -            | -                | -                | -         |    -6.26 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            8 |     1633 | 2024-12-15 | C.S.D.E                | W   | 0.692      | 0.303        | 0.006 (0.001)    | 0.154 (0.032)    | 0 (0.000) |    11.30 | m4tthi, MahaR, Maze, Q-Q, T4gg3D     |
|            7 |     1761 | 2024-12-13 | G2 Ares                | W   | 0.681      | 0.274        | 0.001 (0.000)    | 0.261 (0.049)    | 0 (0.000) |    11.66 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            6 |     1783 | 2024-12-13 | Ex-GODSENT             | L   | 0.680      | -            | -                | -                | -         |   -14.86 | m4tthi, MahaR, Maze, SeBreeZe, zewts |
|            5 |     1826 | 2024-12-12 | SHOO7ERS               | W   | 0.674      | 0.274        | 0.001 (0.000)    | 0.187 (0.035)    | 0 (0.000) |    11.04 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            4 |     1869 | 2024-12-11 | ENRAGE                 | W   | 0.667      | 0.274        | 0.000 (0.000)    | 0.093 (0.017)    | 0 (0.000) |     9.59 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            3 |     1912 | 2024-12-10 | Perfect Storm          | W   | 0.660      | 0.274        | 0.008 (0.001)    | 0.116 (0.021)    | 0 (0.000) |    11.41 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            2 |     2403 | 2024-12-01 | Minsk House            | L   | 0.600      | -            | -                | -                | -         |   -13.34 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            1 |     2416 | 2024-12-01 | Lausanne-Sport Esports | W   | 0.600      | 0.143        | 0.000 (0.000)    | 0.126 (0.011)    | 0 (0.000) |     7.45 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($312.22)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.694 | $450.00        | $312.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
