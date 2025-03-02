### Roster Details<br />
Team Name: Nuclear TigeRES<br />
Roster: flouzer, Fluffy, h1kan, k0s, senka<br />
Global Rank: [152](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [112]( ../standings_europe.md)<br />
<br />
Final Rank Value:  760.5<br />
<br />
Final Rank Value (760.5) = Starting Rank Value (831.8) + Head To Head Adjustments (-71.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.233[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 831.8
- 400 + ( ( 0.216 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 831.8


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
|           47 |      343 | 2025-02-16 | K27                    | L   | 1.000      | -            | -                | -                | -         |   -14.28 | flouzer, Fluffy, h1kan, k0s, senka     |
|           46 |      352 | 2025-02-16 | Eternal premium        | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.215 (0.031)    | 1 (1.000) |    12.26 | flouzer, Fluffy, h1kan, k0s, senka     |
|           45 |      380 | 2025-02-15 | RUSTEC                 | W   | 1.000      | 0.143        | -                | 0.217 (0.031)    | 1 (1.000) |     8.14 | flouzer, Fluffy, h1kan, k0s, senka     |
|           44 |      766 | 2025-02-07 | OG                     | L   | 1.000      | -            | -                | -                | -         |    -7.52 | flouzer, Fluffy, h1kan, k0s, senka     |
|           43 |      977 | 2025-02-04 | TEAM NEXT LEVEL        | L   | 1.000      | -            | -                | -                | -         |   -19.61 | flouzer, Fluffy, h1kan, k0s, senka     |
|           42 |     1017 | 2025-02-03 | Minsk House            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.52 | flouzer, Fluffy, h1kan, k0s, senka     |
|           41 |     1018 | 2025-02-03 | Underrated             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.42 | flouzer, Fluffy, h1kan, k0s, senka     |
|           40 |     1484 | 2024-12-20 | BadGuys                | L   | 0.728      | -            | -                | -                | -         |   -15.82 | flouzer, Fluffy, h1kan, k0s, senka     |
|           39 |     1486 | 2024-12-20 | HOTU                   | W   | 0.728      | 0.143        | 0.003 (0.000)    | 0.777 (0.081)    | 0 (0.000) |    10.19 | flouzer, Fluffy, h1kan, k0s, senka     |
|           38 |     1494 | 2024-12-20 | HAVENs                 | W   | 0.727      | -            | -                | -                | 0 (0.000) |     2.77 | flouzer, Fluffy, h1kan, k0s, senka     |
|           37 |     1787 | 2024-12-13 | Hesta                  | L   | 0.679      | -            | -                | -                | -         |   -12.30 | flouzer, Fluffy, h1kan, k0s, senka     |
|           36 |     1975 | 2024-12-08 | 0to100                 | L   | 0.647      | -            | -                | -                | -         |   -11.05 | flouzer, Fluffy, h1kan, k0s, senka     |
|           35 |     1990 | 2024-12-08 | Soul's Heart Esport    | W   | 0.647      | -            | -                | -                | 0 (0.000) |     3.30 | flouzer, Fluffy, h1kan, k0s, senka     |
|           34 |     2258 | 2024-12-03 | GenOne                 | L   | 0.614      | -            | -                | -                | -         |    -7.58 | flouzer, Fluffy, h1kan, k0s, senka     |
|           33 |     2477 | 2024-11-30 | Leo Team               | L   | 0.594      | -            | -                | -                | -         |    -7.09 | flouzer, Fluffy, h1kan, k0s, senka     |
|           32 |     2608 | 2024-11-28 | GameAgents             | W   | 0.580      | -            | -                | -                | 0 (0.000) |     4.75 | flouzer, Fluffy, h1kan, k0s, senka     |
|           31 |     2702 | 2024-11-26 | Soul's Heart Esport    | W   | 0.567      | -            | -                | -                | 0 (0.000) |     3.94 | flouzer, Fluffy, h1kan, k0s, senka     |
|           30 |     2880 | 2024-11-23 | K27                    | W   | 0.546      | 0.372        | 0.008 (0.002)    | 0.776 (0.158)    | 0 (0.000) |    10.22 | flouzer, Fluffy, h1kan, k0s, senka     |
|           29 |     2886 | 2024-11-23 | 1win                   | L   | 0.546      | -            | -                | -                | -         |    -9.33 | flouzer, Fluffy, h1kan, k0s, senka     |
|           28 |     3019 | 2024-11-21 | Flame Sharks           | L   | 0.533      | -            | -                | -                | -         |   -12.06 | flouzer, Fluffy, h1kan, k0s, senka     |
|           27 |     3182 | 2024-11-18 | Haspers Team           | W   | 0.514      | 0.372        | 0.013 (0.003)    | 0.174 (0.033)    | -         |     6.19 | flouzer, Fluffy, h1kan, k0s, senka     |
|           26 |     3228 | 2024-11-17 | Lazer Cats             | L   | 0.507      | -            | -                | -                | -         |    -9.24 | flouzer, Fluffy, h1kan, k0s, senka     |
|           25 |     3327 | 2024-11-16 | Premdesant             | L   | 0.499      | -            | -                | -                | -         |   -11.01 | flouzer, Fluffy, h1kan, k0s, senka     |
|           24 |     3341 | 2024-11-16 | FLuffy Gangsters       | L   | 0.498      | -            | -                | -                | -         |    -8.07 | flouzer, Fluffy, h1kan, k0s, senka     |
|           23 |     3351 | 2024-11-16 | QUAZAR                 | L   | 0.497      | -            | -                | -                | -         |   -10.14 | flouzer, Fluffy, h1kan, k0s, senka     |
|           22 |     3676 | 2024-11-10 | 4z                     | W   | 0.458      | 0.143        | 0.004 (0.000)    | -                | -         |     3.74 | flouzer, Fluffy, h1kan, k0s, senka     |
|           21 |     3680 | 2024-11-10 | RUSTEC                 | W   | 0.458      | -            | -                | -                | -         |     2.55 | flouzer, Fluffy, h1kan, k0s, senka     |
|           20 |     3740 | 2024-11-09 | RUSH B (Russian team)  | L   | 0.452      | -            | -                | -                | -         |    -6.23 | flouzer, Fluffy, h1kan, k0s, senka     |
|           19 |     3744 | 2024-11-09 | 4z                     | W   | 0.451      | 0.143        | 0.004 (0.000)    | -                | -         |     3.70 | flouzer, Fluffy, h1kan, k0s, senka     |
|           18 |     3844 | 2024-11-07 | BC.Game Esports        | W   | 0.439      | 0.372        | 0.022 (0.004)    | 0.559 (0.091)    | -         |     6.98 | flouzer, Fluffy, h1kan, k0s, senka     |
|           17 |     4186 | 2024-11-01 | RUSH B (Russian team)  | L   | 0.400      | -            | -                | -                | -         |    -5.48 | flouzer, Fluffy, h1kan, k0s, senka     |
|           16 |     4453 | 2024-10-27 | GamerLegion Academy    | L   | 0.367      | -            | -                | -                | -         |    -9.76 | flouzer, Fluffy, h1kan, k0s, senka     |
|           15 |     4505 | 2024-10-26 | Ex-RUBY                | W   | 0.359      | -            | -                | -                | -         |     1.71 | flouzer, Fluffy, h1kan, k0s, senka     |
|           14 |     4591 | 2024-10-25 | Kubix Esports          | W   | 0.352      | 0.372        | 0.045 (0.006)    | 0.496 (0.065)    | -         |     6.97 | flouzer, Fluffy, h1kan, k0s, senka     |
|           13 |     4651 | 2024-10-23 | Lausanne-Sport Esports | W   | 0.340      | -            | -                | -                | -         |     1.84 | flouzer, Fluffy, h1kan, k0s, senka     |
|           12 |     4671 | 2024-10-23 | GUN5 Esports           | W   | 0.339      | 0.143        | 0.102 (0.005)    | -                | -         |     6.91 | flouzer, Fluffy, h1kan, k0s, senka     |
|           11 |     4706 | 2024-10-22 | Poslednii3ae3d         | W   | 0.332      | -            | -                | -                | -         |     2.66 | flouzer, Fluffy, h1kan, k0s, senka     |
|           10 |     4724 | 2024-10-21 | GODSENT                | W   | 0.326      | 0.372        | -                | 0.275 (0.033)    | -         |     2.93 | flouzer, Fluffy, h1kan, k0s, senka     |
|            9 |     5004 | 2024-10-16 | THE GENTLEMEN ESPORTS  | W   | 0.292      | 0.372        | -                | 0.269 (0.029)    | -         |     3.11 | flouzer, Fluffy, h1kan, k0s, senka     |
|            8 |     5100 | 2024-10-14 | TEAM NEXT LEVEL        | W   | 0.279      | 0.372        | 0.039 (0.004)    | 0.508 (0.053)    | -         |     4.80 | flouzer, Fluffy, h1kan, k0s, senka     |
|            7 |     5148 | 2024-10-13 | QUAZAR                 | L   | 0.271      | -            | -                | -                | -         |    -5.63 | flouzer, Fluffy, h1kan, k0s, senka     |
|            6 |     5153 | 2024-10-13 | HellaSlayers99         | W   | 0.271      | -            | -                | -                | -         |     1.80 | flouzer, Fluffy, h1kan, k0s, senka     |
|            5 |     5212 | 2024-10-12 | LEON Esports           | L   | 0.265      | -            | -                | -                | -         |    -4.80 | flouzer, Fluffy, h1kan, k0s, senka     |
|            4 |     5227 | 2024-10-12 | 500 Rush               | W   | 0.265      | -            | -                | -                | -         |     2.29 | flouzer, Fluffy, h1kan, k0s, senka     |
|            3 |     6006 | 2024-09-28 | Ex-ESC Gaming          | L   | 0.173      | -            | -                | -                | -         |    -3.99 | flouzer, Fluffy, h1kan, k0s, OverDrive |
|            2 |     6019 | 2024-09-28 | Superior Esports       | W   | 0.173      | -            | -                | -                | -         |     0.45 | flouzer, Fluffy, h1kan, k0s, OverDrive |
|            1 |     6573 | 2024-09-21 | NO BYSTANDERS          | L   | 0.126      | -            | -                | -                | -         |    -3.47 | flouzer, fluffy, h1kan, k0s, senka     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,368.97)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-16 |      1.000 | $735.49        | $735.49         |
| 2024-11-03 |      0.413 | $1,532.61      | $633.48         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
