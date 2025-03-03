### Roster Details<br />
Team Name: Cloud9<br />
Roster: Ax1Le, Boombl4, HeavyGod, ICY, interz<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  925.2<br />
<br />
Final Rank Value (925.2) = Starting Rank Value (889.2) + Head To Head Adjustments (36.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.245[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 889.2
- 400 + ( ( 0.245 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 889.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     2383 | 2024-12-01 | Complexity      | L   | 0.595      | -            | -                | -                | -         |    -4.22 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           15 |     2464 | 2024-11-30 | PaiN Gaming     | L   | 0.588      | -            | -                | -                | -         |    -0.47 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           14 |     2562 | 2024-11-30 | Fnatic          | W   | 0.583      | 1.000        | 0.072 (0.042)    | 0.459 (0.268)    | 1 (0.583) |    12.83 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           13 |     2573 | 2024-11-29 | Team Liquid     | L   | 0.581      | -            | -                | -                | -         |    -0.63 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           12 |     3176 | 2024-11-19 | FaZe Clan       | L   | 0.510      | -            | -                | -                | -         |    -0.07 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           11 |     3189 | 2024-11-18 | SINNERS Esports | W   | 0.507      | 0.143        | 0.027 (0.002)    | 0.446 (0.032)    | 1 (0.507) |     8.43 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           10 |     3230 | 2024-11-17 | HEROIC          | W   | 0.501      | 0.143        | 0.131 (0.009)    | 0.401 (0.029)    | 1 (0.501) |    11.74 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            9 |     3267 | 2024-11-17 | Nemiga Gaming   | W   | 0.497      | 0.143        | 0.176 (0.012)    | 0.345 (0.024)    | 1 (0.497) |    10.88 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            8 |     3307 | 2024-11-16 | FaZe Clan       | L   | 0.495      | -            | -                | -                | -         |    -0.05 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            7 |     4621 | 2024-10-25 | Fnatic          | L   | 0.343      | -            | -                | -                | -         |    -3.00 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            6 |     4717 | 2024-10-22 | 9z Team         | W   | 0.324      | 0.934        | 0.015 (0.005)    | 0.119 (0.036)    | 0 (0.000) |     3.63 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            5 |     4726 | 2024-10-22 | The MongolZ     | L   | 0.323      | -            | -                | -                | -         |    -0.03 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            4 |     5284 | 2024-10-11 | Passion UA      | L   | 0.249      | -            | -                | -                | -         |    -2.34 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            3 |     7114 | 2024-09-13 | Tricked Esport  | L   | 0.063      | -            | -                | -                | -         |    -1.16 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            2 |     7463 | 2024-09-07 | Zero Tenacity   | W   | 0.023      | 0.384        | 0.028 (0.000)    | 0.684 (0.006)    | 0 (0.000) |     0.34 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            1 |     7637 | 2024-09-05 | ALTERNATE aTTaX | W   | 0.009      | 0.384        | 0.021 (0.000)    | 0.552 (0.002)    | 0 (0.000) |     0.17 | Ax1Le, Boombl4, HeavyGod, ICY, interz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,294.21)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.683 | $10,000.00     | $6,827.55       |
| 2024-09-07 |      0.023 | $20,000.00     | $466.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
