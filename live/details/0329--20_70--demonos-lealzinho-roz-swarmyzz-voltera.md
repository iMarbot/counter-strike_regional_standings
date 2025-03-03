### Roster Details<br />
Team Name: 20/70<br />
Roster: Demonos, lealziNho, Roz, swarmyzz, voltera<br />
Global Rank: [329](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [67]( ../standings_americas.md)<br />
<br />
Final Rank Value:  635.2<br />
<br />
Final Rank Value (635.2) = Starting Rank Value (653.8) + Head To Head Adjustments (-18.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.127<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 653.8
- 400 + ( ( 0.127 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 653.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |     1542 | 2024-12-19 | 9z Academy                | L   | 0.712      | -            | -                | -                | -         |   -10.29 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           34 |     1583 | 2024-12-17 | Game Hunters              | L   | 0.697      | -            | -                | -                | -         |    -9.02 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           33 |     1590 | 2024-12-16 | LaChampionsLiga           | L   | 0.693      | -            | -                | -                | -         |   -10.83 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           32 |     1770 | 2024-12-13 | Players (Brazilian team)  | L   | 0.673      | -            | -                | -                | -         |    -7.16 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           31 |     1840 | 2024-12-12 | 9z Academy                | W   | 0.665      | 0.143        | 0.001 (0.000)    | 0.384 (0.036)    | 0 (0.000) |    10.98 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           30 |     1930 | 2024-12-10 | América eSports           | W   | 0.652      | 0.143        | 0.000 (0.000)    | 0.426 (0.040)    | 0 (0.000) |     9.56 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           29 |     1958 | 2024-12-09 | SamuraiS (Brazilian team) | W   | 0.645      | 0.143        | -                | 0.154 (0.014)    | 0 (0.000) |     6.96 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           28 |     2208 | 2024-12-04 | DB Peek Esports           | W   | 0.613      | 0.143        | 0.000 (0.000)    | 0.236 (0.021)    | 0 (0.000) |     9.19 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           27 |     2264 | 2024-12-03 | SamuraiS (Brazilian team) | L   | 0.606      | -            | -                | -                | -         |   -12.55 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           26 |     2616 | 2024-11-28 | Nitro.GG                  | L   | 0.573      | -            | -                | -                | -         |    -7.79 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           25 |     2643 | 2024-11-28 | Sharks Esports            | L   | 0.572      | -            | -                | -                | -         |    -2.27 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           24 |     2739 | 2024-11-26 | Patins da Ferrari         | W   | 0.558      | 0.371        | -                | 0.124 (0.026)    | 0 (0.000) |     5.91 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           23 |     2765 | 2024-11-25 | ShindeN                   | W   | 0.551      | 0.371        | 0.005 (0.001)    | 0.308 (0.063)    | 0 (0.000) |    10.16 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           22 |     2896 | 2024-11-23 | Players (Brazilian team)  | L   | 0.537      | -            | -                | -                | -         |    -6.23 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           21 |     3049 | 2024-11-21 | Game Hunters              | L   | 0.524      | -            | -                | -                | -         |   -11.45 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           20 |     3084 | 2024-11-20 | Floripa Stars             | W   | 0.520      | 0.143        | 0.001 (0.000)    | 0.296 (0.022)    | 0 (0.000) |     8.35 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           19 |     3149 | 2024-11-19 | Floripa Stars             | W   | 0.513      | 0.371        | 0.001 (0.000)    | 0.296 (0.056)    | 0 (0.000) |     8.46 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           18 |     3713 | 2024-11-09 | Yawara E-Sports           | L   | 0.445      | -            | -                | -                | -         |    -5.76 | Demonos, kln, proSHOW, Roz, voltera        |
|           17 |     3840 | 2024-11-07 | VELOX Argentina           | W   | 0.432      | 0.143        | -                | 0.262 (0.016)    | 0 (0.000) |     4.72 | Demonos, kln, proSHOW, Roz, voltera        |
|           16 |     4001 | 2024-11-04 | Galorys Academy           | W   | 0.412      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     6.28 | Demonos, kln, proSHOW, Roz, voltera        |
|           15 |     4206 | 2024-11-01 | Intense Game              | L   | 0.392      | -            | -                | -                | -         |    -5.48 | Demonos, proSHOW, Roz, suNday, voltera     |
|           14 |     4280 | 2024-10-30 | UNO MILLE                 | L   | 0.380      | -            | -                | -                | -         |    -4.57 | Demonos, proSHOW, Roz, suNday, voltera     |
|           13 |     4418 | 2024-10-28 | Sharks Youngsters         | W   | 0.366      | 0.143        | 0.000 (0.000)    | -                | -         |     4.74 | Demonos, kln, proSHOW, Roz, voltera        |
|           12 |     4653 | 2024-10-23 | Dusty Roots               | W   | 0.333      | 0.333        | 0.009 (0.001)    | 0.366 (0.041)    | -         |     7.05 | Demonos, proSHOW, Roz, suNday, voltera     |
|           11 |     4704 | 2024-10-22 | RED Canids Academy        | L   | 0.325      | -            | -                | -                | -         |    -4.39 | Demonos, kln, proSHOW, Roz, voltera        |
|           10 |     4978 | 2024-10-16 | RED Canids Academy        | L   | 0.287      | -            | -                | -                | -         |    -3.97 | Demonos, proSHOW, Roz, suNday, voltera     |
|            9 |     5754 | 2024-10-02 | Intense Game              | W   | 0.193      | 0.333        | 0.003 (0.000)    | -                | -         |     3.18 | Demonos, proSHOW, Roz, suNday, voltera     |
|            8 |     5762 | 2024-10-02 | UNO MILLE                 | L   | 0.193      | -            | -                | -                | -         |    -2.24 | Demonos, proSHOW, Roz, suNday, voltera     |
|            7 |     5843 | 2024-10-01 | Romanos                   | L   | 0.186      | -            | -                | -                | -         |    -4.21 | Demonos, paqueta, Roz, timid, voltera      |
|            6 |     6014 | 2024-09-28 | Myth e-Sports             | L   | 0.165      | -            | -                | -                | -         |    -3.02 | Demonos, paqueta, Roz, timid, voltera      |
|            5 |     6048 | 2024-09-28 | Só os do JOB              | W   | 0.164      | -            | -                | -                | -         |     1.02 | Demonos, paqueta, Roz, timid, voltera      |
|            4 |     6269 | 2024-09-25 | Bounty Hunters Esports    | L   | 0.146      | -            | -                | -                | -         |    -2.36 | Demonos, proSHOW, Roz, suNday, voltera     |
|            3 |     6274 | 2024-09-25 | Dusty Roots               | L   | 0.146      | -            | -                | -                | -         |    -1.47 | Demonos, proSHOW, Roz, suNday, voltera     |
|            2 |     6367 | 2024-09-24 | SamuraiS (Brazilian team) | W   | 0.139      | -            | -                | -                | -         |     1.31 | Demonos, paqueta, Roz, timid, voltera      |
|            1 |     6746 | 2024-09-18 | RED Canids Academy        | L   | 0.099      | -            | -                | -                | -         |    -1.43 | Demonos, proSHOW, Roz, suNday, voltera     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($426.89)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-13 |      0.673 | $333.50        | $224.32         |
| 2024-11-03 |      0.405 | $500.00        | $202.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
