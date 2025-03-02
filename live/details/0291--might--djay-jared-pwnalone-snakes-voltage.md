### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Jared, PwnAlone, Snakes, Voltage<br />
Global Rank: [291](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [56]( ../standings_americas.md)<br />
<br />
Final Rank Value:  653.0<br />
<br />
Final Rank Value (653.0) = Starting Rank Value (742.5) + Head To Head Adjustments (-89.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.266[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.186[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 742.5
- 400 + ( ( 0.171 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 742.5


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
|           33 |       77 | 2025-02-23 | Take Flyte                | L   | 1.000      | -            | -                | -                | -         |   -22.24 | djay, Jared, PwnAlone, Snakes, Voltage    |
|           32 |      117 | 2025-02-22 | ShanghaiSharks            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.032 (0.005)    | 0 (0.000) |     5.66 | djay, Jared, PwnAlone, Snakes, Voltage    |
|           31 |      390 | 2025-02-15 | Team Aether               | L   | 1.000      | -            | -                | -                | -         |   -23.68 | djay, Jared, Louie, Snakes, Voltage       |
|           30 |      438 | 2025-02-14 | MCS Gaming                | L   | 1.000      | -            | -                | -                | -         |   -19.02 | djay, Jared, Louie, Snakes, Voltage       |
|           29 |      504 | 2025-02-13 | Getting Info              | L   | 1.000      | -            | -                | -                | -         |   -23.55 | djay, Jared, Louie, Snakes, Voltage       |
|           28 |      572 | 2025-02-10 | Party Astronauts          | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.385 (0.055)    | 0 (0.000) |    19.76 | djay, Jared, Louie, Snakes, Voltage       |
|           27 |      578 | 2025-02-10 | Chicken Coop Esports      | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.189 (0.027)    | 0 (0.000) |    13.09 | djay, Jared, Louie, Snakes, Voltage       |
|           26 |      619 | 2025-02-09 | LAG Gaming                | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.027 (0.004)    | 0 (0.000) |    10.26 | djay, Jared, Louie, Snakes, Voltage       |
|           25 |      674 | 2025-02-08 | Party Astronauts          | L   | 1.000      | -            | -                | -                | -         |   -11.68 | djay, Jared, Louie, Snakes, Voltage       |
|           24 |      735 | 2025-02-07 | Nouns Esports             | L   | 1.000      | -            | -                | -                | -         |    -9.45 | djay, Jared, PwnAlone, Snakes, Voltage    |
|           23 |      810 | 2025-02-06 | Blahaj                    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.144 (0.021)    | 0 (0.000) |     9.61 | djay, Jared, Louie, Snakes, Voltage       |
|           22 |      814 | 2025-02-06 | Zomblers                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     4.89 | djay, Jared, Louie, Snakes, Voltage       |
|           21 |      818 | 2025-02-06 | MCS Gaming                | L   | 1.000      | -            | -                | -                | -         |   -18.28 | djay, Jared, Louie, Snakes, Voltage       |
|           20 |      821 | 2025-02-06 | Budgetmythic              | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     4.55 | djay, Jared, Louie, Snakes, Voltage       |
|           19 |     2038 | 2024-12-07 | Undone                    | L   | 0.643      | -            | -                | -                | -         |    -8.68 | djay, Louie, PwnAlone, REKMEISTER, Snakes |
|           18 |     2051 | 2024-12-07 | ROOMBA PEEK               | W   | 0.642      | 0.384        | 0.000 (0.000)    | 0.030 (0.007)    | 1 (0.642) |     5.75 | djay, Louie, PwnAlone, REKMEISTER, Snakes |
|           17 |     2074 | 2024-12-07 | Not Mythic                | W   | 0.640      | -            | -                | -                | 1 (0.640) |     4.09 | djay, Louie, PwnAlone, REKMEISTER, Snakes |
|           16 |     2115 | 2024-12-06 | Sharks Esports            | L   | 0.635      | -            | -                | -                | -         |    -3.45 | djay, Louie, PwnAlone, REKMEISTER, Snakes |
|           15 |     2242 | 2024-12-03 | Immigrants Peek           | L   | 0.616      | -            | -                | -                | -         |   -11.90 | djay, Jonji, louie, PwnAlone, Snakes      |
|           14 |     2379 | 2024-12-01 | Chicken Coop Esports      | L   | 0.602      | -            | -                | -                | -         |   -10.71 | djay, Jonji, louie, PwnAlone, Snakes      |
|           13 |     2568 | 2024-11-29 | Regain                    | W   | 0.589      | 0.372        | -                | 0.157 (0.034)    | -         |     3.88 | djay, Jonji, louie, PwnAlone, Snakes      |
|           12 |     4772 | 2024-10-20 | Timbermen                 | L   | 0.320      | -            | -                | -                | -         |    -5.88 | djay, Jonji, louie, PwnAlone, Snakes      |
|           11 |     4827 | 2024-10-19 | Amped Esports             | W   | 0.315      | -            | -                | -                | 1 (0.315) |     1.28 | djay, Jonji, louie, PwnAlone, Snakes      |
|           10 |     6170 | 2024-09-26 | Familia Maquininha        | L   | 0.161      | -            | -                | -                | -         |    -2.91 | djay, Jonji, louie, PwnAlone, Snakes      |
|            9 |     6602 | 2024-09-20 | FLUFFY AIMERS             | L   | 0.122      | -            | -                | -                | -         |    -1.60 | danss, djay, louie, PwnAlone, Snakes      |
|            8 |     6610 | 2024-09-20 | InControl                 | W   | 0.122      | -            | -                | -                | -         |     0.49 | danss, djay, louie, PwnAlone, Snakes      |
|            7 |     6616 | 2024-09-20 | Not Mythic                | W   | 0.121      | -            | -                | -                | -         |     0.71 | danss, djay, louie, PwnAlone, Snakes      |
|            6 |     6787 | 2024-09-17 | Undefined (American team) | L   | 0.102      | -            | -                | -                | -         |    -2.13 | djay, Jonji, louie, PwnAlone, Snakes      |
|            5 |     6909 | 2024-09-15 | Homyno                    | W   | 0.088      | 0.372        | 0.008 (0.000)    | 0.192 (0.006)    | -         |     1.28 | djay, Jonji, louie, PwnAlone, Snakes      |
|            4 |     7055 | 2024-09-13 | Straykids                 | W   | 0.075      | 0.372        | 0.000 (0.000)    | -                | -         |     0.51 | djay, Jonji, louie, PwnAlone, Snakes      |
|            3 |     7111 | 2024-09-12 | Regain                    | W   | 0.068      | 0.372        | -                | 0.157 (0.004)    | -         |     0.42 | djay, Jonji, louie, PwnAlone, Snakes      |
|            2 |     7370 | 2024-09-07 | Final Form                | L   | 0.035      | -            | -                | -                | -         |    -0.75 | djay, Jonji, louie, PwnAlone, Snakes      |
|            1 |     7543 | 2024-09-05 | Take Flyte                | W   | 0.022      | -            | -                | -                | -         |     0.14 | djay, Jonji, louie, PwnAlone, Snakes      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($578.13)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.321 | $1,000.00      | $321.18         |
| 2024-09-21 |      0.128 | $2,000.00      | $256.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
