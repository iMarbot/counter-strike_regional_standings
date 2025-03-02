### Roster Details<br />
Team Name: Aimclub<br />
Roster: Blytz, lauNX, MoDo, s0und, zewts<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  853.5<br />
<br />
Final Rank Value (853.5) = Starting Rank Value (815.0) + Head To Head Adjustments (38.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.161[<sup>2</sup>](#table1)

The average of these factors is 0.208<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 815.0
- 400 + ( ( 0.208 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 815.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1623 | 2024-12-15 | Nexus Gaming                | W   | 0.693      | 0.143        | 0.186 (0.018)    | 0.808 (0.080)    | 1 (0.693) |    16.67 | Blytz, lauNX, MoDo, s0und, zewts |
|            5 |     1688 | 2024-12-14 | JackBoyz                    | W   | 0.687      | 0.143        | 0.008 (0.001)    | 0.056 (0.005)    | 1 (0.687) |     5.79 | Blytz, lauNX, MoDo, s0und, zewts |
|            4 |     2580 | 2024-11-29 | DEVASTATION (Romanian team) | W   | 0.587      | 0.143        | 0.003 (0.000)    | 0.082 (0.007)    | 0 (0.000) |     4.93 | Blytz, lauNX, MoDo, s0und, zewts |
|            3 |     2592 | 2024-11-29 | HyperSpirit                 | W   | 0.586      | 0.143        | 0.000 (0.000)    | 0.088 (0.007)    | 0 (0.000) |     2.73 | Blytz, lauNX, MoDo, s0und, zewts |
|            2 |     2626 | 2024-11-28 | REDPack Esports             | W   | 0.580      | 0.143        | 0.001 (0.000)    | 0.085 (0.007)    | 0 (0.000) |     4.26 | Blytz, lauNX, MoDo, s0und, zewts |
|            1 |     2637 | 2024-11-28 | PORC CARTEL                 | W   | 0.579      | 0.143        | 0.001 (0.000)    | 0.029 (0.002)    | 0 (0.000) |     4.19 | Blytz, lauNX, MoDo, s0und, zewts |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,093.18)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.693 | $13,130.94     | $9,093.18       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
