### Roster Details<br />
Team Name: Game Hunters<br />
Roster: abr, mello, nolkz, prt, slashzz<br />
Global Rank: [265](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [48]( ../standings_americas.md)<br />
<br />
Final Rank Value:  671.1<br />
<br />
Final Rank Value (671.1) = Starting Rank Value (694.8) + Head To Head Adjustments (-23.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.243[<sup>2</sup>](#table1)
- Opponent Network: 0.070[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.8
- 400 + ( ( 0.148 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 694.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      275 | 2025-02-17 | Players (Brazilian team) | L   | 1.000      | -            | -                | -                | -         |   -11.01 | abr, mello, nolkz, prt, slashzz  |
|           28 |      391 | 2025-02-15 | KRÜ Esports              | W   | 1.000      | 0.371        | 0.001 (0.001)    | 0.132 (0.049)    | 0 (0.000) |    14.94 | abr, mello, nolkz, prt, slashzz  |
|           27 |      479 | 2025-02-14 | ShindeN                  | L   | 1.000      | -            | -                | -                | -         |   -14.09 | abr, mello, nolkz, prt, slashzz  |
|           26 |      524 | 2025-02-12 | Team Solid               | L   | 1.000      | -            | -                | -                | -         |    -8.33 | abr, mello, nolkz, prt, slashzz  |
|           25 |      620 | 2025-02-09 | AdalYamigos              | W   | 1.000      | 0.371        | 0.004 (0.002)    | 0.194 (0.072)    | 0 (0.000) |    17.73 | abr, mello, nolkz, prt, slashzz  |
|           24 |      739 | 2025-02-07 | BESTIA                   | L   | 1.000      | -            | -                | -                | -         |    -4.84 | abr, mello, nolkz, prt, slashzz  |
|           23 |      936 | 2025-02-04 | W7m esports              | L   | 1.000      | -            | -                | -                | -         |   -22.94 | abr, mello, nolkz, prt, slashzz  |
|           22 |     1204 | 2025-01-09 | Fake do Biru             | L   | 0.861      | -            | -                | -                | -         |   -17.53 | abr, mello, nolkz, pedrinzy, prt |
|           21 |     1431 | 2024-12-21 | LaChampionsLiga          | W   | 0.734      | 0.384        | 0.003 (0.001)    | 0.444 (0.125)    | 0 (0.000) |     9.72 | abr, Lich, mello, pedrinzy, prt  |
|           20 |     1503 | 2024-12-20 | Fake do Biru             | L   | 0.726      | -            | -                | -                | -         |   -15.52 | abr, Lich, mello, pedrinzy, prt  |
|           19 |     1571 | 2024-12-17 | 20/70                    | W   | 0.706      | 0.384        | 0.001 (0.000)    | 0.290 (0.079)    | 0 (0.000) |     9.13 | abr, Lich, mello, pedrinzy, prt  |
|           18 |     1607 | 2024-12-15 | Bounty Hunters Esports   | L   | 0.694      | -            | -                | -                | -         |   -10.74 | abr, Lich, mello, pedrinzy, prt  |
|           17 |     1666 | 2024-12-14 | Hype Esports             | W   | 0.688      | -            | -                | -                | 0 (0.000) |     9.31 | abr, Lich, mello, pedrinzy, prt  |
|           16 |     1756 | 2024-12-13 | TROPA DO TACO            | L   | 0.681      | -            | -                | -                | -         |    -8.80 | abr, Lich, mello, pedrinzy, prt  |
|           15 |     1794 | 2024-12-13 | Bad News Chickens        | L   | 0.679      | -            | -                | -                | -         |   -12.33 | abr, Lich, mello, pedrinzy, prt  |
|           14 |     1948 | 2024-12-09 | UNO MILLE                | L   | 0.653      | -            | -                | -                | -         |    -9.73 | abr, Lich, mello, pedrinzy, prt  |
|           13 |     2264 | 2024-12-03 | UNO MILLE                | W   | 0.613      | 0.262        | 0.010 (0.002)    | 0.526 (0.084)    | 0 (0.000) |    10.16 | abr, Lich, mello, pedrinzy, prt  |
|           12 |     2339 | 2024-12-02 | AMIGOS (Brazilian team)  | W   | 0.606      | -            | -                | -                | 0 (0.000) |     4.52 | abr, Lich, mello, pedrinzy, prt  |
|           11 |     2502 | 2024-11-30 | TROPA DO TACO            | W   | 0.593      | 0.262        | 0.004 (0.001)    | 0.381 (0.059)    | 0 (0.000) |    10.55 | abr, Lich, mello, pedrinzy, prt  |
|           10 |     3640 | 2024-11-10 | Bad News Chickens        | W   | 0.461      | 0.242        | 0.003 (0.000)    | -                | 0 (0.000) |     6.51 | abr, Lich, mello, pedrinzy, prt  |
|            9 |     3692 | 2024-11-09 | Nitro.GG                 | W   | 0.455      | 0.242        | 0.002 (0.000)    | 0.518 (0.057)    | 0 (0.000) |     6.62 | abr, Lich, mello, pedrinzy, prt  |
|            8 |     3774 | 2024-11-08 | PaiN Gaming Academy      | W   | 0.448      | -            | -                | -                | -         |     3.48 | abr, Lich, mello, pedrinzy, prt  |
|            7 |     3786 | 2024-11-08 | Sharks Esports           | L   | 0.447      | -            | -                | -                | -         |    -2.14 | abr, Lich, mello, pedrinzy, prt  |
|            6 |     3882 | 2024-11-06 | Bad News Chickens        | W   | 0.433      | 0.371        | 0.003 (0.000)    | 0.239 (0.038)    | -         |     6.30 | abr, Lich, mello, pedrinzy, prt  |
|            5 |     4115 | 2024-11-02 | Nova holanda             | L   | 0.407      | -            | -                | -                | -         |    -8.34 | abr, Lich, mello, pedrinzy, prt  |
|            4 |     4167 | 2024-11-01 | Floripa Stars            | W   | 0.402      | 0.371        | -                | 0.302 (0.045)    | -         |     6.05 | abr, Lich, mello, pedrinzy, prt  |
|            3 |     4253 | 2024-10-31 | Players (Brazilian team) | W   | 0.392      | 0.371        | 0.008 (0.001)    | 0.637 (0.093)    | -         |     7.08 | abr, Lich, mello, pedrinzy, prt  |
|            2 |     4401 | 2024-10-28 | Patins da Ferrari        | W   | 0.374      | -            | -                | -                | -         |     3.19 | abr, Lich, mello, pedrinzy, prt  |
|            1 |     6099 | 2024-09-27 | Bad News Chickens        | L   | 0.167      | -            | -                | -                | -         |    -2.69 | abr, Lich, mello, pedrinzy, prt  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($840.50)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-09 |      0.653 | $500.00        | $326.67         |
| 2024-11-10 |      0.461 | $375.00        | $172.71         |
| 2024-11-09 |      0.455 | $750.00        | $341.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
