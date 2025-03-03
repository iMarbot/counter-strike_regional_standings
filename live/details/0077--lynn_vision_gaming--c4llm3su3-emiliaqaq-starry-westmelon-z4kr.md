### Roster Details<br />
Team Name: Lynn Vision Gaming<br />
Roster: C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  888.8<br />
<br />
Final Rank Value (888.8) = Starting Rank Value (870.0) + Head To Head Adjustments (18.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.079[<sup>2</sup>](#table1)
- LAN Wins: 0.202[<sup>2</sup>](#table1)

The average of these factors is 0.235<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 870.0
- 400 + ( ( 0.235 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 870.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      532 | 2025-02-12 | The Huns Esports        | L   | 1.000      | -            | -                | -                | -         |   -15.79 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           40 |      546 | 2025-02-12 | ATOX Esports            | W   | 1.000      | 0.143        | 0.064 (0.009)    | 0.601 (0.086)    | 0 (0.000) |    24.12 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           39 |      550 | 2025-02-12 | The Huns Esports        | W   | 1.000      | 0.143        | 0.025 (0.004)    | 0.553 (0.079)    | 0 (0.000) |    16.82 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           38 |      552 | 2025-02-11 | Unsettled Resentment    | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |    11.35 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           37 |      570 | 2025-02-11 | TYLOO                   | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.290 (0.041)    | 0 (0.000) |    14.46 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           36 |      576 | 2025-02-11 | The Huns Esports        | L   | 1.000      | -            | -                | -                | -         |   -13.74 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           35 |     1255 | 2024-12-30 | Rare Atom               | L   | 0.782      | -            | -                | -                | -         |    -8.38 | EmiliaQAQ, kwkw, suki272, westmelon, z4kr     |
|           34 |     1343 | 2024-12-27 | Unsettled Resentment    | W   | 0.764      | 0.396        | 0.014 (0.004)    | 0.258 (0.078)    | 0 (0.000) |     8.53 | EmiliaQAQ, kwkw, suki272, westmelon, z4kr     |
|           33 |     1350 | 2024-12-27 | DogEvil                 | W   | 0.762      | 0.396        | 0.024 (0.007)    | 0.895 (0.271)    | 0 (0.000) |    11.38 | EmiliaQAQ, kwkw, suki272, westmelon, z4kr     |
|           32 |     2687 | 2024-11-27 | TYLOO                   | L   | 0.564      | -            | -                | -                | -         |   -10.13 | afufu, EmiliaQAQ, kwkw, westmelon, z4kr       |
|           31 |     2692 | 2024-11-27 | Boring Players          | W   | 0.563      | -            | -                | -                | -         |     2.42 | afufu, EmiliaQAQ, kwkw, westmelon, z4kr       |
|           30 |     2696 | 2024-11-26 | Teamwork (Chinese team) | W   | 0.561      | 0.143        | 0.032 (0.003)    | -                | -         |     5.09 | afufu, EmiliaQAQ, kwkw, westmelon, z4kr       |
|           29 |     2747 | 2024-11-26 | DogEvil                 | L   | 0.556      | -            | -                | -                | -         |   -10.44 | afufu, EmiliaQAQ, kwkw, westmelon, z4kr       |
|           28 |     3527 | 2024-11-13 | FlyQuest                | L   | 0.470      | -            | -                | -                | -         |    -3.01 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           27 |     3535 | 2024-11-12 | TALON                   | W   | 0.469      | -            | -                | -                | 1 (0.469) |     2.46 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           26 |     3593 | 2024-11-11 | Alter Ego               | W   | 0.461      | -            | -                | -                | 1 (0.461) |     2.44 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           25 |     3639 | 2024-11-11 | Adventurers             | L   | 0.456      | -            | -                | -                | -         |    -7.91 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           24 |     4102 | 2024-11-03 | TYLOO                   | L   | 0.403      | -            | -                | -                | -         |    -7.77 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           23 |     4105 | 2024-11-02 | ATOX Esports            | W   | 0.402      | -            | -                | -                | 1 (0.402) |     3.84 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           22 |     4171 | 2024-11-02 | Unsettled Resentment    | W   | 0.395      | 0.417        | 0.014 (0.002)    | 0.258 (0.043)    | 1 (0.395) |     4.26 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           21 |     4956 | 2024-10-17 | The Huns Esports        | W   | 0.290      | 0.417        | 0.025 (0.003)    | 0.553 (0.067)    | -         |     5.52 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           20 |     5022 | 2024-10-16 | ATOX Esports            | L   | 0.283      | -            | -                | -                | -         |    -6.16 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           19 |     5365 | 2024-10-09 | TYLOO                   | W   | 0.237      | -            | -                | -                | -         |     2.89 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           18 |     5371 | 2024-10-09 | TYLOO                   | W   | 0.237      | -            | -                | -                | -         |     2.94 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           17 |     5442 | 2024-10-08 | Harizma                 | L   | 0.230      | -            | -                | -                | -         |    -4.93 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           16 |     5448 | 2024-10-08 | Harizma                 | L   | 0.230      | -            | -                | -                | -         |    -5.01 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           15 |     5794 | 2024-10-02 | The QUBE Esports        | W   | 0.190      | -            | -                | -                | -         |     1.17 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           14 |     5799 | 2024-10-02 | The QUBE Esports        | W   | 0.190      | -            | -                | -                | -         |     1.18 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           13 |     5870 | 2024-10-01 | Chinggis Warriors       | W   | 0.183      | 0.417        | -                | 0.563 (0.043)    | -         |     3.46 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           12 |     5876 | 2024-10-01 | Chinggis Warriors       | W   | 0.183      | 0.417        | -                | 0.563 (0.043)    | -         |     3.51 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           11 |     6313 | 2024-09-25 | Nomads (Mongolian team) | L   | 0.143      | -            | -                | -                | -         |    -3.50 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           10 |     6319 | 2024-09-25 | Nomads (Mongolian team) | L   | 0.143      | -            | -                | -                | -         |    -3.53 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            9 |     6407 | 2024-09-24 | DEWA United             | L   | 0.137      | -            | -                | -                | -         |    -3.73 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            8 |     6414 | 2024-09-24 | DEWA United             | L   | 0.137      | -            | -                | -                | -         |    -3.74 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            7 |     6480 | 2024-09-23 | Passion UA              | L   | 0.131      | -            | -                | -                | -         |    -1.20 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            6 |     6533 | 2024-09-22 | Insilio                 | L   | 0.124      | -            | -                | -                | -         |    -2.85 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            5 |     6656 | 2024-09-20 | ECSTATIC                | W   | 0.110      | 0.435        | -                | 0.820 (0.039)    | -         |     1.77 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            4 |     6868 | 2024-09-17 | Nexus Gaming            | W   | 0.089      | 0.435        | 0.187 (0.007)    | -                | -         |     2.40 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            3 |     6942 | 2024-09-15 | FAVBET Team             | L   | 0.077      | -            | -                | -                | -         |    -1.31 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            2 |     7533 | 2024-09-06 | FlyQuest                | L   | 0.017      | -            | -                | -                | -         |    -0.12 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            1 |     7671 | 2024-09-04 | Team Falcons            | L   | 0.005      | -            | -                | -                | -         |     0.00 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,612.82)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.783 | $2,500.00      | $1,957.99       |
| 2024-11-03 |      0.403 | $8,000.00      | $3,220.74       |
| 2024-09-22 |      0.124 | $3,500.00      | $434.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
