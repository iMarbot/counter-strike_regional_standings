### Roster Details<br />
Team Name: ANimaleGG<br />
Roster: klyrO, mAXeLL-, Reqqen, s1nku, taevasyo<br />
Global Rank: [554](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [341]( ../standings_europe.md)<br />
<br />
Final Rank Value:  476.0<br />
<br />
Final Rank Value (476.0) = Starting Rank Value (485.0) + Head To Head Adjustments (-9.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.169[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.043<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 485.0
- 400 + ( ( 0.043 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 485.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     2782 | 2024-11-24 | M1Z                       | L   | 0.546      | -            | -                | -                | -         |   -10.18 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            8 |     2789 | 2024-11-24 | Godne                     | W   | 0.545      | 0.143        | 0.000 (0.000)    | 0.045 (0.003)    | 0 (0.000) |     6.61 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            7 |     3236 | 2024-11-17 | GENESIS (Estonian team)   | L   | 0.499      | -            | -                | -                | -         |    -7.26 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            6 |     3654 | 2024-11-10 | SHOO7ERS                  | L   | 0.452      | -            | -                | -                | -         |    -3.81 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            5 |     4064 | 2024-11-03 | Truck Drivers             | W   | 0.405      | 0.143        | 0.002 (0.000)    | 0.120 (0.007)    | 0 (0.000) |     9.72 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            4 |     4470 | 2024-10-27 | Godne                     | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.045 (0.002)    | 0 (0.000) |     4.33 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            3 |     4789 | 2024-10-20 | M1Z                       | L   | 0.311      | -            | -                | -                | -         |    -5.96 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            2 |     5139 | 2024-10-13 | W2TE                      | L   | 0.265      | -            | -                | -                | -         |    -5.17 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            1 |     5531 | 2024-10-06 | FullShock (Estonian team) | W   | 0.218      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     2.62 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
