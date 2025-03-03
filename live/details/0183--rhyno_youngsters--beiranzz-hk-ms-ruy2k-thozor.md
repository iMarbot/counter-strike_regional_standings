### Roster Details<br />
Team Name: Rhyno Youngsters<br />
Roster: BeiranZz, hk, ms, Ruy2k, ThozoR<br />
Global Rank: [183](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [131]( ../standings_europe.md)<br />
<br />
Final Rank Value:  723.9<br />
<br />
Final Rank Value (723.9) = Starting Rank Value (753.3) + Head To Head Adjustments (-29.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.218[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.3
- 400 + ( ( 0.177 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 753.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     1307 | 2024-12-28 | The Agency Clan         | L   | 0.771      | -            | -                | -                | -         |    -7.82 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           18 |     1312 | 2024-12-28 | GOOFYBOYZ               | W   | 0.771      | 0.143        | 0.003 (0.000)    | 0.179 (0.020)    | 0 (0.000) |    13.14 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           17 |     1401 | 2024-12-22 | The Agency Clan         | L   | 0.732      | -            | -                | -                | -         |    -7.40 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           16 |     1415 | 2024-12-22 | GOOFYBOYZ               | W   | 0.731      | 0.143        | 0.003 (0.000)    | 0.179 (0.019)    | 1 (0.731) |    13.07 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           15 |     1476 | 2024-12-21 | After 8                 | W   | 0.724      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.724) |     5.37 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           14 |     2493 | 2024-11-30 | SkyFury                 | L   | 0.586      | -            | -                | -                | -         |   -10.06 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|           13 |     2653 | 2024-11-28 | Metizport X             | L   | 0.571      | -            | -                | -                | -         |   -10.78 | hk, ms, opdust, Ruy2k, ThozoR       |
|           12 |     2721 | 2024-11-26 | ENTERPRISE Genesis      | L   | 0.559      | -            | -                | -                | -         |   -10.88 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|           11 |     3727 | 2024-11-09 | Rhyno Esports           | L   | 0.445      | -            | -                | -                | -         |    -4.79 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|           10 |     4061 | 2024-11-03 | GOOFYBOYZ               | L   | 0.405      | -            | -                | -                | -         |    -6.16 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            9 |     4078 | 2024-11-03 | SSKT                    | W   | 0.404      | 0.143        | 0.000 (0.000)    | 0.034 (0.002)    | 1 (0.404) |     4.22 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            8 |     4681 | 2024-10-23 | GOOFYBOYZ               | L   | 0.331      | -            | -                | -                | -         |    -5.31 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            7 |     4713 | 2024-10-22 | RogerBall               | L   | 0.325      | -            | -                | -                | -         |    -8.34 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            6 |     5212 | 2024-10-12 | Mixzada                 | W   | 0.257      | 0.143        | 0.000 (0.000)    | 0.031 (0.001)    | 0 (0.000) |     2.42 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            5 |     5232 | 2024-10-12 | Impulse GW              | W   | 0.257      | 0.143        | 0.006 (0.000)    | 0.169 (0.006)    | 0 (0.000) |     3.77 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            4 |     5605 | 2024-10-05 | Rhyno Esports           | L   | 0.211      | -            | -                | -                | -         |    -2.47 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            3 |     6848 | 2024-09-17 | Rhyno Esports           | W   | 0.091      | 0.143        | 0.002 (0.000)    | 0.080 (0.001)    | 0 (0.000) |     1.10 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            2 |     6893 | 2024-09-16 | GOOFYBOYZ               | W   | 0.085      | 0.143        | 0.003 (0.000)    | 0.179 (0.002)    | 0 (0.000) |     1.36 | BeiranZz, drext, ms, opdust, Ruy2k  |
|            1 |     7429 | 2024-09-07 | SQUAD (Portuguese team) | W   | 0.024      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.14 | BeiranZz, ms, opdust, Ruy2k, ThozoR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,012.23)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.771 | $312.86        | $241.25         |
| 2024-12-22 |      0.732 | $417.21        | $305.58         |
| 2024-11-22 |      0.531 | $261.78        | $138.96         |
| 2024-11-03 |      0.406 | $217.62        | $88.35          |
| 2024-10-06 |      0.217 | $1,098.17      | $238.09         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
