### Roster Details<br />
Team Name: Team Space<br />
Roster: Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V<br />
Global Rank: [517](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [322]( ../standings_europe.md)<br />
<br />
Final Rank Value:  497.9<br />
<br />
Final Rank Value (497.9) = Starting Rank Value (492.3) + Head To Head Adjustments (5.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.183[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.046<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 492.3
- 400 + ( ( 0.046 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 492.3


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
|           19 |     5921 | 2024-09-30 | Insilio                                   | L   | 0.185      | -            | -                | -                | -         |    -1.40 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           18 |     6150 | 2024-09-27 | EYEBALLERS                                | L   | 0.164      | -            | -                | -                | -         |    -0.82 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           17 |     6194 | 2024-09-26 | Nexus Gaming                              | L   | 0.159      | -            | -                | -                | -         |    -0.11 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           16 |     6517 | 2024-09-22 | Copenhagen Wolves (American organization) | L   | 0.132      | -            | -                | -                | -         |    -1.81 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           15 |     6527 | 2024-09-22 | Revenant Esports                          | W   | 0.131      | 0.384        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     2.09 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           14 |     6646 | 2024-09-20 | Ex-ENTERPRISE esports                     | W   | 0.118      | 0.384        | 0.003 (0.000)    | 0.085 (0.004)    | 0 (0.000) |     2.89 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           13 |     6765 | 2024-09-18 | QUAZAR                                    | W   | 0.106      | 0.143        | 0.005 (0.000)    | 0.257 (0.004)    | 0 (0.000) |     2.57 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           12 |     6845 | 2024-09-17 | Rhyno Esports                             | W   | 0.098      | 0.143        | 0.002 (0.000)    | 0.084 (0.001)    | 0 (0.000) |     2.27 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           11 |     7088 | 2024-09-13 | GUN5 Esports                              | L   | 0.072      | -            | -                | -                | -         |    -0.18 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|           10 |     7095 | 2024-09-13 | FLuffy Gangsters                          | L   | 0.072      | -            | -                | -                | -         |    -0.35 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            9 |     7240 | 2024-09-10 | Monte                                     | L   | 0.053      | -            | -                | -                | -         |    -0.14 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            8 |     7291 | 2024-09-09 | FLuffy Gangsters                          | W   | 0.046      | 0.143        | 0.014 (0.000)    | 0.925 (0.006)    | 0 (0.000) |     1.23 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            7 |     7512 | 2024-09-06 | Insilio                                   | L   | 0.026      | -            | -                | -                | -         |    -0.20 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            6 |     7533 | 2024-09-06 | Los kogutos                               | L   | 0.024      | -            | -                | -                | -         |    -0.04 | Chill, danistzz, H4SAN4TOR, TruNiQ, X5G7V |
|            5 |     7539 | 2024-09-06 | Rhyno Esports                             | L   | 0.024      | -            | -                | -                | -         |    -0.20 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            4 |     7579 | 2024-09-05 | GameAgents                                | L   | 0.020      | -            | -                | -                | -         |    -0.16 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            3 |     7681 | 2024-09-04 | FAVBET Team                               | L   | 0.011      | -            | -                | -                | -         |    -0.04 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            2 |     7726 | 2024-09-03 | Insilio                                   | L   | 0.006      | -            | -                | -                | -         |    -0.05 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|            1 |     7745 | 2024-09-03 | Los kogutos                               | L   | 0.005      | -            | -                | -                | -         |    -0.01 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
