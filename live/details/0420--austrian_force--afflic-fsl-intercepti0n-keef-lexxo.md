### Roster Details<br />
Team Name: Austrian Force<br />
Roster: afflic, fSL, Intercepti0n, keef, lexxo<br />
Global Rank: [420](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [261]( ../standings_europe.md)<br />
<br />
Final Rank Value:  580.8<br />
<br />
Final Rank Value (580.8) = Starting Rank Value (580.1) + Head To Head Adjustments (0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.124[<sup>2</sup>](#table1)

The average of these factors is 0.090<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 580.1
- 400 + ( ( 0.090 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 580.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     4485 | 2024-10-27 | Sissi State Punks | L   | 0.364      | -            | -                | -                | -         |    -4.27 | afflic, fSL, Intercepti0n, keef, lexxo |
|            4 |     4565 | 2024-10-25 | Dontcaremehr      | W   | 0.355      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 1 (0.355) |     3.23 | afflic, fSL, Intercepti0n, keef, lexxo |
|            3 |     4567 | 2024-10-25 | TelevisaPresenta  | W   | 0.355      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 1 (0.355) |     3.19 | afflic, fSL, Intercepti0n, keef, lexxo |
|            2 |     4568 | 2024-10-25 | BiBaBu Lenkradaim | W   | 0.355      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.355) |     2.90 | afflic, fSL, Intercepti0n, keef, lexxo |
|            1 |     4571 | 2024-10-25 | Sissi State Punks | L   | 0.355      | -            | -                | -                | -         |    -4.29 | afflic, fSL, Intercepti0n, keef, lexxo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($196.64)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.364 | $539.99        | $196.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
