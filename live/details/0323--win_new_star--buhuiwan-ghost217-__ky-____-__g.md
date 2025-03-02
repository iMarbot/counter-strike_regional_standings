### Roster Details<br />
Team Name: Win New Star<br />
Roster: BUHUIWAN, Ghost217, 余欢ky, 沙包兄弟, 神仙G<br />
Global Rank: [323](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [50]( ../standings_asia.md)<br />
<br />
Final Rank Value:  638.4<br />
<br />
Final Rank Value (638.4) = Starting Rank Value (625.8) + Head To Head Adjustments (12.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.269[<sup>1</sup>](#table2)
- Bounty Collected: 0.181[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 625.8
- 400 + ( ( 0.113 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 625.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     2553 | 2024-11-29 | Nalakuvara Gaming | L   | 0.590      | -            | -                | -                | -         |   -12.64 | BUHUIWAN, Ghost217, 余欢ky, 沙包兄弟, 神仙G     |
|            4 |     3686 | 2024-11-10 | Magic Cape        | W   | 0.457      | 0.143        | 0.004 (0.000)    | 0.201 (0.013)    | 0 (0.000) |     8.16 | BUHUIWAN, Ghost217^, 余欢ky, 沙包兄弟, 神仙GGGG |
|            3 |     3689 | 2024-11-09 | DQZS              | W   | 0.456      | 0.143        | 0.000 (0.000)    | 0.042 (0.003)    | 0 (0.000) |     6.38 | BUHUIWAN, Ghost217^, 余欢ky, 沙包兄弟, 神仙GGGG |
|            2 |     3762 | 2024-11-08 | RSTking           | W   | 0.450      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     6.05 | BUHUIWAN, Ghost217^, 余欢ky, 沙包兄弟, 神仙GGGG |
|            1 |     3767 | 2024-11-08 | 只等你到5点20          | W   | 0.450      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.64 | BUHUIWAN, Ghost217^, 余欢ky, 沙包兄弟, 神仙GGGG |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($652.93)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-30 |      0.591 | $1,104.71      | $652.93         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
