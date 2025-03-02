### Roster Details<br />
Team Name: Copenhagen Wolves (American organization)<br />
Roster: BøghmagiC, Fessor, h4rn, sense, Tapewaare<br />
Global Rank: [316](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [210]( ../standings_europe.md)<br />
<br />
Final Rank Value:  640.0<br />
<br />
Final Rank Value (640.0) = Starting Rank Value (635.6) + Head To Head Adjustments (4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.242[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 635.6
- 400 + ( ( 0.118 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 635.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     6820 | 2024-09-17 | FAVBET Team      | L   | 0.100      | -            | -                | -                | -         |    -0.76 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            6 |     6918 | 2024-09-15 | FLuffy Gangsters | W   | 0.087      | 0.372        | 0.014 (0.000)    | 0.925 (0.030)    | 0 (0.000) |     1.93 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            5 |     7075 | 2024-09-13 | Daystar          | W   | 0.073      | 0.372        | 0.000 (0.000)    | 0.135 (0.004)    | 0 (0.000) |     1.20 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            4 |     7193 | 2024-09-11 | Dynamo Eclot     | W   | 0.059      | 0.372        | 0.127 (0.003)    | 0.703 (0.015)    | 0 (0.000) |     1.71 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            3 |     7422 | 2024-09-07 | Endpoint         | L   | 0.032      | -            | -                | -                | -         |    -0.32 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            2 |     7593 | 2024-09-05 | UNiTY esports    | W   | 0.019      | 0.372        | 0.025 (0.000)    | 0.412 (0.003)    | 0 (0.000) |     0.46 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            1 |     7730 | 2024-09-03 | Leo Team         | W   | 0.006      | 0.372        | 0.026 (0.000)    | 0.758 (0.002)    | 0 (0.000) |     0.14 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($250.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.125 | $2,000.00      | $250.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
