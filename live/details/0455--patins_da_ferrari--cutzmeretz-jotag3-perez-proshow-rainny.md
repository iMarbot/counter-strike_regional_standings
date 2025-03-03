### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: CutzMeretz, Jotag3, perez, proSHOW, rainny<br />
Global Rank: [455](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [101]( ../standings_americas.md)<br />
<br />
Final Rank Value:  556.6<br />
<br />
Final Rank Value (556.6) = Starting Rank Value (527.8) + Head To Head Adjustments (28.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.064<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 527.8
- 400 + ( ( 0.064 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 527.8


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
|            6 |     1215 | 2025-01-09 | ShindeN                  | L   | 0.853      | -            | -                | -                | -         |    -8.03 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            5 |     1451 | 2024-12-21 | Nitro.GG                 | W   | 0.725      | 0.384        | 0.002 (0.000)    | 0.512 (0.143)    | 0 (0.000) |    14.87 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            4 |     1507 | 2024-12-20 | UNO MILLE                | L   | 0.719      | -            | -                | -                | -         |    -5.18 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            3 |     1575 | 2024-12-17 | Players (Brazilian team) | W   | 0.700      | 0.384        | 0.008 (0.002)    | 0.632 (0.170)    | 0 (0.000) |    17.42 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            2 |     1638 | 2024-12-15 | Galorys Academy          | W   | 0.684      | 0.384        | 0.001 (0.000)    | 0.154 (0.041)    | 0 (0.000) |    12.46 | CutzMeretz, Jotag3, perez, proSHOW, rainny |
|            1 |     1767 | 2024-12-13 | Team Solid               | L   | 0.673      | -            | -                | -                | -         |    -2.75 | CutzMeretz, Jotag3, perez, proSHOW, rainny |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
