### Roster Details<br />
Team Name: AK BARS<br />
Roster: enzero, kamazbob, kenz1, plushax, SNk<br />
Global Rank: [93](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  865.7<br />
<br />
Final Rank Value (865.7) = Starting Rank Value (841.0) + Head To Head Adjustments (24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.286[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 841.0
- 400 + ( ( 0.220 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 841.0


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
|           18 |     1652 | 2024-12-15 | Team Novaq             | L   | 0.683      | -            | -                | -                | -         |    -4.48 | enzero, kamazbob, kenz1, plushax, SNk |
|           17 |     1727 | 2024-12-14 | AimAssassins           | W   | 0.676      | 0.333        | 0.004 (0.001)    | 0.238 (0.054)    | 1 (0.676) |    13.19 | enzero, kamazbob, kenz1, plushax, SNk |
|           16 |     1801 | 2024-12-13 | Team Novaq             | W   | 0.671      | 0.333        | 0.030 (0.007)    | 0.393 (0.088)    | 1 (0.671) |    17.13 | enzero, kamazbob, kenz1, plushax, SNk |
|           15 |     1809 | 2024-12-13 | GamePoint (Uzbek team) | W   | 0.670      | 0.333        | -                | 0.038 (0.009)    | 1 (0.670) |     4.96 | enzero, kamazbob, kenz1, plushax, SNk |
|           14 |     2404 | 2024-12-01 | RAGE (Kazakh team)     | W   | 0.593      | 0.143        | 0.005 (0.000)    | 0.179 (0.015)    | 0 (0.000) |     8.63 | enzero, kamazbob, kenz1, plushax, SNk |
|           13 |     2416 | 2024-12-01 | Mix52                  | W   | 0.592      | 0.143        | 0.002 (0.000)    | 0.063 (0.005)    | 0 (0.000) |     7.38 | enzero, kamazbob, kenz1, plushax, SNk |
|           12 |     2439 | 2024-12-01 | ALLINNERS              | L   | 0.591      | -            | -                | -                | -         |   -12.38 | enzero, kamazbob, kenz1, plushax, SNk |
|           11 |     3729 | 2024-11-09 | ALLINNERS              | L   | 0.445      | -            | -                | -                | -         |    -9.06 | arun, enzero, kamazbob, kenz1, Yaqk   |
|           10 |     3751 | 2024-11-09 | DEPO                   | W   | 0.443      | 0.143        | 0.006 (0.000)    | 0.291 (0.018)    | 0 (0.000) |     5.77 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            9 |     3807 | 2024-11-08 | ALLINNERS              | L   | 0.438      | -            | -                | -                | -         |    -9.14 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            8 |     3907 | 2024-11-06 | MYSKILL                | W   | 0.424      | 0.143        | 0.002 (0.000)    | 0.127 (0.008)    | 0 (0.000) |     3.73 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            7 |     4162 | 2024-11-02 | Yamato Esports         | W   | 0.397      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.74 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            6 |     5548 | 2024-10-06 | RAGE (Kazakh team)     | L   | 0.216      | -            | -                | -                | -         |    -3.52 | enzero, kade0, kamazbob, kenz1, SNk   |
|            5 |     5560 | 2024-10-05 | MYSKILL                | W   | 0.215      | 0.333        | 0.002 (0.000)    | 0.127 (0.009)    | 1 (0.215) |     1.90 | enzero, kade0, kamazbob, kenz1, SNk   |
|            4 |     5630 | 2024-10-05 | DEPO                   | W   | 0.209      | 0.333        | 0.006 (0.000)    | 0.291 (0.020)    | 1 (0.209) |     2.71 | enzero, kade0, kamazbob, kenz1, SNk   |
|            3 |     5642 | 2024-10-04 | RAGE (Kazakh team)     | L   | 0.208      | -            | -                | -                | -         |    -3.43 | enzero, kade0, kamazbob, kenz1, SNk   |
|            2 |     6528 | 2024-09-22 | MYSKILL                | W   | 0.124      | 0.143        | 0.002 (0.000)    | 0.127 (0.002)    | -         |     1.09 | enzero, kade0, kamazbob, kenz1, SNk   |
|            1 |     7064 | 2024-09-13 | MYSKILL                | L   | 0.068      | -            | -                | -                | -         |    -1.56 | arun, enzero, kamazbob, kenz1, SNk    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,712.82)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.683 | $2,500.00      | $1,707.99       |
| 2024-11-09 |      0.445 | $1,044.04      | $464.21         |
| 2024-10-06 |      0.216 | $2,500.00      | $540.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
