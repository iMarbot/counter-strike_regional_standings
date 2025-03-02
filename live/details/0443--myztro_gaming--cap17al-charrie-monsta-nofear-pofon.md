### Roster Details<br />
Team Name: Myztro Gaming<br />
Roster: cap17al, CHARRIE, mONSTA, NOFEAR, Pofon<br />
Global Rank: [443](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [276]( ../standings_europe.md)<br />
<br />
Final Rank Value:  562.3<br />
<br />
Final Rank Value (562.3) = Starting Rank Value (574.3) + Head To Head Adjustments (-12.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.208[<sup>1</sup>](#table2)
- Bounty Collected: 0.141[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.087<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 574.3
- 400 + ( ( 0.087 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 574.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     4286 | 2024-10-30 | Budapest Five                 | L   | 0.387      | -            | -                | -                | -         |    -4.75 | cap17al, CHARRIE, mONSTA, NOFEAR, Pofon |
|            4 |     4310 | 2024-10-30 | Team Hungary                  | L   | 0.386      | -            | -                | -                | -         |    -2.88 | cap17al, CHARRIE, mONSTA, NOFEAR, Pofon |
|            3 |     4575 | 2024-10-25 | Békéscsabai E-Sport Egyesület | L   | 0.353      | -            | -                | -                | -         |    -5.42 | cap17al, CHARRIE, mONSTA, NOFEAR, Pofon |
|            2 |     4670 | 2024-10-23 | ManageYself                   | W   | 0.339      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     5.38 | cap17al, CHARRIE, mONSTA, NOFEAR, Pofon |
|            1 |     4791 | 2024-10-20 | SKIBIDIES                     | L   | 0.319      | -            | -                | -                | -         |    -4.32 | cap17al, CHARRIE, mONSTA, NOFEAR, Pofon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($53.34)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-01 |      0.400 | $133.22        | $53.34          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
