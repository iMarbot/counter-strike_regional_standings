### Roster Details<br />
Team Name: Vagrants<br />
Roster: brett, Cyrix, mason, Sandman, Seb<br />
Global Rank: [224](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  694.8<br />
<br />
Final Rank Value (694.8) = Starting Rank Value (659.3) + Head To Head Adjustments (35.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.256[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.006[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 659.3
- 400 + ( ( 0.130 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 659.3


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
|           26 |      585 | 2025-02-10 | Immigrants Peek        | L   | 1.000      | -            | -                | -                | -         |   -17.49 | brett, Cyrix, mason, Sandman, Seb |
|           25 |      628 | 2025-02-09 | SUPER EVIL GANG        | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.352 (0.050)    | 0 (0.000) |    16.89 | brett, Cyrix, mason, Sandman, Seb |
|           24 |      665 | 2025-02-08 | Nouns Esports          | L   | 1.000      | -            | -                | -                | -         |    -8.13 | brett, Cyrix, mason, Sandman, Seb |
|           23 |      684 | 2025-02-08 | Immigrants Peek        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.366 (0.052)    | 0 (0.000) |    12.97 | brett, Cyrix, mason, Sandman, Seb |
|           22 |      746 | 2025-02-07 | Chicken Coop Esports   | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.187 (0.027)    | 0 (0.000) |    14.88 | brett, Cyrix, mason, Sandman, Seb |
|           21 |     1671 | 2024-12-14 | Nouns Esports          | L   | 0.680      | -            | -                | -                | -         |    -5.22 | Cyrix, mason, micro, Sandman, Seb |
|           20 |     1754 | 2024-12-13 | Akimbo Esports         | W   | 0.674      | 0.143        | 0.003 (0.000)    | 0.327 (0.031)    | 0 (0.000) |    10.45 | Cyrix, mason, micro, Sandman, Seb |
|           19 |     1757 | 2024-12-13 | MarcaRegistrada        | W   | 0.674      | 0.143        | 0.000 (0.000)    | 0.124 (0.012)    | 0 (0.000) |     9.31 | Cyrix, mason, micro, Sandman, Seb |
|           18 |     1760 | 2024-12-13 | Get Fked               | W   | 0.674      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     4.02 | Cyrix, mason, micro, Sandman, Seb |
|           17 |     5316 | 2024-10-09 | Timbermen              | L   | 0.240      | -            | -                | -                | -         |    -3.92 | Cyrix, DJF, Sandman, Seb, Tender  |
|           16 |     5323 | 2024-10-09 | Timbermen              | W   | 0.240      | 0.477        | 0.003 (0.000)    | 0.044 (0.005)    | 0 (0.000) |     3.71 | Cyrix, DJF, Sandman, Seb, Tender  |
|           15 |     5386 | 2024-10-08 | Mythic                 | W   | 0.234      | 0.477        | -                | 0.021 (0.002)    | 0 (0.000) |     2.27 | Cyrix, DJF, Sandman, Seb, Tender  |
|           14 |     5392 | 2024-10-08 | Mythic                 | W   | 0.233      | 0.477        | -                | 0.021 (0.002)    | -         |     2.31 | Cyrix, DJF, Sandman, Seb, Tender  |
|           13 |     5708 | 2024-10-03 | Legacy                 | L   | 0.200      | -            | -                | -                | -         |    -1.28 | Cyrix, DJF, Sandman, Seb, Tender  |
|           12 |     5713 | 2024-10-03 | Legacy                 | L   | 0.200      | -            | -                | -                | -         |    -1.30 | Cyrix, DJF, Sandman, Seb, Tender  |
|           11 |     5819 | 2024-10-01 | Bad News Capybaras     | W   | 0.187      | 0.477        | 0.000 (0.000)    | 0.113 (0.010)    | -         |     3.03 | Cyrix, DJF, Sandman, Seb, Tender  |
|           10 |     5824 | 2024-10-01 | Bad News Capybaras     | L   | 0.187      | -            | -                | -                | -         |    -2.90 | Cyrix, DJF, Sandman, Seb, Tender  |
|            9 |     6252 | 2024-09-25 | BLUEJAYS               | L   | 0.147      | -            | -                | -                | -         |    -0.25 | Cyrix, DJF, Sandman, Seb, Tender  |
|            8 |     6256 | 2024-09-25 | BLUEJAYS               | W   | 0.147      | 0.477        | 0.031 (0.002)    | 0.511 (0.036)    | -         |     4.38 | Cyrix, DJF, Sandman, Seb, Tender  |
|            7 |     6348 | 2024-09-24 | Familia Maquininha     | L   | 0.140      | -            | -                | -                | -         |    -2.03 | Cyrix, DJF, Sandman, Seb, Tender  |
|            6 |     6350 | 2024-09-24 | Familia Maquininha     | L   | 0.140      | -            | -                | -                | -         |    -2.05 | Cyrix, DJF, Sandman, Seb, Tender  |
|            5 |     6509 | 2024-09-22 | Jahsdnmasjdm v2        | L   | 0.126      | -            | -                | -                | -         |    -2.87 | Andrew, Cyrix, DJF, Sandman, Seb  |
|            4 |     6687 | 2024-09-19 | Chill Guys             | L   | 0.106      | -            | -                | -                | -         |    -1.64 | Andrew, Cyrix, DJF, Sandman, Seb  |
|            3 |     7345 | 2024-09-08 | Nouns Esports          | L   | 0.032      | -            | -                | -                | -         |    -0.41 | Cyrix, DJF, Sandman, Seb, Wolffe  |
|            2 |     7389 | 2024-09-07 | LAG Gaming             | W   | 0.026      | 0.333        | 0.004 (0.000)    | -                | 1 (0.026) |     0.56 | Cyrix, DJF, Sandman, Seb, Wolffe  |
|            1 |     7423 | 2024-09-07 | Kraken (American team) | W   | 0.025      | -            | -                | -                | 1 (0.025) |     0.15 | Cyrix, DJF, Sandman, Seb, Wolffe  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($409.11)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.313 | $1,200.00      | $375.50         |
| 2024-09-08 |      0.034 | $1,000.00      | $33.61          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
