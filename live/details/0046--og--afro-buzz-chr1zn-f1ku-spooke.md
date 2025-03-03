### Roster Details<br />
Team Name: OG<br />
Roster: afro, Buzz, Chr1zN, F1KU, spooke<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  993.8<br />
<br />
Final Rank Value (993.8) = Starting Rank Value (909.3) + Head To Head Adjustments (84.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.403[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.255<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 909.3
- 400 + ( ( 0.255 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 909.3


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
|           48 |       15 | 2025-03-01 | FAVBET Team           | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.801 (0.114)    | 0 (0.000) |     9.34 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           47 |       53 | 2025-02-25 | ESC Gaming            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.85 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           46 |       70 | 2025-02-24 | Iberian Soul          | L   | 1.000      | -            | -                | -                | -         |   -21.81 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           45 |       77 | 2025-02-24 | Tricked Esport        | W   | 1.000      | 0.143        | 0.034 (0.005)    | 0.687 (0.098)    | 0 (0.000) |    10.19 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           44 |      167 | 2025-02-22 | BC.Game Esports       | W   | 1.000      | 0.143        | 0.078 (0.011)    | 0.945 (0.135)    | 0 (0.000) |    23.20 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           43 |      227 | 2025-02-21 | Aurora Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.88 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           42 |      289 | 2025-02-17 | Leo Team              | W   | 1.000      | 0.143        | -                | 0.748 (0.107)    | 0 (0.000) |    12.38 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           41 |      292 | 2025-02-17 | CYBERSHOKE Esports    | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    13.43 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           40 |      301 | 2025-02-17 | WeLoveUSmooya         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.12 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           39 |      308 | 2025-02-17 | Moneytrees            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.66 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           38 |      339 | 2025-02-16 | QUAZAR                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.43 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           37 |      430 | 2025-02-15 | Rebels Gaming         | L   | 1.000      | -            | -                | -                | -         |   -23.93 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           36 |      471 | 2025-02-14 | PARIVISION            | W   | 1.000      | -            | -                | -                | -         |    10.56 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           35 |      598 | 2025-02-10 | BIG                   | L   | 1.000      | -            | -                | -                | -         |    -2.46 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           34 |      608 | 2025-02-10 | Astralis              | L   | 1.000      | -            | -                | -                | -         |    -0.33 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           33 |      645 | 2025-02-09 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |   -16.85 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           32 |      650 | 2025-02-09 | Sashi Esport          | L   | 1.000      | -            | -                | -                | -         |   -17.72 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           31 |      681 | 2025-02-08 | TEAM NEXT LEVEL       | W   | 1.000      | -            | -                | -                | -         |     7.96 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           30 |      690 | 2025-02-08 | Benched               | W   | 1.000      | -            | -                | -                | -         |     3.33 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           29 |      700 | 2025-02-08 | 500                   | L   | 1.000      | -            | -                | -                | -         |   -10.42 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           28 |      710 | 2025-02-08 | Mission Possible      | W   | 1.000      | -            | -                | -                | -         |     3.27 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           27 |      778 | 2025-02-07 | Nuclear TigeRES       | W   | 1.000      | -            | -                | -                | -         |     7.57 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           26 |      802 | 2025-02-07 | AMKAL ESPORTS         | W   | 1.000      | -            | -                | -                | -         |    10.75 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           25 |      865 | 2025-02-06 | Alliance              | W   | 1.000      | -            | -                | -                | -         |    13.34 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           24 |      887 | 2025-02-05 | SINNERS Esports       | W   | 1.000      | 0.435        | 0.027 (0.012)    | 0.446 (0.194)    | -         |    14.46 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           23 |     1040 | 2025-02-03 | Natus Vincere Junior  | W   | 1.000      | 0.435        | 0.091 (0.039)    | 0.865 (0.376)    | -         |    18.15 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           22 |     1079 | 2025-02-01 | Fnatic                | L   | 1.000      | -            | -                | -                | -         |    -9.59 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           21 |     3659 | 2024-11-10 | Johnny Speeds         | L   | 0.452      | -            | -                | -                | -         |    -7.17 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           20 |     3841 | 2024-11-07 | Natus Vincere Junior  | L   | 0.432      | -            | -                | -                | -         |    -5.44 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           19 |     3862 | 2024-11-07 | Sashi Esport          | L   | 0.430      | -            | -                | -                | -         |    -6.76 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           18 |     3888 | 2024-11-06 | BetBoom Team          | W   | 0.425      | 0.143        | 0.104 (0.006)    | -                | -         |     8.40 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           17 |     3945 | 2024-11-05 | Los kogutos           | W   | 0.418      | 0.384        | 0.032 (0.005)    | -                | -         |     6.12 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           16 |     4079 | 2024-11-03 | 3DMAX                 | L   | 0.404      | -            | -                | -                | -         |    -0.34 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           15 |     4143 | 2024-11-02 | Team Falcons          | L   | 0.398      | -            | -                | -                | -         |    -0.05 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           14 |     4212 | 2024-11-01 | Johnny Speeds         | L   | 0.391      | -            | -                | -                | -         |    -6.24 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           13 |     4343 | 2024-10-30 | 9INE                  | L   | 0.376      | -            | -                | -                | -         |    -8.04 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           12 |     4392 | 2024-10-29 | Zero Tenacity         | W   | 0.371      | -            | -                | -                | -         |     4.69 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           11 |     4398 | 2024-10-29 | Wu-Tang Clan          | W   | 0.370      | -            | -                | -                | -         |     1.08 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           10 |     4449 | 2024-10-28 | 500                   | L   | 0.364      | -            | -                | -                | -         |    -4.41 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            9 |     4567 | 2024-10-26 | BIG                   | W   | 0.349      | 0.934        | 0.248 (0.081)    | 0.572 (0.187)    | -         |    10.57 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            8 |     4614 | 2024-10-25 | Virtus.pro            | W   | 0.343      | 0.934        | 0.272 (0.087)    | 0.436 (0.140)    | -         |    10.65 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            7 |     4733 | 2024-10-21 | 3DMAX                 | L   | 0.318      | -            | -                | -                | -         |    -0.25 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            6 |     4761 | 2024-10-21 | Virtus.pro            | W   | 0.317      | 0.934        | 0.272 (0.081)    | 0.436 (0.129)    | -         |     9.84 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            5 |     5301 | 2024-10-10 | Team Spirit Academy   | L   | 0.244      | -            | -                | -                | -         |    -3.55 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|            4 |     6125 | 2024-09-27 | GameAgents            | L   | 0.158      | -            | -                | -                | -         |    -3.81 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            3 |     6150 | 2024-09-27 | B8                    | L   | 0.157      | -            | -                | -                | -         |    -1.22 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            2 |     7028 | 2024-09-14 | Sashi Esport          | L   | 0.070      | -            | -                | -                | -         |    -0.96 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            1 |     7162 | 2024-09-12 | Team Sampi            | W   | 0.056      | -            | -                | -                | -         |     0.63 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,385.35)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.444 | $15.18         | $6.74           |
| 2024-11-03 |      0.405 | $50,000.00     | $20,236.11      |
| 2024-09-14 |      0.071 | $2,000.00      | $142.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
