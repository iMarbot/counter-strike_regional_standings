### Roster Details<br />
Team Name: KONO.ECF<br />
Roster: amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [131]( ../standings_europe.md)<br />
<br />
Final Rank Value:  724.8<br />
<br />
Final Rank Value (724.8) = Starting Rank Value (587.7) + Head To Head Adjustments (137.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.282[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.094<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 587.7
- 400 + ( ( 0.094 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 587.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      402 | 2025-02-15 | Rebels Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -14.35 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           14 |      408 | 2025-02-15 | BAKS Esports                              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.153 (0.022)    | 0 (0.000) |     8.85 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           13 |      416 | 2025-02-15 | RUSH B (Russian team)                     | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.921 (0.132)    | 0 (0.000) |    25.06 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           12 |      464 | 2025-02-14 | Little Red Door                           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.187 (0.027)    | 0 (0.000) |    11.69 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           11 |      623 | 2025-02-09 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |    -9.52 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           10 |      877 | 2025-02-05 | Zero Tenacity                             | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.692 (0.099)    | 0 (0.000) |    22.49 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            9 |      951 | 2025-02-04 | Adventurers                               | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.166 (0.024)    | 0 (0.000) |    21.44 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            8 |     1118 | 2025-01-28 | ECSTATIC                                  | L   | 0.984      | -            | -                | -                | -         |    -6.90 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            7 |     1130 | 2025-01-25 | Copenhagen Wolves (American organization) | L   | 0.967      | -            | -                | -                | -         |    -6.75 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            6 |     1141 | 2025-01-24 | Iberian Soul                              | W   | 0.959      | 0.143        | 0.015 (0.002)    | 0.553 (0.076)    | 0 (0.000) |    22.15 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            5 |     1202 | 2025-01-10 | SINNERS Esports                           | L   | 0.864      | -            | -                | -                | -         |    -5.45 | amster, byr9, cptkurtka023, s4ltovsk1yy, Sijeyy  |
|            4 |     1207 | 2025-01-09 | BadGuys                                   | W   | 0.859      | 0.417        | 0.000 (0.000)    | 0.281 (0.101)    | 0 (0.000) |    15.06 | amster, byr9, cptkurtka023, s4ltovsk1yy, Sijeyy  |
|            3 |     1219 | 2025-01-05 | ECSTATIC                                  | W   | 0.833      | 0.417        | 0.033 (0.011)    | 0.828 (0.288)    | 0 (0.000) |    22.10 | amster, byr9, cptkurtka023, s4ltovsk1yy, Sijeyy  |
|            2 |     1227 | 2025-01-03 | Rhyno Esports                             | W   | 0.819      | 0.417        | 0.013 (0.005)    | 0.447 (0.153)    | 0 (0.000) |    21.02 | amster, byr9, cptkurtka023, s4ltovsk1yy, Sijeyy  |
|            1 |     1323 | 2024-12-27 | CS2NEWS                                   | W   | 0.773      | 0.417        | 0.000 (0.000)    | 0.062 (0.020)    | 0 (0.000) |    10.27 | amster, byr9, kensizor, s4ltovsk1yy, Sijeyy      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
