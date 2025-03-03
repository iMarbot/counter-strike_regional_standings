### Roster Details<br />
Team Name: Asdmix<br />
Roster: for2na, kumao, M1naru, renzy, tlewwka<br />
Global Rank: [349](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [223]( ../standings_europe.md)<br />
<br />
Final Rank Value:  625.5<br />
<br />
Final Rank Value (625.5) = Starting Rank Value (618.7) + Head To Head Adjustments (6.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.212[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.224[<sup>2</sup>](#table1)

The average of these factors is 0.109<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 618.7
- 400 + ( ( 0.109 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 618.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     2014 | 2024-12-08 | AimAssassins   | L   | 0.638      | -            | -                | -                | -         |    -3.07 | for2na, kumao, M1naru, renzy, tlewwka |
|            5 |     2018 | 2024-12-08 | Dmoai          | W   | 0.637      | 0.143        | 0.000 (0.000)    | 0.089 (0.008)    | 1 (0.637) |     7.30 | for2na, kumao, M1naru, renzy, tlewwka |
|            4 |     2022 | 2024-12-08 | Yamato Esports | W   | 0.637      | 0.143        | 0.000 (0.000)    | 0.060 (0.005)    | 1 (0.637) |     6.58 | for2na, kumao, M1naru, renzy, tlewwka |
|            3 |     2027 | 2024-12-08 | INVI           | W   | 0.637      | 0.143        | 0.000 (0.000)    | 0.030 (0.003)    | 1 (0.637) |     5.29 | for2na, kumao, M1naru, renzy, tlewwka |
|            2 |     2042 | 2024-12-07 | 69peek         | L   | 0.636      | -            | -                | -                | -         |    -6.40 | for2na, kumao, M1naru, renzy, tlewwka |
|            1 |     2047 | 2024-12-07 | AimAssassins   | L   | 0.635      | -            | -                | -                | -         |    -2.81 | for2na, kumao, M1naru, renzy, tlewwka |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($62.70)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.638 | $98.25         | $62.70          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
