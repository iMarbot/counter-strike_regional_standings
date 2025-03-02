### Roster Details<br />
Team Name: ROUNDS<br />
Roster: foqu, Kollo, m0n0xx, p12, Villeboe<br />
Global Rank: [552](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [342]( ../standings_europe.md)<br />
<br />
Final Rank Value:  476.8<br />
<br />
Final Rank Value (476.8) = Starting Rank Value (526.2) + Head To Head Adjustments (-49.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 526.2
- 400 + ( ( 0.063 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 526.2


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
|           20 |     1164 | 2025-01-18 | Ex-UHKA eSports                           | L   | 0.919      | -            | -                | -                | -         |   -12.28 | foqu, Kollo, m0n0xx, p12, Villeboe |
|           19 |     1172 | 2025-01-17 | Team yaNgile                              | L   | 0.913      | -            | -                | -                | -         |   -17.95 | foqu, Kollo, m0n0xx, p12, Villeboe |
|           18 |     2969 | 2024-11-22 | Los kogutos                               | W   | 0.539      | 0.372        | 0.032 (0.006)    | 0.527 (0.106)    | 0 (0.000) |    15.44 | foqu, Kollo, p12, p3kko, Villeboe  |
|           17 |     3035 | 2024-11-21 | The Suspect                               | L   | 0.532      | -            | -                | -                | -         |    -3.61 | foqu, Kollo, p12, p3kko, Villeboe  |
|           16 |     3092 | 2024-11-20 | Infinite Gaming                           | L   | 0.527      | -            | -                | -                | -         |    -8.22 | foqu, Kollo, p12, p3kko, Villeboe  |
|           15 |     3153 | 2024-11-19 | Ex-RUBY                                   | L   | 0.520      | -            | -                | -                | -         |    -7.15 | foqu, Kollo, p12, p3kko, Villeboe  |
|           14 |     3494 | 2024-11-13 | ADEPTS                                    | L   | 0.480      | -            | -                | -                | -         |    -4.11 | foqu, Kollo, p12, p3kko, Villeboe  |
|           13 |     3542 | 2024-11-12 | HyperSpirit                               | L   | 0.473      | -            | -                | -                | -         |    -4.70 | foqu, Kollo, p12, p3kko, Villeboe  |
|           12 |     3656 | 2024-11-10 | Metizport X                               | L   | 0.460      | -            | -                | -                | -         |    -4.69 | foqu, Kollo, p12, p3kko, Villeboe  |
|           11 |     3831 | 2024-11-07 | Anonymo Esports                           | W   | 0.440      | 0.372        | 0.000 (0.000)    | 0.101 (0.017)    | 0 (0.000) |     7.64 | foqu, Kollo, p12, p3kko, Villeboe  |
|           10 |     3893 | 2024-11-06 | GamerLegion Academy                       | L   | 0.432      | -            | -                | -                | -         |    -5.88 | foqu, Kollo, p12, p3kko, Villeboe  |
|            9 |     4006 | 2024-11-04 | Kubix Esports                             | L   | 0.419      | -            | -                | -                | -         |    -1.26 | foqu, Kollo, p12, p3kko, Villeboe  |
|            8 |     4357 | 2024-10-29 | FORZE Reload                              | L   | 0.380      | -            | -                | -                | -         |    -1.57 | foqu, Kollo, p12, p3kko, Villeboe  |
|            7 |     4424 | 2024-10-28 | ALTERNATE aTTaX                           | L   | 0.373      | -            | -                | -                | -         |    -1.22 | foqu, Kollo, p12, p3kko, Villeboe  |
|            6 |     4726 | 2024-10-21 | PCIFIC Espor                              | L   | 0.326      | -            | -                | -                | -         |    -2.13 | foqu, Kollo, p12, p3kko, Villeboe  |
|            5 |     4774 | 2024-10-20 | ARCRED                                    | L   | 0.320      | -            | -                | -                | -         |    -2.29 | foqu, Kollo, p12, p3kko, Villeboe  |
|            4 |     4783 | 2024-10-20 | Ins (Polish team)                         | W   | 0.319      | 0.143        | 0.004 (0.000)    | 0.280 (0.013)    | 0 (0.000) |     7.15 | foqu, Kollo, p12, p3kko, Villeboe  |
|            3 |     5000 | 2024-10-16 | Fire Flux Esports                         | L   | 0.292      | -            | -                | -                | -         |    -1.13 | foqu, Kollo, p12, p3kko, Villeboe  |
|            2 |     5072 | 2024-10-15 | Copenhagen Wolves (American organization) | L   | 0.285      | -            | -                | -                | -         |    -1.24 | foqu, Kollo, p12, p3kko, Villeboe  |
|            1 |     5344 | 2024-10-09 | ALASKA                                    | L   | 0.246      | -            | -                | -                | -         |    -0.25 | foqu, Kollo, p12, p3kko, Villeboe  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
