### Roster Details<br />
Team Name: Case Esports<br />
Roster: bsd, nyezin, RICIOLI, urban0, yepz<br />
Global Rank: [227](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [42]( ../standings_americas.md)<br />
<br />
Final Rank Value:  689.6<br />
<br />
Final Rank Value (689.6) = Starting Rank Value (682.9) + Head To Head Adjustments (6.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.273[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 682.9
- 400 + ( ( 0.142 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 682.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |     3519 | 2024-11-13 | RED Canids                                | L   | 0.477      | -            | -                | -                | -         |    -4.41 | bsd, nyezin, RICIOLI, urban0, yepz |
|           21 |     3559 | 2024-11-12 | FURIA                                     | L   | 0.471      | -            | -                | -                | -         |    -0.22 | bsd, nyezin, RICIOLI, urban0, yepz |
|           20 |     3573 | 2024-11-11 | Imperial Esports                          | L   | 0.470      | -            | -                | -                | -         |    -2.37 | bsd, nyezin, RICIOLI, urban0, yepz |
|           19 |     3626 | 2024-11-11 | Copenhagen Wolves (American organization) | L   | 0.465      | -            | -                | -                | -         |    -4.41 | bsd, nyezin, RICIOLI, urban0, yepz |
|           18 |     3741 | 2024-11-09 | Viperio                                   | L   | 0.452      | -            | -                | -                | -         |    -6.44 | bsd, nyezin, RICIOLI, urban0, yepz |
|           17 |     3853 | 2024-11-07 | ALASKA                                    | W   | 0.438      | 0.333        | 0.030 (0.004)    | 0.875 (0.128)    | 0 (0.000) |    12.21 | bsd, nyezin, RICIOLI, urban0, yepz |
|           16 |     4023 | 2024-11-04 | Illuminar Gaming                          | L   | 0.417      | -            | -                | -                | -         |    -3.87 | bsd, nyezin, RICIOLI, urban0, yepz |
|           15 |     4258 | 2024-10-31 | ALASKA                                    | W   | 0.392      | 0.333        | 0.030 (0.004)    | 0.875 (0.114)    | 0 (0.000) |    11.07 | bsd, nyezin, RICIOLI, urban0, yepz |
|           14 |     5038 | 2024-10-15 | Sharks Esports                            | L   | 0.287      | -            | -                | -                | -         |    -1.21 | bsd, nyezin, RICIOLI, urban0, yepz |
|           13 |     5318 | 2024-10-09 | Hype Esports                              | W   | 0.248      | 0.450        | 0.001 (0.000)    | 0.070 (0.008)    | 0 (0.000) |     3.83 | bsd, nyezin, RICIOLI, urban0, yepz |
|           12 |     5326 | 2024-10-09 | Hype Esports                              | L   | 0.247      | -            | -                | -                | -         |    -4.04 | bsd, nyezin, RICIOLI, urban0, yepz |
|           11 |     5392 | 2024-10-08 | Sharks Esports                            | L   | 0.241      | -            | -                | -                | -         |    -1.03 | bsd, nyezin, RICIOLI, urban0, yepz |
|           10 |     5403 | 2024-10-08 | Sharks Esports                            | L   | 0.241      | -            | -                | -                | -         |    -1.04 | bsd, nyezin, RICIOLI, urban0, yepz |
|            9 |     5761 | 2024-10-02 | BESTIA                                    | L   | 0.200      | -            | -                | -                | -         |    -1.35 | bsd, nyezin, RICIOLI, urban0, yepz |
|            8 |     5766 | 2024-10-02 | BESTIA                                    | L   | 0.200      | -            | -                | -                | -         |    -1.37 | bsd, nyezin, RICIOLI, urban0, yepz |
|            7 |     5818 | 2024-10-01 | MIBR                                      | L   | 0.195      | -            | -                | -                | -         |    -0.10 | bsd, nyezin, RICIOLI, urban0, yepz |
|            6 |     5822 | 2024-10-01 | MIBR                                      | W   | 0.194      | 0.450        | 0.141 (0.012)    | 0.471 (0.041)    | 0 (0.000) |     6.03 | bsd, nyezin, RICIOLI, urban0, yepz |
|            5 |     6086 | 2024-09-27 | Team Solid                                | L   | 0.168      | -            | -                | -                | -         |    -1.62 | bsd, nyezin, RICIOLI, urban0, yepz |
|            4 |     6096 | 2024-09-27 | Bad News Chickens                         | W   | 0.168      | 0.143        | 0.003 (0.000)    | 0.239 (0.006)    | 0 (0.000) |     2.65 | bsd, nyezin, RICIOLI, urban0, yepz |
|            3 |     6177 | 2024-09-26 | UNO MILLE                                 | W   | 0.161      | 0.143        | 0.010 (0.000)    | 0.526 (0.012)    | 0 (0.000) |     2.92 | bsd, nyezin, RICIOLI, urban0, yepz |
|            2 |     6282 | 2024-09-25 | Dusty Roots                               | W   | 0.153      | 0.450        | 0.008 (0.001)    | 0.371 (0.026)    | 0 (0.000) |     3.14 | bsd, nyezin, RICIOLI, urban0, yepz |
|            1 |     6286 | 2024-09-25 | Dusty Roots                               | L   | 0.153      | -            | -                | -                | -         |    -1.70 | bsd, nyezin, RICIOLI, urban0, yepz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($480.21)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.320 | $1,500.00      | $480.21         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
