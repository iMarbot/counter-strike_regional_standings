### Roster Details<br />
Team Name: Shanghai Sharks<br />
Roster: Cud, harbor, KRAXYT, mag1c, w0mbat<br />
Global Rank: [556](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [88]( ../standings_asia.md)<br />
<br />
Final Rank Value:  475.4<br />
<br />
Final Rank Value (475.4) = Starting Rank Value (489.6) + Head To Head Adjustments (-14.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.045<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 489.6
- 400 + ( ( 0.045 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 489.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1912 | 2024-12-11 | Rebound                          | L   | 0.656      | -            | -                | -                | -         |    -9.95 | Cud, harbor, KRAXYT, mag1c, w0mbat |
|            5 |     1949 | 2024-12-10 | TALON                            | L   | 0.649      | -            | -                | -                | -         |    -8.07 | Cud, harbor, KRAXYT, mag1c, w0mbat |
|            4 |     2152 | 2024-12-06 | Underground Esports Club         | L   | 0.623      | -            | -                | -                | -         |    -6.53 | Cud, harbor, KRAXYT, mag1c, w0mbat |
|            3 |     2184 | 2024-12-05 | Fazen Klan                       | W   | 0.616      | 0.270        | 0.000 (0.000)    | 0.057 (0.009)    | 0 (0.000) |     7.60 | Cud, harbor, KRAXYT, mag1c, w0mbat |
|            2 |     2369 | 2024-12-02 | Above The Rest (Australian team) | L   | 0.596      | -            | -                | -                | -         |    -9.60 | Cud, harbor, KRAXYT, mag1c, w0mbat |
|            1 |     2455 | 2024-12-01 | Underground Esports Club         | W   | 0.589      | 0.270        | 0.001 (0.000)    | 0.240 (0.038)    | 0 (0.000) |    12.33 | Cud, harbor, KRAXYT, mag1c, w0mbat |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
