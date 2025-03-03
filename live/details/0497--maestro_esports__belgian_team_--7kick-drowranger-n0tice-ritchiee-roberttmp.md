### Roster Details<br />
Team Name: Maestro Esports (Belgian team)<br />
Roster: 7kick, drowranger, n0tice, ritchiEE, RoberttMP<br />
Global Rank: [497](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [308]( ../standings_europe.md)<br />
<br />
Final Rank Value:  518.8<br />
<br />
Final Rank Value (518.8) = Starting Rank Value (491.9) + Head To Head Adjustments (26.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.177[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.046<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 491.9
- 400 + ( ( 0.046 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 491.9


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
|            7 |      976 | 2025-02-04 | BC.Game Esports        | L   | 1.000      | -            | -                | -                | -         |    -1.66 | 7kick, drowranger, n0tice, ritchiEE, RoberttMP |
|            6 |      991 | 2025-02-04 | Lausanne-Sport Esports | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.124 (0.018)    | 0 (0.000) |    17.77 | 7kick, drowranger, n0tice, ritchiEE, RoberttMP |
|            5 |     1512 | 2024-12-20 | Permitta Esports       | L   | 0.719      | -            | -                | -                | -         |    -2.85 | 7kick, n0tice, ritchiEE, Stev0se, wonsz        |
|            4 |     2217 | 2024-12-04 | Rhyno Esports          | L   | 0.612      | -            | -                | -                | -         |    -2.11 | 7kick, n0tice, ottob, ritchiEE, Stev0se        |
|            3 |     2538 | 2024-11-30 | LEON Esports           | L   | 0.584      | -            | -                | -                | -         |    -3.56 | 7kick, n0tice, ottob, ritchiEE, Stev0se        |
|            2 |     2629 | 2024-11-28 | Ex-ESC Gaming          | W   | 0.572      | 0.333        | 0.001 (0.000)    | 0.239 (0.046)    | 0 (0.000) |    12.81 | 7kick, n0tice, ottob, ritchiEE, Stev0se        |
|            1 |     2728 | 2024-11-26 | CASTA                  | W   | 0.559      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.50 | 7kick, n0tice, ottob, ritchiEE, Stev0se        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
