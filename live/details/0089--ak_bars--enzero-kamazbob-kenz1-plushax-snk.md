### Roster Details<br />
Team Name: AK BARS<br />
Roster: enzero, kamazbob, kenz1, plushax, SNk<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  867.5<br />
<br />
Final Rank Value (867.5) = Starting Rank Value (842.7) + Head To Head Adjustments (24.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.290[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 842.7
- 400 + ( ( 0.222 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 842.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     1640 | 2024-12-15 | Team Novaq             | L   | 0.691      | -            | -                | -                | -         |    -4.51 | enzero, kamazbob, kenz1, plushax, SNk |
|           17 |     1715 | 2024-12-14 | AimAssassins           | W   | 0.685      | 0.333        | 0.004 (0.001)    | 0.240 (0.055)    | 1 (0.685) |    13.35 | enzero, kamazbob, kenz1, plushax, SNk |
|           16 |     1789 | 2024-12-13 | Team Novaq             | W   | 0.679      | 0.333        | 0.030 (0.007)    | 0.396 (0.090)    | 1 (0.679) |    17.37 | enzero, kamazbob, kenz1, plushax, SNk |
|           15 |     1797 | 2024-12-13 | GamePoint (Uzbek team) | W   | 0.679      | 0.333        | -                | 0.039 (0.009)    | 1 (0.679) |     5.00 | enzero, kamazbob, kenz1, plushax, SNk |
|           14 |     2392 | 2024-12-01 | RAGE (Kazakh team)     | W   | 0.601      | 0.143        | 0.005 (0.000)    | 0.182 (0.016)    | 0 (0.000) |     8.78 | enzero, kamazbob, kenz1, plushax, SNk |
|           13 |     2406 | 2024-12-01 | Mix52                  | W   | 0.600      | 0.143        | 0.002 (0.000)    | 0.064 (0.005)    | 0 (0.000) |     7.46 | enzero, kamazbob, kenz1, plushax, SNk |
|           12 |     2427 | 2024-12-01 | ALLINNERS              | L   | 0.599      | -            | -                | -                | -         |   -12.57 | enzero, kamazbob, kenz1, plushax, SNk |
|           11 |     3717 | 2024-11-09 | ALLINNERS              | L   | 0.453      | -            | -                | -                | -         |    -9.24 | arun, enzero, kamazbob, kenz1, Yaqk   |
|           10 |     3739 | 2024-11-09 | DEPO                   | W   | 0.452      | 0.143        | 0.006 (0.000)    | 0.297 (0.019)    | 0 (0.000) |     5.91 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            9 |     3795 | 2024-11-08 | ALLINNERS              | L   | 0.446      | -            | -                | -                | -         |    -9.33 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            8 |     3895 | 2024-11-06 | MYSKILL                | W   | 0.432      | 0.143        | 0.002 (0.000)    | 0.129 (0.008)    | 0 (0.000) |     3.81 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            7 |     4150 | 2024-11-02 | Yamato Esports         | W   | 0.405      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.76 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            6 |     5536 | 2024-10-06 | RAGE (Kazakh team)     | L   | 0.224      | -            | -                | -                | -         |    -3.64 | enzero, kade0, kamazbob, kenz1, SNk   |
|            5 |     5548 | 2024-10-05 | MYSKILL                | W   | 0.223      | 0.333        | 0.002 (0.000)    | 0.129 (0.010)    | 1 (0.223) |     1.98 | enzero, kade0, kamazbob, kenz1, SNk   |
|            4 |     5618 | 2024-10-05 | DEPO                   | W   | 0.218      | 0.333        | 0.006 (0.000)    | 0.297 (0.022)    | 1 (0.218) |     2.83 | enzero, kade0, kamazbob, kenz1, SNk   |
|            3 |     5630 | 2024-10-04 | RAGE (Kazakh team)     | L   | 0.217      | -            | -                | -                | -         |    -3.55 | enzero, kade0, kamazbob, kenz1, SNk   |
|            2 |     6516 | 2024-09-22 | MYSKILL                | W   | 0.132      | 0.143        | 0.002 (0.000)    | 0.129 (0.002)    | -         |     1.17 | enzero, kade0, kamazbob, kenz1, SNk   |
|            1 |     7052 | 2024-09-13 | MYSKILL                | L   | 0.077      | -            | -                | -                | -         |    -1.75 | arun, enzero, kamazbob, kenz1, SNk    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,762.35)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.691 | $2,500.00      | $1,728.47       |
| 2024-11-09 |      0.453 | $1,044.04      | $472.77         |
| 2024-10-06 |      0.224 | $2,500.00      | $561.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
