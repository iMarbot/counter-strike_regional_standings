### Roster Details<br />
Team Name: Only One Word<br />
Roster: BaN4na, Freeman, Oath, Terryyy, viridian<br />
Global Rank: [295](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [41]( ../standings_asia.md)<br />
<br />
Final Rank Value:  651.9<br />
<br />
Final Rank Value (651.9) = Starting Rank Value (634.4) + Head To Head Adjustments (17.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.250[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 634.4
- 400 + ( ( 0.117 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 634.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |       46 | 2025-02-25 | KZG                         | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.164 (0.023)    | 0 (0.000) |    14.57 | BaN4na, Freeman, Oath, Terryyy, viridian |
|           23 |       49 | 2025-02-25 | Vantage Esports             | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.336 (0.048)    | 0 (0.000) |    17.44 | BaN4na, Freeman, Oath, Terryyy, viridian |
|           22 |       67 | 2025-02-24 | Justice For Tomorrow        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.425 (0.061)    | 0 (0.000) |    17.41 | BaN4na, Freeman, Oath, Terryyy, viridian |
|           21 |       83 | 2025-02-24 | SemperFi Esports            | L   | 1.000      | -            | -                | -                | -         |   -11.55 | BaN4na, Freeman, Oath, Terryyy, viridian |
|           20 |      660 | 2025-02-08 | Shika                       | L   | 1.000      | -            | -                | -                | -         |   -17.23 | BaN4na, neo, Oath, Terryyy, viridian     |
|           19 |      740 | 2025-02-07 | Gods Reign                  | L   | 1.000      | -            | -                | -                | -         |    -6.50 | BaN4na, neo, Oath, Terryyy, viridian     |
|           18 |     4920 | 2024-10-18 | Housebets                   | L   | 0.295      | -            | -                | -                | -         |    -4.88 | BaN4na, neo, Oath, Terryyy, viridian     |
|           17 |     4970 | 2024-10-17 | Mindfreak (Australian team) | L   | 0.289      | -            | -                | -                | -         |    -3.64 | BaN4na, neo, Oath, Terryyy, viridian     |
|           16 |     5376 | 2024-10-09 | MANTRA                      | W   | 0.236      | 0.333        | 0.000 (0.000)    | 0.174 (0.014)    | 0 (0.000) |     3.34 | BaN4na, neo, Oath, Terryyy, viridian     |
|           15 |     5380 | 2024-10-09 | MANTRA                      | W   | 0.236      | 0.333        | 0.000 (0.000)    | 0.174 (0.014)    | 0 (0.000) |     3.41 | BaN4na, neo, Oath, Terryyy, viridian     |
|           14 |     5561 | 2024-10-05 | SemperFi Esports            | L   | 0.215      | -            | -                | -                | -         |    -4.15 | BaN4na, neo, Oath, Terryyy, viridian     |
|           13 |     5562 | 2024-10-05 | Mindfreak (Australian team) | W   | 0.214      | 0.143        | 0.002 (0.000)    | 0.091 (0.003)    | 0 (0.000) |     4.00 | BaN4na, neo, Oath, Terryyy, viridian     |
|           12 |     5565 | 2024-10-05 | Vantage Esports             | W   | 0.213      | 0.143        | 0.003 (0.000)    | 0.336 (0.010)    | 0 (0.000) |     3.51 | BaN4na, neo, Oath, Terryyy, viridian     |
|           11 |     5644 | 2024-10-04 | Housebets                   | W   | 0.208      | 0.143        | 0.001 (0.000)    | 0.122 (0.004)    | 0 (0.000) |     3.18 | BaN4na, neo, Oath, Terryyy, viridian     |
|           10 |     5650 | 2024-10-04 | Rebound                     | W   | 0.208      | -            | -                | -                | 0 (0.000) |     2.16 | BaN4na, neo, Oath, Terryyy, viridian     |
|            9 |     5654 | 2024-10-04 | Vantage Esports             | L   | 0.207      | -            | -                | -                | -         |    -3.09 | BaN4na, neo, Oath, Terryyy, viridian     |
|            8 |     5808 | 2024-10-02 | DXA Esports                 | L   | 0.189      | -            | -                | -                | -         |    -3.32 | BaN4na, neo, Oath, Terryyy, viridian     |
|            7 |     5810 | 2024-10-02 | DXA Esports                 | W   | 0.189      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     2.67 | BaN4na, neo, Oath, Terryyy, viridian     |
|            6 |     6166 | 2024-09-27 | FlyQuest                    | L   | 0.156      | -            | -                | -                | -         |    -0.34 | BaN4na, neo, Oath, Terryyy, viridian     |
|            5 |     6168 | 2024-09-27 | FlyQuest                    | L   | 0.156      | -            | -                | -                | -         |    -0.34 | BaN4na, neo, Oath, Terryyy, viridian     |
|            4 |     6331 | 2024-09-25 | Mindfreak (Australian team) | L   | 0.143      | -            | -                | -                | -         |    -1.84 | BaN4na, neo, Oath, Terryyy, viridian     |
|            3 |     6337 | 2024-09-25 | Mindfreak (Australian team) | W   | 0.142      | 0.333        | 0.002 (0.000)    | 0.091 (0.004)    | -         |     2.68 | BaN4na, neo, Oath, Terryyy, viridian     |
|            2 |     6961 | 2024-09-15 | KZG                         | W   | 0.076      | 0.333        | -                | 0.164 (0.004)    | -         |     1.17 | BaN4na, neo, Oath, Terryyy, viridian     |
|            1 |     6966 | 2024-09-15 | KZG                         | L   | 0.076      | -            | -                | -                | -         |    -1.23 | BaN4na, neo, Oath, Terryyy, viridian     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($323.60)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.308 | $1,050.00      | $323.60         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
