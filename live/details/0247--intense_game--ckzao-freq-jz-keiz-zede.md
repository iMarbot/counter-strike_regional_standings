### Roster Details<br />
Team Name: Intense Game<br />
Roster: ckzao, fREQ, jz, keiz, zede<br />
Global Rank: [247](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  679.5<br />
<br />
Final Rank Value (679.5) = Starting Rank Value (665.5) + Head To Head Adjustments (14.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 665.5
- 400 + ( ( 0.133 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 665.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     3643 | 2024-11-10 | TROPA DO TACO          | L   | 0.460      | -            | -                | -                | -         |    -6.24 | ckzao, fREQ, jz, keiz, zede  |
|           24 |     3819 | 2024-11-07 | TROPA DO TACO          | L   | 0.441      | -            | -                | -                | -         |    -6.15 | ckzao, fREQ, jz, keiz, zede  |
|           23 |     3874 | 2024-11-06 | MIBR Academy           | W   | 0.434      | 0.143        | 0.001 (0.000)    | 0.470 (0.029)    | 0 (0.000) |     6.96 | ckzao, fREQ, jz, keiz, zede  |
|           22 |     3910 | 2024-11-05 | Sharks Esports         | L   | 0.428      | -            | -                | -                | -         |    -1.90 | ckzao, fREQ, jz, keiz, zede  |
|           21 |     3969 | 2024-11-04 | UNO MILLE              | L   | 0.421      | -            | -                | -                | -         |    -5.58 | ckzao, fREQ, jz, keiz, zede  |
|           20 |     3993 | 2024-11-04 | Floripa Stars          | W   | 0.420      | 0.143        | 0.001 (0.000)    | 0.302 (0.018)    | 0 (0.000) |     6.51 | ckzao, fREQ, jz, keiz, zede  |
|           19 |     4026 | 2024-11-03 | Galorys Academy        | W   | 0.415      | 0.143        | 0.001 (0.000)    | 0.158 (0.009)    | 0 (0.000) |     5.67 | ckzao, fREQ, jz, keiz, zede  |
|           18 |     4098 | 2024-11-02 | RED Canids Academy     | L   | 0.408      | -            | -                | -                | -         |    -6.01 | ckzao, fREQ, jz, keiz, zede  |
|           17 |     4103 | 2024-11-02 | ODDIK                  | L   | 0.407      | -            | -                | -                | -         |    -3.96 | ckzao, fREQ, jz, keiz, zede  |
|           16 |     4168 | 2024-11-01 | Team Solid             | L   | 0.401      | -            | -                | -                | -         |    -3.94 | ckzao, fREQ, jz, keiz, zede  |
|           15 |     4171 | 2024-11-01 | Bounty Hunters Esports | W   | 0.401      | 0.143        | 0.005 (0.000)    | 0.524 (0.030)    | 0 (0.000) |     6.69 | ckzao, fREQ, jz, keiz, zede  |
|           14 |     4194 | 2024-11-01 | 20/70                  | W   | 0.400      | 0.333        | 0.001 (0.000)    | 0.290 (0.039)    | 0 (0.000) |     5.58 | ckzao, fREQ, jz, keiz, zede  |
|           13 |     4277 | 2024-10-30 | RED Canids Academy     | W   | 0.388      | 0.333        | 0.005 (0.001)    | 0.240 (0.031)    | 0 (0.000) |     6.60 | ckzao, fREQ, jz, keiz, zede  |
|           12 |     4296 | 2024-10-30 | Fluxo                  | L   | 0.387      | -            | -                | -                | -         |    -2.33 | ckzao, fREQ, jz, keiz, zede  |
|           11 |     4349 | 2024-10-29 | América eSports        | W   | 0.381      | 0.143        | -                | 0.429 (0.023)    | 0 (0.000) |     4.99 | ckzao, fREQ, jz, keiz, zede  |
|           10 |     4391 | 2024-10-28 | AdalYamigos            | W   | 0.375      | 0.143        | 0.004 (0.000)    | 0.194 (0.010)    | 0 (0.000) |     7.53 | ckzao, fREQ, jz, keiz, zede  |
|            9 |     4413 | 2024-10-28 | Myth e-Sports          | L   | 0.374      | -            | -                | -                | -         |    -7.11 | ckzao, fREQ, jz, keiz, zede  |
|            8 |     4640 | 2024-10-23 | UNO MILLE              | W   | 0.341      | 0.333        | 0.010 (0.001)    | 0.526 (0.060)    | 0 (0.000) |     6.23 | ckzao, fREQ, jz, keiz, zede  |
|            7 |     4643 | 2024-10-23 | Bounty Hunters Esports | W   | 0.341      | 0.333        | 0.001 (0.000)    | -                | 0 (0.000) |     5.33 | ckzao, fREQ, jz, keiz, zede  |
|            6 |     4967 | 2024-10-16 | Dusty Roots            | W   | 0.295      | 0.333        | 0.008 (0.001)    | 0.371 (0.036)    | -         |     6.10 | ckzao, fREQ, keiz, mxa, zede |
|            5 |     5742 | 2024-10-02 | 20/70                  | L   | 0.201      | -            | -                | -                | -         |    -3.31 | ckzao, fREQ, keiz, mxa, zede |
|            4 |     5830 | 2024-10-01 | UNO MILLE              | L   | 0.194      | -            | -                | -                | -         |    -2.41 | ckzao, fREQ, keiz, mxa, zede |
|            3 |     6248 | 2024-09-25 | RED Canids Academy     | L   | 0.155      | -            | -                | -                | -         |    -2.25 | ckzao, fREQ, keiz, mxa, zede |
|            2 |     6677 | 2024-09-19 | Bounty Hunters Esports | L   | 0.114      | -            | -                | -                | -         |    -1.91 | ckzao, fREQ, keiz, mxa, zede |
|            1 |     6737 | 2024-09-18 | Dusty Roots            | L   | 0.107      | -            | -                | -                | -         |    -1.13 | ckzao, fREQ, keiz, mxa, zede |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($857.54)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-05 |      0.429 | $1,035.89      | $444.21         |
| 2024-11-03 |      0.413 | $1,000.00      | $413.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
