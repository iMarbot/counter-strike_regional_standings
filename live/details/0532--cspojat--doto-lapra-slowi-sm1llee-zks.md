### Roster Details<br />
Team Name: Cspojat<br />
Roster: doto, Lapra, sLowi, Sm1llee, zks<br />
Global Rank: [532](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [330]( ../standings_europe.md)<br />
<br />
Final Rank Value:  487.7<br />
<br />
Final Rank Value (487.7) = Starting Rank Value (481.5) + Head To Head Adjustments (6.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.161[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.041<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 481.5
- 400 + ( ( 0.041 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 481.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     5539 | 2024-10-06 | Heimo Esports   | L   | 0.224      | -            | -                | -                | -         |    -1.33 | doto, Lapra, sLowi, Sm1llee, zks    |
|            6 |     5605 | 2024-10-05 | JANO Esports    | L   | 0.218      | -            | -                | -                | -         |    -0.56 | doto, Lapra, sLowi, Sm1llee, zks    |
|            5 |     5910 | 2024-09-30 | HAVU            | W   | 0.186      | 0.143        | 0.002 (0.000)    | 0.378 (0.010)    | 0 (0.000) |     4.25 | doto, Lapra, sLowi, Sm1llee, zks    |
|            4 |     5983 | 2024-09-29 | Smuuttikusilkki | W   | 0.177      | 0.143        | 0.000 (0.000)    | 0.224 (0.006)    | 0 (0.000) |     2.70 | doto, Lapra, m0n0xx, sLowi, Sm1llee |
|            3 |     6467 | 2024-09-23 | Heimo Esports   | L   | 0.139      | -            | -                | -                | -         |    -0.81 | doto, Lapra, m4tthi, Sm1llee, zks   |
|            2 |     6885 | 2024-09-16 | HAVU            | W   | 0.093      | 0.143        | 0.002 (0.000)    | 0.378 (0.005)    | 0 (0.000) |     2.13 | doto, Lapra, sLowi, Sm1llee, zks    |
|            1 |     7354 | 2024-09-08 | ENCE Academy    | L   | 0.038      | -            | -                | -                | -         |    -0.16 | doto, Lapra, sLowi, Sm1llee, zks    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
