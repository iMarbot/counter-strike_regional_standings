### Roster Details<br />
Team Name: M1Z<br />
Roster: Ancient, Freesies, klausyk, qwant, Styx<br />
Global Rank: [581](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [354]( ../standings_europe.md)<br />
<br />
Final Rank Value:  425.8<br />
<br />
Final Rank Value (425.8) = Starting Rank Value (400.5) + Head To Head Adjustments (25.2)<br />

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
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.5


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
|           12 |     1322 | 2024-12-27 | BRUTE                     | L   | 0.774      | -            | -                | -                | -         |    -4.14 | Ancient, Freesies, klausyk, qwant, Styx |
|           11 |     1343 | 2024-12-26 | Dark Cloud Esports        | L   | 0.767      | -            | -                | -                | -         |    -1.98 | Ancient, Freesies, klausyk, qwant, Styx |
|           10 |     1345 | 2024-12-26 | Sissi State Punks         | W   | 0.766      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    11.08 | Ancient, Freesies, klausyk, qwant, Styx |
|            9 |     2007 | 2024-12-08 | SHOO7ERS                  | L   | 0.646      | -            | -                | -                | -         |    -3.95 | Ancient, Freesies, klausyk, qwant, Styx |
|            8 |     2770 | 2024-11-24 | ANimaleGG                 | W   | 0.554      | 0.143        | 0.000 (0.000)    | 0.056 (0.004)    | 0 (0.000) |    10.32 | Ancient, Freesies, klausyk, qwant, Styx |
|            7 |     3231 | 2024-11-17 | SHOO7ERS                  | L   | 0.506      | -            | -                | -                | -         |    -3.06 | Ancient, Freesies, klausyk, qwant, Styx |
|            6 |     3657 | 2024-11-10 | W2TE                      | W   | 0.460      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     6.80 | Ancient, Freesies, klausyk, qwant, Styx |
|            5 |     4036 | 2024-11-03 | FullShock (Estonian team) | W   | 0.413      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     6.35 | Ancient, Freesies, klausyk, qwant, Styx |
|            4 |     4461 | 2024-10-27 | GENESIS (Estonian team)   | L   | 0.366      | -            | -                | -                | -         |    -4.43 | Ancient, Freesies, klausyk, qwant, Styx |
|            3 |     4777 | 2024-10-20 | ANimaleGG                 | W   | 0.319      | 0.143        | 0.000 (0.000)    | 0.056 (0.003)    | 0 (0.000) |     6.11 | Ancient, Freesies, klausyk, qwant, Styx |
|            2 |     5124 | 2024-10-13 | Truck Drivers             | L   | 0.273      | -            | -                | -                | -         |    -1.40 | Ancient, Freesies, klausyk, qwant, Styx |
|            1 |     5523 | 2024-10-06 | Godne                     | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.045 (0.001)    | 0 (0.000) |     3.54 | Ancient, Freesies, klausyk, qwant, Styx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
