### Roster Details<br />
Team Name: BetBoom Team<br />
Roster: Ax1Le, Boombl4, Magnojez, s1ren, zorte<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1093.6<br />
<br />
Final Rank Value (1093.6) = Starting Rank Value (1020.5) + Head To Head Adjustments (73.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.503[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.100[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.311<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1020.5
- 400 + ( ( 0.311 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1020.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      552 | 2025-02-11 | Astralis           | L   | 1.000      | -            | -                | -                | -         |    -0.92 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           30 |      559 | 2025-02-11 | Hesta              | W   | 1.000      | 0.143        | -                | 0.656 (0.094)    | 0 (0.000) |     5.33 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           29 |      588 | 2025-02-10 | Team Falcons       | L   | 1.000      | -            | -                | -                | -         |    -0.50 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           28 |      598 | 2025-02-10 | Nemiga Gaming      | W   | 1.000      | 0.143        | 0.177 (0.025)    | 0.351 (0.050)    | 0 (0.000) |    11.98 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           27 |      804 | 2025-02-07 | Passion UA         | L   | 1.000      | -            | -                | -                | -         |   -15.86 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           26 |      850 | 2025-02-06 | Ninjas in Pyjamas  | W   | 1.000      | 0.143        | -                | 0.606 (0.087)    | 0 (0.000) |     2.91 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           25 |      909 | 2025-02-05 | Passion UA         | L   | 1.000      | -            | -                | -                | -         |   -17.19 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           24 |      920 | 2025-02-05 | Ninjas in Pyjamas  | W   | 1.000      | 0.143        | -                | 0.606 (0.087)    | 0 (0.000) |     2.38 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           23 |     1144 | 2025-01-23 | G2 Esports         | L   | 0.953      | -            | -                | -                | -         |    -0.48 | Ax1Le, KaiR0N-, Magnojez, nafany, s1ren  |
|           22 |     1155 | 2025-01-19 | FURIA              | W   | 0.925      | 0.363        | 0.094 (0.032)    | 0.384 (0.129)    | 0 (0.000) |    25.92 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           21 |     1170 | 2025-01-17 | MOUZ               | W   | 0.913      | 0.363        | 1.000 (0.331)    | 0.473 (0.157)    | 0 (0.000) |    28.57 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           20 |     3127 | 2024-11-20 | GamerLegion        | L   | 0.525      | -            | -                | -                | -         |    -0.90 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           19 |     3136 | 2024-11-19 | SAW                | W   | 0.522      | 0.143        | 0.262 (0.020)    | -                | 1 (0.522) |    13.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           18 |     3174 | 2024-11-18 | Nemiga Gaming      | W   | 0.516      | 0.143        | 0.177 (0.013)    | -                | 1 (0.516) |     8.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           17 |     3216 | 2024-11-17 | Fnatic             | L   | 0.510      | -            | -                | -                | -         |    -7.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           16 |     3265 | 2024-11-17 | Team Vitality      | L   | 0.505      | -            | -                | -                | -         |    -0.12 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           15 |     3284 | 2024-11-16 | UNiTY esports      | W   | 0.504      | -            | -                | -                | 1 (0.504) |     4.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           14 |     3545 | 2024-11-12 | 500                | W   | 0.473      | 0.384        | 0.091 (0.017)    | 1.000 (0.182)    | -         |     7.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           13 |     3552 | 2024-11-12 | Ninjas in Pyjamas  | W   | 0.472      | 0.384        | 0.025 (0.004)    | -                | -         |     4.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           12 |     3613 | 2024-11-11 | Dynamo Eclot       | W   | 0.466      | 0.384        | 0.127 (0.023)    | 0.703 (0.126)    | -         |     8.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           11 |     3876 | 2024-11-06 | OG                 | L   | 0.434      | -            | -                | -                | -         |    -8.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           10 |     5267 | 2024-10-11 | FAVBET Team        | L   | 0.258      | -            | -                | -                | -         |    -6.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            9 |     5561 | 2024-10-05 | SAW                | L   | 0.220      | -            | -                | -                | -         |    -1.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            8 |     5596 | 2024-10-05 | Rooster            | W   | 0.219      | -            | -                | -                | 1 (0.219) |     0.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            7 |     5669 | 2024-10-04 | FlyQuest           | L   | 0.212      | -            | -                | -                | -         |    -2.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            6 |     6018 | 2024-09-28 | GamerLegion        | W   | 0.173      | -            | -                | -                | -         |     0.79 | KaiR0N-, Magnojez, s1ren, SELLTER, zorte |
|            5 |     6074 | 2024-09-28 | 3DMAX              | W   | 0.171      | 0.435        | 0.295 (0.022)    | 0.535 (0.040)    | -         |     5.19 | KaiR0N-, Magnojez, s1ren, SELLTER, zorte |
|            4 |     6114 | 2024-09-27 | HEROIC             | W   | 0.166      | 0.435        | 0.131 (0.009)    | -                | -         |     3.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            3 |     6208 | 2024-09-26 | Monte              | W   | 0.159      | 0.435        | -                | 0.704 (0.049)    | -         |     1.80 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            2 |     7538 | 2024-09-06 | CYBERSHOKE Esports | L   | 0.024      | -            | -                | -                | -         |    -0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            1 |     7612 | 2024-09-05 | Tricked Esport     | W   | 0.019      | -            | -                | -                | -         |     0.15 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,706.75)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-01-26 |      0.973 | $25,000.00     | $24,312.50      |
| 2024-11-12 |      0.473 | $12,500.00     | $5,907.70       |
| 2024-10-06 |      0.227 | $3,000.00      | $681.88         |
| 2024-09-28 |      0.173 | $22,000.00     | $3,804.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
