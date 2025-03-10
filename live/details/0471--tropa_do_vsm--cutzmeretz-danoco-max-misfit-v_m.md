### Roster Details<br />
Team Name: Tropa do VSM<br />
Roster: CutzMeretz, danoco, max, Misfit, v$m<br />
Global Rank: [471](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [105]( ../standings_americas.md)<br />
<br />
Final Rank Value:  540.1<br />
<br />
Final Rank Value (540.1) = Starting Rank Value (499.4) + Head To Head Adjustments (40.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 499.4
- 400 + ( ( 0.050 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 499.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |      404 | 2025-02-15 | LaChampionsLiga | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.440 (0.063)    | 0 (0.000) |    20.63 | CutzMeretz, danoco, max, Misfit, v$m |
|            4 |      409 | 2025-02-15 | W7m esports     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.234 (0.033)    | 0 (0.000) |    16.12 | CutzMeretz, danoco, max, Misfit, v$m |
|            3 |      412 | 2025-02-15 | Fake do Biru    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.292 (0.042)    | 0 (0.000) |    20.81 | CutzMeretz, danoco, max, Misfit, v$m |
|            2 |      852 | 2025-02-06 | Elevate         | L   | 1.000      | -            | -                | -                | -         |   -11.96 | CutzMeretz, farias, max, Misfit, v$m |
|            1 |      910 | 2025-02-05 | 9z Team         | L   | 1.000      | -            | -                | -                | -         |    -4.96 | CutzMeretz, farias, max, Misfit, v$m |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
