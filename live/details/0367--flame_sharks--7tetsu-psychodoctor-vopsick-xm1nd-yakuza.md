### Roster Details<br />
Team Name: Flame Sharks<br />
Roster: 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza<br />
Global Rank: [367](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [233]( ../standings_europe.md)<br />
<br />
Final Rank Value:  615.3<br />
<br />
Final Rank Value (615.3) = Starting Rank Value (647.0) + Head To Head Adjustments (-31.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.225[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 647.0
- 400 + ( ( 0.123 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 647.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      253 | 2025-02-20 | Wolves eSports        | L   | 1.000      | -            | -                | -                | -         |   -21.47 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           23 |      468 | 2025-02-14 | ALGO                  | L   | 1.000      | -            | -                | -                | -         |   -21.57 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           22 |      633 | 2025-02-09 | K27                   | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.769 (0.110)    | 0 (0.000) |    21.44 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           21 |      641 | 2025-02-09 | FLuffy Gangsters      | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.909 (0.130)    | 0 (0.000) |    22.46 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           20 |      986 | 2025-02-04 | ENRAGE                | L   | 1.000      | -            | -                | -                | -         |   -15.57 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           19 |     1691 | 2024-12-14 | Underrated            | L   | 0.679      | -            | -                | -                | -         |    -9.93 | 7tetsu, HEiS, PsychoDoctor, xm1nd, Yakuza    |
|           18 |     2490 | 2024-11-30 | GameAgents            | L   | 0.586      | -            | -                | -                | -         |    -9.99 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           17 |     2734 | 2024-11-26 | FLuffy Gangsters      | L   | 0.558      | -            | -                | -                | -         |    -4.38 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           16 |     2847 | 2024-11-23 | FLuffy Gangsters      | L   | 0.539      | -            | -                | -                | -         |    -4.45 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           15 |     2852 | 2024-11-23 | 4z                    | W   | 0.539      | 0.262        | 0.004 (0.001)    | 0.140 (0.020)    | 0 (0.000) |     8.42 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           14 |     3031 | 2024-11-21 | Nuclear TigeRES       | W   | 0.525      | 0.372        | 0.004 (0.001)    | 0.580 (0.113)    | 0 (0.000) |    11.90 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           13 |     4563 | 2024-10-26 | Aimhaus               | L   | 0.349      | -            | -                | -                | -         |    -7.93 | 7tetsu, Dis1, Wadeshot, xm1nd, Yakuza        |
|           12 |     6021 | 2024-09-28 | K27                   | L   | 0.165      | -            | -                | -                | -         |    -0.92 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|           11 |     6041 | 2024-09-28 | MASONIC               | W   | 0.165      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.04 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|           10 |     6531 | 2024-09-22 | NewBALLS              | L   | 0.124      | -            | -                | -                | -         |    -1.88 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            9 |     6584 | 2024-09-21 | Ex-DOSKI              | W   | 0.118      | 0.143        | 0.000 (0.000)    | 0.019 (0.000)    | 0 (0.000) |     0.74 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            8 |     6765 | 2024-09-18 | THE GENTLEMEN ESPORTS | L   | 0.098      | -            | -                | -                | -         |    -1.37 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            7 |     6831 | 2024-09-17 | Infinite Gaming       | W   | 0.092      | 0.333        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.21 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            6 |     6885 | 2024-09-16 | QUAZAR                | L   | 0.085      | -            | -                | -                | -         |    -1.12 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            5 |     7084 | 2024-09-13 | THE GENTLEMEN ESPORTS | W   | 0.065      | 0.333        | 0.001 (0.000)    | 0.263 (0.006)    | 0 (0.000) |     1.14 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            4 |     7287 | 2024-09-09 | XI Esport             | W   | 0.038      | 0.333        | 0.001 (0.000)    | 0.282 (0.004)    | 0 (0.000) |     0.66 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            3 |     7506 | 2024-09-06 | Team PeeP             | L   | 0.018      | -            | -                | -                | -         |    -0.41 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            2 |     7517 | 2024-09-06 | Team OWL              | W   | 0.018      | 0.221        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     0.16 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            1 |     7579 | 2024-09-05 | GoodCall              | W   | 0.012      | 0.333        | -                | 0.001 (0.000)    | -         |     0.10 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($117.64)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.118 | $1,000.00      | $117.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
