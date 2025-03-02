### Roster Details<br />
Team Name: HellaSlayers99<br />
Roster: eightz, JIaYm, la3euka, S1LoNN, Snoob<br />
Global Rank: [406](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [253]( ../standings_europe.md)<br />
<br />
Final Rank Value:  594.6<br />
<br />
Final Rank Value (594.6) = Starting Rank Value (588.8) + Head To Head Adjustments (5.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.176[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.094<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 588.8
- 400 + ( ( 0.094 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 588.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     2473 | 2024-11-30 | ARCRED             | L   | 0.594      | -            | -                | -                | -         |    -4.76 | eightz, JIaYm, la3euka, S1LoNN, Snoob   |
|            5 |     2500 | 2024-11-30 | RAGE (Kazakh team) | W   | 0.593      | 0.262        | 0.005 (0.001)    | 0.182 (0.028)    | 0 (0.000) |    14.70 | eightz, JIaYm, la3euka, S1LoNN, Snoob   |
|            4 |     4069 | 2024-11-03 | Donstu Esports     | L   | 0.412      | -            | -                | -                | -         |    -8.14 | bogemtdarf, eightz, JIaYm, kade0, Snoob |
|            3 |     4083 | 2024-11-03 | RUSTEC             | W   | 0.411      | 0.143        | 0.002 (0.000)    | 0.100 (0.006)    | 0 (0.000) |     8.02 | bogemtdarf, eightz, JIaYm, kade0, Snoob |
|            2 |     5153 | 2024-10-13 | Nuclear TigeRES    | L   | 0.271      | -            | -                | -                | -         |    -1.80 | bogemtdarf, eightz, JIaYm, kade0, Snoob |
|            1 |     6568 | 2024-09-21 | Freesunshine       | L   | 0.126      | -            | -                | -                | -         |    -2.15 | eightz, JIaYm, kade0, Snoob, z1w0w      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-23 |      0.140 | $50.00         | $7.00           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
