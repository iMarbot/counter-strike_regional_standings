### Roster Details<br />
Team Name: DEVASTATION (Romanian team)<br />
Roster: dan7, N0R1, NoXera, reizk, shin<br />
Global Rank: [317](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [211]( ../standings_europe.md)<br />
<br />
Final Rank Value:  639.9<br />
<br />
Final Rank Value (639.9) = Starting Rank Value (632.2) + Head To Head Adjustments (7.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.177[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.2
- 400 + ( ( 0.116 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 632.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1987 | 2024-12-08 | Perfect Storm   | L   | 0.647      | -            | -                | -                | -         |    -9.31 | dan7, N0R1, NoXera, reizk, shin |
|            4 |     2577 | 2024-11-29 | HyperSpirit     | W   | 0.587      | 0.143        | 0.000 (0.000)    | 0.088 (0.007)    | 0 (0.000) |     5.86 | dan7, N0R1, NoXera, reizk, shin |
|            3 |     2580 | 2024-11-29 | Aimclub         | L   | 0.587      | -            | -                | -                | -         |    -4.93 | dan7, N0R1, NoXera, reizk, shin |
|            2 |     2584 | 2024-11-29 | PORC CARTEL     | W   | 0.586      | 0.143        | 0.001 (0.000)    | 0.029 (0.002)    | 0 (0.000) |     7.49 | dan7, N0R1, NoXera, reizk, shin |
|            1 |     2632 | 2024-11-28 | REDPack Esports | W   | 0.580      | 0.143        | 0.001 (0.000)    | 0.085 (0.007)    | 0 (0.000) |     8.63 | dan7, N0R1, NoXera, reizk, shin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,091.18)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.693 | $1,575.71      | $1,091.18       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
