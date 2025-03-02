### Roster Details<br />
Team Name: ANimaleGG<br />
Roster: klyrO, mAXeLL-, Reqqen, s1nku, taevasyo<br />
Global Rank: [555](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [343]( ../standings_europe.md)<br />
<br />
Final Rank Value:  475.8<br />
<br />
Final Rank Value (475.8) = Starting Rank Value (485.0) + Head To Head Adjustments (-9.2)<br />

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
- 400 + ( ( 0.043 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 485.0


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
|            9 |     2770 | 2024-11-24 | M1Z                       | L   | 0.554      | -            | -                | -                | -         |   -10.32 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            8 |     2777 | 2024-11-24 | Godne                     | W   | 0.553      | 0.143        | 0.000 (0.000)    | 0.045 (0.004)    | 0 (0.000) |     6.71 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            7 |     3224 | 2024-11-17 | GENESIS (Estonian team)   | L   | 0.507      | -            | -                | -                | -         |    -7.36 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            6 |     3642 | 2024-11-10 | SHOO7ERS                  | L   | 0.460      | -            | -                | -                | -         |    -3.87 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            5 |     4052 | 2024-11-03 | Truck Drivers             | W   | 0.413      | 0.143        | 0.002 (0.000)    | 0.122 (0.007)    | 0 (0.000) |     9.91 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            4 |     4458 | 2024-10-27 | Godne                     | W   | 0.366      | 0.143        | 0.000 (0.000)    | 0.045 (0.002)    | 0 (0.000) |     4.43 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            3 |     4777 | 2024-10-20 | M1Z                       | L   | 0.319      | -            | -                | -                | -         |    -6.11 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            2 |     5127 | 2024-10-13 | W2TE                      | L   | 0.273      | -            | -                | -                | -         |    -5.33 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |
|            1 |     5519 | 2024-10-06 | FullShock (Estonian team) | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     2.72 | klyrO, mAXeLL-, Reqqen, s1nku, taevasyo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
