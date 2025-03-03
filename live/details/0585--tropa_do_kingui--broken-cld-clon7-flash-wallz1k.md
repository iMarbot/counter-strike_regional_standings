### Roster Details<br />
Team Name: Tropa do KinGui<br />
Roster: brokeN, cLd, CloN7, flash, wallz1k<br />
Global Rank: [585](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [136]( ../standings_americas.md)<br />
<br />
Final Rank Value:  414.7<br />
<br />
Final Rank Value (414.7) = Starting Rank Value (402.4) + Head To Head Adjustments (12.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.001<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 402.4
- 400 + ( ( 0.001 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 402.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |       94 | 2025-02-23 | América eSports          | L   | 1.000      | -            | -                | -                | -         |    -8.23 | brokeN, cLd, CloN7, flash, wallz1k |
|            5 |      100 | 2025-02-23 | MAGICOS                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.076 (0.011)    | 0 (0.000) |    18.75 | brokeN, cLd, CloN7, flash, wallz1k |
|            4 |      141 | 2025-02-22 | VELOX Argentina          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.262 (0.037)    | 0 (0.000) |    20.63 | brokeN, cLd, CloN7, flash, wallz1k |
|            3 |      348 | 2025-02-16 | VELOX Argentina          | L   | 1.000      | -            | -                | -                | -         |    -9.80 | brokeN, cLd, CloN7, flash, wallz1k |
|            2 |      750 | 2025-02-07 | LaChampionsLiga          | L   | 1.000      | -            | -                | -                | -         |    -6.54 | brokeN, cLd, CloN7, flash, wallz1k |
|            1 |     1521 | 2024-12-20 | Players (Brazilian team) | L   | 0.717      | -            | -                | -                | -         |    -2.55 | brokeN, cLd, CloN7, flash, k1not1  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
