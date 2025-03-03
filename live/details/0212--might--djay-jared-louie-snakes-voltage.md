### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Jared, Louie, Snakes, Voltage<br />
Global Rank: [212](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
<br />
Final Rank Value:  705.6<br />
<br />
Final Rank Value (705.6) = Starting Rank Value (802.2) + Head To Head Adjustments (-96.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.265[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.301[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 802.2
- 400 + ( ( 0.201 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 802.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |        3 | 2025-03-01 | BLUEJAYS                  | L   | 1.000      | -            | -                | -                | -         |    -3.98 | djay, Jared, Louie, Snakes, Voltage       |
|           34 |       10 | 2025-03-01 | Akimbo LITE               | W   | 1.000      | 0.333        | 0.000 (0.000)    | -                | 1 (1.000) |     4.73 | djay, Jared, Louie, Snakes, Voltage       |
|           33 |       92 | 2025-02-23 | Take Flyte                | L   | 1.000      | -            | -                | -                | -         |   -22.13 | djay, Jared, PwnAlone, Snakes, Voltage    |
|           32 |      132 | 2025-02-22 | ShanghaiSharks            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.032 (0.005)    | 0 (0.000) |     4.44 | djay, Jared, PwnAlone, Snakes, Voltage    |
|           31 |      402 | 2025-02-15 | Team Aether               | L   | 1.000      | -            | -                | -                | -         |   -25.29 | djay, Jared, Louie, Snakes, Voltage       |
|           30 |      450 | 2025-02-14 | MCS Gaming                | L   | 1.000      | -            | -                | -                | -         |   -20.17 | djay, Jared, Louie, Snakes, Voltage       |
|           29 |      516 | 2025-02-13 | Getting Info              | L   | 1.000      | -            | -                | -                | -         |   -10.55 | djay, Jared, Louie, Snakes, Voltage       |
|           28 |      584 | 2025-02-10 | Party Astronauts          | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.382 (0.055)    | 0 (0.000) |    18.25 | djay, Jared, Louie, Snakes, Voltage       |
|           27 |      590 | 2025-02-10 | Chicken Coop Esports      | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.187 (0.027)    | 0 (0.000) |    11.64 | djay, Jared, Louie, Snakes, Voltage       |
|           26 |      631 | 2025-02-09 | LAG Gaming                | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.120 (0.017)    | 0 (0.000) |    14.01 | djay, Jared, Louie, Snakes, Voltage       |
|           25 |      686 | 2025-02-08 | Party Astronauts          | L   | 1.000      | -            | -                | -                | -         |   -13.20 | djay, Jared, Louie, Snakes, Voltage       |
|           24 |      747 | 2025-02-07 | Nouns Esports             | L   | 1.000      | -            | -                | -                | -         |   -10.42 | djay, Jared, PwnAlone, Snakes, Voltage    |
|           23 |      822 | 2025-02-06 | Blahaj                    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.144 (0.021)    | 0 (0.000) |     8.01 | djay, Jared, Louie, Snakes, Voltage       |
|           22 |      826 | 2025-02-06 | Zomblers                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     3.92 | djay, Jared, Louie, Snakes, Voltage       |
|           21 |      830 | 2025-02-06 | MCS Gaming                | L   | 1.000      | -            | -                | -                | -         |   -20.20 | djay, Jared, Louie, Snakes, Voltage       |
|           20 |      833 | 2025-02-06 | Budgetmythic              | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | -         |     3.58 | djay, Jared, Louie, Snakes, Voltage       |
|           19 |     2050 | 2024-12-07 | Undone                    | L   | 0.634      | -            | -                | -                | -         |    -9.88 | djay, Louie, PwnAlone, REKMEISTER, Snakes |
|           18 |     2063 | 2024-12-07 | ROOMBA PEEK               | W   | 0.633      | 0.384        | -                | 0.029 (0.007)    | 1 (0.633) |     4.60 | djay, Louie, PwnAlone, REKMEISTER, Snakes |
|           17 |     2086 | 2024-12-07 | Not Mythic                | W   | 0.632      | -            | -                | -                | 1 (0.632) |     3.20 | djay, Louie, PwnAlone, REKMEISTER, Snakes |
|           16 |     2127 | 2024-12-06 | Sharks Esports            | L   | 0.627      | -            | -                | -                | -         |    -4.30 | djay, Louie, PwnAlone, REKMEISTER, Snakes |
|           15 |     2254 | 2024-12-03 | Immigrants Peek           | L   | 0.608      | -            | -                | -                | -         |   -13.05 | djay, Jonji, louie, PwnAlone, Snakes      |
|           14 |     2391 | 2024-12-01 | Chicken Coop Esports      | L   | 0.594      | -            | -                | -                | -         |   -11.88 | djay, Jonji, louie, PwnAlone, Snakes      |
|           13 |     2580 | 2024-11-29 | Regain                    | W   | 0.581      | 0.372        | -                | 0.155 (0.034)    | -         |     2.94 | djay, Jonji, louie, PwnAlone, Snakes      |
|           12 |     4784 | 2024-10-20 | Timbermen                 | L   | 0.311      | -            | -                | -                | -         |    -6.48 | djay, Jonji, louie, PwnAlone, Snakes      |
|           11 |     4839 | 2024-10-19 | Amped Esports             | W   | 0.307      | -            | -                | -                | 1 (0.307) |     0.94 | djay, Jonji, louie, PwnAlone, Snakes      |
|           10 |     6182 | 2024-09-26 | Familia Maquininha        | L   | 0.153      | -            | -                | -                | -         |    -3.18 | djay, Jonji, louie, PwnAlone, Snakes      |
|            9 |     6614 | 2024-09-20 | FLUFFY AIMERS             | L   | 0.114      | -            | -                | -                | -         |    -1.78 | danss, djay, louie, PwnAlone, Snakes      |
|            8 |     6622 | 2024-09-20 | InControl                 | W   | 0.113      | -            | -                | -                | -         |     0.34 | danss, djay, louie, PwnAlone, Snakes      |
|            7 |     6628 | 2024-09-20 | Not Mythic                | W   | 0.113      | -            | -                | -                | -         |     0.50 | danss, djay, louie, PwnAlone, Snakes      |
|            6 |     6799 | 2024-09-17 | Undefined (American team) | L   | 0.094      | -            | -                | -                | -         |    -2.17 | djay, Jonji, louie, PwnAlone, Snakes      |
|            5 |     6921 | 2024-09-15 | Homyno                    | W   | 0.080      | 0.372        | 0.008 (0.000)    | 0.189 (0.006)    | -         |     0.96 | djay, Jonji, louie, PwnAlone, Snakes      |
|            4 |     7067 | 2024-09-13 | Straykids                 | W   | 0.067      | 0.372        | 0.000 (0.000)    | -                | -         |     0.34 | djay, Jonji, louie, PwnAlone, Snakes      |
|            3 |     7123 | 2024-09-12 | Regain                    | W   | 0.060      | 0.372        | -                | 0.155 (0.003)    | -         |     0.28 | djay, Jonji, louie, PwnAlone, Snakes      |
|            2 |     7382 | 2024-09-07 | Final Form                | L   | 0.027      | -            | -                | -                | -         |    -0.63 | djay, Jonji, louie, PwnAlone, Snakes      |
|            1 |     7555 | 2024-09-05 | Take Flyte                | W   | 0.014      | -            | -                | -                | -         |     0.09 | djay, Jonji, louie, PwnAlone, Snakes      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($553.54)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.313 | $1,000.00      | $312.99         |
| 2024-09-21 |      0.120 | $2,000.00      | $240.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
