### Roster Details<br />
Team Name: Devils.one<br />
Roster: baljs, fanatyk, Frontsiderr, PeTeRoOo, suonko<br />
Global Rank: [306](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [205]( ../standings_europe.md)<br />
<br />
Final Rank Value:  645.2<br />
<br />
Final Rank Value (645.2) = Starting Rank Value (650.0) + Head To Head Adjustments (-4.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.246[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 650.0
- 400 + ( ( 0.125 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 650.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     3900 | 2024-11-06 | 777 Esports                 | L   | 0.432      | -            | -                | -                | -         |    -6.38 | baljs, fanatyk, Frontsiderr, PeTeRoOo, suonko     |
|           24 |     4156 | 2024-11-02 | Leo Team                    | L   | 0.404      | -            | -                | -                | -         |    -3.52 | baljs, fanatyk, Frontsiderr, PeTeRoOo, suonko     |
|           23 |     4350 | 2024-10-29 | Kyoto (European mix-team)   | L   | 0.381      | -            | -                | -                | -         |    -5.67 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           22 |     4993 | 2024-10-16 | Team Czech Republic         | L   | 0.293      | -            | -                | -                | -         |    -3.92 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           21 |     5067 | 2024-10-15 | ENTERPRISE Genesis          | W   | 0.286      | 0.143        | 0.001 (0.000)    | 0.178 (0.007)    | 0 (0.000) |     4.21 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           20 |     5099 | 2024-10-14 | Kyoto (European mix-team)   | L   | 0.280      | -            | -                | -                | -         |    -4.27 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           19 |     5110 | 2024-10-14 | KUUSAMO.gg                  | W   | 0.279      | 0.278        | -                | 0.164 (0.013)    | 0 (0.000) |     2.62 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           18 |     5131 | 2024-10-13 | XI Esport                   | L   | 0.273      | -            | -                | -                | -         |    -6.02 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           17 |     5427 | 2024-10-08 | 777 Esports                 | W   | 0.239      | 0.278        | 0.002 (0.000)    | 0.239 (0.016)    | 0 (0.000) |     3.66 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           16 |     5582 | 2024-10-05 | ENTERPRISE Genesis          | W   | 0.219      | 0.278        | 0.001 (0.000)    | 0.178 (0.011)    | 0 (0.000) |     3.25 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           15 |     5905 | 2024-09-30 | GardenGarage                | L   | 0.186      | -            | -                | -                | -         |    -2.25 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           14 |     5971 | 2024-09-29 | Los kogutos                 | W   | 0.178      | 0.143        | 0.032 (0.001)    | 0.527 (0.013)    | 0 (0.000) |     4.87 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           13 |     6364 | 2024-09-24 | Dynamo Eclot                | L   | 0.146      | -            | -                | -                | -         |    -0.41 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           12 |     6382 | 2024-09-24 | Error404                    | W   | 0.146      | -            | -                | -                | 0 (0.000) |     0.88 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           11 |     6590 | 2024-09-21 | 9Pandas                     | L   | 0.125      | -            | -                | -                | -         |    -0.57 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|           10 |     6643 | 2024-09-20 | Johnny Speeds               | L   | 0.118      | -            | -                | -                | -         |    -0.77 | fanatyk, Frontsiderr, karmazynsz, Pelle, PeTeRoOo |
|            9 |     6700 | 2024-09-19 | BC.Game Esports             | W   | 0.112      | 0.443        | 0.077 (0.004)    | 0.945 (0.047)    | 0 (0.000) |     3.17 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            8 |     7011 | 2024-09-14 | 9INE                        | W   | 0.078      | 0.443        | 0.011 (0.000)    | 0.222 (0.008)    | 0 (0.000) |     1.59 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            7 |     7043 | 2024-09-14 | RUSH B (Russian team)       | W   | 0.077      | 0.443        | 0.028 (0.001)    | 0.921 (0.032)    | 0 (0.000) |     1.94 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            6 |     7228 | 2024-09-10 | Zero Tenacity               | W   | 0.054      | 0.143        | 0.028 (0.000)    | 0.692 (0.005)    | 0 (0.000) |     1.31 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|            5 |     7232 | 2024-09-10 | 500 Rush                    | W   | 0.053      | 0.143        | 0.002 (0.000)    | 0.146 (0.001)    | -         |     0.83 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|            4 |     7596 | 2024-09-05 | Sleepwalkers (Russian team) | W   | 0.019      | -            | -                | -                | -         |     0.12 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            3 |     7608 | 2024-09-05 | Iuhop (Russian team)        | W   | 0.019      | -            | -                | -                | -         |     0.17 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            2 |     7647 | 2024-09-04 | LEON Esports                | W   | 0.013      | 0.221        | 0.010 (0.000)    | -                | -         |     0.28 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            1 |     7651 | 2024-09-04 | 5goblinz                    | W   | 0.013      | -            | -                | -                | -         |     0.08 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($293.28)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-24 |      0.145 | $2,000.00      | $289.44         |
| 2024-09-05 |      0.019 | $200.00        | $3.83           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
