### Roster Details<br />
Team Name: Infinite Gaming<br />
Roster: CHANKY, d1maje, grecu, LkS, starplajerz<br />
Global Rank: [426](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [264]( ../standings_europe.md)<br />
<br />
Final Rank Value:  577.7<br />
<br />
Final Rank Value (577.7) = Starting Rank Value (590.4) + Head To Head Adjustments (-12.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.215[<sup>1</sup>](#table2)
- Bounty Collected: 0.166[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.095<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 590.4
- 400 + ( ( 0.095 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 590.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     4844 | 2024-10-19 | PORC CARTEL | L   | 0.312      | -            | -                | -                | -         |    -4.74 | CHANKY, d1maje, grecu, LkS, starplajerz  |
|            4 |     4847 | 2024-10-19 | Aimclub     | L   | 0.312      | -            | -                | -                | -         |    -6.45 | CHANKY, d1maje, grecu, LkS, starplajerz  |
|            3 |     6057 | 2024-09-28 | POOHANK     | L   | 0.172      | -            | -                | -                | -         |    -2.83 | CHANKY, d1maje, grecu, LkS, starplajerz  |
|            2 |     7294 | 2024-09-09 | BRUTE       | W   | 0.046      | 0.333        | 0.004 (0.000)    | 0.345 (0.005)    | 0 (0.000) |     0.98 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            1 |     7613 | 2024-09-05 | Chroma      | W   | 0.018      | 0.333        | 0.005 (0.000)    | 0.094 (0.001)    | 0 (0.000) |     0.36 | CHANKY, d1maje, mhN1, starplajerz, zewts |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($75.50)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.126 | $600.00        | $75.50          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
