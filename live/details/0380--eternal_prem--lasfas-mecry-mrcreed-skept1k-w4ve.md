### Roster Details<br />
Team Name: Eternal prem<br />
Roster: lasfas, mecry, MRCreed, skept1K, w4vE<br />
Global Rank: [380](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [240]( ../standings_europe.md)<br />
<br />
Final Rank Value:  607.4<br />
<br />
Final Rank Value (607.4) = Starting Rank Value (600.9) + Head To Head Adjustments (6.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.205[<sup>1</sup>](#table2)
- Bounty Collected: 0.195[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.101<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 600.9
- 400 + ( ( 0.101 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 600.9


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
|            6 |     5228 | 2024-10-12 | FORZE Reload   | L   | 0.265      | -            | -                | -                | -         |    -1.74 | lasfas, mecry, MRCreed, skept1K, w4vE   |
|            5 |     5240 | 2024-10-12 | Harizma        | W   | 0.264      | 0.143        | 0.002 (0.000)    | 0.433 (0.016)    | 0 (0.000) |     5.46 | lasfas, mecry, MRCreed, skept1K, w4vE   |
|            4 |     6747 | 2024-09-18 | DEPO           | L   | 0.107      | -            | -                | -                | -         |    -0.92 | lasfas, MRCreed, rokilan, skept1K, w4vE |
|            3 |     6834 | 2024-09-17 | Eco Warriors   | W   | 0.099      | 0.310        | 0.022 (0.001)    | 0.244 (0.008)    | 0 (0.000) |     2.35 | lasfas, MRCreed, rokilan, skept1K, w4vE |
|            2 |     6876 | 2024-09-16 | MronZ          | W   | 0.093      | 0.310        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.71 | lasfas, MRCreed, rokilan, skept1K, w4vE |
|            1 |     6920 | 2024-09-15 | TheLastDragons | W   | 0.087      | 0.310        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.67 | lasfas, MRCreed, rokilan, skept1K, w4vE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44.28)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.127 | $350.00        | $44.28          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
