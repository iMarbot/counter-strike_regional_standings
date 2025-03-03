### Roster Details<br />
Team Name: Game Hunters<br />
Roster: abr, mello, nolkz, prt, slashzz<br />
Global Rank: [269](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [52]( ../standings_americas.md)<br />
<br />
Final Rank Value:  670.0<br />
<br />
Final Rank Value (670.0) = Starting Rank Value (694.3) + Head To Head Adjustments (-24.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.069[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.3
- 400 + ( ( 0.147 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 694.3


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
|           29 |      287 | 2025-02-17 | Players (Brazilian team) | L   | 1.000      | -            | -                | -                | -         |   -11.06 | abr, mello, nolkz, prt, slashzz  |
|           28 |      403 | 2025-02-15 | KRÜ Esports              | W   | 1.000      | 0.371        | 0.001 (0.001)    | 0.131 (0.049)    | 0 (0.000) |    14.92 | abr, mello, nolkz, prt, slashzz  |
|           27 |      491 | 2025-02-14 | ShindeN                  | L   | 1.000      | -            | -                | -                | -         |   -14.21 | abr, mello, nolkz, prt, slashzz  |
|           26 |      536 | 2025-02-12 | Team Solid               | L   | 1.000      | -            | -                | -                | -         |    -8.37 | abr, mello, nolkz, prt, slashzz  |
|           25 |      632 | 2025-02-09 | AdalYamigos              | W   | 1.000      | 0.371        | 0.004 (0.002)    | 0.193 (0.072)    | 0 (0.000) |    17.72 | abr, mello, nolkz, prt, slashzz  |
|           24 |      751 | 2025-02-07 | BESTIA                   | L   | 1.000      | -            | -                | -                | -         |    -4.80 | abr, mello, nolkz, prt, slashzz  |
|           23 |      948 | 2025-02-04 | W7m esports              | L   | 1.000      | -            | -                | -                | -         |   -22.91 | abr, mello, nolkz, prt, slashzz  |
|           22 |     1216 | 2025-01-09 | Fake do Biru             | L   | 0.852      | -            | -                | -                | -         |   -17.38 | abr, mello, nolkz, pedrinzy, prt |
|           21 |     1443 | 2024-12-21 | LaChampionsLiga          | W   | 0.726      | 0.384        | 0.003 (0.001)    | 0.440 (0.123)    | 0 (0.000) |     9.60 | abr, Lich, mello, pedrinzy, prt  |
|           20 |     1515 | 2024-12-20 | Fake do Biru             | L   | 0.718      | -            | -                | -                | -         |   -15.35 | abr, Lich, mello, pedrinzy, prt  |
|           19 |     1583 | 2024-12-17 | 20/70                    | W   | 0.697      | 0.384        | 0.001 (0.000)    | 0.286 (0.077)    | 0 (0.000) |     9.02 | abr, Lich, mello, pedrinzy, prt  |
|           18 |     1619 | 2024-12-15 | Bounty Hunters Esports   | L   | 0.686      | -            | -                | -                | -         |   -10.60 | abr, Lich, mello, pedrinzy, prt  |
|           17 |     1678 | 2024-12-14 | Hype Esports             | W   | 0.680      | -            | -                | -                | 0 (0.000) |     9.18 | abr, Lich, mello, pedrinzy, prt  |
|           16 |     1768 | 2024-12-13 | TROPA DO TACO            | L   | 0.673      | -            | -                | -                | -         |    -8.72 | abr, Lich, mello, pedrinzy, prt  |
|           15 |     1806 | 2024-12-13 | Bad News Chickens        | L   | 0.671      | -            | -                | -                | -         |   -12.19 | abr, Lich, mello, pedrinzy, prt  |
|           14 |     1960 | 2024-12-09 | UNO MILLE                | L   | 0.645      | -            | -                | -                | -         |    -9.62 | abr, Lich, mello, pedrinzy, prt  |
|           13 |     2276 | 2024-12-03 | UNO MILLE                | W   | 0.605      | 0.262        | 0.010 (0.002)    | 0.522 (0.083)    | 0 (0.000) |    10.02 | abr, Lich, mello, pedrinzy, prt  |
|           12 |     2351 | 2024-12-02 | AMIGOS (Brazilian team)  | W   | 0.598      | -            | -                | -                | 0 (0.000) |     4.46 | abr, Lich, mello, pedrinzy, prt  |
|           11 |     2514 | 2024-11-30 | TROPA DO TACO            | W   | 0.585      | 0.262        | 0.004 (0.001)    | 0.377 (0.058)    | 0 (0.000) |    10.38 | abr, Lich, mello, pedrinzy, prt  |
|           10 |     3652 | 2024-11-10 | Bad News Chickens        | W   | 0.452      | 0.242        | 0.002 (0.000)    | -                | 0 (0.000) |     6.38 | abr, Lich, mello, pedrinzy, prt  |
|            9 |     3704 | 2024-11-09 | Nitro.GG                 | W   | 0.447      | 0.242        | 0.002 (0.000)    | 0.512 (0.055)    | 0 (0.000) |     6.50 | abr, Lich, mello, pedrinzy, prt  |
|            8 |     3786 | 2024-11-08 | PaiN Gaming Academy      | W   | 0.440      | -            | -                | -                | -         |     3.39 | abr, Lich, mello, pedrinzy, prt  |
|            7 |     3798 | 2024-11-08 | Sharks Esports           | L   | 0.439      | -            | -                | -                | -         |    -2.07 | abr, Lich, mello, pedrinzy, prt  |
|            6 |     3894 | 2024-11-06 | Bad News Chickens        | W   | 0.425      | 0.371        | 0.002 (0.000)    | 0.234 (0.037)    | -         |     6.17 | abr, Lich, mello, pedrinzy, prt  |
|            5 |     4127 | 2024-11-02 | Nova holanda             | L   | 0.398      | -            | -                | -                | -         |    -8.16 | abr, Lich, mello, pedrinzy, prt  |
|            4 |     4179 | 2024-11-01 | Floripa Stars            | W   | 0.393      | 0.371        | -                | 0.296 (0.043)    | -         |     5.91 | abr, Lich, mello, pedrinzy, prt  |
|            3 |     4265 | 2024-10-31 | Players (Brazilian team) | W   | 0.384      | 0.371        | 0.008 (0.001)    | 0.632 (0.090)    | -         |     6.93 | abr, Lich, mello, pedrinzy, prt  |
|            2 |     4413 | 2024-10-28 | Patins da Ferrari        | W   | 0.366      | -            | -                | -                | -         |     3.11 | abr, Lich, mello, pedrinzy, prt  |
|            1 |     6111 | 2024-09-27 | Bad News Chickens        | L   | 0.159      | -            | -                | -                | -         |    -2.56 | abr, Lich, mello, pedrinzy, prt  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($827.19)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-09 |      0.645 | $500.00        | $322.57         |
| 2024-11-10 |      0.452 | $375.00        | $169.64         |
| 2024-11-09 |      0.447 | $750.00        | $334.98         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
