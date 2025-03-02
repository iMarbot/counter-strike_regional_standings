### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, FL4MUS, ICY<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1592.1<br />
<br />
Final Rank Value (1592.1) = Starting Rank Value (1657.5) + Head To Head Adjustments (-65.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.636[<sup>1</sup>](#table2)
- Bounty Collected: 0.630[<sup>2</sup>](#table1)
- Opponent Network: 0.295[<sup>2</sup>](#table1)
- LAN Wins: 0.957[<sup>2</sup>](#table1)

The average of these factors is 0.630<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1657.5
- 400 + ( ( 0.630 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1657.5


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
|           35 |      267 | 2025-02-18 | MOUZ          | L   | 1.000      | -            | -                | -                | -         |    -6.01 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           34 |      287 | 2025-02-17 | PaiN Gaming   | L   | 1.000      | -            | -                | -                | -         |   -15.92 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           33 |      369 | 2025-02-16 | Wildcard      | W   | 1.000      | 1.000        | 0.176 (0.176)    | 0.428 (0.428)    | 1 (1.000) |     6.01 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           32 |      425 | 2025-02-15 | Complexity    | W   | 1.000      | 1.000        | 0.097 (0.097)    | 0.229 (0.229)    | 1 (1.000) |     1.87 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           31 |      498 | 2025-02-14 | 3DMAX         | L   | 1.000      | -            | -                | -                | -         |   -17.34 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           30 |      779 | 2025-02-07 | Team Spirit   | L   | 1.000      | -            | -                | -                | -         |    -3.85 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           29 |      955 | 2025-02-04 | Team Vitality | L   | 1.000      | -            | -                | -                | -         |    -5.28 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           28 |     1035 | 2025-02-02 | Eternal Fire  | W   | 1.000      | 1.000        | 0.591 (0.591)    | 0.512 (0.512)    | 1 (1.000) |    25.08 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           27 |     1061 | 2025-02-01 | G2 Esports    | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.359 (0.359)    | 1 (1.000) |    24.45 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           26 |     1091 | 2025-01-31 | MIBR          | W   | 1.000      | 1.000        | 0.141 (0.141)    | 0.471 (0.471)    | 1 (1.000) |     8.89 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           25 |     1102 | 2025-01-30 | SAW           | W   | 0.998      | 1.000        | 0.262 (0.262)    | 0.329 (0.329)    | 1 (0.998) |     5.36 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           24 |     1113 | 2025-01-29 | PaiN Gaming   | L   | 0.991      | -            | -                | -                | -         |   -14.59 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           23 |     1149 | 2025-01-19 | Team Vitality | L   | 0.927      | -            | -                | -                | -         |    -4.07 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           22 |     1180 | 2025-01-16 | Complexity    | W   | 0.905      | 0.363        | 0.097 (0.032)    | 0.229 (0.075)    | -         |     2.28 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           21 |     2359 | 2024-12-02 | Wildcard      | L   | 0.604      | -            | -                | -                | -         |   -15.58 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2455 | 2024-11-30 | BIG           | L   | 0.596      | -            | -                | -                | -         |   -12.67 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2541 | 2024-11-30 | Rare Atom     | W   | 0.591      | 1.000        | 0.063 (0.037)    | 0.581 (0.343)    | 1 (0.591) |     0.50 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2563 | 2024-11-29 | MIBR          | L   | 0.589      | -            | -                | -                | -         |   -14.38 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2920 | 2024-11-22 | Sashi Esport  | W   | 0.543      | -            | -                | -                | 1 (0.543) |     0.41 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     3002 | 2024-11-21 | 9Pandas       | W   | 0.536      | -            | -                | -                | 1 (0.536) |     0.67 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     3043 | 2024-11-21 | TSM           | W   | 0.532      | -            | -                | -                | 1 (0.532) |     0.12 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           14 |     3068 | 2024-11-20 | Passion UA    | L   | 0.530      | -            | -                | -                | -         |   -16.29 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           13 |     4602 | 2024-10-25 | OG            | L   | 0.352      | -            | -                | -                | -         |   -10.90 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           12 |     4738 | 2024-10-21 | Team Falcons  | W   | 0.326      | -            | -                | -                | -         |     0.06 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           11 |     4749 | 2024-10-21 | OG            | L   | 0.325      | -            | -                | -                | -         |   -10.09 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           10 |     5260 | 2024-10-11 | Natus Vincere | L   | 0.259      | -            | -                | -                | -         |    -3.61 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            9 |     5332 | 2024-10-09 | The MongolZ   | W   | 0.247      | 0.624        | 1.000 (0.154)    | 0.579 (0.089)    | -         |     6.41 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            8 |     5347 | 2024-10-09 | Astralis      | W   | 0.245      | 0.624        | 0.609 (0.093)    | 0.787 (0.120)    | -         |     5.73 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            7 |     5426 | 2024-10-08 | 9z Team       | W   | 0.239      | -            | -                | -                | -         |     0.06 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            6 |     5470 | 2024-10-07 | The MongolZ   | L   | 0.233      | -            | -                | -                | -         |    -1.25 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            5 |     6848 | 2024-09-17 | Team Falcons  | L   | 0.098      | -            | -                | -                | -         |    -0.59 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            4 |     7061 | 2024-09-13 | FURIA         | W   | 0.073      | -            | -                | -                | -         |     0.53 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            3 |     7100 | 2024-09-13 | Team Falcons  | W   | 0.071      | -            | -                | -                | -         |     0.01 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            2 |     7145 | 2024-09-12 | Team Liquid   | L   | 0.065      | -            | -                | -                | -         |    -1.39 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            1 |     7239 | 2024-09-10 | RED Canids    | W   | 0.053      | -            | -                | -                | -         |     0.02 | electroNic, fame, FL1T, Jame, n0rb3r7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($90,154.46)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.27) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $31,250.00     | $31,250.00      |
| 2025-02-09 |      1.000 | $40,000.00     | $40,000.00      |
| 2025-01-19 |      0.927 | $7,500.00      | $6,953.30       |
| 2024-12-15 |      0.691 | $10,000.00     | $6,909.49       |
| 2024-10-13 |      0.273 | $10,000.00     | $2,727.78       |
| 2024-09-22 |      0.132 | $17,500.00     | $2,313.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
