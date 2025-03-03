### Roster Details<br />
Team Name: M1Z<br />
Roster: Ancient, Freesies, klausyk, qwant, Styx<br />
Global Rank: [580](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [353]( ../standings_europe.md)<br />
<br />
Final Rank Value:  425.3<br />
<br />
Final Rank Value (425.3) = Starting Rank Value (400.5) + Head To Head Adjustments (24.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.5
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.5


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
|           12 |     1334 | 2024-12-27 | BRUTE                     | L   | 0.766      | -            | -                | -                | -         |    -4.10 | Ancient, Freesies, klausyk, qwant, Styx |
|           11 |     1355 | 2024-12-26 | Dark Cloud Esports        | L   | 0.759      | -            | -                | -                | -         |    -1.97 | Ancient, Freesies, klausyk, qwant, Styx |
|           10 |     1357 | 2024-12-26 | Sissi State Punks         | W   | 0.758      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    10.98 | Ancient, Freesies, klausyk, qwant, Styx |
|            9 |     2019 | 2024-12-08 | SHOO7ERS                  | L   | 0.637      | -            | -                | -                | -         |    -3.90 | Ancient, Freesies, klausyk, qwant, Styx |
|            8 |     2782 | 2024-11-24 | ANimaleGG                 | W   | 0.546      | 0.143        | 0.000 (0.000)    | 0.055 (0.004)    | 0 (0.000) |    10.18 | Ancient, Freesies, klausyk, qwant, Styx |
|            7 |     3243 | 2024-11-17 | SHOO7ERS                  | L   | 0.498      | -            | -                | -                | -         |    -3.01 | Ancient, Freesies, klausyk, qwant, Styx |
|            6 |     3669 | 2024-11-10 | W2TE                      | W   | 0.452      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     6.69 | Ancient, Freesies, klausyk, qwant, Styx |
|            5 |     4048 | 2024-11-03 | FullShock (Estonian team) | W   | 0.405      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     6.23 | Ancient, Freesies, klausyk, qwant, Styx |
|            4 |     4473 | 2024-10-27 | GENESIS (Estonian team)   | L   | 0.358      | -            | -                | -                | -         |    -4.33 | Ancient, Freesies, klausyk, qwant, Styx |
|            3 |     4789 | 2024-10-20 | ANimaleGG                 | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.055 (0.002)    | 0 (0.000) |     5.96 | Ancient, Freesies, klausyk, qwant, Styx |
|            2 |     5136 | 2024-10-13 | Truck Drivers             | L   | 0.265      | -            | -                | -                | -         |    -1.36 | Ancient, Freesies, klausyk, qwant, Styx |
|            1 |     5535 | 2024-10-06 | Godne                     | W   | 0.217      | 0.143        | 0.000 (0.000)    | 0.045 (0.001)    | 0 (0.000) |     3.41 | Ancient, Freesies, klausyk, qwant, Styx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
