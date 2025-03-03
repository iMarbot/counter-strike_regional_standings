### Roster Details<br />
Team Name: Nomads (Mongolian team)<br />
Roster: ctrlmad, ezlan, hoolig4n, KRST, shinobi<br />
Global Rank: [335](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [52]( ../standings_asia.md)<br />
<br />
Final Rank Value:  632.0<br />
<br />
Final Rank Value (632.0) = Starting Rank Value (632.8) + Head To Head Adjustments (-0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.237[<sup>1</sup>](#table2)
- Bounty Collected: 0.223[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.8
- 400 + ( ( 0.116 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 632.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     5362 | 2024-10-09 | Noobs But Diligent | L   | 0.237      | -            | -                | -                | -         |    -5.25 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            7 |     5368 | 2024-10-09 | Noobs But Diligent | L   | 0.237      | -            | -                | -                | -         |    -5.34 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            6 |     5872 | 2024-10-01 | TYLOO              | L   | 0.183      | -            | -                | -                | -         |    -1.93 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            5 |     5875 | 2024-10-01 | TYLOO              | L   | 0.183      | -            | -                | -                | -         |    -1.95 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            4 |     5936 | 2024-09-30 | ATOX Esports       | W   | 0.177      | 0.417        | 0.008 (0.001)    | 0.059 (0.004)    | 0 (0.000) |     3.31 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            3 |     5939 | 2024-09-30 | ATOX Esports       | W   | 0.177      | 0.417        | 0.008 (0.001)    | 0.059 (0.004)    | 0 (0.000) |     3.36 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            2 |     6313 | 2024-09-25 | Lynn Vision Gaming | W   | 0.143      | 0.417        | 0.017 (0.001)    | 0.365 (0.022)    | 0 (0.000) |     3.50 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            1 |     6319 | 2024-09-25 | Lynn Vision Gaming | W   | 0.143      | 0.417        | 0.017 (0.001)    | 0.365 (0.022)    | 0 (0.000) |     3.53 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($201.30)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.403 | $500.00        | $201.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
