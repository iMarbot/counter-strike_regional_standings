### Roster Details<br />
Team Name: URI Sailor<br />
Roster: Blackze, juliano, lucasss, pertile, pvL<br />
Global Rank: [550](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [125]( ../standings_americas.md)<br />
<br />
Final Rank Value:  480.9<br />
<br />
Final Rank Value (480.9) = Starting Rank Value (467.9) + Head To Head Adjustments (13.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.136[<sup>2</sup>](#table1)

The average of these factors is 0.034<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 467.9
- 400 + ( ( 0.034 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 467.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     4921 | 2024-10-17 | UnB Green Owls    | W   | 0.300      | 0.143        | 0.000 (0.000)    | 0.040 (0.002)    | 1 (0.300) |     4.53 | Blackze, juliano, lucasss, pertile, pvL |
|            4 |     4974 | 2024-10-16 | UTFPR Pato Branco | W   | 0.294      | 0.143        | 0.000 (0.000)    | 0.041 (0.002)    | 1 (0.294) |     4.38 | Blackze, juliano, lucasss, pertile, pvL |
|            3 |     5053 | 2024-10-15 | UFG Eagles        | W   | 0.286      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 1 (0.286) |     3.91 | Blackze, juliano, lucasss, pertile, pvL |
|            2 |     5088 | 2024-10-14 | UNOESC Versatch   | W   | 0.282      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.282) |     3.63 | Blackze, juliano, lucasss, pertile, pvL |
|            1 |     5575 | 2024-10-05 | Martians Oldsters | L   | 0.220      | -            | -                | -                | -         |    -3.45 | Blackze, juliano, lucasss, pertile, pvL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
