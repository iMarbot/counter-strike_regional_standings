### Roster Details<br />
Team Name: Believe.<br />
Roster: 21cc, Erye, L1nxiaoshan, Nero, Tdonmi<br />
Global Rank: [460](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [75]( ../standings_asia.md)<br />
<br />
Final Rank Value:  553.4<br />
<br />
Final Rank Value (553.4) = Starting Rank Value (495.2) + Head To Head Adjustments (58.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.184[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.048<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 495.2
- 400 + ( ( 0.048 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 495.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |      617 | 2025-02-09 | Chinggis Warriors           | L   | 1.000      | -            | -                | -                | -         |    -4.87 | 21cc, Erye, L1nxiaoshan, Nero, Tdonmi |
|            6 |      654 | 2025-02-08 | Eruption                    | L   | 1.000      | -            | -                | -                | -         |    -3.76 | 21cc, Erye, L1nxiaoshan, Nero, Tdonmi |
|            5 |      739 | 2025-02-07 | Mindfreak (Australian team) | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.091 (0.013)    | 0 (0.000) |    21.74 | 21cc, Erye, L1nxiaoshan, Nero, Tdonmi |
|            4 |      857 | 2025-02-06 | DogEvil                     | L   | 1.000      | -            | -                | -                | -         |    -4.74 | 21cc, Erye, L1nxiaoshan, Nero, Tdonmi |
|            3 |      864 | 2025-02-06 | Five Handsome Guys          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.148 (0.021)    | 0 (0.000) |    22.65 | 21cc, Erye, L1nxiaoshan, Nero, Tdonmi |
|            2 |      867 | 2025-02-06 | LaiShanHui                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.188 (0.027)    | 0 (0.000) |    10.85 | 21cc, Erye, L1nxiaoshan, Nero, Tdonmi |
|            1 |      877 | 2025-02-05 | E9 Esports                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.037 (0.005)    | 0 (0.000) |    16.35 | 21cc, Erye, L1nxiaoshan, Nero, Tdonmi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
