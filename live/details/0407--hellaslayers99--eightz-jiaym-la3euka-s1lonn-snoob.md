### Roster Details<br />
Team Name: HellaSlayers99<br />
Roster: eightz, JIaYm, la3euka, S1LoNN, Snoob<br />
Global Rank: [407](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [252]( ../standings_europe.md)<br />
<br />
Final Rank Value:  594.4<br />
<br />
Final Rank Value (594.4) = Starting Rank Value (588.5) + Head To Head Adjustments (5.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.175[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.094<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 588.5
- 400 + ( ( 0.094 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 588.5


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
|            6 |     2485 | 2024-11-30 | ARCRED             | L   | 0.586      | -            | -                | -                | -         |    -4.72 | eightz, JIaYm, la3euka, S1LoNN, Snoob   |
|            5 |     2512 | 2024-11-30 | RAGE (Kazakh team) | W   | 0.585      | 0.262        | 0.005 (0.001)    | 0.179 (0.027)    | 0 (0.000) |    14.46 | eightz, JIaYm, la3euka, S1LoNN, Snoob   |
|            4 |     4081 | 2024-11-03 | Donstu Esports     | L   | 0.404      | -            | -                | -                | -         |    -7.98 | bogemtdarf, eightz, JIaYm, kade0, Snoob |
|            3 |     4095 | 2024-11-03 | RUSTEC             | W   | 0.403      | 0.143        | 0.002 (0.000)    | 0.099 (0.006)    | 0 (0.000) |     7.86 | bogemtdarf, eightz, JIaYm, kade0, Snoob |
|            2 |     5165 | 2024-10-13 | Nuclear TigeRES    | L   | 0.263      | -            | -                | -                | -         |    -1.74 | bogemtdarf, eightz, JIaYm, kade0, Snoob |
|            1 |     6580 | 2024-09-21 | Freesunshine       | L   | 0.118      | -            | -                | -                | -         |    -2.01 | eightz, JIaYm, kade0, Snoob, z1w0w      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6.59)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-23 |      0.132 | $50.00         | $6.59           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
