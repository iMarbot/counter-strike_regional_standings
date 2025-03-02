### Roster Details<br />
Team Name: W2TE<br />
Roster: --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar<br />
Global Rank: [625](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [382]( ../standings_europe.md)<br />
<br />
Final Rank Value:  377.7<br />
<br />
Final Rank Value (377.7) = Starting Rank Value (400.1) + Head To Head Adjustments (-22.4)<br />

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


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3227 | 2024-11-17 | Godne                     | L   | 0.507      | -            | -                | -                | -         |    -7.75 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            6 |     3657 | 2024-11-10 | M1Z                       | L   | 0.460      | -            | -                | -                | -         |    -6.80 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            5 |     4045 | 2024-11-03 | SHOO7ERS                  | L   | 0.413      | -            | -                | -                | -         |    -2.32 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            4 |     4449 | 2024-10-27 | FullShock (Estonian team) | L   | 0.367      | -            | -                | -                | -         |    -5.88 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            3 |     4789 | 2024-10-20 | GENESIS (Estonian team)   | L   | 0.319      | -            | -                | -                | -         |    -3.86 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            2 |     5127 | 2024-10-13 | ANimaleGG                 | W   | 0.273      | 0.143        | 0.000 (0.000)    | 0.056 (0.002)    | 0 (0.000) |     5.33 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            1 |     5515 | 2024-10-06 | Truck Drivers             | L   | 0.226      | -            | -                | -                | -         |    -1.14 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
