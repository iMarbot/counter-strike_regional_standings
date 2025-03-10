### Roster Details<br />
Team Name: Wu-Tang Clan<br />
Roster: m4tthi, Maze, Q-Q, zaNNN, zewts<br />
Global Rank: [289](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [194]( ../standings_europe.md)<br />
<br />
Final Rank Value:  657.9<br />
<br />
Final Rank Value (657.9) = Starting Rank Value (646.9) + Head To Head Adjustments (11.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.248[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.9
- 400 + ( ( 0.123 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 646.9


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
|           14 |     1234 | 2025-01-05 | WOPA Esport            | L   | 0.823      | -            | -                | -                | -         |    -7.26 | m4tthi, Maze, Q-Q, zaNNN, zewts      |
|           13 |     1268 | 2024-12-29 | GenOne                 | L   | 0.778      | -            | -                | -                | -         |    -7.68 | m4tthi, Maze, Q-Q, zaNNN, zewts      |
|           12 |     1308 | 2024-12-28 | FLuffy Gangsters       | L   | 0.771      | -            | -                | -                | -         |    -6.86 | m4tthi, Maze, Q-Q, zaNNN, zewts      |
|           11 |     1548 | 2024-12-19 | Dark Cloud Esports     | L   | 0.711      | -            | -                | -                | -         |    -6.18 | m4tthi, Maze, Q-Q, SeBreeZe, zewts   |
|           10 |     1602 | 2024-12-16 | VOLT (European team)   | W   | 0.690      | 0.303        | 0.003 (0.001)    | 0.162 (0.034)    | 0 (0.000) |    11.47 | m4tthi, Maze, Q-Q, SeBreeZe, zewts   |
|            9 |     1622 | 2024-12-15 | AMKAL ESPORTS          | L   | 0.686      | -            | -                | -                | -         |    -6.24 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            8 |     1645 | 2024-12-15 | C.S.D.E                | W   | 0.684      | 0.303        | 0.006 (0.001)    | 0.153 (0.032)    | 0 (0.000) |    11.17 | m4tthi, MahaR, Maze, Q-Q, T4gg3D     |
|            7 |     1773 | 2024-12-13 | G2 Ares                | W   | 0.672      | 0.274        | 0.001 (0.000)    | 0.257 (0.047)    | 0 (0.000) |    11.49 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            6 |     1795 | 2024-12-13 | Ex-GODSENT             | L   | 0.671      | -            | -                | -                | -         |   -14.68 | m4tthi, MahaR, Maze, SeBreeZe, zewts |
|            5 |     1838 | 2024-12-12 | SHOO7ERS               | W   | 0.665      | 0.274        | 0.001 (0.000)    | 0.184 (0.034)    | 0 (0.000) |    10.89 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            4 |     1881 | 2024-12-11 | ENRAGE                 | W   | 0.659      | 0.274        | 0.000 (0.000)    | 0.094 (0.017)    | 0 (0.000) |     9.49 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            3 |     1924 | 2024-12-10 | Perfect Storm          | W   | 0.652      | 0.274        | 0.008 (0.001)    | 0.115 (0.021)    | 0 (0.000) |    11.28 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            2 |     2420 | 2024-12-01 | Minsk House            | L   | 0.592      | -            | -                | -                | -         |   -13.16 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |
|            1 |     2431 | 2024-12-01 | Lausanne-Sport Esports | W   | 0.592      | 0.143        | 0.000 (0.000)    | 0.124 (0.010)    | 0 (0.000) |     7.32 | Maze, Q-Q, SeBreeZe, woozzzi, zewts  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($308.53)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.686 | $450.00        | $308.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
