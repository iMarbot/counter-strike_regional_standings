### Roster Details<br />
Team Name: URI Sailor<br />
Roster: Blackze, juliano, lucasss, pertile, pvL<br />
Global Rank: [550](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [127]( ../standings_americas.md)<br />
<br />
Final Rank Value:  479.0<br />
<br />
Final Rank Value (479.0) = Starting Rank Value (466.3) + Head To Head Adjustments (12.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.132[<sup>2</sup>](#table1)

The average of these factors is 0.033<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 466.3
- 400 + ( ( 0.033 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 466.3


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
|            5 |     4933 | 2024-10-17 | UnB Green Owls    | W   | 0.292      | 0.143        | 0.000 (0.000)    | 0.039 (0.002)    | 1 (0.292) |     4.41 | Blackze, juliano, lucasss, pertile, pvL |
|            4 |     4986 | 2024-10-16 | UTFPR Pato Branco | W   | 0.286      | 0.143        | 0.000 (0.000)    | 0.039 (0.002)    | 1 (0.286) |     4.26 | Blackze, juliano, lucasss, pertile, pvL |
|            3 |     5065 | 2024-10-15 | UFG Eagles        | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 1 (0.278) |     3.81 | Blackze, juliano, lucasss, pertile, pvL |
|            2 |     5100 | 2024-10-14 | UNOESC Versatch   | W   | 0.273      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.273) |     3.54 | Blackze, juliano, lucasss, pertile, pvL |
|            1 |     5587 | 2024-10-05 | Martians Oldsters | L   | 0.212      | -            | -                | -                | -         |    -3.31 | Blackze, juliano, lucasss, pertile, pvL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
