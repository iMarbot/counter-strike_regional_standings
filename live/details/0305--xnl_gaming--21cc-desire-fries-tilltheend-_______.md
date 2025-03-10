### Roster Details<br />
Team Name: XNL Gaming<br />
Roster: 21cc, DesirE, Fries, TillTheEnd, あくいんあっか<br />
Global Rank: [305](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [44]( ../standings_asia.md)<br />
<br />
Final Rank Value:  647.0<br />
<br />
Final Rank Value (647.0) = Starting Rank Value (632.1) + Head To Head Adjustments (15.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.283[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.1
- 400 + ( ( 0.116 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 632.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     2557 | 2024-11-30 | Nalakuvara Gaming     | L   | 0.583      | -            | -                | -                | -         |   -12.39 | 21cc, DesirE, Fries, TillTheEnd, あくいんあっか |
|            4 |     2571 | 2024-11-29 | Never Say Never-      | W   | 0.582      | 0.143        | 0.002 (0.000)    | 0.119 (0.010)    | 0 (0.000) |     8.30 | 21cc, DesirE, Fries, TillTheEnd, あくいんあっか |
|            3 |     3697 | 2024-11-10 | Inner Mongolia Gaming | W   | 0.449      | 0.143        | 0.001 (0.000)    | 0.063 (0.004)    | 0 (0.000) |     6.88 | 21cc, DesirE, Fries, TillTheEnd, あくいんあっか |
|            2 |     3699 | 2024-11-09 | 冯福山冯福令                | W   | 0.448      | 0.143        | 0.000 (0.000)    | 0.042 (0.003)    | 0 (0.000) |     6.25 | 21cc, DesirE, Fries, TillTheEnd, あくいんあっか |
|            1 |     3761 | 2024-11-09 | From Far Away         | W   | 0.443      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     5.93 | 21cc, DesirE, Fries, TillTheEnd, あくいんあっか |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($965.82)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-30 |      0.583 | $1,657.07      | $965.82         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
