### Roster Details<br />
Team Name: Nuclear TigeRES<br />
Roster: flouzer, Fluffy, h1kan, k0s, senka<br />
Global Rank: [151](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [110]( ../standings_europe.md)<br />
<br />
Final Rank Value:  760.8<br />
<br />
Final Rank Value (760.8) = Starting Rank Value (832.0) + Head To Head Adjustments (-71.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.275[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.234[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 832.0
- 400 + ( ( 0.216 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 832.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |      355 | 2025-02-16 | K27                    | L   | 1.000      | -            | -                | -                | -         |   -14.27 | flouzer, Fluffy, h1kan, k0s, senka     |
|           46 |      364 | 2025-02-16 | Eternal premium        | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.215 (0.031)    | 1 (1.000) |    12.28 | flouzer, Fluffy, h1kan, k0s, senka     |
|           45 |      392 | 2025-02-15 | RUSTEC                 | W   | 1.000      | 0.143        | -                | 0.216 (0.031)    | 1 (1.000) |     8.10 | flouzer, Fluffy, h1kan, k0s, senka     |
|           44 |      778 | 2025-02-07 | OG                     | L   | 1.000      | -            | -                | -                | -         |    -7.57 | flouzer, Fluffy, h1kan, k0s, senka     |
|           43 |      989 | 2025-02-04 | TEAM NEXT LEVEL        | L   | 1.000      | -            | -                | -                | -         |   -19.64 | flouzer, Fluffy, h1kan, k0s, senka     |
|           42 |     1029 | 2025-02-03 | Minsk House            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.51 | flouzer, Fluffy, h1kan, k0s, senka     |
|           41 |     1030 | 2025-02-03 | Underrated             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.41 | flouzer, Fluffy, h1kan, k0s, senka     |
|           40 |     1496 | 2024-12-20 | BadGuys                | L   | 0.720      | -            | -                | -                | -         |   -15.69 | flouzer, Fluffy, h1kan, k0s, senka     |
|           39 |     1498 | 2024-12-20 | HOTU                   | W   | 0.720      | 0.143        | 0.003 (0.000)    | 0.768 (0.079)    | 0 (0.000) |    10.03 | flouzer, Fluffy, h1kan, k0s, senka     |
|           38 |     1506 | 2024-12-20 | HAVENs                 | W   | 0.719      | -            | -                | -                | 0 (0.000) |     2.73 | flouzer, Fluffy, h1kan, k0s, senka     |
|           37 |     1799 | 2024-12-13 | Hesta                  | L   | 0.671      | -            | -                | -                | -         |   -12.16 | flouzer, Fluffy, h1kan, k0s, senka     |
|           36 |     1987 | 2024-12-08 | 0to100                 | L   | 0.639      | -            | -                | -                | -         |   -10.94 | flouzer, Fluffy, h1kan, k0s, senka     |
|           35 |     2002 | 2024-12-08 | Soul's Heart Esport    | W   | 0.638      | -            | -                | -                | 0 (0.000) |     3.26 | flouzer, Fluffy, h1kan, k0s, senka     |
|           34 |     2270 | 2024-12-03 | GenOne                 | L   | 0.606      | -            | -                | -                | -         |    -7.54 | flouzer, Fluffy, h1kan, k0s, senka     |
|           33 |     2489 | 2024-11-30 | Leo Team               | L   | 0.586      | -            | -                | -                | -         |    -7.06 | flouzer, Fluffy, h1kan, k0s, senka     |
|           32 |     2620 | 2024-11-28 | GameAgents             | W   | 0.572      | -            | -                | -                | 0 (0.000) |     4.63 | flouzer, Fluffy, h1kan, k0s, senka     |
|           31 |     2714 | 2024-11-26 | Soul's Heart Esport    | W   | 0.559      | -            | -                | -                | 0 (0.000) |     3.86 | flouzer, Fluffy, h1kan, k0s, senka     |
|           30 |     2892 | 2024-11-23 | K27                    | W   | 0.538      | 0.372        | 0.008 (0.002)    | 0.769 (0.154)    | 0 (0.000) |    10.08 | flouzer, Fluffy, h1kan, k0s, senka     |
|           29 |     2898 | 2024-11-23 | 1win                   | L   | 0.537      | -            | -                | -                | -         |    -9.24 | flouzer, Fluffy, h1kan, k0s, senka     |
|           28 |     3031 | 2024-11-21 | Flame Sharks           | L   | 0.525      | -            | -                | -                | -         |   -11.90 | flouzer, Fluffy, h1kan, k0s, senka     |
|           27 |     3194 | 2024-11-18 | Haspers Team           | W   | 0.505      | 0.372        | 0.013 (0.003)    | 0.171 (0.032)    | -         |     6.07 | flouzer, Fluffy, h1kan, k0s, senka     |
|           26 |     3240 | 2024-11-17 | Lazer Cats             | L   | 0.498      | -            | -                | -                | -         |    -9.14 | flouzer, Fluffy, h1kan, k0s, senka     |
|           25 |     3339 | 2024-11-16 | Premdesant             | L   | 0.491      | -            | -                | -                | -         |   -10.83 | flouzer, Fluffy, h1kan, k0s, senka     |
|           24 |     3353 | 2024-11-16 | FLuffy Gangsters       | L   | 0.490      | -            | -                | -                | -         |    -7.99 | flouzer, Fluffy, h1kan, k0s, senka     |
|           23 |     3363 | 2024-11-16 | QUAZAR                 | L   | 0.489      | -            | -                | -                | -         |   -10.00 | flouzer, Fluffy, h1kan, k0s, senka     |
|           22 |     3688 | 2024-11-10 | 4z                     | W   | 0.450      | 0.143        | 0.004 (0.000)    | -                | -         |     3.68 | flouzer, Fluffy, h1kan, k0s, senka     |
|           21 |     3692 | 2024-11-10 | RUSTEC                 | W   | 0.450      | -            | -                | -                | -         |     2.49 | flouzer, Fluffy, h1kan, k0s, senka     |
|           20 |     3752 | 2024-11-09 | RUSH B (Russian team)  | L   | 0.443      | -            | -                | -                | -         |    -6.12 | flouzer, Fluffy, h1kan, k0s, senka     |
|           19 |     3756 | 2024-11-09 | 4z                     | W   | 0.443      | 0.143        | 0.004 (0.000)    | -                | -         |     3.64 | flouzer, Fluffy, h1kan, k0s, senka     |
|           18 |     3856 | 2024-11-07 | BC.Game Esports        | W   | 0.431      | 0.372        | 0.022 (0.003)    | 0.551 (0.088)    | -         |     6.82 | flouzer, Fluffy, h1kan, k0s, senka     |
|           17 |     4198 | 2024-11-01 | RUSH B (Russian team)  | L   | 0.392      | -            | -                | -                | -         |    -5.37 | flouzer, Fluffy, h1kan, k0s, senka     |
|           16 |     4465 | 2024-10-27 | GamerLegion Academy    | L   | 0.358      | -            | -                | -                | -         |    -9.55 | flouzer, Fluffy, h1kan, k0s, senka     |
|           15 |     4517 | 2024-10-26 | Ex-RUBY                | W   | 0.351      | -            | -                | -                | -         |     1.67 | flouzer, Fluffy, h1kan, k0s, senka     |
|           14 |     4603 | 2024-10-25 | Kubix Esports          | W   | 0.344      | 0.372        | 0.045 (0.006)    | 0.487 (0.062)    | -         |     6.79 | flouzer, Fluffy, h1kan, k0s, senka     |
|           13 |     4663 | 2024-10-23 | Lausanne-Sport Esports | W   | 0.332      | -            | -                | -                | -         |     1.79 | flouzer, Fluffy, h1kan, k0s, senka     |
|           12 |     4683 | 2024-10-23 | GUN5 Esports           | W   | 0.331      | 0.143        | 0.103 (0.005)    | -                | -         |     6.72 | flouzer, Fluffy, h1kan, k0s, senka     |
|           11 |     4718 | 2024-10-22 | Poslednii3ae3d         | W   | 0.324      | -            | -                | -                | -         |     2.59 | flouzer, Fluffy, h1kan, k0s, senka     |
|           10 |     4736 | 2024-10-21 | GODSENT                | W   | 0.318      | 0.372        | -                | 0.269 (0.032)    | -         |     2.84 | flouzer, Fluffy, h1kan, k0s, senka     |
|            9 |     5016 | 2024-10-16 | THE GENTLEMEN ESPORTS  | W   | 0.284      | 0.372        | -                | 0.263 (0.028)    | -         |     3.00 | flouzer, Fluffy, h1kan, k0s, senka     |
|            8 |     5112 | 2024-10-14 | TEAM NEXT LEVEL        | W   | 0.271      | 0.372        | 0.040 (0.004)    | 0.500 (0.050)    | -         |     4.63 | flouzer, Fluffy, h1kan, k0s, senka     |
|            7 |     5160 | 2024-10-13 | QUAZAR                 | L   | 0.263      | -            | -                | -                | -         |    -5.47 | flouzer, Fluffy, h1kan, k0s, senka     |
|            6 |     5165 | 2024-10-13 | HellaSlayers99         | W   | 0.263      | -            | -                | -                | -         |     1.74 | flouzer, Fluffy, h1kan, k0s, senka     |
|            5 |     5224 | 2024-10-12 | LEON Esports           | L   | 0.257      | -            | -                | -                | -         |    -4.66 | flouzer, Fluffy, h1kan, k0s, senka     |
|            4 |     5239 | 2024-10-12 | 500 Rush               | W   | 0.257      | -            | -                | -                | -         |     2.20 | flouzer, Fluffy, h1kan, k0s, senka     |
|            3 |     6018 | 2024-09-28 | Ex-ESC Gaming          | L   | 0.165      | -            | -                | -                | -         |    -3.81 | flouzer, Fluffy, h1kan, k0s, OverDrive |
|            2 |     6031 | 2024-09-28 | Superior Esports       | W   | 0.165      | -            | -                | -                | -         |     0.43 | flouzer, Fluffy, h1kan, k0s, OverDrive |
|            1 |     6585 | 2024-09-21 | NO BYSTANDERS          | L   | 0.118      | -            | -                | -                | -         |    -3.24 | flouzer, fluffy, h1kan, k0s, senka     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,356.41)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-16 |      1.000 | $735.49        | $735.49         |
| 2024-11-03 |      0.405 | $1,532.61      | $620.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
