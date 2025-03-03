### Roster Details<br />
Team Name: Natus Vincere Youth<br />
Roster: ad3r, AJ, balage, kodak, yoki<br />
Global Rank: [547](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [337]( ../standings_europe.md)<br />
<br />
Final Rank Value:  481.0<br />
<br />
Final Rank Value (481.0) = Starting Rank Value (488.4) + Head To Head Adjustments (-7.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.175[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.044<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 488.4
- 400 + ( ( 0.044 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 488.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     3797 | 2024-11-08 | Daystar               | L   | 0.439      | -            | -                | -                | -         |    -4.19 | ad3r, AJ, balage, kodak, yoki |
|           10 |     4006 | 2024-11-04 | Mission Possible      | L   | 0.412      | -            | -                | -                | -         |    -5.38 | ad3r, AJ, balage, kodak, yoki |
|            9 |     4145 | 2024-11-02 | Preasy Esport         | L   | 0.398      | -            | -                | -                | -         |    -2.04 | ad3r, AJ, balage, kodak, Yoki |
|            8 |     4209 | 2024-11-01 | ZOTIX                 | W   | 0.391      | 0.333        | 0.001 (0.000)    | 0.147 (0.019)    | 0 (0.000) |     8.45 | ad3r, AJ, balage, kodak, Yoki |
|            7 |     4384 | 2024-10-29 | GODSENT               | L   | 0.371      | -            | -                | -                | -         |    -3.11 | ad3r, AJ, balage, kodak, Yoki |
|            6 |     6461 | 2024-09-23 | Partizan Esports      | L   | 0.132      | -            | -                | -                | -         |    -0.14 | ad3r, AJ, Balage, kodak, Yoki |
|            5 |     6495 | 2024-09-23 | GODSENT               | L   | 0.130      | -            | -                | -                | -         |    -1.10 | ad3r, AJ, Balage, kodak, Yoki |
|            4 |     6632 | 2024-09-20 | LOADING (French team) | W   | 0.112      | 0.333        | 0.000 (0.000)    | 0.022 (0.001)    | 0 (0.000) |     1.90 | ad3r, AJ, Balage, kodak, Yoki |
|            3 |     6647 | 2024-09-20 | ROYALS                | L   | 0.111      | -            | -                | -                | -         |    -0.88 | ad3r, AJ, Balage, kodak, Yoki |
|            2 |     6695 | 2024-09-19 | GenOne                | L   | 0.105      | -            | -                | -                | -         |    -0.43 | ad3r, AJ, Balage, kodak, Yoki |
|            1 |     6720 | 2024-09-19 | Preasy Esport         | L   | 0.103      | -            | -                | -                | -         |    -0.47 | ad3r, AJ, Balage, kodak, Yoki |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
