### Roster Details<br />
Team Name: Case Esports<br />
Roster: bsd, nyezin, RICIOLI, urban0, yepz<br />
Global Rank: [233](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  688.5<br />
<br />
Final Rank Value (688.5) = Starting Rank Value (682.2) + Head To Head Adjustments (6.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 682.2
- 400 + ( ( 0.141 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 682.2


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
|           22 |     3531 | 2024-11-13 | RED Canids                                | L   | 0.469      | -            | -                | -                | -         |    -4.38 | bsd, nyezin, RICIOLI, urban0, yepz |
|           21 |     3571 | 2024-11-12 | FURIA                                     | L   | 0.463      | -            | -                | -                | -         |    -0.22 | bsd, nyezin, RICIOLI, urban0, yepz |
|           20 |     3585 | 2024-11-11 | Imperial Esports                          | L   | 0.462      | -            | -                | -                | -         |    -2.35 | bsd, nyezin, RICIOLI, urban0, yepz |
|           19 |     3638 | 2024-11-11 | Copenhagen Wolves (American organization) | L   | 0.457      | -            | -                | -                | -         |    -4.32 | bsd, nyezin, RICIOLI, urban0, yepz |
|           18 |     3753 | 2024-11-09 | Viperio                                   | L   | 0.443      | -            | -                | -                | -         |    -6.35 | bsd, nyezin, RICIOLI, urban0, yepz |
|           17 |     3865 | 2024-11-07 | ALASKA                                    | W   | 0.430      | 0.333        | 0.031 (0.004)    | 0.867 (0.124)    | 0 (0.000) |    12.01 | bsd, nyezin, RICIOLI, urban0, yepz |
|           16 |     4035 | 2024-11-04 | Illuminar Gaming                          | L   | 0.409      | -            | -                | -                | -         |    -3.81 | bsd, nyezin, RICIOLI, urban0, yepz |
|           15 |     4270 | 2024-10-31 | ALASKA                                    | W   | 0.383      | 0.333        | 0.031 (0.004)    | 0.867 (0.111)    | 0 (0.000) |    10.86 | bsd, nyezin, RICIOLI, urban0, yepz |
|           14 |     5050 | 2024-10-15 | Sharks Esports                            | L   | 0.279      | -            | -                | -                | -         |    -1.16 | bsd, nyezin, RICIOLI, urban0, yepz |
|           13 |     5330 | 2024-10-09 | Hype Esports                              | W   | 0.240      | 0.450        | 0.001 (0.000)    | 0.067 (0.007)    | 0 (0.000) |     3.70 | bsd, nyezin, RICIOLI, urban0, yepz |
|           12 |     5338 | 2024-10-09 | Hype Esports                              | L   | 0.239      | -            | -                | -                | -         |    -3.91 | bsd, nyezin, RICIOLI, urban0, yepz |
|           11 |     5404 | 2024-10-08 | Sharks Esports                            | L   | 0.233      | -            | -                | -                | -         |    -0.98 | bsd, nyezin, RICIOLI, urban0, yepz |
|           10 |     5415 | 2024-10-08 | Sharks Esports                            | L   | 0.233      | -            | -                | -                | -         |    -0.99 | bsd, nyezin, RICIOLI, urban0, yepz |
|            9 |     5773 | 2024-10-02 | BESTIA                                    | L   | 0.192      | -            | -                | -                | -         |    -1.30 | bsd, nyezin, RICIOLI, urban0, yepz |
|            8 |     5778 | 2024-10-02 | BESTIA                                    | L   | 0.192      | -            | -                | -                | -         |    -1.32 | bsd, nyezin, RICIOLI, urban0, yepz |
|            7 |     5830 | 2024-10-01 | MIBR                                      | L   | 0.187      | -            | -                | -                | -         |    -0.09 | bsd, nyezin, RICIOLI, urban0, yepz |
|            6 |     5834 | 2024-10-01 | MIBR                                      | W   | 0.186      | 0.450        | 0.142 (0.012)    | 0.465 (0.039)    | 0 (0.000) |     5.78 | bsd, nyezin, RICIOLI, urban0, yepz |
|            5 |     6098 | 2024-09-27 | Team Solid                                | L   | 0.160      | -            | -                | -                | -         |    -1.54 | bsd, nyezin, RICIOLI, urban0, yepz |
|            4 |     6108 | 2024-09-27 | Bad News Chickens                         | W   | 0.159      | 0.143        | 0.002 (0.000)    | 0.234 (0.005)    | 0 (0.000) |     2.52 | bsd, nyezin, RICIOLI, urban0, yepz |
|            3 |     6189 | 2024-09-26 | UNO MILLE                                 | W   | 0.153      | 0.143        | 0.010 (0.000)    | 0.522 (0.011)    | 0 (0.000) |     2.78 | bsd, nyezin, RICIOLI, urban0, yepz |
|            2 |     6294 | 2024-09-25 | Dusty Roots                               | W   | 0.145      | 0.450        | 0.009 (0.001)    | 0.366 (0.024)    | 0 (0.000) |     2.97 | bsd, nyezin, RICIOLI, urban0, yepz |
|            1 |     6298 | 2024-09-25 | Dusty Roots                               | L   | 0.145      | -            | -                | -                | -         |    -1.61 | bsd, nyezin, RICIOLI, urban0, yepz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($467.92)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.312 | $1,500.00      | $467.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
