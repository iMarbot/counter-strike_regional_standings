### Roster Details<br />
Team Name: 20/70<br />
Roster: Demonos, lealziNho, Roz, swarmyzz, voltera<br />
Global Rank: [327](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [65]( ../standings_americas.md)<br />
<br />
Final Rank Value:  636.3<br />
<br />
Final Rank Value (636.3) = Starting Rank Value (654.1) + Head To Head Adjustments (-17.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.127<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.1
- 400 + ( ( 0.127 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 654.1


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
|           35 |     1530 | 2024-12-19 | 9z Academy                | L   | 0.720      | -            | -                | -                | -         |   -10.38 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           34 |     1571 | 2024-12-17 | Game Hunters              | L   | 0.706      | -            | -                | -                | -         |    -9.13 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           33 |     1578 | 2024-12-16 | LaChampionsLiga           | L   | 0.701      | -            | -                | -                | -         |   -10.95 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           32 |     1758 | 2024-12-13 | Players (Brazilian team)  | L   | 0.681      | -            | -                | -                | -         |    -7.23 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           31 |     1828 | 2024-12-12 | 9z Academy                | W   | 0.674      | 0.143        | 0.001 (0.000)    | 0.388 (0.037)    | 0 (0.000) |    11.13 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           30 |     1918 | 2024-12-10 | América eSports           | W   | 0.660      | 0.143        | 0.000 (0.000)    | 0.429 (0.040)    | 0 (0.000) |     9.65 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           29 |     1946 | 2024-12-09 | SamuraiS (Brazilian team) | W   | 0.654      | 0.143        | -                | 0.157 (0.015)    | 0 (0.000) |     7.03 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           28 |     2196 | 2024-12-04 | DB Peek Esports           | W   | 0.621      | 0.143        | 0.000 (0.000)    | 0.240 (0.021)    | 0 (0.000) |     9.32 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           27 |     2252 | 2024-12-03 | SamuraiS (Brazilian team) | L   | 0.614      | -            | -                | -                | -         |   -12.73 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           26 |     2604 | 2024-11-28 | Nitro.GG                  | L   | 0.581      | -            | -                | -                | -         |    -7.90 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           25 |     2631 | 2024-11-28 | Sharks Esports            | L   | 0.580      | -            | -                | -                | -         |    -2.34 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           24 |     2727 | 2024-11-26 | Patins da Ferrari         | W   | 0.566      | 0.371        | -                | 0.127 (0.027)    | 0 (0.000) |     6.02 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           23 |     2753 | 2024-11-25 | ShindeN                   | W   | 0.560      | 0.371        | 0.005 (0.001)    | 0.310 (0.064)    | 0 (0.000) |    10.36 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           22 |     2884 | 2024-11-23 | Players (Brazilian team)  | L   | 0.546      | -            | -                | -                | -         |    -6.32 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           21 |     3037 | 2024-11-21 | Game Hunters              | L   | 0.532      | -            | -                | -                | -         |   -11.62 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           20 |     3072 | 2024-11-20 | Floripa Stars             | W   | 0.528      | 0.143        | 0.001 (0.000)    | 0.302 (0.023)    | 0 (0.000) |     8.48 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           19 |     3137 | 2024-11-19 | Floripa Stars             | W   | 0.522      | 0.371        | 0.001 (0.000)    | 0.302 (0.058)    | 0 (0.000) |     8.59 | Demonos, lealziNho, Roz, swarmyzz, voltera |
|           18 |     3701 | 2024-11-09 | Yawara E-Sports           | L   | 0.454      | -            | -                | -                | -         |    -5.85 | Demonos, kln, proSHOW, Roz, voltera        |
|           17 |     3828 | 2024-11-07 | VELOX Argentina           | W   | 0.440      | 0.143        | -                | 0.266 (0.017)    | 0 (0.000) |     6.05 | Demonos, kln, proSHOW, Roz, voltera        |
|           16 |     3989 | 2024-11-04 | Galorys Academy           | W   | 0.420      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     6.42 | Demonos, kln, proSHOW, Roz, voltera        |
|           15 |     4194 | 2024-11-01 | Intense Game              | L   | 0.400      | -            | -                | -                | -         |    -5.58 | Demonos, proSHOW, Roz, suNday, voltera     |
|           14 |     4268 | 2024-10-30 | UNO MILLE                 | L   | 0.389      | -            | -                | -                | -         |    -4.66 | Demonos, proSHOW, Roz, suNday, voltera     |
|           13 |     4406 | 2024-10-28 | Sharks Youngsters         | W   | 0.374      | 0.143        | 0.000 (0.000)    | -                | -         |     4.85 | Demonos, kln, proSHOW, Roz, voltera        |
|           12 |     4641 | 2024-10-23 | Dusty Roots               | W   | 0.341      | 0.333        | 0.008 (0.001)    | 0.371 (0.042)    | -         |     7.22 | Demonos, proSHOW, Roz, suNday, voltera     |
|           11 |     4692 | 2024-10-22 | RED Canids Academy        | L   | 0.333      | -            | -                | -                | -         |    -4.49 | Demonos, kln, proSHOW, Roz, voltera        |
|           10 |     4966 | 2024-10-16 | RED Canids Academy        | L   | 0.295      | -            | -                | -                | -         |    -4.08 | Demonos, proSHOW, Roz, suNday, voltera     |
|            9 |     5742 | 2024-10-02 | Intense Game              | W   | 0.201      | 0.333        | 0.003 (0.000)    | -                | -         |     3.31 | Demonos, proSHOW, Roz, suNday, voltera     |
|            8 |     5750 | 2024-10-02 | UNO MILLE                 | L   | 0.201      | -            | -                | -                | -         |    -2.33 | Demonos, proSHOW, Roz, suNday, voltera     |
|            7 |     5831 | 2024-10-01 | Romanos                   | L   | 0.194      | -            | -                | -                | -         |    -4.40 | Demonos, paqueta, Roz, timid, voltera      |
|            6 |     6002 | 2024-09-28 | Myth e-Sports             | L   | 0.174      | -            | -                | -                | -         |    -3.17 | Demonos, paqueta, Roz, timid, voltera      |
|            5 |     6036 | 2024-09-28 | Só os do JOB              | W   | 0.173      | -            | -                | -                | -         |     1.07 | Demonos, paqueta, Roz, timid, voltera      |
|            4 |     6257 | 2024-09-25 | Bounty Hunters Esports    | L   | 0.154      | -            | -                | -                | -         |    -2.49 | Demonos, proSHOW, Roz, suNday, voltera     |
|            3 |     6262 | 2024-09-25 | Dusty Roots               | L   | 0.154      | -            | -                | -                | -         |    -1.55 | Demonos, proSHOW, Roz, suNday, voltera     |
|            2 |     6355 | 2024-09-24 | SamuraiS (Brazilian team) | W   | 0.147      | -            | -                | -                | -         |     1.39 | Demonos, paqueta, Roz, timid, voltera      |
|            1 |     6734 | 2024-09-18 | RED Canids Academy        | L   | 0.108      | -            | -                | -                | -         |    -1.55 | Demonos, proSHOW, Roz, suNday, voltera     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($433.72)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-13 |      0.681 | $333.50        | $227.05         |
| 2024-11-03 |      0.413 | $500.00        | $206.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
