### Roster Details<br />
Team Name: HyperSpirit<br />
Roster: adeX, e1543, GEOHYPE, kritik, RoberttMP<br />
Global Rank: [511](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [316]( ../standings_europe.md)<br />
<br />
Final Rank Value:  502.9<br />
<br />
Final Rank Value (502.9) = Starting Rank Value (488.7) + Head To Head Adjustments (14.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.176[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.044<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 488.7
- 400 + ( ( 0.044 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 488.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     1505 | 2024-12-20 | Permitta Esports            | L   | 0.719      | -            | -                | -                | -         |    -2.82 | adeX, e1543, GEOHYPE, kritik, RoberttMP |
|            6 |     1509 | 2024-12-20 | The Adventurers             | W   | 0.719      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.13 | adeX, e1543, GEOHYPE, kritik, RoberttMP |
|            5 |     2095 | 2024-12-07 | Theboyz                     | L   | 0.631      | -            | -                | -                | -         |    -6.06 | adeX, e1543, GEOHYPE, kritik, swiiffter |
|            4 |     2589 | 2024-11-29 | DEVASTATION (Romanian team) | L   | 0.579      | -            | -                | -                | -         |    -5.77 | adeX, e1543, GEOHYPE, kritik, swiiffter |
|            3 |     2604 | 2024-11-29 | Aimclub                     | L   | 0.578      | -            | -                | -                | -         |    -2.69 | adeX, e1543, GEOHYPE, kritik, swiiffter |
|            2 |     2631 | 2024-11-28 | PORC CARTEL                 | W   | 0.572      | 0.143        | 0.001 (0.000)    | 0.029 (0.002)    | 0 (0.000) |    11.22 | adeX, e1543, GEOHYPE, kritik, swiiffter |
|            1 |     2652 | 2024-11-28 | REDPack Esports             | W   | 0.571      | 0.143        | 0.001 (0.000)    | 0.084 (0.007)    | 0 (0.000) |    12.23 | adeX, e1543, GEOHYPE, kritik, swiiffter |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
