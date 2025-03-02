### Roster Details<br />
Team Name: Vagrants<br />
Roster: brett, Cyrix, mason, Sandman, Seb<br />
Global Rank: [223](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
<br />
Final Rank Value:  693.4<br />
<br />
Final Rank Value (693.4) = Starting Rank Value (660.2) + Head To Head Adjustments (33.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.008[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.2
- 400 + ( ( 0.130 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 660.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      573 | 2025-02-10 | Immigrants Peek        | L   | 1.000      | -            | -                | -                | -         |   -17.55 | brett, Cyrix, mason, Sandman, Seb |
|           25 |      616 | 2025-02-09 | Alter Iron Club        | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.356 (0.051)    | 0 (0.000) |    16.11 | brett, Cyrix, mason, Sandman, Seb |
|           24 |      653 | 2025-02-08 | Nouns Esports          | L   | 1.000      | -            | -                | -                | -         |    -8.76 | brett, Cyrix, mason, Sandman, Seb |
|           23 |      672 | 2025-02-08 | Immigrants Peek        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.366 (0.052)    | 0 (0.000) |    12.88 | brett, Cyrix, mason, Sandman, Seb |
|           22 |      734 | 2025-02-07 | Chicken Coop Esports   | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.189 (0.027)    | 0 (0.000) |    14.68 | brett, Cyrix, mason, Sandman, Seb |
|           21 |     1659 | 2024-12-14 | Nouns Esports          | L   | 0.688      | -            | -                | -                | -         |    -5.63 | Cyrix, mason, micro, Sandman, Seb |
|           20 |     1742 | 2024-12-13 | Akimbo Esports         | W   | 0.682      | 0.143        | 0.003 (0.000)    | 0.331 (0.032)    | 0 (0.000) |    10.59 | Cyrix, mason, micro, Sandman, Seb |
|           19 |     1745 | 2024-12-13 | MarcaRegistrada        | W   | 0.682      | 0.143        | 0.000 (0.000)    | 0.125 (0.012)    | 0 (0.000) |     9.41 | Cyrix, mason, micro, Sandman, Seb |
|           18 |     1748 | 2024-12-13 | Get Fked               | W   | 0.682      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     4.05 | Cyrix, mason, micro, Sandman, Seb |
|           17 |     5304 | 2024-10-09 | Timbermen              | L   | 0.249      | -            | -                | -                | -         |    -3.31 | Cyrix, DJF, Sandman, Seb, Tender  |
|           16 |     5311 | 2024-10-09 | Timbermen              | W   | 0.248      | 0.477        | 0.011 (0.001)    | 0.160 (0.019)    | 0 (0.000) |     4.60 | Cyrix, DJF, Sandman, Seb, Tender  |
|           15 |     5374 | 2024-10-08 | Mythic                 | W   | 0.242      | 0.477        | -                | 0.023 (0.003)    | 0 (0.000) |     2.29 | Cyrix, DJF, Sandman, Seb, Tender  |
|           14 |     5380 | 2024-10-08 | Mythic                 | W   | 0.242      | 0.477        | -                | 0.023 (0.003)    | -         |     2.33 | Cyrix, DJF, Sandman, Seb, Tender  |
|           13 |     5696 | 2024-10-03 | Legacy                 | L   | 0.209      | -            | -                | -                | -         |    -1.33 | Cyrix, DJF, Sandman, Seb, Tender  |
|           12 |     5701 | 2024-10-03 | Legacy                 | L   | 0.208      | -            | -                | -                | -         |    -1.34 | Cyrix, DJF, Sandman, Seb, Tender  |
|           11 |     5807 | 2024-10-01 | Bad News Capybaras     | W   | 0.195      | 0.477        | 0.001 (0.000)    | 0.115 (0.011)    | -         |     3.14 | Cyrix, DJF, Sandman, Seb, Tender  |
|           10 |     5812 | 2024-10-01 | Bad News Capybaras     | L   | 0.195      | -            | -                | -                | -         |    -3.05 | Cyrix, DJF, Sandman, Seb, Tender  |
|            9 |     6240 | 2024-09-25 | BOSS                   | L   | 0.155      | -            | -                | -                | -         |    -0.98 | Cyrix, DJF, Sandman, Seb, Tender  |
|            8 |     6244 | 2024-09-25 | BOSS                   | W   | 0.155      | 0.477        | 0.014 (0.001)    | 0.327 (0.024)    | -         |     3.93 | Cyrix, DJF, Sandman, Seb, Tender  |
|            7 |     6336 | 2024-09-24 | Familia Maquininha     | L   | 0.148      | -            | -                | -                | -         |    -2.10 | Cyrix, DJF, Sandman, Seb, Tender  |
|            6 |     6338 | 2024-09-24 | Familia Maquininha     | L   | 0.148      | -            | -                | -                | -         |    -2.12 | Cyrix, DJF, Sandman, Seb, Tender  |
|            5 |     6497 | 2024-09-22 | Jahsdnmasjdm v2        | L   | 0.134      | -            | -                | -                | -         |    -3.06 | Andrew, Cyrix, DJF, Sandman, Seb  |
|            4 |     6675 | 2024-09-19 | Chill Guys             | L   | 0.114      | -            | -                | -                | -         |    -1.79 | Andrew, Cyrix, DJF, Sandman, Seb  |
|            3 |     7333 | 2024-09-08 | Nouns Esports          | L   | 0.040      | -            | -                | -                | -         |    -0.52 | Cyrix, DJF, Sandman, Seb, Wolffe  |
|            2 |     7377 | 2024-09-07 | LAG Gaming             | W   | 0.035      | 0.333        | 0.001 (0.000)    | -                | 1 (0.035) |     0.49 | Cyrix, DJF, Sandman, Seb, Wolffe  |
|            1 |     7411 | 2024-09-07 | Kraken (American team) | W   | 0.033      | -            | -                | -                | 1 (0.033) |     0.20 | Cyrix, DJF, Sandman, Seb, Wolffe  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($427.14)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.321 | $1,200.00      | $385.33         |
| 2024-09-08 |      0.042 | $1,000.00      | $41.81          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
