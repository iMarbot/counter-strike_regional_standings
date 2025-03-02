### Roster Details<br />
Team Name: UNO MILLE<br />
Roster: bnc, Leomonster, realz1n, rem1x, zmb<br />
Global Rank: [143](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [28]( ../standings_americas.md)<br />
<br />
Final Rank Value:  769.9<br />
<br />
Final Rank Value (769.9) = Starting Rank Value (740.4) + Head To Head Adjustments (29.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 740.4
- 400 + ( ( 0.170 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 740.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      225 | 2025-02-20 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |    -6.68 | bnc, Leomonster, realz1n, rem1x, zmb |
|           45 |      326 | 2025-02-16 | ShindeN                | W   | 1.000      | 0.371        | 0.005 (0.002)    | 0.310 (0.115)    | 0 (0.000) |    13.23 | bnc, Leomonster, realz1n, rem1x, zmb |
|           44 |      452 | 2025-02-14 | ODDIK                  | L   | 1.000      | -            | -                | -                | -         |   -11.11 | bnc, Leomonster, realz1n, rem1x, zmb |
|           43 |      528 | 2025-02-12 | KRÜ Esports            | W   | 1.000      | 0.371        | 0.001 (0.001)    | -                | 0 (0.000) |    11.98 | bnc, Leomonster, realz1n, rem1x, zmb |
|           42 |      569 | 2025-02-10 | Bounty Hunters Esports | W   | 1.000      | 0.371        | 0.005 (0.002)    | 0.524 (0.194)    | 0 (0.000) |    15.58 | bnc, Leomonster, realz1n, rem1x, zmb |
|           41 |      741 | 2025-02-07 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |    -8.43 | bnc, Leomonster, realz1n, rem1x, zmb |
|           40 |      927 | 2025-02-04 | Familia Maquininha     | L   | 1.000      | -            | -                | -                | -         |   -18.23 | bnc, Leomonster, realz1n, rem1x, zmb |
|           39 |      939 | 2025-02-04 | América eSports        | W   | 1.000      | 0.143        | -                | 0.429 (0.061)    | 0 (0.000) |     8.55 | bnc, Leomonster, realz1n, rem1x, zmb |
|           38 |     1206 | 2025-01-09 | Team Solid             | L   | 0.860      | -            | -                | -                | -         |    -9.92 | bnc, max, realz1n, rem1x, zmb        |
|           37 |     1495 | 2024-12-20 | Patins da Ferrari      | W   | 0.727      | -            | -                | -                | 0 (0.000) |     5.22 | bnc, max, realz1n, rem1x, zmb        |
|           36 |     1554 | 2024-12-18 | Nitro.GG               | W   | 0.712      | 0.384        | 0.002 (0.000)    | 0.518 (0.142)    | 0 (0.000) |     8.30 | bnc, max, realz1n, rem1x, zmb        |
|           35 |     1579 | 2024-12-16 | Bad News Chickens      | L   | 0.701      | -            | -                | -                | -         |   -13.47 | bnc, max, realz1n, rem1x, zmb        |
|           34 |     1759 | 2024-12-13 | Galorys Academy        | W   | 0.681      | -            | -                | -                | 0 (0.000) |     5.81 | bnc, max, realz1n, rem1x, zmb        |
|           33 |     1948 | 2024-12-09 | Game Hunters           | W   | 0.653      | 0.262        | 0.002 (0.000)    | 0.396 (0.068)    | 0 (0.000) |     9.73 | lukiz, pancc, realz1n, rem1x, zmb    |
|           32 |     1991 | 2024-12-08 | Yawara E-Sports        | W   | 0.647      | 0.262        | -                | 0.454 (0.077)    | 0 (0.000) |     8.73 | lukiz, pancc, realz1n, rem1x, zmb    |
|           31 |     2264 | 2024-12-03 | Game Hunters           | L   | 0.613      | -            | -                | -                | -         |   -10.16 | lukiz, pancc, realz1n, rem1x, zmb    |
|           30 |     2314 | 2024-12-02 | DB Peek Esports        | W   | 0.608      | -            | -                | -                | 0 (0.000) |     6.49 | lukiz, pancc, realz1n, rem1x, zmb    |
|           29 |     2507 | 2024-11-30 | Yawara E-Sports        | W   | 0.593      | 0.262        | -                | 0.454 (0.070)    | -         |     8.25 | lukiz, pancc, realz1n, rem1x, zmb    |
|           28 |     2663 | 2024-11-27 | Nitro.GG               | L   | 0.573      | -            | -                | -                | -         |   -10.50 | lukiz, pancc, realz1n, rem1x, zmb    |
|           27 |     3837 | 2024-11-07 | ODDIK                  | L   | 0.440      | -            | -                | -                | -         |    -5.34 | lukiz, pancc, realz1n, rem1x, zmb    |
|           26 |     3909 | 2024-11-05 | Galorys Academy        | W   | 0.429      | -            | -                | -                | -         |     4.16 | lukiz, pancc, realz1n, rem1x, zmb    |
|           25 |     3967 | 2024-11-04 | Floripa Stars          | W   | 0.421      | -            | -                | -                | -         |     5.21 | lukiz, pancc, realz1n, rem1x, zmb    |
|           24 |     3969 | 2024-11-04 | Intense Game           | W   | 0.421      | -            | -                | -                | -         |     5.58 | lukiz, pancc, realz1n, rem1x, zmb    |
|           23 |     4029 | 2024-11-03 | ODDIK                  | W   | 0.414      | 0.143        | 0.028 (0.002)    | -                | -         |     8.22 | lukiz, pancc, realz1n, rem1x, zmb    |
|           22 |     4039 | 2024-11-03 | RED Canids Academy     | W   | 0.413      | 0.333        | 0.005 (0.001)    | -                | -         |     6.11 | lukiz, pancc, realz1n, rem1x, zmb    |
|           21 |     4096 | 2024-11-02 | TROPA DO TACO          | L   | 0.408      | -            | -                | -                | -         |    -6.67 | lukiz, pancc, realz1n, rem1x, zmb    |
|           20 |     4099 | 2024-11-02 | Team Solid             | L   | 0.408      | -            | -                | -                | -         |    -4.74 | lukiz, pancc, realz1n, rem1x, zmb    |
|           19 |     4111 | 2024-11-02 | Bounty Hunters Esports | W   | 0.407      | 0.333        | 0.005 (0.001)    | 0.524 (0.071)    | -         |     5.89 | lukiz, pancc, realz1n, rem1x, zmb    |
|           18 |     4164 | 2024-11-01 | Bounty Hunters Esports | L   | 0.402      | -            | -                | -                | -         |    -7.00 | lukiz, pancc, realz1n, rem1x, zmb    |
|           17 |     4178 | 2024-11-01 | Dusty Roots            | W   | 0.401      | 0.333        | 0.008 (0.001)    | 0.371 (0.050)    | -         |     6.50 | lukiz, pancc, realz1n, rem1x, zmb    |
|           16 |     4225 | 2024-10-31 | Fluxo                  | L   | 0.395      | -            | -                | -                | -         |    -3.12 | lukiz, pancc, realz1n, rem1x, zmb    |
|           15 |     4245 | 2024-10-31 | VELOX Argentina        | W   | 0.393      | -            | -                | -                | -         |     4.08 | lukiz, pancc, realz1n, rem1x, zmb    |
|           14 |     4268 | 2024-10-30 | 20/70                  | W   | 0.389      | -            | -                | -                | -         |     4.66 | lukiz, pancc, realz1n, rem1x, zmb    |
|           13 |     4283 | 2024-10-30 | América eSports        | W   | 0.387      | -            | -                | -                | -         |     4.10 | lukiz, pancc, realz1n, rem1x, zmb    |
|           12 |     4338 | 2024-10-29 | AdalYamigos            | L   | 0.382      | -            | -                | -                | -         |    -5.53 | lukiz, pancc, realz1n, rem1x, zmb    |
|           11 |     4397 | 2024-10-28 | Sharks Esports         | W   | 0.374      | 0.143        | 0.054 (0.003)    | -                | -         |     9.92 | lukiz, pancc, realz1n, rem1x, zmb    |
|           10 |     4438 | 2024-10-28 | Nitro.GG               | W   | 0.372      | 0.371        | -                | 0.518 (0.071)    | -         |     5.19 | lukiz, pancc, realz1n, rem1x, zmb    |
|            9 |     4640 | 2024-10-23 | Intense Game           | L   | 0.341      | -            | -                | -                | -         |    -6.23 | honda, lukiz, realz1n, rem1x, zmb    |
|            8 |     4642 | 2024-10-23 | RED Canids Academy     | L   | 0.341      | -            | -                | -                | -         |    -5.87 | honda, lukiz, realz1n, rem1x, zmb    |
|            7 |     4965 | 2024-10-16 | Bounty Hunters Esports | L   | 0.295      | -            | -                | -                | -         |    -5.68 | honda, lukiz, realz1n, rem1x, zmb    |
|            6 |     4972 | 2024-10-16 | Dusty Roots            | L   | 0.294      | -            | -                | -                | -         |    -4.26 | honda, lukiz, realz1n, rem1x, zmb    |
|            5 |     5750 | 2024-10-02 | 20/70                  | W   | 0.201      | -            | -                | -                | -         |     2.33 | honda, lukiz, realz1n, rem1x, zmb    |
|            4 |     5830 | 2024-10-01 | Intense Game           | W   | 0.194      | -            | -                | -                | -         |     2.41 | honda, lukiz, realz1n, rem1x, zmb    |
|            3 |     6177 | 2024-09-26 | Case Esports           | L   | 0.161      | -            | -                | -                | -         |    -2.92 | honda, lukiz, realz1n, rem1x, zmb    |
|            2 |     6728 | 2024-09-18 | RED Canids Academy     | L   | 0.108      | -            | -                | -                | -         |    -1.96 | honda, lukiz, realz1n, rem1x, zmb    |
|            1 |     7163 | 2024-09-11 | Dusty Roots            | W   | 0.061      | -            | -                | -                | -         |     1.10 | honda, lukiz, realz1n, rem1x, zmb    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,460.35)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-09 |      0.653 | $1,000.00      | $653.33         |
| 2024-11-05 |      0.429 | $1,726.49      | $740.35         |
| 2024-11-03 |      0.413 | $5,000.00      | $2,066.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
