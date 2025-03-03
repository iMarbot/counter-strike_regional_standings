### Roster Details<br />
Team Name: BetBoom Team<br />
Roster: Ax1Le, Boombl4, Magnojez, s1ren, zorte<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1091.0<br />
<br />
Final Rank Value (1091.0) = Starting Rank Value (1018.9) + Head To Head Adjustments (72.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.433[<sup>2</sup>](#table1)
- Opponent Network: 0.098[<sup>2</sup>](#table1)
- LAN Wins: 0.202[<sup>2</sup>](#table1)

The average of these factors is 0.309<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1018.9
- 400 + ( ( 0.309 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1018.9


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
|           31 |      564 | 2025-02-11 | Astralis           | L   | 1.000      | -            | -                | -                | -         |    -0.90 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           30 |      571 | 2025-02-11 | Hesta              | W   | 1.000      | 0.143        | -                | 0.655 (0.094)    | 0 (0.000) |     5.40 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           29 |      600 | 2025-02-10 | Team Falcons       | L   | 1.000      | -            | -                | -                | -         |    -0.49 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           28 |      610 | 2025-02-10 | Nemiga Gaming      | W   | 1.000      | 0.143        | 0.176 (0.025)    | 0.345 (0.049)    | 0 (0.000) |    11.96 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           27 |      816 | 2025-02-07 | Passion UA         | L   | 1.000      | -            | -                | -                | -         |   -15.82 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           26 |      862 | 2025-02-06 | Ninjas in Pyjamas  | W   | 1.000      | 0.143        | -                | 0.607 (0.087)    | 0 (0.000) |     2.94 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           25 |      921 | 2025-02-05 | Passion UA         | L   | 1.000      | -            | -                | -                | -         |   -17.15 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           24 |      932 | 2025-02-05 | Ninjas in Pyjamas  | W   | 1.000      | 0.143        | -                | 0.607 (0.087)    | 0 (0.000) |     2.40 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           23 |     1156 | 2025-01-23 | G2 Esports         | L   | 0.945      | -            | -                | -                | -         |    -0.48 | Ax1Le, KaiR0N-, Magnojez, nafany, s1ren  |
|           22 |     1167 | 2025-01-19 | FURIA              | W   | 0.917      | 0.363        | 0.094 (0.031)    | 0.379 (0.126)    | 0 (0.000) |    25.68 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           21 |     1182 | 2025-01-17 | MOUZ               | W   | 0.905      | 0.363        | 1.000 (0.328)    | 0.470 (0.154)    | 0 (0.000) |    28.32 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           20 |     3139 | 2024-11-20 | GamerLegion        | L   | 0.517      | -            | -                | -                | -         |    -0.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           19 |     3148 | 2024-11-19 | SAW                | W   | 0.514      | 0.143        | 0.266 (0.020)    | -                | 1 (0.514) |    13.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           18 |     3186 | 2024-11-18 | Nemiga Gaming      | W   | 0.508      | 0.143        | 0.176 (0.013)    | -                | 1 (0.508) |     7.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           17 |     3228 | 2024-11-17 | Fnatic             | L   | 0.502      | -            | -                | -                | -         |    -7.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           16 |     3277 | 2024-11-17 | Team Vitality      | L   | 0.496      | -            | -                | -                | -         |    -0.12 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           15 |     3296 | 2024-11-16 | UNiTY esports      | W   | 0.496      | -            | -                | -                | 1 (0.496) |     3.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           14 |     3557 | 2024-11-12 | 500                | W   | 0.464      | 0.384        | 0.093 (0.017)    | 1.000 (0.178)    | -         |     7.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           13 |     3564 | 2024-11-12 | Ninjas in Pyjamas  | W   | 0.464      | 0.384        | 0.024 (0.004)    | -                | -         |     4.55 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           12 |     3625 | 2024-11-11 | Dynamo Eclot       | W   | 0.458      | 0.384        | 0.128 (0.022)    | 0.692 (0.122)    | -         |     8.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           11 |     3888 | 2024-11-06 | OG                 | L   | 0.425      | -            | -                | -                | -         |    -8.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           10 |     5279 | 2024-10-11 | FAVBET Team        | L   | 0.250      | -            | -                | -                | -         |    -5.85 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            9 |     5573 | 2024-10-05 | SAW                | L   | 0.212      | -            | -                | -                | -         |    -1.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            8 |     5608 | 2024-10-05 | Rooster            | W   | 0.211      | -            | -                | -                | 1 (0.211) |     0.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            7 |     5681 | 2024-10-04 | FlyQuest           | L   | 0.204      | -            | -                | -                | -         |    -2.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            6 |     6030 | 2024-09-28 | GamerLegion        | W   | 0.165      | -            | -                | -                | -         |     0.75 | KaiR0N-, Magnojez, s1ren, SELLTER, zorte |
|            5 |     6086 | 2024-09-28 | 3DMAX              | W   | 0.163      | 0.435        | 0.298 (0.021)    | 0.528 (0.037)    | -         |     4.94 | KaiR0N-, Magnojez, s1ren, SELLTER, zorte |
|            4 |     6126 | 2024-09-27 | HEROIC             | W   | 0.158      | 0.435        | 0.131 (0.009)    | -                | -         |     2.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            3 |     6220 | 2024-09-26 | Monte              | W   | 0.151      | 0.435        | -                | 0.696 (0.046)    | -         |     1.70 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            2 |     7550 | 2024-09-06 | CYBERSHOKE Esports | L   | 0.016      | -            | -                | -                | -         |    -0.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            1 |     7624 | 2024-09-05 | Tricked Esport     | W   | 0.010      | -            | -                | -                | -         |     0.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,194.59)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-01-26 |      0.964 | $25,000.00     | $24,107.64      |
| 2024-11-12 |      0.464 | $12,500.00     | $5,805.27       |
| 2024-10-06 |      0.219 | $3,000.00      | $657.29         |
| 2024-09-28 |      0.165 | $22,000.00     | $3,624.40       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
