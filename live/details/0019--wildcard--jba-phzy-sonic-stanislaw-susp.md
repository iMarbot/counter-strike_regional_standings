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
Final Rank Value:  1337.0<br />
<br />
Final Rank Value (1337.0) = Starting Rank Value (1370.2) + Head To Head Adjustments (-33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.572[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.252[<sup>2</sup>](#table1)
- LAN Wins: 0.653[<sup>2</sup>](#table1)

The average of these factors is 0.485<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1370.2
- 400 + ( ( 0.485 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1370.2


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
|           48 |      317 | 2025-02-17 | BIG                | L   | 1.000      | -            | -                | -                | -         |   -14.86 | JBa, phzy, Sonic, stanislaw, susp  |
|           47 |      381 | 2025-02-16 | Virtus.pro         | L   | 1.000      | -            | -                | -                | -         |    -6.02 | JBa, phzy, Sonic, stanislaw, susp  |
|           46 |      438 | 2025-02-15 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -1.24 | JBa, phzy, Sonic, stanislaw, susp  |
|           45 |      494 | 2025-02-14 | MIBR               | W   | 1.000      | 1.000        | 0.142 (0.142)    | 0.465 (0.465)    | 1 (1.000) |    16.85 | JBa, phzy, Sonic, stanislaw, susp  |
|           44 |     1102 | 2025-01-31 | Team Liquid        | L   | 0.998      | -            | -                | -                | -         |    -9.49 | JBa, phzy, Sonic, stanislaw, susp  |
|           43 |     1105 | 2025-01-31 | FURIA              | L   | 0.997      | -            | -                | -                | -         |   -11.55 | JBa, phzy, Sonic, stanislaw, susp  |
|           42 |     1120 | 2025-01-29 | BIG                | W   | 0.984      | 1.000        | 0.248 (0.244)    | 0.572 (0.563)    | 1 (0.984) |    19.34 | JBa, phzy, Sonic, stanislaw, susp  |
|           41 |     1196 | 2025-01-15 | Astralis           | L   | 0.890      | -            | -                | -                | -         |    -1.93 | JBa, phzy, Sonic, stanislaw, susp  |
|           40 |     1202 | 2025-01-12 | 9Pandas            | W   | 0.871      | 0.417        | 0.085 (0.031)    | 0.477 (0.173)    | -         |     4.55 | JBa, phzy, Sonic, stanislaw, susp  |
|           39 |     1205 | 2025-01-11 | SINNERS Esports    | W   | 0.865      | 0.417        | 0.027 (0.010)    | 0.446 (0.161)    | -         |     2.15 | JBa, phzy, Sonic, stanislaw, susp  |
|           38 |     1209 | 2025-01-10 | Insilio            | W   | 0.859      | 0.417        | -                | 0.500 (0.179)    | -         |     0.95 | JBa, phzy, Sonic, stanislaw, susp  |
|           37 |     2157 | 2024-12-05 | GamerLegion        | L   | 0.622      | -            | -                | -                | -         |    -4.37 | JBa, phzy, Sonic, stanislaw, susp  |
|           36 |     2186 | 2024-12-05 | Team Spirit        | L   | 0.616      | -            | -                | -                | -         |    -0.68 | JBa, phzy, Sonic, stanislaw, susp  |
|           35 |     2198 | 2024-12-04 | FaZe Clan          | L   | 0.615      | -            | -                | -                | -         |    -0.84 | JBa, phzy, Sonic, stanislaw, susp  |
|           34 |     2303 | 2024-12-03 | Passion UA         | W   | 0.603      | 1.000        | 0.044 (0.027)    | 0.545 (0.328)    | 1 (0.603) |     3.00 | JBa, phzy, Sonic, stanislaw, susp  |
|           33 |     2371 | 2024-12-02 | Virtus.pro         | W   | 0.596      | 1.000        | 0.272 (0.162)    | 0.436 (0.260)    | 1 (0.596) |    15.35 | JBa, phzy, Sonic, stanislaw, susp  |
|           32 |     2465 | 2024-11-30 | FURIA              | L   | 0.588      | -            | -                | -                | -         |    -6.65 | JBa, phzy, Sonic, stanislaw, susp  |
|           31 |     2552 | 2024-11-30 | Team Liquid        | L   | 0.583      | -            | -                | -                | -         |    -4.92 | JBa, phzy, Sonic, stanislaw, susp  |
|           30 |     2569 | 2024-11-29 | Fnatic             | W   | 0.582      | 1.000        | 0.072 (0.042)    | 0.459 (0.267)    | 1 (0.582) |     3.51 | JBa, phzy, Sonic, stanislaw, susp  |
|           29 |     3537 | 2024-11-12 | 9z Team            | W   | 0.468      | -            | -                | -                | 1 (0.468) |     0.69 | JBa, phzy, Sonic, stanislaw, susp  |
|           28 |     3572 | 2024-11-12 | PaiN Gaming        | W   | 0.463      | 0.143        | 0.323 (0.021)    | -                | 1 (0.463) |    12.02 | JBa, phzy, Sonic, stanislaw, susp  |
|           27 |     3592 | 2024-11-11 | Team Liquid        | W   | 0.461      | 0.143        | 0.187 (0.012)    | -                | 1 (0.461) |    10.99 | JBa, phzy, Sonic, stanislaw, susp  |
|           26 |     4924 | 2024-10-17 | NRG                | L   | 0.293      | -            | -                | -                | -         |    -7.93 | JBa, phzy, Sonic, stanislaw, susp  |
|           25 |     4976 | 2024-10-16 | BLUEJAYS           | W   | 0.287      | 0.477        | 0.031 (0.004)    | 0.511 (0.070)    | -         |     2.60 | JBa, phzy, Sonic, stanislaw, susp  |
|           24 |     5043 | 2024-10-15 | Nouns Esports      | L   | 0.280      | -            | -                | -                | -         |    -8.48 | JBa, phzy, Sonic, stanislaw, susp  |
|           23 |     5317 | 2024-10-09 | Party Astronauts   | L   | 0.240      | -            | -                | -                | -         |    -7.22 | JBa, phzy, Sonic, stanislaw, susp  |
|           22 |     5324 | 2024-10-09 | Party Astronauts   | L   | 0.240      | -            | -                | -                | -         |    -7.24 | JBa, phzy, Sonic, stanislaw, susp  |
|           21 |     5397 | 2024-10-08 | M80                | L   | 0.233      | -            | -                | -                | -         |    -6.67 | JBa, phzy, Sonic, stanislaw, susp  |
|           20 |     5408 | 2024-10-08 | M80                | L   | 0.233      | -            | -                | -                | -         |    -6.71 | JBa, phzy, Sonic, stanislaw, susp  |
|           19 |     5539 | 2024-10-06 | FlyQuest           | L   | 0.217      | -            | -                | -                | -         |    -5.47 | fr3nd, JBa, Sonic, stanislaw, susp |
|           18 |     5590 | 2024-10-05 | M80                | W   | 0.211      | -            | -                | -                | 1 (0.211) |     0.54 | fr3nd, JBa, Sonic, stanislaw, susp |
|           17 |     5656 | 2024-10-04 | ODDIK              | W   | 0.206      | 0.500        | -                | 0.518 (0.053)    | 1 (0.206) |     0.30 | fr3nd, JBa, Sonic, stanislaw, susp |
|           16 |     5668 | 2024-10-04 | M80                | L   | 0.205      | -            | -                | -                | -         |    -5.96 | fr3nd, JBa, Sonic, stanislaw, susp |
|           15 |     5823 | 2024-10-01 | BLUEJAYS           | W   | 0.187      | -            | -                | -                | -         |     1.45 | JBa, phzy, Sonic, stanislaw, susp  |
|           14 |     5826 | 2024-10-01 | BLUEJAYS           | W   | 0.187      | -            | -                | -                | -         |     1.47 | JBa, phzy, Sonic, stanislaw, susp  |
|           13 |     5952 | 2024-09-29 | Legacy             | L   | 0.174      | -            | -                | -                | -         |    -5.12 | JBa, phzy, Sonic, stanislaw, susp  |
|           12 |     6003 | 2024-09-28 | Legacy             | W   | 0.167      | -            | -                | -                | -         |     0.33 | JBa, phzy, Sonic, stanislaw, susp  |
|           11 |     6010 | 2024-09-28 | MarcaRegistrada    | W   | 0.166      | -            | -                | -                | -         |     0.08 | JBa, phzy, Sonic, stanislaw, susp  |
|           10 |     6677 | 2024-09-19 | NRG                | L   | 0.107      | -            | -                | -                | -         |    -2.94 | JBa, phzy, Sonic, stanislaw, susp  |
|            9 |     6681 | 2024-09-19 | NRG                | L   | 0.106      | -            | -                | -                | -         |    -2.94 | JBa, phzy, Sonic, stanislaw, susp  |
|            8 |     6731 | 2024-09-18 | Familia Maquininha | W   | 0.100      | -            | -                | -                | -         |     0.06 | JBa, phzy, Sonic, stanislaw, susp  |
|            7 |     6736 | 2024-09-18 | Familia Maquininha | W   | 0.100      | -            | -                | -                | -         |     0.06 | JBa, phzy, Sonic, stanislaw, susp  |
|            6 |     6743 | 2024-09-18 | Chill Guys         | W   | 0.100      | -            | -                | -                | -         |     0.06 | JBa, phzy, Sonic, stanislaw, susp  |
|            5 |     6747 | 2024-09-18 | Chill Guys         | W   | 0.099      | -            | -                | -                | -         |     0.06 | JBa, phzy, Sonic, stanislaw, susp  |
|            4 |     7437 | 2024-09-07 | 3DMAX              | L   | 0.024      | -            | -                | -                | -         |    -0.16 | JBa, phzy, Sonic, stanislaw, susp  |
|            3 |     7510 | 2024-09-06 | Iberian Soul       | W   | 0.018      | -            | -                | -                | -         |     0.03 | JBa, phzy, Sonic, stanislaw, susp  |
|            2 |     7617 | 2024-09-05 | 9z Team            | L   | 0.011      | -            | -                | -                | -         |    -0.32 | JBa, phzy, Sonic, stanislaw, susp  |
|            1 |     7692 | 2024-09-04 | Team Spirit        | L   | 0.003      | -            | -                | -                | -         |    -0.00 | JBa, phzy, Sonic, stanislaw, susp  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($58,708.04)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $18,750.00     | $18,750.00      |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2025-01-12 |      0.871 | $20,000.00     | $17,413.89      |
| 2024-12-15 |      0.683 | $20,000.00     | $13,655.09      |
| 2024-10-20 |      0.313 | $4,250.00      | $1,329.90       |
| 2024-10-06 |      0.219 | $10,000.00     | $2,190.97       |
| 2024-09-22 |      0.124 | $7,000.00      | $868.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
