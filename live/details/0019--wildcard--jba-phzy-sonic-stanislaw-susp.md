### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, phzy, Sonic, stanislaw, susp<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1335.3<br />
<br />
Final Rank Value (1335.3) = Starting Rank Value (1372.7) + Head To Head Adjustments (-37.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.570[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.255[<sup>2</sup>](#table1)
- LAN Wins: 0.659[<sup>2</sup>](#table1)

The average of these factors is 0.487<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1372.7
- 400 + ( ( 0.487 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1372.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |      305 | 2025-02-17 | BIG                | L   | 1.000      | -            | -                | -                | -         |   -14.77 | JBa, phzy, Sonic, stanislaw, susp  |
|           47 |      369 | 2025-02-16 | Virtus.pro         | L   | 1.000      | -            | -                | -                | -         |    -6.01 | JBa, phzy, Sonic, stanislaw, susp  |
|           46 |      426 | 2025-02-15 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -1.22 | JBa, phzy, Sonic, stanislaw, susp  |
|           45 |      482 | 2025-02-14 | MIBR               | W   | 1.000      | 1.000        | 0.141 (0.141)    | 0.471 (0.471)    | 1 (1.000) |    17.00 | JBa, phzy, Sonic, stanislaw, susp  |
|           44 |     1090 | 2025-01-31 | Team Liquid        | L   | 1.000      | -            | -                | -                | -         |    -9.33 | JBa, phzy, Sonic, stanislaw, susp  |
|           43 |     1093 | 2025-01-31 | FURIA              | L   | 1.000      | -            | -                | -                | -         |   -11.37 | JBa, phzy, Sonic, stanislaw, susp  |
|           42 |     1108 | 2025-01-29 | BIG                | W   | 0.992      | 1.000        | 0.246 (0.244)    | 0.579 (0.574)    | 1 (0.992) |    19.60 | JBa, phzy, Sonic, stanislaw, susp  |
|           41 |     1184 | 2025-01-15 | Astralis           | L   | 0.898      | -            | -                | -                | -         |    -1.95 | JBa, phzy, Sonic, stanislaw, susp  |
|           40 |     1190 | 2025-01-12 | 9Pandas            | W   | 0.879      | 0.417        | 0.085 (0.031)    | 0.485 (0.178)    | -         |     4.71 | JBa, phzy, Sonic, stanislaw, susp  |
|           39 |     1193 | 2025-01-11 | SINNERS Esports    | W   | 0.873      | 0.417        | 0.027 (0.010)    | 0.451 (0.164)    | -         |     2.22 | JBa, phzy, Sonic, stanislaw, susp  |
|           38 |     1197 | 2025-01-10 | Insilio            | W   | 0.867      | 0.417        | -                | 0.504 (0.182)    | -         |     0.99 | JBa, phzy, Sonic, stanislaw, susp  |
|           37 |     2145 | 2024-12-05 | GamerLegion        | L   | 0.630      | -            | -                | -                | -         |    -4.34 | JBa, phzy, Sonic, stanislaw, susp  |
|           36 |     2174 | 2024-12-05 | Team Spirit        | L   | 0.624      | -            | -                | -                | -         |    -0.68 | JBa, phzy, Sonic, stanislaw, susp  |
|           35 |     2186 | 2024-12-04 | FaZe Clan          | L   | 0.623      | -            | -                | -                | -         |    -0.85 | JBa, phzy, Sonic, stanislaw, susp  |
|           34 |     2291 | 2024-12-03 | Passion UA         | W   | 0.611      | 1.000        | 0.044 (0.027)    | 0.557 (0.340)    | 1 (0.611) |     3.11 | JBa, phzy, Sonic, stanislaw, susp  |
|           33 |     2359 | 2024-12-02 | Virtus.pro         | W   | 0.604      | 1.000        | 0.268 (0.162)    | 0.439 (0.265)    | 1 (0.604) |    15.58 | JBa, phzy, Sonic, stanislaw, susp  |
|           32 |     2453 | 2024-11-30 | FURIA              | L   | 0.596      | -            | -                | -                | -         |    -6.58 | JBa, phzy, Sonic, stanislaw, susp  |
|           31 |     2540 | 2024-11-30 | Team Liquid        | L   | 0.591      | -            | -                | -                | -         |    -4.86 | JBa, phzy, Sonic, stanislaw, susp  |
|           30 |     2557 | 2024-11-29 | Fnatic             | W   | 0.590      | 1.000        | 0.072 (0.042)    | 0.461 (0.272)    | 1 (0.590) |     3.67 | JBa, phzy, Sonic, stanislaw, susp  |
|           29 |     3525 | 2024-11-12 | 9z Team            | W   | 0.477      | -            | -                | -                | 1 (0.477) |     0.73 | JBa, phzy, Sonic, stanislaw, susp  |
|           28 |     3560 | 2024-11-12 | PaiN Gaming        | W   | 0.471      | 0.143        | 0.318 (0.021)    | -                | 1 (0.471) |    12.25 | JBa, phzy, Sonic, stanislaw, susp  |
|           27 |     3580 | 2024-11-11 | Team Liquid        | W   | 0.469      | 0.143        | 0.186 (0.012)    | -                | 1 (0.469) |    11.29 | JBa, phzy, Sonic, stanislaw, susp  |
|           26 |     4912 | 2024-10-17 | NRG                | L   | 0.302      | -            | -                | -                | -         |    -8.16 | JBa, phzy, Sonic, stanislaw, susp  |
|           25 |     4964 | 2024-10-16 | BOSS               | W   | 0.295      | -            | -                | -                | -         |     0.88 | JBa, phzy, Sonic, stanislaw, susp  |
|           24 |     5031 | 2024-10-15 | Nouns Esports      | L   | 0.288      | -            | -                | -                | -         |    -8.72 | JBa, phzy, Sonic, stanislaw, susp  |
|           23 |     5305 | 2024-10-09 | Party Astronauts   | L   | 0.249      | -            | -                | -                | -         |    -7.46 | JBa, phzy, Sonic, stanislaw, susp  |
|           22 |     5312 | 2024-10-09 | Party Astronauts   | L   | 0.248      | -            | -                | -                | -         |    -7.48 | JBa, phzy, Sonic, stanislaw, susp  |
|           21 |     5385 | 2024-10-08 | M80                | L   | 0.241      | -            | -                | -                | -         |    -6.89 | JBa, phzy, Sonic, stanislaw, susp  |
|           20 |     5396 | 2024-10-08 | M80                | L   | 0.241      | -            | -                | -                | -         |    -6.93 | JBa, phzy, Sonic, stanislaw, susp  |
|           19 |     5527 | 2024-10-06 | FlyQuest           | L   | 0.225      | -            | -                | -                | -         |    -5.65 | fr3nd, JBa, Sonic, stanislaw, susp |
|           18 |     5578 | 2024-10-05 | M80                | W   | 0.219      | 0.500        | 0.038 (0.004)    | 0.465 (0.051)    | 1 (0.219) |     0.58 | fr3nd, JBa, Sonic, stanislaw, susp |
|           17 |     5644 | 2024-10-04 | ODDIK              | W   | 0.215      | 0.500        | -                | 0.521 (0.056)    | 1 (0.215) |     0.32 | fr3nd, JBa, Sonic, stanislaw, susp |
|           16 |     5656 | 2024-10-04 | M80                | L   | 0.213      | -            | -                | -                | -         |    -6.18 | fr3nd, JBa, Sonic, stanislaw, susp |
|           15 |     5811 | 2024-10-01 | BOSS               | W   | 0.195      | -            | -                | -                | -         |     0.43 | JBa, phzy, Sonic, stanislaw, susp  |
|           14 |     5814 | 2024-10-01 | BOSS               | W   | 0.195      | -            | -                | -                | -         |     0.43 | JBa, phzy, Sonic, stanislaw, susp  |
|           13 |     5940 | 2024-09-29 | Legacy             | L   | 0.182      | -            | -                | -                | -         |    -5.37 | JBa, phzy, Sonic, stanislaw, susp  |
|           12 |     5991 | 2024-09-28 | Legacy             | W   | 0.175      | -            | -                | -                | -         |     0.34 | JBa, phzy, Sonic, stanislaw, susp  |
|           11 |     5998 | 2024-09-28 | MarcaRegistrada    | W   | 0.174      | -            | -                | -                | -         |     0.08 | JBa, phzy, Sonic, stanislaw, susp  |
|           10 |     6665 | 2024-09-19 | NRG                | L   | 0.115      | -            | -                | -                | -         |    -3.18 | JBa, phzy, Sonic, stanislaw, susp  |
|            9 |     6669 | 2024-09-19 | NRG                | L   | 0.114      | -            | -                | -                | -         |    -3.18 | JBa, phzy, Sonic, stanislaw, susp  |
|            8 |     6719 | 2024-09-18 | Familia Maquininha | W   | 0.108      | -            | -                | -                | -         |     0.07 | JBa, phzy, Sonic, stanislaw, susp  |
|            7 |     6724 | 2024-09-18 | Familia Maquininha | W   | 0.108      | -            | -                | -                | -         |     0.07 | JBa, phzy, Sonic, stanislaw, susp  |
|            6 |     6731 | 2024-09-18 | Chill Guys         | W   | 0.108      | -            | -                | -                | -         |     0.06 | JBa, phzy, Sonic, stanislaw, susp  |
|            5 |     6735 | 2024-09-18 | Chill Guys         | W   | 0.107      | -            | -                | -                | -         |     0.06 | JBa, phzy, Sonic, stanislaw, susp  |
|            4 |     7425 | 2024-09-07 | 3DMAX              | L   | 0.032      | -            | -                | -                | -         |    -0.21 | JBa, phzy, Sonic, stanislaw, susp  |
|            3 |     7498 | 2024-09-06 | Iberian Soul       | W   | 0.026      | -            | -                | -                | -         |     0.04 | JBa, phzy, Sonic, stanislaw, susp  |
|            2 |     7605 | 2024-09-05 | 9z Team            | L   | 0.019      | -            | -                | -                | -         |    -0.57 | JBa, phzy, Sonic, stanislaw, susp  |
|            1 |     7680 | 2024-09-04 | Team Spirit        | L   | 0.011      | -            | -                | -                | -         |    -0.01 | JBa, phzy, Sonic, stanislaw, susp  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,209.95)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $18,750.00     | $18,750.00      |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2025-01-12 |      0.879 | $20,000.00     | $17,577.78      |
| 2024-12-15 |      0.691 | $20,000.00     | $13,818.98      |
| 2024-10-20 |      0.321 | $4,250.00      | $1,364.72       |
| 2024-10-06 |      0.227 | $10,000.00     | $2,272.92       |
| 2024-09-22 |      0.132 | $7,000.00      | $925.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
