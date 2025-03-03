### Roster Details<br />
Team Name: Underground Esports Club<br />
Roster: coops, jBr, Mechanical, N1ghtraid, vanillaicey<br />
Global Rank: [383](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [64]( ../standings_asia.md)<br />
<br />
Final Rank Value:  606.6<br />
<br />
Final Rank Value (606.6) = Starting Rank Value (618.6) + Head To Head Adjustments (-12.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.254[<sup>1</sup>](#table2)
- Bounty Collected: 0.173[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.109<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 618.6
- 400 + ( ( 0.109 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 618.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      266 | 2025-02-19 | Justice For Tomorrow             | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.425 (0.061)    | 0 (0.000) |    19.59 | coops, jBr, Mechanical, N1ghtraid, vanillaicey  |
|           13 |      267 | 2025-02-19 | VerySerious                      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.18 | coops, jBr, Mechanical, N1ghtraid, vanillaicey  |
|           12 |      513 | 2025-02-13 | SemperFi Esports                 | L   | 1.000      | -            | -                | -                | -         |   -12.90 | alecc, coops, Mechanical, N1ghtraid, Omichella  |
|           11 |     1059 | 2025-02-01 | SemperFi Esports                 | L   | 1.000      | -            | -                | -                | -         |   -16.18 | coops, Mechanical, N1ghtraid, Omichella, rahley |
|           10 |     1662 | 2024-12-15 | MANTRA                           | L   | 0.683      | -            | -                | -                | -         |   -11.03 | coops, Mechanical, mpr, N1ghtraid, Rahley       |
|            9 |     1735 | 2024-12-14 | Above The Rest (Australian team) | W   | 0.676      | 0.143        | 0.000 (0.000)    | 0.086 (0.008)    | 0 (0.000) |     7.07 | coops, Mechanical, mpr, N1ghtraid, Rahley       |
|            8 |     1824 | 2024-12-13 | TALON                            | L   | 0.669      | -            | -                | -                | -         |   -11.57 | coops, Mechanical, mpr, N1ghtraid, Rahley       |
|            7 |     2040 | 2024-12-08 | Vantage Esports                  | L   | 0.636      | -            | -                | -                | -         |    -9.30 | coops, Mechanical, mpr, N1ghtraid, Rahley       |
|            6 |     2106 | 2024-12-07 | Above The Rest (Australian team) | W   | 0.629      | 0.270        | 0.000 (0.000)    | 0.086 (0.015)    | 0 (0.000) |     6.26 | coops, Mechanical, mpr, N1ghtraid, Rahley       |
|            5 |     2152 | 2024-12-06 | Shanghai Sharks                  | W   | 0.623      | 0.270        | 0.000 (0.000)    | 0.057 (0.010)    | 0 (0.000) |     6.53 | coops, Mechanical, mpr, N1ghtraid, Rahley       |
|            4 |     2190 | 2024-12-05 | Altered Edge                     | W   | 0.616      | 0.270        | 0.000 (0.000)    | 0.027 (0.004)    | 0 (0.000) |     4.51 | coops, Mechanical, mpr, N1ghtraid, Rahley       |
|            3 |     2241 | 2024-12-04 | Gods Work                        | W   | 0.609      | 0.270        | 0.000 (0.000)    | 0.033 (0.005)    | 0 (0.000) |     4.70 | coops, Mechanical, mpr, N1ghtraid, Rahley       |
|            2 |     2295 | 2024-12-03 | GCSY                             | W   | 0.603      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.50 | coops, Mechanical, mpr, N1ghtraid, Rahley       |
|            1 |     2455 | 2024-12-01 | Shanghai Sharks                  | L   | 0.589      | -            | -                | -                | -         |   -12.33 | coops, Mechanical, mpr, N1ghtraid, Rahley       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($381.42)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.636 | $600.00        | $381.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
