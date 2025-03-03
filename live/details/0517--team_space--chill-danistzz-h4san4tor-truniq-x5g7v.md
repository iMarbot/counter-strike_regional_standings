### Roster Details<br />
Team Name: Team Space<br />
Roster: Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V<br />
Global Rank: [517](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [321]( ../standings_europe.md)<br />
<br />
Final Rank Value:  496.7<br />
<br />
Final Rank Value (496.7) = Starting Rank Value (491.5) + Head To Head Adjustments (5.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.182[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.046<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 491.5
- 400 + ( ( 0.046 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 491.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     5933 | 2024-09-30 | Insilio                                   | L   | 0.177      | -            | -                | -                | -         |    -1.36 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           16 |     6162 | 2024-09-27 | EYEBALLERS                                | L   | 0.156      | -            | -                | -                | -         |    -0.78 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           15 |     6206 | 2024-09-26 | Nexus Gaming                              | L   | 0.151      | -            | -                | -                | -         |    -0.11 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           14 |     6529 | 2024-09-22 | Copenhagen Wolves (American organization) | L   | 0.124      | -            | -                | -                | -         |    -1.71 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           13 |     6539 | 2024-09-22 | Revenant Esports                          | W   | 0.123      | 0.384        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     1.96 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           12 |     6658 | 2024-09-20 | Ex-ENTERPRISE esports                     | W   | 0.110      | 0.384        | 0.003 (0.000)    | 0.082 (0.003)    | 0 (0.000) |     2.69 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           11 |     6777 | 2024-09-18 | QUAZAR                                    | W   | 0.097      | 0.143        | 0.005 (0.000)    | 0.251 (0.003)    | 0 (0.000) |     2.37 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           10 |     6857 | 2024-09-17 | Rhyno Esports                             | W   | 0.090      | 0.143        | 0.002 (0.000)    | 0.080 (0.001)    | 0 (0.000) |     2.08 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|            9 |     7100 | 2024-09-13 | GUN5 Esports                              | L   | 0.064      | -            | -                | -                | -         |    -0.16 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|            8 |     7107 | 2024-09-13 | FLuffy Gangsters                          | L   | 0.063      | -            | -                | -                | -         |    -0.31 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            7 |     7252 | 2024-09-10 | Monte                                     | L   | 0.045      | -            | -                | -                | -         |    -0.12 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            6 |     7303 | 2024-09-09 | FLuffy Gangsters                          | W   | 0.038      | 0.143        | 0.014 (0.000)    | 0.909 (0.005)    | 0 (0.000) |     1.01 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            5 |     7524 | 2024-09-06 | Insilio                                   | L   | 0.018      | -            | -                | -                | -         |    -0.14 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            4 |     7545 | 2024-09-06 | Los kogutos                               | L   | 0.016      | -            | -                | -                | -         |    -0.03 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|            3 |     7551 | 2024-09-06 | Rhyno Esports                             | L   | 0.015      | -            | -                | -                | -         |    -0.13 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            2 |     7591 | 2024-09-05 | GameAgents                                | L   | 0.012      | -            | -                | -                | -         |    -0.09 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            1 |     7693 | 2024-09-04 | FAVBET Team                               | L   | 0.003      | -            | -                | -                | -         |    -0.01 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
