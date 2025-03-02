### Roster Details<br />
Team Name: True Rippers Esports<br />
Roster: Anasasis, Crunchy, Defaulter, Mcg1LLzZz, Rossi<br />
Global Rank: [592](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [97]( ../standings_asia.md)<br />
<br />
Final Rank Value:  408.1<br />
<br />
Final Rank Value (408.1) = Starting Rank Value (400.1) + Head To Head Adjustments (8.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.1
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     4819 | 2024-10-20 | Gods Reign         | L   | 0.317      | -            | -                | -                | -         |    -0.65 | Anasasis, Crunchy, Defaulter, Mcg1LLzZz, Rossi |
|            5 |     5967 | 2024-09-29 | Carnival Gaming    | W   | 0.178      | 0.143        | 0.000 (0.000)    | 0.023 (0.001)    | 0 (0.000) |     3.47 | Anasasis, Crunchy, Defaulter, Mcg1LLzZz, Rossi |
|            4 |     5975 | 2024-09-29 | Gods Reign         | L   | 0.178      | -            | -                | -                | -         |    -0.31 | Anasasis, Crunchy, Defaulter, Mcg1LLzZz, Rossi |
|            3 |     6134 | 2024-09-27 | Carnival Gaming    | W   | 0.165      | 0.143        | 0.000 (0.000)    | 0.023 (0.001)    | 0 (0.000) |     3.21 | Anasasis, Crunchy, Defaulter, Mcg1LLzZz, Rossi |
|            2 |     6211 | 2024-09-26 | Brain lag E-sports | W   | 0.159      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.50 | Anasasis, Crunchy, Defaulter, Mcg1LLzZz, Rossi |
|            1 |     6539 | 2024-09-21 | Gods Reign         | L   | 0.130      | -            | -                | -                | -         |    -0.22 | Anasasis, Crunchy, Defaulter, Mcg1LLzZz, Rossi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
