### Roster Details<br />
Team Name: W2TE<br />
Roster: --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar<br />
Global Rank: [626](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [381]( ../standings_europe.md)<br />
<br />
Final Rank Value:  378.1<br />
<br />
Final Rank Value (378.1) = Starting Rank Value (400.1) + Head To Head Adjustments (-22.0)<br />

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
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.1


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
|            7 |     3239 | 2024-11-17 | Godne                     | L   | 0.498      | -            | -                | -                | -         |    -7.63 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            6 |     3669 | 2024-11-10 | M1Z                       | L   | 0.452      | -            | -                | -                | -         |    -6.69 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            5 |     4057 | 2024-11-03 | SHOO7ERS                  | L   | 0.405      | -            | -                | -                | -         |    -2.27 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            4 |     4461 | 2024-10-27 | FullShock (Estonian team) | L   | 0.359      | -            | -                | -                | -         |    -5.74 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            3 |     4801 | 2024-10-20 | GENESIS (Estonian team)   | L   | 0.311      | -            | -                | -                | -         |    -3.76 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            2 |     5139 | 2024-10-13 | ANimaleGG                 | W   | 0.265      | 0.143        | 0.000 (0.000)    | 0.055 (0.002)    | 0 (0.000) |     5.17 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |
|            1 |     5527 | 2024-10-06 | Truck Drivers             | L   | 0.218      | -            | -                | -                | -         |    -1.10 | --KR, fl1pzzy, kosmonaut69, ucr0, wr1stmar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
