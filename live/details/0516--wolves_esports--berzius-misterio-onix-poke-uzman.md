### Roster Details<br />
Team Name: Wolves eSports<br />
Roster: Berzius, Misterio, OniX, PoKe, Uzman<br />
Global Rank: [516](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [321]( ../standings_europe.md)<br />
<br />
Final Rank Value:  498.2<br />
<br />
Final Rank Value (498.2) = Starting Rank Value (482.4) + Head To Head Adjustments (15.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.159[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.041<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 482.4
- 400 + ( ( 0.041 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 482.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |       96 | 2025-02-23 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |    -3.62 | Berzius, Misterio, OniX, PoKe, Uzman  |
|            4 |      146 | 2025-02-22 | RUSTEC                                    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.217 (0.031)    | 0 (0.000) |    18.57 | Berzius, Misterio, OniX, PoKe, Uzman  |
|            3 |      213 | 2025-02-21 | BASEMENT BOYS                             | L   | 1.000      | -            | -                | -                | -         |   -18.18 | Berzius, Misterio, OniX, PoKe, Uzman  |
|            2 |      241 | 2025-02-20 | Flame Sharks                              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.170 (0.024)    | 0 (0.000) |    21.48 | Berzius, Misterio, OniX, PoKe, Uzman  |
|            1 |     5565 | 2024-10-05 | Haspers Team                              | L   | 0.220      | -            | -                | -                | -         |    -2.42 | Berzius, Darkas, Misterio, OniX, PoKe |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
