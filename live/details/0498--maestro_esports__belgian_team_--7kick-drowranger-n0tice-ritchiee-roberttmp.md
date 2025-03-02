### Roster Details<br />
Team Name: Maestro Esports (Belgian team)<br />
Roster: 7kick, drowranger, n0tice, ritchiEE, RoberttMP<br />
Global Rank: [498](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [310]( ../standings_europe.md)<br />
<br />
Final Rank Value:  519.0<br />
<br />
Final Rank Value (519.0) = Starting Rank Value (491.9) + Head To Head Adjustments (27.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.177[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.046<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 491.9
- 400 + ( ( 0.046 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 491.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |      964 | 2025-02-04 | BC.Game Esports        | L   | 1.000      | -            | -                | -                | -         |    -1.66 | 7kick, drowranger, n0tice, ritchiEE, RoberttMP |
|            6 |      979 | 2025-02-04 | Lausanne-Sport Esports | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.126 (0.018)    | 0 (0.000) |    17.79 | 7kick, drowranger, n0tice, ritchiEE, RoberttMP |
|            5 |     1500 | 2024-12-20 | Permitta Esports       | L   | 0.727      | -            | -                | -                | -         |    -2.85 | 7kick, n0tice, ritchiEE, Stev0se, wonsz        |
|            4 |     2205 | 2024-12-04 | Rhyno Esports          | L   | 0.620      | -            | -                | -                | -         |    -2.12 | 7kick, n0tice, ottob, ritchiEE, Stev0se        |
|            3 |     2526 | 2024-11-30 | LEON Esports           | L   | 0.593      | -            | -                | -                | -         |    -3.61 | 7kick, n0tice, ottob, ritchiEE, Stev0se        |
|            2 |     2617 | 2024-11-28 | Ex-ESC Gaming          | W   | 0.580      | 0.333        | 0.001 (0.000)    | 0.243 (0.047)    | 0 (0.000) |    12.99 | 7kick, n0tice, ottob, ritchiEE, Stev0se        |
|            1 |     2716 | 2024-11-26 | CASTA                  | W   | 0.567      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.60 | 7kick, n0tice, ottob, ritchiEE, Stev0se        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
