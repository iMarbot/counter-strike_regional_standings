### Roster Details<br />
Team Name: BLUEJAYS<br />
Roster: freshie, Fruitcupx, SLIGHT, snav, Wolffe<br />
Global Rank: [30](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [8]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1068.2<br />
<br />
Final Rank Value (1068.2) = Starting Rank Value (1177.5) + Head To Head Adjustments (-109.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.398[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.066[<sup>2</sup>](#table1)
- LAN Wins: 0.820[<sup>2</sup>](#table1)

The average of these factors is 0.389<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1177.5
- 400 + ( ( 0.389 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1177.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |        0 | 2025-03-02 | Marsborne         | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.234 (0.078)    | 1 (1.000) |     9.31 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           42 |        2 | 2025-03-02 | LAG Gaming        | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.120 (0.040)    | 1 (1.000) |     4.05 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           41 |        3 | 2025-03-01 | MIGHT             | W   | 1.000      | 0.333        | -                | 0.489 (0.163)    | 1 (1.000) |     3.98 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           40 |       13 | 2025-03-01 | Anti-Eco Club     | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.80 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           39 |      466 | 2025-02-14 | M80               | L   | 1.000      | -            | -                | -                | -         |   -16.98 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           38 |      478 | 2025-02-14 | Getting Info      | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.309 (0.044)    | 0 (0.000) |     8.91 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           37 |      517 | 2025-02-13 | Immigrants Peek   | W   | 1.000      | 0.143        | -                | 0.366 (0.052)    | -         |     3.27 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           36 |      537 | 2025-02-12 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -22.66 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           35 |      554 | 2025-02-11 | NRG               | L   | 1.000      | -            | -                | -                | -         |   -17.60 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           34 |      559 | 2025-02-11 | Nouns Esports     | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.327 (0.047)    | -         |     7.21 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           33 |     1665 | 2024-12-14 | Getting Info      | L   | 0.681      | -            | -                | -                | -         |   -17.03 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           32 |     1980 | 2024-12-08 | Sharks Esports    | L   | 0.640      | -            | -                | -                | -         |   -13.12 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           31 |     1984 | 2024-12-08 | Nouns Esports     | W   | 0.639      | 0.384        | 0.007 (0.002)    | 0.327 (0.080)    | 1 (0.639) |     4.30 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           30 |     2004 | 2024-12-08 | FLUFFY AIMERS     | W   | 0.638      | 0.384        | 0.005 (0.001)    | 0.213 (0.052)    | 1 (0.638) |     3.09 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           29 |     2055 | 2024-12-07 | NRG               | L   | 0.634      | -            | -                | -                | -         |   -13.02 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           28 |     2070 | 2024-12-07 | ROOMBA PEEK       | W   | 0.633      | -            | -                | -                | 1 (0.633) |     0.80 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           27 |     2121 | 2024-12-06 | What's for Dinner | W   | 0.627      | -            | -                | -                | 1 (0.627) |     0.33 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           26 |     2780 | 2024-11-24 | Nouns Esports     | L   | 0.546      | -            | -                | -                | -         |   -14.35 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           25 |     2840 | 2024-11-23 | Undone            | W   | 0.539      | 0.303        | -                | 0.282 (0.046)    | -         |     1.99 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           24 |     3492 | 2024-11-13 | BESTIA            | L   | 0.475      | -            | -                | -                | -         |   -11.15 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           23 |     3541 | 2024-11-12 | FURIA             | L   | 0.468      | -            | -                | -                | -         |    -2.41 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           22 |     3567 | 2024-11-12 | Complexity        | L   | 0.463      | -            | -                | -                | -         |    -7.19 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           21 |     3587 | 2024-11-11 | M80               | W   | 0.462      | 0.143        | 0.038 (0.002)    | -                | 1 (0.462) |     3.50 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           20 |     4976 | 2024-10-16 | Wildcard          | L   | 0.287      | -            | -                | -                | -         |    -2.60 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           19 |     5045 | 2024-10-15 | FLUFFY AIMERS     | W   | 0.280      | 0.477        | 0.005 (0.001)    | -                | -         |     1.11 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           18 |     5314 | 2024-10-09 | M80               | L   | 0.240      | -            | -                | -                | -         |    -5.88 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           17 |     5320 | 2024-10-09 | M80               | W   | 0.240      | 0.477        | 0.038 (0.004)    | 0.462 (0.053)    | -         |     1.70 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           16 |     5458 | 2024-10-07 | FLUFFY AIMERS     | W   | 0.227      | -            | -                | -                | -         |     0.96 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           15 |     5460 | 2024-10-07 | FLUFFY AIMERS     | L   | 0.227      | -            | -                | -                | -         |    -6.23 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           14 |     5563 | 2024-10-05 | FLUFFY AIMERS     | W   | 0.214      | -            | -                | -                | -         |     0.86 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           13 |     5575 | 2024-10-05 | Party Astronauts  | W   | 0.212      | -            | -                | -                | -         |     0.70 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           12 |     5709 | 2024-10-03 | NRG               | W   | 0.200      | 0.371        | 0.049 (0.004)    | -                | -         |     1.92 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           11 |     5823 | 2024-10-01 | Wildcard          | L   | 0.187      | -            | -                | -                | -         |    -1.45 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           10 |     5826 | 2024-10-01 | Wildcard          | L   | 0.187      | -            | -                | -                | -         |    -1.47 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            9 |     5895 | 2024-09-30 | Mythic            | W   | 0.180      | -            | -                | -                | -         |     0.14 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            8 |     6106 | 2024-09-27 | Legacy            | L   | 0.159      | -            | -                | -                | -         |    -4.21 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            7 |     6185 | 2024-09-26 | Exceritus         | W   | 0.153      | -            | -                | -                | -         |     0.22 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            6 |     6252 | 2024-09-25 | Vagrants          | W   | 0.147      | -            | -                | -                | -         |     0.25 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            5 |     6256 | 2024-09-25 | Vagrants          | L   | 0.147      | -            | -                | -                | -         |    -4.38 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            4 |     6345 | 2024-09-24 | Party Astronauts  | W   | 0.140      | -            | -                | -                | -         |     0.43 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            3 |     6352 | 2024-09-24 | Party Astronauts  | L   | 0.140      | -            | -                | -                | -         |    -4.00 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            2 |     6510 | 2024-09-22 | Nouns Esports     | L   | 0.126      | -            | -                | -                | -         |    -3.68 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            1 |     6558 | 2024-09-21 | Timbermen         | W   | 0.120      | -            | -                | -                | -         |     0.19 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,176.77)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-02 |      1.000 | $5,500.00      | $5,500.00       |
| 2024-12-08 |      0.641 | $2,500.00      | $1,601.91       |
| 2024-10-20 |      0.313 | $3,000.00      | $938.75         |
| 2024-10-05 |      0.214 | $10,000.00     | $2,136.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
