### Roster Details<br />
Team Name: Nomads (Mongolian team)<br />
Roster: ctrlmad, ezlan, hoolig4n, KRST, shinobi<br />
Global Rank: [332](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [52]( ../standings_asia.md)<br />
<br />
Final Rank Value:  632.6<br />
<br />
Final Rank Value (632.6) = Starting Rank Value (633.2) + Head To Head Adjustments (-0.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.237[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 633.2
- 400 + ( ( 0.117 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 633.2


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
|            8 |     5350 | 2024-10-09 | Noobs But Diligent | L   | 0.245      | -            | -                | -                | -         |    -5.44 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            7 |     5356 | 2024-10-09 | Noobs But Diligent | L   | 0.245      | -            | -                | -                | -         |    -5.53 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            6 |     5860 | 2024-10-01 | TYLOO              | L   | 0.192      | -            | -                | -                | -         |    -2.01 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            5 |     5863 | 2024-10-01 | TYLOO              | L   | 0.191      | -            | -                | -                | -         |    -2.04 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            4 |     5924 | 2024-09-30 | ATOX Esports       | W   | 0.185      | 0.417        | 0.008 (0.001)    | 0.061 (0.005)    | 0 (0.000) |     3.46 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            3 |     5927 | 2024-09-30 | ATOX Esports       | W   | 0.185      | 0.417        | 0.008 (0.001)    | 0.061 (0.005)    | 0 (0.000) |     3.52 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            2 |     6301 | 2024-09-25 | Lynn Vision Gaming | W   | 0.152      | 0.417        | 0.017 (0.001)    | 0.368 (0.023)    | 0 (0.000) |     3.71 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |
|            1 |     6307 | 2024-09-25 | Lynn Vision Gaming | W   | 0.151      | 0.417        | 0.017 (0.001)    | 0.368 (0.023)    | 0 (0.000) |     3.73 | ctrlmad, ezlan, hoolig4n, KRST, shinobi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($205.39)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.411 | $500.00        | $205.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
