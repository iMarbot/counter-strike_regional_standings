### Roster Details<br />
Team Name: Rhyno Youngsters<br />
Roster: BeiranZz, hk, ms, Ruy2k, ThozoR<br />
Global Rank: [182](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [132]( ../standings_europe.md)<br />
<br />
Final Rank Value:  724.3<br />
<br />
Final Rank Value (724.3) = Starting Rank Value (754.0) + Head To Head Adjustments (-29.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.220[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 754.0
- 400 + ( ( 0.177 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 754.0


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
|           19 |     1295 | 2024-12-28 | The Agency Clan         | L   | 0.779      | -            | -                | -                | -         |    -7.88 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           18 |     1300 | 2024-12-28 | GOOFYBOYZ               | W   | 0.779      | 0.143        | 0.003 (0.000)    | 0.183 (0.020)    | 0 (0.000) |    13.29 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           17 |     1389 | 2024-12-22 | The Agency Clan         | L   | 0.740      | -            | -                | -                | -         |    -7.46 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           16 |     1403 | 2024-12-22 | GOOFYBOYZ               | W   | 0.739      | 0.143        | 0.003 (0.000)    | 0.183 (0.019)    | 1 (0.739) |    13.23 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           15 |     1464 | 2024-12-21 | After 8                 | W   | 0.732      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.732) |     5.42 | BeiranZz, hk, ms, Ruy2k, ThozoR     |
|           14 |     2481 | 2024-11-30 | SkyFury                 | L   | 0.594      | -            | -                | -                | -         |   -10.20 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|           13 |     2641 | 2024-11-28 | Metizport X             | L   | 0.579      | -            | -                | -                | -         |   -10.94 | hk, ms, opdust, Ruy2k, ThozoR       |
|           12 |     2709 | 2024-11-26 | ENTERPRISE Genesis      | L   | 0.567      | -            | -                | -                | -         |   -11.04 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|           11 |     3715 | 2024-11-09 | Rhyno Esports           | L   | 0.453      | -            | -                | -                | -         |    -4.85 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|           10 |     4049 | 2024-11-03 | GOOFYBOYZ               | L   | 0.413      | -            | -                | -                | -         |    -6.29 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            9 |     4066 | 2024-11-03 | SSKT                    | W   | 0.412      | 0.143        | 0.000 (0.000)    | 0.034 (0.002)    | 1 (0.412) |     4.29 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            8 |     4669 | 2024-10-23 | GOOFYBOYZ               | L   | 0.339      | -            | -                | -                | -         |    -5.45 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            7 |     4701 | 2024-10-22 | RogerBall               | L   | 0.333      | -            | -                | -                | -         |    -8.55 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            6 |     5200 | 2024-10-12 | Mixzada                 | W   | 0.266      | 0.143        | 0.000 (0.000)    | 0.032 (0.001)    | 0 (0.000) |     2.48 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            5 |     5221 | 2024-10-12 | Impulse GW              | W   | 0.265      | 0.143        | 0.006 (0.000)    | 0.172 (0.007)    | 0 (0.000) |     3.88 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            4 |     5593 | 2024-10-05 | Rhyno Esports           | L   | 0.219      | -            | -                | -                | -         |    -2.56 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            3 |     6836 | 2024-09-17 | Rhyno Esports           | W   | 0.099      | 0.143        | 0.002 (0.000)    | 0.084 (0.001)    | 0 (0.000) |     1.20 | BeiranZz, ms, opdust, Ruy2k, ThozoR |
|            2 |     6881 | 2024-09-16 | GOOFYBOYZ               | W   | 0.093      | 0.143        | 0.003 (0.000)    | 0.183 (0.002)    | 0 (0.000) |     1.49 | BeiranZz, drext, ms, opdust, Ruy2k  |
|            1 |     7417 | 2024-09-07 | SQUAD (Portuguese team) | W   | 0.033      | 0.143        | 0.000 (0.000)    | 0.011 (0.000)    | 0 (0.000) |     0.18 | BeiranZz, ms, opdust, Ruy2k, ThozoR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,031.14)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.779 | $312.86        | $243.82         |
| 2024-12-22 |      0.741 | $417.21        | $309.00         |
| 2024-11-22 |      0.539 | $261.78        | $141.10         |
| 2024-11-03 |      0.414 | $217.62        | $90.13          |
| 2024-10-06 |      0.225 | $1,098.17      | $247.09         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
