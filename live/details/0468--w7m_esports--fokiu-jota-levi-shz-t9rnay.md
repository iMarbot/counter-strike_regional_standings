### Roster Details<br />
Team Name: W7m esports<br />
Roster: fokiu, JOTA, levi, shz, t9rnay<br />
Global Rank: [468](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [103]( ../standings_americas.md)<br />
<br />
Final Rank Value:  542.9<br />
<br />
Final Rank Value (542.9) = Starting Rank Value (501.3) + Head To Head Adjustments (41.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 501.3
- 400 + ( ( 0.051 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 501.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |      172 | 2025-02-21 | Fudidos e anonymous    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.093 (0.013)    | 0 (0.000) |    11.15 | fokiu, JOTA, levi, shz, t9rnay |
|            7 |      176 | 2025-02-21 | VELOX Argentina        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.266 (0.038)    | 0 (0.000) |    18.02 | fokiu, JOTA, levi, shz, t9rnay |
|            6 |      193 | 2025-02-21 | América eSports        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.429 (0.061)    | 0 (0.000) |    18.98 | fokiu, JOTA, levi, shz, t9rnay |
|            5 |      282 | 2025-02-17 | Galorys                | L   | 1.000      | -            | -                | -                | -         |   -16.91 | fokiu, JOTA, levi, shz, t9rnay |
|            4 |      397 | 2025-02-15 | Tropa do VSM           | L   | 1.000      | -            | -                | -                | -         |   -16.11 | fokiu, JOTA, levi, shz, t9rnay |
|            3 |      401 | 2025-02-15 | Seleção do BT          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    10.35 | fokiu, JOTA, levi, shz, t9rnay |
|            2 |      931 | 2025-02-04 | Bounty Hunters Esports | L   | 1.000      | -            | -                | -                | -         |    -6.81 | fokiu, JOTA, levi, shz, t9rnay |
|            1 |      936 | 2025-02-04 | Game Hunters           | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.396 (0.057)    | 0 (0.000) |    22.94 | fokiu, JOTA, levi, shz, t9rnay |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
