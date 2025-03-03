### Roster Details<br />
Team Name: UNO MILLE<br />
Roster: bnc, Leomonster, realz1n, rem1x, zmb<br />
Global Rank: [146](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [29]( ../standings_americas.md)<br />
<br />
Final Rank Value:  768.2<br />
<br />
Final Rank Value (768.2) = Starting Rank Value (740.0) + Head To Head Adjustments (28.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.090[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 740.0
- 400 + ( ( 0.170 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 740.0


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
|           46 |      237 | 2025-02-20 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |    -6.63 | bnc, Leomonster, realz1n, rem1x, zmb |
|           45 |      338 | 2025-02-16 | ShindeN                | W   | 1.000      | 0.371        | 0.005 (0.002)    | 0.308 (0.114)    | 0 (0.000) |    13.15 | bnc, Leomonster, realz1n, rem1x, zmb |
|           44 |      464 | 2025-02-14 | ODDIK                  | L   | 1.000      | -            | -                | -                | -         |   -11.12 | bnc, Leomonster, realz1n, rem1x, zmb |
|           43 |      540 | 2025-02-12 | KRÜ Esports            | W   | 1.000      | 0.371        | 0.001 (0.001)    | 0.131 (0.049)    | 0 (0.000) |    11.99 | bnc, Leomonster, realz1n, rem1x, zmb |
|           42 |      581 | 2025-02-10 | Bounty Hunters Esports | W   | 1.000      | 0.371        | 0.005 (0.002)    | 0.523 (0.194)    | 0 (0.000) |    15.63 | bnc, Leomonster, realz1n, rem1x, zmb |
|           41 |      753 | 2025-02-07 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |    -8.36 | bnc, Leomonster, realz1n, rem1x, zmb |
|           40 |      939 | 2025-02-04 | Familia Maquininha     | L   | 1.000      | -            | -                | -                | -         |   -18.47 | bnc, Leomonster, realz1n, rem1x, zmb |
|           39 |      951 | 2025-02-04 | América eSports        | W   | 1.000      | 0.143        | -                | 0.426 (0.061)    | 0 (0.000) |     8.61 | bnc, Leomonster, realz1n, rem1x, zmb |
|           38 |     1218 | 2025-01-09 | Team Solid             | L   | 0.852      | -            | -                | -                | -         |    -9.85 | bnc, max, realz1n, rem1x, zmb        |
|           37 |     1507 | 2024-12-20 | Patins da Ferrari      | W   | 0.719      | -            | -                | -                | 0 (0.000) |     5.18 | bnc, max, realz1n, rem1x, zmb        |
|           36 |     1566 | 2024-12-18 | Nitro.GG               | W   | 0.704      | 0.384        | 0.002 (0.000)    | 0.512 (0.139)    | 0 (0.000) |     8.23 | bnc, max, realz1n, rem1x, zmb        |
|           35 |     1591 | 2024-12-16 | Bad News Chickens      | L   | 0.692      | -            | -                | -                | -         |   -13.32 | bnc, max, realz1n, rem1x, zmb        |
|           34 |     1771 | 2024-12-13 | Galorys Academy        | W   | 0.673      | -            | -                | -                | 0 (0.000) |     5.77 | bnc, max, realz1n, rem1x, zmb        |
|           33 |     1960 | 2024-12-09 | Game Hunters           | W   | 0.645      | 0.262        | 0.003 (0.000)    | 0.392 (0.066)    | 0 (0.000) |     9.62 | lukiz, pancc, realz1n, rem1x, zmb    |
|           32 |     2003 | 2024-12-08 | Yawara E-Sports        | W   | 0.638      | 0.262        | -                | 0.448 (0.075)    | 0 (0.000) |     8.62 | lukiz, pancc, realz1n, rem1x, zmb    |
|           31 |     2276 | 2024-12-03 | Game Hunters           | L   | 0.605      | -            | -                | -                | -         |   -10.02 | lukiz, pancc, realz1n, rem1x, zmb    |
|           30 |     2326 | 2024-12-02 | DB Peek Esports        | W   | 0.600      | -            | -                | -                | 0 (0.000) |     6.39 | lukiz, pancc, realz1n, rem1x, zmb    |
|           29 |     2519 | 2024-11-30 | Yawara E-Sports        | W   | 0.585      | 0.262        | -                | 0.448 (0.068)    | -         |     8.14 | lukiz, pancc, realz1n, rem1x, zmb    |
|           28 |     2675 | 2024-11-27 | Nitro.GG               | L   | 0.565      | -            | -                | -                | -         |   -10.34 | lukiz, pancc, realz1n, rem1x, zmb    |
|           27 |     3849 | 2024-11-07 | ODDIK                  | L   | 0.432      | -            | -                | -                | -         |    -5.23 | lukiz, pancc, realz1n, rem1x, zmb    |
|           26 |     3921 | 2024-11-05 | Galorys Academy        | W   | 0.421      | -            | -                | -                | -         |     4.10 | lukiz, pancc, realz1n, rem1x, zmb    |
|           25 |     3979 | 2024-11-04 | Floripa Stars          | W   | 0.413      | -            | -                | -                | -         |     5.11 | lukiz, pancc, realz1n, rem1x, zmb    |
|           24 |     3981 | 2024-11-04 | Intense Game           | W   | 0.413      | -            | -                | -                | -         |     5.49 | lukiz, pancc, realz1n, rem1x, zmb    |
|           23 |     4041 | 2024-11-03 | ODDIK                  | W   | 0.406      | 0.143        | 0.028 (0.002)    | -                | -         |     8.06 | lukiz, pancc, realz1n, rem1x, zmb    |
|           22 |     4051 | 2024-11-03 | RED Canids Academy     | W   | 0.405      | 0.333        | 0.005 (0.001)    | -                | -         |     5.99 | lukiz, pancc, realz1n, rem1x, zmb    |
|           21 |     4108 | 2024-11-02 | TROPA DO TACO          | L   | 0.400      | -            | -                | -                | -         |    -6.53 | lukiz, pancc, realz1n, rem1x, zmb    |
|           20 |     4111 | 2024-11-02 | Team Solid             | L   | 0.400      | -            | -                | -                | -         |    -4.65 | lukiz, pancc, realz1n, rem1x, zmb    |
|           19 |     4123 | 2024-11-02 | Bounty Hunters Esports | W   | 0.399      | 0.333        | 0.005 (0.001)    | 0.523 (0.070)    | -         |     5.80 | lukiz, pancc, realz1n, rem1x, zmb    |
|           18 |     4176 | 2024-11-01 | Bounty Hunters Esports | L   | 0.394      | -            | -                | -                | -         |    -6.83 | lukiz, pancc, realz1n, rem1x, zmb    |
|           17 |     4190 | 2024-11-01 | Dusty Roots            | W   | 0.392      | 0.333        | 0.009 (0.001)    | -                | -         |     6.40 | lukiz, pancc, realz1n, rem1x, zmb    |
|           16 |     4237 | 2024-10-31 | Fluxo                  | L   | 0.387      | -            | -                | -                | -         |    -3.07 | lukiz, pancc, realz1n, rem1x, zmb    |
|           15 |     4257 | 2024-10-31 | VELOX Argentina        | W   | 0.385      | -            | -                | -                | -         |     3.01 | lukiz, pancc, realz1n, rem1x, zmb    |
|           14 |     4280 | 2024-10-30 | 20/70                  | W   | 0.380      | -            | -                | -                | -         |     4.57 | lukiz, pancc, realz1n, rem1x, zmb    |
|           13 |     4295 | 2024-10-30 | América eSports        | W   | 0.379      | -            | -                | -                | -         |     4.01 | lukiz, pancc, realz1n, rem1x, zmb    |
|           12 |     4350 | 2024-10-29 | AdalYamigos            | L   | 0.373      | -            | -                | -                | -         |    -5.44 | lukiz, pancc, realz1n, rem1x, zmb    |
|           11 |     4409 | 2024-10-28 | Sharks Esports         | W   | 0.366      | 0.143        | 0.055 (0.003)    | -                | -         |     9.72 | lukiz, pancc, realz1n, rem1x, zmb    |
|           10 |     4450 | 2024-10-28 | Nitro.GG               | W   | 0.364      | 0.371        | -                | 0.512 (0.069)    | -         |     5.06 | lukiz, pancc, realz1n, rem1x, zmb    |
|            9 |     4652 | 2024-10-23 | Intense Game           | L   | 0.333      | -            | -                | -                | -         |    -6.08 | honda, lukiz, realz1n, rem1x, zmb    |
|            8 |     4654 | 2024-10-23 | RED Canids Academy     | L   | 0.332      | -            | -                | -                | -         |    -5.74 | honda, lukiz, realz1n, rem1x, zmb    |
|            7 |     4977 | 2024-10-16 | Bounty Hunters Esports | L   | 0.287      | -            | -                | -                | -         |    -5.53 | honda, lukiz, realz1n, rem1x, zmb    |
|            6 |     4984 | 2024-10-16 | Dusty Roots            | L   | 0.286      | -            | -                | -                | -         |    -4.14 | honda, lukiz, realz1n, rem1x, zmb    |
|            5 |     5762 | 2024-10-02 | 20/70                  | W   | 0.193      | -            | -                | -                | -         |     2.24 | honda, lukiz, realz1n, rem1x, zmb    |
|            4 |     5842 | 2024-10-01 | Intense Game           | W   | 0.186      | -            | -                | -                | -         |     2.31 | honda, lukiz, realz1n, rem1x, zmb    |
|            3 |     6189 | 2024-09-26 | Case Esports           | L   | 0.153      | -            | -                | -                | -         |    -2.78 | honda, lukiz, realz1n, rem1x, zmb    |
|            2 |     6740 | 2024-09-18 | RED Canids Academy     | L   | 0.100      | -            | -                | -                | -         |    -1.81 | honda, lukiz, realz1n, rem1x, zmb    |
|            1 |     7175 | 2024-09-11 | Dusty Roots            | W   | 0.053      | -            | -                | -                | -         |     0.95 | honda, lukiz, realz1n, rem1x, zmb    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,397.04)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-09 |      0.645 | $1,000.00      | $645.14         |
| 2024-11-05 |      0.421 | $1,726.49      | $726.20         |
| 2024-11-03 |      0.405 | $5,000.00      | $2,025.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
