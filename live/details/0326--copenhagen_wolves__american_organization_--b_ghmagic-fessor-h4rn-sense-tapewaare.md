### Roster Details<br />
Team Name: Copenhagen Wolves (American organization)<br />
Roster: BøghmagiC, Fessor, h4rn, sense, Tapewaare<br />
Global Rank: [326](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [212]( ../standings_europe.md)<br />
<br />
Final Rank Value:  636.6<br />
<br />
Final Rank Value (636.6) = Starting Rank Value (633.0) + Head To Head Adjustments (3.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.241[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 633.0
- 400 + ( ( 0.116 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 633.0


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
|            6 |     6832 | 2024-09-17 | FAVBET Team      | L   | 0.092      | -            | -                | -                | -         |    -0.69 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            5 |     6930 | 2024-09-15 | FLuffy Gangsters | W   | 0.078      | 0.372        | 0.014 (0.000)    | 0.909 (0.027)    | 0 (0.000) |     1.75 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            4 |     7087 | 2024-09-13 | Daystar          | W   | 0.065      | 0.372        | 0.000 (0.000)    | 0.131 (0.003)    | 0 (0.000) |     1.07 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            3 |     7205 | 2024-09-11 | Dynamo Eclot     | W   | 0.050      | 0.372        | 0.128 (0.002)    | 0.692 (0.013)    | 0 (0.000) |     1.47 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            2 |     7434 | 2024-09-07 | Endpoint         | L   | 0.024      | -            | -                | -                | -         |    -0.23 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |
|            1 |     7605 | 2024-09-05 | UNiTY esports    | W   | 0.011      | 0.372        | 0.025 (0.000)    | 0.403 (0.002)    | 0 (0.000) |     0.26 | BøghmagiC, Fessor, h4rn, sense, Tapewaare |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($233.61)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.117 | $2,000.00      | $233.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
