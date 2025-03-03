### Roster Details<br />
Team Name: Lemondogs<br />
Roster: dZ, hemzk9, treckiz, xelos, zeak<br />
Global Rank: [589](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [358]( ../standings_europe.md)<br />
<br />
Final Rank Value:  410.9<br />
<br />
Final Rank Value (410.9) = Starting Rank Value (400.2) + Head To Head Adjustments (10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.2
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3549 | 2024-11-12 | Northern Lights | W   | 0.465      | 0.143        | 0.000 (0.000)    | 0.037 (0.002)    | 0 (0.000) |     7.22 | dZ, hemzk9, treckiz, xelos, zeak |
|            6 |     4375 | 2024-10-29 | Kario Mart      | L   | 0.372      | -            | -                | -                | -         |    -2.64 | dZ, hemzk9, treckiz, xelos, zeak |
|            5 |     5666 | 2024-10-04 | KILLBOX         | W   | 0.205      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     3.82 | dZ, hemzk9, treckiz, xelos, zeak |
|            4 |     6389 | 2024-09-24 | Alliance        | L   | 0.138      | -            | -                | -                | -         |    -0.26 | dZ, hemzk9, treckiz, xelos, zeak |
|            3 |     6939 | 2024-09-15 | IngenKeps       | W   | 0.078      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.22 | dZ, otto, toshas, treckiz, zeak  |
|            2 |     6989 | 2024-09-14 | Hall of famers  | W   | 0.072      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.13 | dZ, otto, toshas, treckiz, zeak  |
|            1 |     7519 | 2024-09-06 | Deathsquad      | W   | 0.018      | 0.143        | 0.000 (0.000)    | 0.011 (0.000)    | 0 (0.000) |     0.28 | dZ, hemzk9, treckiz, xelos, zeak |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
