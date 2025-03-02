### Roster Details<br />
Team Name: BERMOOD<br />
Roster: ares666x, dARkjezz, jaw1ko, Schwarzkopf, sorr1k<br />
Global Rank: [604](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [100]( ../standings_asia.md)<br />
<br />
Final Rank Value:  402.2<br />
<br />
Final Rank Value (402.2) = Starting Rank Value (409.9) + Head To Head Adjustments (-7.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.020[<sup>2</sup>](#table1)

The average of these factors is 0.005<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 409.9
- 400 + ( ( 0.005 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 409.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     4009 | 2024-11-04 | Yamato Esports   | L   | 0.419      | -            | -                | -                | -         |    -4.67 | ares666x, dARkjezz, jaw1ko, Schwarzkopf, sorr1k |
|            4 |     4151 | 2024-11-02 | MYSKILL          | L   | 0.405      | -            | -                | -                | -         |    -2.37 | ares666x, dARkjezz, jaw1ko, Schwarzkopf, sorr1k |
|            3 |     5986 | 2024-09-29 | BEZONE           | L   | 0.177      | -            | -                | -                | -         |    -2.70 | ares, dARkjezz, jaw1ko, lordsei, Schwarzkopf    |
|            2 |     6068 | 2024-09-28 | DEPO             | L   | 0.171      | -            | -                | -                | -         |    -0.62 | ares, dARkjezz, jaw1ko, lordsei, Schwarzkopf    |
|            1 |     6079 | 2024-09-28 | Storm Uzbekistan | W   | 0.170      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.170) |     2.61 | ares, dARkjezz, jaw1ko, lordsei, Schwarzkopf    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
