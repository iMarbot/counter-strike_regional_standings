### Roster Details<br />
Team Name: Eternal prem<br />
Roster: lasfas, mecry, MRCreed, skept1K, w4vE<br />
Global Rank: [384](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [240]( ../standings_europe.md)<br />
<br />
Final Rank Value:  606.2<br />
<br />
Final Rank Value (606.2) = Starting Rank Value (600.1) + Head To Head Adjustments (6.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.204[<sup>1</sup>](#table2)
- Bounty Collected: 0.194[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 600.1
- 400 + ( ( 0.100 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 600.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     5240 | 2024-10-12 | FORZE Reload   | L   | 0.257      | -            | -                | -                | -         |    -1.68 | lasfas, mecry, MRCreed, skept1K, w4vE   |
|            5 |     5251 | 2024-10-12 | Harizma        | W   | 0.256      | 0.143        | 0.002 (0.000)    | 0.428 (0.016)    | 0 (0.000) |     5.29 | lasfas, mecry, MRCreed, skept1K, w4vE   |
|            4 |     6759 | 2024-09-18 | DEPO           | L   | 0.098      | -            | -                | -                | -         |    -0.86 | lasfas, MRCreed, rokilan, skept1K, w4vE |
|            3 |     6846 | 2024-09-17 | Eco Warriors   | W   | 0.091      | 0.310        | 0.022 (0.001)    | 0.241 (0.007)    | 0 (0.000) |     2.15 | lasfas, MRCreed, rokilan, skept1K, w4vE |
|            2 |     6888 | 2024-09-16 | MronZ          | W   | 0.085      | 0.310        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.66 | lasfas, MRCreed, rokilan, skept1K, w4vE |
|            1 |     6932 | 2024-09-15 | TheLastDragons | W   | 0.078      | 0.310        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.61 | lasfas, MRCreed, rokilan, skept1K, w4vE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41.42)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.118 | $350.00        | $41.42          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
