### Roster Details<br />
Team Name: Fire in The Hole (Brazilian team)<br />
Roster: coldizinha, Dudi, F-AK4, sphynx, Tofer<br />
Global Rank: [620](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [142]( ../standings_americas.md)<br />
<br />
Final Rank Value:  387.1<br />
<br />
Final Rank Value (387.1) = Starting Rank Value (400.1) + Head To Head Adjustments (-12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.1
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     4220 | 2024-10-31 | Fluxo Demons        | L   | 0.395      | -            | -                | -                | -         |    -1.21 | coldizinha, Dudi, F-AK4, sphynx, Tofer |
|            7 |     4224 | 2024-10-31 | Fluxo Demons        | L   | 0.395      | -            | -                | -                | -         |    -1.23 | coldizinha, Dudi, F-AK4, sphynx, Tofer |
|            6 |     4274 | 2024-10-30 | Metanoia Female     | L   | 0.388      | -            | -                | -                | -         |    -6.11 | coldizinha, Dudi, F-AK4, sphynx, Tofer |
|            5 |     4278 | 2024-10-30 | Metanoia Female     | W   | 0.388      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     6.24 | coldizinha, Dudi, F-AK4, sphynx, Tofer |
|            4 |     4342 | 2024-10-29 | Peak Academy Female | L   | 0.381      | -            | -                | -                | -         |    -2.68 | coldizinha, Dudi, F-AK4, sphynx, Tofer |
|            3 |     4345 | 2024-10-29 | Peak Academy Female | L   | 0.381      | -            | -                | -                | -         |    -2.74 | coldizinha, Dudi, F-AK4, sphynx, Tofer |
|            2 |     4396 | 2024-10-28 | União BRARG         | L   | 0.375      | -            | -                | -                | -         |    -2.56 | coldizinha, Dudi, F-AK4, sphynx, Tofer |
|            1 |     4399 | 2024-10-28 | União BRARG         | L   | 0.374      | -            | -                | -                | -         |    -2.61 | coldizinha, Dudi, F-AK4, sphynx, Tofer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
