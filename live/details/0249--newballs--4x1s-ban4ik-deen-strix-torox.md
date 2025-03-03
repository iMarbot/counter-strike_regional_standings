### Roster Details<br />
Team Name: NewBALLS<br />
Roster: 4X1s, Ban4ik, deeN, strix, torox<br />
Global Rank: [249](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [173]( ../standings_europe.md)<br />
<br />
Final Rank Value:  680.4<br />
<br />
Final Rank Value (680.4) = Starting Rank Value (659.7) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 659.7
- 400 + ( ( 0.130 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 659.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |      372 | 2025-02-16 | K27                          | L   | 1.000      | -            | -                | -                | -         |   -11.81 | 4X1s, Ban4ik, deeN, strix, torox |
|           26 |      890 | 2025-02-05 | VP.Prodigy                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.204 (0.029)    | 0 (0.000) |     7.51 | 4X1s, Ban4ik, deeN, strix, torox |
|           25 |      893 | 2025-02-05 | K27                          | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.769 (0.110)    | 0 (0.000) |    21.67 | 4X1s, Ban4ik, deeN, strix, torox |
|           24 |     2013 | 2024-12-08 | XPERION NXT                  | L   | 0.638      | -            | -                | -                | -         |   -10.44 | 4X1s, Alv, deeN, strix, torox    |
|           23 |     2100 | 2024-12-07 | 777 Esports                  | W   | 0.631      | 0.333        | 0.002 (0.000)    | 0.235 (0.049)    | 0 (0.000) |     9.35 | 4X1s, Alv, deeN, strix, torox    |
|           22 |     2231 | 2024-12-04 | Dragon Esports Club          | W   | 0.612      | 0.333        | 0.007 (0.001)    | 0.309 (0.063)    | 0 (0.000) |    10.53 | 4X1s, Alv, deeN, strix, torox    |
|           21 |     2346 | 2024-12-02 | VOID GAMING (Russian team)   | W   | 0.598      | 0.333        | 0.000 (0.000)    | 0.027 (0.005)    | 0 (0.000) |     4.77 | 4X1s, Alv, deeN, strix, torox    |
|           20 |     2432 | 2024-12-01 | Insilio                      | L   | 0.592      | -            | -                | -                | -         |    -9.68 | 4X1s, Alv, deeN, strix, torox    |
|           19 |     2507 | 2024-11-30 | CASTA                        | W   | 0.585      | -            | -                | -                | 0 (0.000) |     3.43 | 4X1s, Alv, deeN, strix, torox    |
|           18 |     2624 | 2024-11-28 | GardenGarage                 | L   | 0.572      | -            | -                | -                | -         |    -6.83 | 4X1s, Alv, deeN, strix, torox    |
|           17 |     4088 | 2024-11-03 | 9INE                         | L   | 0.403      | -            | -                | -                | -         |    -4.14 | 4X1s, Alv, deeN, strix, torox    |
|           16 |     4223 | 2024-11-01 | ARCRED                       | W   | 0.390      | 0.384        | 0.018 (0.003)    | 0.480 (0.072)    | 0 (0.000) |     8.14 | 4X1s, Alv, deeN, strix, torox    |
|           15 |     4636 | 2024-10-24 | RUSH B (Russian team)        | L   | 0.337      | -            | -                | -                | -         |    -2.38 | 4X1s, Alv, deeN, strix, torox    |
|           14 |     4641 | 2024-10-24 | Endpoint                     | L   | 0.336      | -            | -                | -                | -         |    -3.56 | 4X1s, Alv, deeN, strix, torox    |
|           13 |     4720 | 2024-10-22 | K27                          | L   | 0.324      | -            | -                | -                | -         |    -2.02 | 4X1s, Alv, deeN, strix, torox    |
|           12 |     4914 | 2024-10-18 | GameAgents                   | W   | 0.296      | 0.384        | 0.003 (0.000)    | 0.111 (0.013)    | 0 (0.000) |     4.90 | 4X1s, Alv, deeN, strix, torox    |
|           11 |     5217 | 2024-10-12 | 9Pandas                      | L   | 0.257      | -            | -                | -                | -         |    -1.19 | 4X1s, Alv, deeN, strix, torox    |
|           10 |     5913 | 2024-09-30 | G2 Ares                      | L   | 0.178      | -            | -                | -                | -         |    -2.61 | 4X1s, Alv, deeN, strix, torox    |
|            9 |     6519 | 2024-09-22 | CS2NEWS                      | W   | 0.125      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.38 | 4X1s, Alv, deeN, strix, torox    |
|            8 |     6531 | 2024-09-22 | Flame Sharks                 | W   | 0.124      | 0.143        | 0.000 (0.000)    | 0.167 (0.003)    | 0 (0.000) |     1.88 | 4X1s, Alv, deeN, strix, torox    |
|            7 |     6582 | 2024-09-21 | Xdclan                       | W   | 0.118      | -            | -                | -                | -         |     0.70 | 4X1s, Alv, deeN, strix, torox    |
|            6 |     7010 | 2024-09-14 | FLuffy Gangsters             | L   | 0.071      | -            | -                | -                | -         |    -0.72 | 4X1s, Alv, deeN, strix, torox    |
|            5 |     7016 | 2024-09-14 | EC BANGA                     | W   | 0.071      | 0.215        | -                | 0.052 (0.001)    | -         |     0.64 | 4X1s, Alv, deeN, strix, torox    |
|            4 |     7025 | 2024-09-14 | LookingForOrg (Turkish team) | W   | 0.070      | -            | -                | -                | -         |     0.42 | 4X1s, Alv, deeN, strix, torox    |
|            3 |     7031 | 2024-09-14 | 500 Rush                     | W   | 0.070      | 0.215        | 0.002 (0.000)    | 0.141 (0.002)    | -         |     1.05 | 4X1s, Alv, deeN, strix, torox    |
|            2 |     7439 | 2024-09-07 | Grannys Knockers             | L   | 0.024      | -            | -                | -                | -         |    -0.42 | 4X1s, Alv, deeN, strix, torox    |
|            1 |     7455 | 2024-09-07 | Naaaa                        | W   | 0.024      | -            | -                | -                | -         |     0.14 | 4X1s, Alv, deeN, strix, torox    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($295.06)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.405 | $715.22        | $289.76         |
| 2024-09-14 |      0.071 | $75.00         | $5.30           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
