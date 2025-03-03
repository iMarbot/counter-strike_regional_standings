### Roster Details<br />
Team Name: KONO.ECF<br />
Roster: amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN<br />
Global Rank: [184](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [132]( ../standings_europe.md)<br />
<br />
Final Rank Value:  723.4<br />
<br />
Final Rank Value (723.4) = Starting Rank Value (587.1) + Head To Head Adjustments (136.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.282[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.094<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 587.1
- 400 + ( ( 0.094 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 587.1


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
|           15 |      414 | 2025-02-15 | Rebels Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -14.36 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           14 |      420 | 2025-02-15 | BAKS Esports                              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.151 (0.022)    | 0 (0.000) |     8.88 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           13 |      428 | 2025-02-15 | RUSH B (Russian team)                     | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.915 (0.131)    | 0 (0.000) |    25.06 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           12 |      476 | 2025-02-14 | Little Red Door                           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.188 (0.027)    | 0 (0.000) |    11.75 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           11 |      635 | 2025-02-09 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |    -9.50 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|           10 |      889 | 2025-02-05 | Zero Tenacity                             | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.684 (0.098)    | 0 (0.000) |    22.46 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            9 |      963 | 2025-02-04 | Adventurers                               | W   | 1.000      | 0.143        | 0.016 (0.002)    | 0.161 (0.023)    | 0 (0.000) |    21.37 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            8 |     1130 | 2025-01-28 | ECSTATIC                                  | L   | 0.976      | -            | -                | -                | -         |    -6.86 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            7 |     1142 | 2025-01-25 | Copenhagen Wolves (American organization) | L   | 0.959      | -            | -                | -                | -         |    -6.70 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            6 |     1153 | 2025-01-24 | Iberian Soul                              | W   | 0.950      | 0.143        | 0.015 (0.002)    | 0.551 (0.075)    | 0 (0.000) |    21.96 | amster, cptkurtka023, s4ltovsk1yy, Sijeyy, zogeN |
|            5 |     1214 | 2025-01-10 | SINNERS Esports                           | L   | 0.856      | -            | -                | -                | -         |    -5.41 | amster, byr9, cptkurtka023, s4ltovsk1yy, Sijeyy  |
|            4 |     1219 | 2025-01-09 | BadGuys                                   | W   | 0.851      | 0.417        | 0.000 (0.000)    | 0.279 (0.099)    | 0 (0.000) |    14.90 | amster, byr9, cptkurtka023, s4ltovsk1yy, Sijeyy  |
|            3 |     1231 | 2025-01-05 | ECSTATIC                                  | W   | 0.825      | 0.417        | 0.033 (0.011)    | 0.820 (0.282)    | 0 (0.000) |    21.86 | amster, byr9, cptkurtka023, s4ltovsk1yy, Sijeyy  |
|            2 |     1239 | 2025-01-03 | Rhyno Esports                             | W   | 0.811      | 0.417        | 0.013 (0.004)    | 0.441 (0.149)    | 0 (0.000) |    20.77 | amster, byr9, cptkurtka023, s4ltovsk1yy, Sijeyy  |
|            1 |     1335 | 2024-12-27 | CS2NEWS                                   | W   | 0.765      | 0.417        | 0.000 (0.000)    | 0.062 (0.020)    | 0 (0.000) |    10.18 | amster, byr9, kensizor, s4ltovsk1yy, Sijeyy      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
