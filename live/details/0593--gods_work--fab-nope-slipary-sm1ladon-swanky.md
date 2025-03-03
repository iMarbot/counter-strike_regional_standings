### Roster Details<br />
Team Name: Gods Work<br />
Roster: Fab, nope, slipary, SM1LADON, SWANKY<br />
Global Rank: [593](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [98]( ../standings_asia.md)<br />
<br />
Final Rank Value:  407.6<br />
<br />
Final Rank Value (407.6) = Starting Rank Value (400.4) + Head To Head Adjustments (7.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.4
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     2241 | 2024-12-04 | Underground Esports Club        | L   | 0.609      | -            | -                | -                | -         |    -4.70 | Fab, nope, slipary, SM1LADON, SWANKY |
|            5 |     2301 | 2024-12-03 | PrevailANZ                      | W   | 0.603      | 0.270        | 0.000 (0.000)    | 0.047 (0.008)    | 0 (0.000) |    11.13 | Fab, nope, slipary, SM1LADON, SWANKY |
|            4 |     6863 | 2024-09-17 | Justice For Tomorrow            | L   | 0.089      | -            | -                | -                | -         |    -0.59 | Fab, lazah, nibke, nope, slipary     |
|            3 |     7163 | 2024-09-12 | PrevailANZ                      | W   | 0.056      | 0.270        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.88 | Fab, lazah, nibke, nope, SWANKY      |
|            2 |     7221 | 2024-09-11 | The Bardolphs (Australian team) | W   | 0.049      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.78 | Fab, lazah, nibke, nope, SWANKY      |
|            1 |     7488 | 2024-09-07 | Rebound                         | L   | 0.023      | -            | -                | -                | -         |    -0.25 | Fab, lazah, nibke, nope, SWANKY      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
