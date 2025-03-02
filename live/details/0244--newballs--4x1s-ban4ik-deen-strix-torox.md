### Roster Details<br />
Team Name: NewBALLS<br />
Roster: 4X1s, Ban4ik, deeN, strix, torox<br />
Global Rank: [244](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [173]( ../standings_europe.md)<br />
<br />
Final Rank Value:  680.9<br />
<br />
Final Rank Value (680.9) = Starting Rank Value (659.9) + Head To Head Adjustments (21.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 659.9
- 400 + ( ( 0.130 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 659.9


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
|           27 |      360 | 2025-02-16 | K27                          | L   | 1.000      | -            | -                | -                | -         |   -11.85 | 4X1s, Ban4ik, deeN, strix, torox |
|           26 |      878 | 2025-02-05 | VP.Prodigy                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.206 (0.029)    | 0 (0.000) |     7.51 | 4X1s, Ban4ik, deeN, strix, torox |
|           25 |      881 | 2025-02-05 | K27                          | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.776 (0.111)    | 0 (0.000) |    21.62 | 4X1s, Ban4ik, deeN, strix, torox |
|           24 |     2001 | 2024-12-08 | XPERION NXT                  | L   | 0.646      | -            | -                | -                | -         |   -10.58 | 4X1s, Alv, deeN, strix, torox    |
|           23 |     2088 | 2024-12-07 | 777 Esports                  | W   | 0.639      | 0.333        | 0.002 (0.001)    | 0.239 (0.051)    | 0 (0.000) |     9.51 | 4X1s, Alv, deeN, strix, torox    |
|           22 |     2219 | 2024-12-04 | Dragon Esports Club          | W   | 0.620      | 0.333        | 0.007 (0.001)    | 0.312 (0.064)    | 0 (0.000) |    10.65 | 4X1s, Alv, deeN, strix, torox    |
|           21 |     2334 | 2024-12-02 | VOID GAMING (Russian team)   | W   | 0.607      | 0.333        | 0.000 (0.000)    | 0.028 (0.006)    | 0 (0.000) |     4.82 | 4X1s, Alv, deeN, strix, torox    |
|           20 |     2420 | 2024-12-01 | Insilio                      | L   | 0.600      | -            | -                | -                | -         |    -9.77 | 4X1s, Alv, deeN, strix, torox    |
|           19 |     2495 | 2024-11-30 | CASTA                        | W   | 0.594      | -            | -                | -                | 0 (0.000) |     3.47 | 4X1s, Alv, deeN, strix, torox    |
|           18 |     2612 | 2024-11-28 | GardenGarage                 | L   | 0.580      | -            | -                | -                | -         |    -6.93 | 4X1s, Alv, deeN, strix, torox    |
|           17 |     4076 | 2024-11-03 | 9INE                         | L   | 0.411      | -            | -                | -                | -         |    -4.17 | 4X1s, Alv, deeN, strix, torox    |
|           16 |     4211 | 2024-11-01 | ARCRED                       | W   | 0.398      | 0.384        | 0.018 (0.003)    | 0.484 (0.074)    | 0 (0.000) |     8.32 | 4X1s, Alv, deeN, strix, torox    |
|           15 |     4624 | 2024-10-24 | RUSH B (Russian team)        | L   | 0.345      | -            | -                | -                | -         |    -2.44 | 4X1s, Alv, deeN, strix, torox    |
|           14 |     4629 | 2024-10-24 | Endpoint                     | L   | 0.344      | -            | -                | -                | -         |    -3.64 | 4X1s, Alv, deeN, strix, torox    |
|           13 |     4708 | 2024-10-22 | K27                          | L   | 0.332      | -            | -                | -                | -         |    -2.08 | 4X1s, Alv, deeN, strix, torox    |
|           12 |     4902 | 2024-10-18 | GameAgents                   | W   | 0.304      | 0.384        | 0.003 (0.000)    | 0.119 (0.014)    | 0 (0.000) |     5.08 | 4X1s, Alv, deeN, strix, torox    |
|           11 |     5205 | 2024-10-12 | 9Pandas                      | L   | 0.265      | -            | -                | -                | -         |    -1.22 | 4X1s, Alv, deeN, strix, torox    |
|           10 |     5901 | 2024-09-30 | G2 Ares                      | L   | 0.187      | -            | -                | -                | -         |    -2.73 | 4X1s, Alv, deeN, strix, torox    |
|            9 |     6507 | 2024-09-22 | CS2NEWS                      | W   | 0.133      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.47 | 4X1s, Alv, deeN, strix, torox    |
|            8 |     6519 | 2024-09-22 | Flame Sharks                 | W   | 0.132      | 0.143        | 0.000 (0.000)    | 0.170 (0.003)    | 0 (0.000) |     2.00 | 4X1s, Alv, deeN, strix, torox    |
|            7 |     6570 | 2024-09-21 | Xdclan                       | W   | 0.126      | -            | -                | -                | -         |     0.75 | 4X1s, Alv, deeN, strix, torox    |
|            6 |     6998 | 2024-09-14 | FLuffy Gangsters             | L   | 0.079      | -            | -                | -                | -         |    -0.79 | 4X1s, Alv, deeN, strix, torox    |
|            5 |     7004 | 2024-09-14 | EC BANGA                     | W   | 0.079      | 0.215        | -                | 0.054 (0.001)    | -         |     0.71 | 4X1s, Alv, deeN, strix, torox    |
|            4 |     7013 | 2024-09-14 | LookingForOrg (Turkish team) | W   | 0.078      | -            | -                | -                | -         |     0.47 | 4X1s, Alv, deeN, strix, torox    |
|            3 |     7019 | 2024-09-14 | 500 Rush                     | W   | 0.078      | 0.215        | 0.002 (0.000)    | 0.146 (0.002)    | -         |     1.18 | 4X1s, Alv, deeN, strix, torox    |
|            2 |     7427 | 2024-09-07 | Grannys Knockers             | L   | 0.032      | -            | -                | -                | -         |    -0.57 | 4X1s, Alv, deeN, strix, torox    |
|            1 |     7443 | 2024-09-07 | Naaaa                        | W   | 0.032      | -            | -                | -                | -         |     0.19 | 4X1s, Alv, deeN, strix, torox    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($301.54)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.413 | $715.22        | $295.62         |
| 2024-09-14 |      0.079 | $75.00         | $5.91           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
