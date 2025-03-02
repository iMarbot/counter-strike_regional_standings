### Roster Details<br />
Team Name: OG<br />
Roster: afro, Buzz, Chr1zN, F1KU, spooke<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  995.0<br />
<br />
Final Rank Value (995.0) = Starting Rank Value (910.2) + Head To Head Adjustments (84.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.404[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.255<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 910.2
- 400 + ( ( 0.255 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 910.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |        0 | 2025-03-01 | FAVBET Team           | W   | 1.000      | 0.143        | 0.032 (0.005)    | 0.814 (0.116)    | 0 (0.000) |     9.36 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           47 |       38 | 2025-02-25 | ESC Gaming            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.85 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           46 |       55 | 2025-02-24 | Iberian Soul          | L   | 1.000      | -            | -                | -                | -         |   -21.80 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           45 |       62 | 2025-02-24 | Tricked Esport        | W   | 1.000      | 0.143        | 0.033 (0.005)    | 0.696 (0.099)    | 0 (0.000) |    10.22 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           44 |      154 | 2025-02-22 | BC.Game Esports       | W   | 1.000      | 0.143        | 0.077 (0.011)    | 0.945 (0.135)    | 0 (0.000) |    23.18 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           43 |      215 | 2025-02-21 | Aurora Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.88 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           42 |      277 | 2025-02-17 | Leo Team              | W   | 1.000      | 0.143        | -                | 0.758 (0.108)    | 0 (0.000) |    12.41 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           41 |      280 | 2025-02-17 | CYBERSHOKE Esports    | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    13.43 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           40 |      289 | 2025-02-17 | WeLoveUSmooya         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.10 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           39 |      296 | 2025-02-17 | Moneytrees            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.65 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           38 |      327 | 2025-02-16 | QUAZAR                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.44 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           37 |      418 | 2025-02-15 | Rebels Gaming         | L   | 1.000      | -            | -                | -                | -         |   -23.91 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           36 |      459 | 2025-02-14 | PARIVISION            | W   | 1.000      | -            | -                | -                | -         |    10.53 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           35 |      586 | 2025-02-10 | BIG                   | L   | 1.000      | -            | -                | -                | -         |    -2.47 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           34 |      596 | 2025-02-10 | Astralis              | L   | 1.000      | -            | -                | -                | -         |    -0.33 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           33 |      633 | 2025-02-09 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |   -16.84 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           32 |      638 | 2025-02-09 | Sashi Esport          | L   | 1.000      | -            | -                | -                | -         |   -17.71 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           31 |      669 | 2025-02-08 | TEAM NEXT LEVEL       | W   | 1.000      | -            | -                | -                | -         |     7.93 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           30 |      678 | 2025-02-08 | Benched               | W   | 1.000      | -            | -                | -                | -         |     3.30 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           29 |      688 | 2025-02-08 | 500                   | L   | 1.000      | -            | -                | -                | -         |   -10.44 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           28 |      698 | 2025-02-08 | Mission Possible      | W   | 1.000      | -            | -                | -                | -         |     3.28 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           27 |      766 | 2025-02-07 | Nuclear TigeRES       | W   | 1.000      | -            | -                | -                | -         |     7.52 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           26 |      790 | 2025-02-07 | AMKAL ESPORTS         | W   | 1.000      | -            | -                | -                | -         |    10.80 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           25 |      853 | 2025-02-06 | Alliance              | W   | 1.000      | -            | -                | -                | -         |    13.32 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           24 |      875 | 2025-02-05 | SINNERS Esports       | W   | 1.000      | 0.435        | 0.027 (0.012)    | 0.451 (0.196)    | -         |    14.48 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           23 |     1028 | 2025-02-03 | Natus Vincere Junior  | W   | 1.000      | 0.435        | 0.091 (0.039)    | 0.878 (0.381)    | -         |    18.20 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           22 |     1067 | 2025-02-01 | Fnatic                | L   | 1.000      | -            | -                | -                | -         |    -9.54 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           21 |     3647 | 2024-11-10 | Johnny Speeds         | L   | 0.460      | -            | -                | -                | -         |    -7.27 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           20 |     3829 | 2024-11-07 | Natus Vincere Junior  | L   | 0.440      | -            | -                | -                | -         |    -5.52 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           19 |     3850 | 2024-11-07 | Sashi Esport          | L   | 0.439      | -            | -                | -                | -         |    -6.89 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           18 |     3876 | 2024-11-06 | BetBoom Team          | W   | 0.434      | 0.143        | 0.103 (0.006)    | -                | -         |     8.57 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           17 |     3933 | 2024-11-05 | Los kogutos           | W   | 0.427      | 0.384        | 0.032 (0.005)    | -                | -         |     6.23 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           16 |     4067 | 2024-11-03 | 3DMAX                 | L   | 0.412      | -            | -                | -                | -         |    -0.34 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           15 |     4131 | 2024-11-02 | Team Falcons          | L   | 0.406      | -            | -                | -                | -         |    -0.05 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           14 |     4200 | 2024-11-01 | Johnny Speeds         | L   | 0.399      | -            | -                | -                | -         |    -6.33 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           13 |     4331 | 2024-10-30 | 9INE                  | L   | 0.384      | -            | -                | -                | -         |    -8.18 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           12 |     4380 | 2024-10-29 | Zero Tenacity         | W   | 0.379      | -            | -                | -                | -         |     4.82 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           11 |     4386 | 2024-10-29 | Wu-Tang Clan          | W   | 0.378      | -            | -                | -                | -         |     1.10 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           10 |     4437 | 2024-10-28 | 500                   | L   | 0.372      | -            | -                | -                | -         |    -4.53 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            9 |     4555 | 2024-10-26 | BIG                   | W   | 0.357      | 0.934        | 0.246 (0.082)    | 0.579 (0.193)    | -         |    10.82 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            8 |     4602 | 2024-10-25 | Virtus.pro            | W   | 0.352      | 0.934        | 0.268 (0.088)    | 0.439 (0.144)    | -         |    10.90 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            7 |     4721 | 2024-10-21 | 3DMAX                 | L   | 0.327      | -            | -                | -                | -         |    -0.26 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            6 |     4749 | 2024-10-21 | Virtus.pro            | W   | 0.325      | 0.934        | 0.268 (0.081)    | 0.439 (0.133)    | -         |    10.09 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            5 |     5289 | 2024-10-10 | Team Spirit Academy   | L   | 0.252      | -            | -                | -                | -         |    -3.64 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|            4 |     6113 | 2024-09-27 | GameAgents            | L   | 0.166      | -            | -                | -                | -         |    -3.99 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            3 |     6138 | 2024-09-27 | B8                    | L   | 0.165      | -            | -                | -                | -         |    -1.28 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            2 |     7016 | 2024-09-14 | Sashi Esport          | L   | 0.078      | -            | -                | -                | -         |    -1.07 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            1 |     7150 | 2024-09-12 | Team Sampi            | W   | 0.064      | -            | -                | -                | -         |     0.72 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,811.59)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.452 | $15.18         | $6.87           |
| 2024-11-03 |      0.413 | $50,000.00     | $20,645.83      |
| 2024-09-14 |      0.079 | $2,000.00      | $158.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
