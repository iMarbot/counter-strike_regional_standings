### Roster Details<br />
Team Name: AgenciUSB<br />
Roster: blacktear5, Futrzak, Jakras, mlodziutk1, sanT<br />
Global Rank: [504](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [312]( ../standings_europe.md)<br />
<br />
Final Rank Value:  511.1<br />
<br />
Final Rank Value (511.1) = Starting Rank Value (485.8) + Head To Head Adjustments (25.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.169[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.043<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 485.8
- 400 + ( ( 0.043 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 485.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |      705 | 2025-02-08 | ENCE                | L   | 1.000      | -            | -                | -                | -         |    -1.72 | blacktear5, Futrzak, Jakras, mlodziutk1, sanT |
|            7 |      759 | 2025-02-07 | Virtual Cottage     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |    15.87 | blacktear5, Futrzak, Jakras, mlodziutk1, sanT |
|            6 |     4544 | 2024-10-26 | Illuminar Gaming    | L   | 0.350      | -            | -                | -                | -         |    -1.26 | blacktear5, Futrzak, Jakras, pr3e, sanT       |
|            5 |     4557 | 2024-10-26 | Los kogutos         | L   | 0.350      | -            | -                | -                | -         |    -0.85 | blacktear5, Futrzak, Jakras, pr3e, sanT       |
|            4 |     5207 | 2024-10-12 | Haspers Team        | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.028 (0.001)    | 0 (0.000) |     5.20 | blacktear5, Futrzak, Jakras, pr3e, sanT       |
|            3 |     5220 | 2024-10-12 | GameAgents          | W   | 0.257      | 0.143        | 0.003 (0.000)    | 0.111 (0.004)    | 0 (0.000) |     6.14 | blacktear5, Futrzak, Jakras, pr3e, sanT       |
|            2 |     6047 | 2024-09-28 | Soul's Heart Esport | W   | 0.164      | 0.143        | 0.000 (0.000)    | 0.112 (0.003)    | 0 (0.000) |     2.95 | blacktear5, Futrzak, Jakras, pr3e, sanT       |
|            1 |     6466 | 2024-09-23 | GameAgents          | L   | 0.132      | -            | -                | -                | -         |    -1.02 | blacktear5, frox, Futrzak, Jakras, onStyle    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
