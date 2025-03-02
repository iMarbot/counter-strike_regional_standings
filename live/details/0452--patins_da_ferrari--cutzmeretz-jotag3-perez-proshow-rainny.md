### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: CutzMeretz, Jotag3, perez, proSHOW, rainny<br />
Global Rank: [452](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [98]( ../standings_americas.md)<br />
<br />
Final Rank Value:  557.4<br />
<br />
Final Rank Value (557.4) = Starting Rank Value (528.0) + Head To Head Adjustments (29.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.064<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 528.0
- 400 + ( ( 0.064 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 528.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1203 | 2025-01-09 | ShindeN                  | L   | 0.861      | -            | -                | -                | -         |    -8.00 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            5 |     1439 | 2024-12-21 | Nitro.GG                 | W   | 0.733      | 0.384        | 0.002 (0.000)    | 0.518 (0.146)    | 0 (0.000) |    15.04 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            4 |     1495 | 2024-12-20 | UNO MILLE                | L   | 0.727      | -            | -                | -                | -         |    -5.22 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            3 |     1563 | 2024-12-17 | Players (Brazilian team) | W   | 0.708      | 0.384        | 0.008 (0.002)    | 0.637 (0.173)    | 0 (0.000) |    17.65 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            2 |     1626 | 2024-12-15 | Galorys Academy          | W   | 0.692      | 0.384        | 0.001 (0.000)    | 0.158 (0.042)    | 0 (0.000) |    12.61 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            1 |     1755 | 2024-12-13 | Team Solid               | L   | 0.681      | -            | -                | -                | -         |    -2.75 | CutzMeretz, Jotag3, perez, proSHOW, rainny |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
