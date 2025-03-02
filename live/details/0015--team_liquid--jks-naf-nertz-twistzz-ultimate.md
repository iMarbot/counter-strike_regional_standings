### Roster Details<br />
Team Name: Team Liquid<br />
Roster: jks, NAF, NertZ, Twistzz, ultimate<br />
Global Rank: [15](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1527.3<br />
<br />
Final Rank Value (1527.3) = Starting Rank Value (1521.7) + Head To Head Adjustments (5.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.577[<sup>1</sup>](#table2)
- Bounty Collected: 0.574[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.834[<sup>2</sup>](#table1)

The average of these factors is 0.562<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1521.7
- 400 + ( ( 0.562 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1521.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      995 | 2025-02-04 | Team Spirit   | L   | 1.000      | -            | -                | -                | -         |    -2.44 | jks, NAF, NertZ, Twistzz, ultimate    |
|           32 |     1027 | 2025-02-03 | MOUZ          | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.473 (0.473)    | 1 (1.000) |    28.08 | jks, NAF, NertZ, Twistzz, ultimate    |
|           31 |     1039 | 2025-02-02 | The MongolZ   | L   | 1.000      | -            | -                | -                | -         |    -2.38 | jks, NAF, NertZ, Twistzz, ultimate    |
|           30 |     1090 | 2025-01-31 | Wildcard      | W   | 1.000      | 1.000        | 0.176 (0.176)    | 0.428 (0.428)    | 1 (1.000) |     9.33 | jks, NAF, NertZ, Twistzz, ultimate    |
|           29 |     1094 | 2025-01-31 | Complexity    | W   | 1.000      | 1.000        | 0.097 (0.097)    | 0.229 (0.229)    | 1 (1.000) |     3.96 | jks, NAF, NertZ, Twistzz, ultimate    |
|           28 |     1104 | 2025-01-29 | HEROIC        | L   | 0.993      | -            | -                | -                | -         |   -27.67 | jks, NAF, NertZ, Twistzz, ultimate    |
|           27 |     1166 | 2025-01-18 | HEROIC        | L   | 0.918      | -            | -                | -                | -         |   -26.39 | jks, NAF, NertZ, Twistzz, ultimate    |
|           26 |     1186 | 2025-01-14 | 9Pandas       | W   | 0.893      | 0.363        | 0.085 (0.027)    | 0.485 (0.157)    | -         |     1.71 | jks, NAF, NertZ, Twistzz, ultimate    |
|           25 |     1846 | 2024-12-12 | Team Spirit   | L   | 0.671      | -            | -                | -                | -         |    -1.99 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           24 |     2103 | 2024-12-06 | MIBR          | W   | 0.637      | 1.000        | 0.141 (0.090)    | 0.471 (0.300)    | 1 (0.637) |     6.96 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           23 |     2148 | 2024-12-05 | FURIA         | W   | 0.629      | 1.000        | 0.094 (0.059)    | 0.384 (0.242)    | 1 (0.629) |     8.10 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           22 |     2180 | 2024-12-05 | GamerLegion   | W   | 0.624      | 1.000        | 0.127 (0.079)    | 0.493 (0.308)    | 1 (0.624) |    11.18 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           21 |     2190 | 2024-12-04 | Natus Vincere | L   | 0.623      | -            | -                | -                | -         |    -4.92 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           20 |     2450 | 2024-11-30 | FlyQuest      | W   | 0.596      | 1.000        | 0.105 (0.062)    | 0.239 (0.143)    | 1 (0.596) |     1.90 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           19 |     2540 | 2024-11-30 | Wildcard      | W   | 0.591      | 1.000        | 0.176 (0.104)    | 0.428 (0.253)    | 1 (0.591) |     4.86 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           18 |     2561 | 2024-11-29 | Cloud9        | W   | 0.590      | -            | -                | -                | 1 (0.590) |     0.64 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           17 |     3472 | 2024-11-14 | FURIA         | W   | 0.484      | -            | -                | -                | 1 (0.484) |     6.18 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           16 |     3527 | 2024-11-12 | BESTIA        | W   | 0.476      | -            | -                | -                | -         |     0.63 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           15 |     3548 | 2024-11-12 | KRÜ Esports   | W   | 0.472      | -            | -                | -                | -         |     0.15 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           14 |     3580 | 2024-11-11 | Wildcard      | L   | 0.469      | -            | -                | -                | -         |   -11.29 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           13 |     4259 | 2024-10-31 | Team Vitality | L   | 0.391      | -            | -                | -                | -         |    -1.30 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           12 |     4329 | 2024-10-30 | G2 Esports    | L   | 0.385      | -            | -                | -                | -         |    -2.15 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           11 |     5410 | 2024-10-08 | FaZe Clan     | L   | 0.240      | -            | -                | -                | -         |    -0.79 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           10 |     5450 | 2024-10-07 | Natus Vincere | L   | 0.234      | -            | -                | -                | -         |    -1.93 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            9 |     5486 | 2024-10-07 | Complexity    | W   | 0.232      | -            | -                | -                | -         |     0.83 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            8 |     6122 | 2024-09-27 | FaZe Clan     | L   | 0.166      | -            | -                | -                | -         |    -0.53 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            7 |     6181 | 2024-09-26 | Team Vitality | L   | 0.160      | -            | -                | -                | -         |    -0.52 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            6 |     6291 | 2024-09-25 | Team Spirit   | W   | 0.153      | 0.729        | 1.000 (0.111)    | 0.663 (0.074)    | -         |     4.49 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            5 |     6626 | 2024-09-20 | G2 Esports    | L   | 0.120      | -            | -                | -                | -         |    -0.68 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            4 |     6754 | 2024-09-18 | Complexity    | W   | 0.106      | -            | -                | -                | -         |     0.39 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            3 |     6924 | 2024-09-15 | Team Vitality | L   | 0.086      | -            | -                | -                | -         |    -0.27 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            2 |     7145 | 2024-09-12 | Virtus.pro    | W   | 0.065      | -            | -                | -                | -         |     1.39 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            1 |     7250 | 2024-09-10 | ENCE          | W   | 0.052      | -            | -                | -                | -         |     0.09 | jks, NAF, Twistzz, ultimate, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($62,422.43)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-12-15 |      0.691 | $45,000.00     | $31,092.71      |
| 2024-11-03 |      0.411 | $15,000.00     | $6,162.50       |
| 2024-10-13 |      0.273 | $5,000.00      | $1,363.89       |
| 2024-09-29 |      0.179 | $20,000.00     | $3,572.22       |
| 2024-09-22 |      0.132 | $32,000.00     | $4,231.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
