### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, draken, hampus, Ro1f, spooke<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  930.6<br />
<br />
Final Rank Value (930.6) = Starting Rank Value (893.0) + Head To Head Adjustments (37.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.186[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.0
- 400 + ( ( 0.246 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 893.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |     2882 | 2024-11-23 | Alliance             | W   | 0.538      | -            | -                | -                | 1 (0.538) |     7.43 | bobeksde, draken, hampus, Ro1f, spooke |
|           45 |     2899 | 2024-11-23 | Monte                | L   | 0.537      | -            | -                | -                | -         |    -9.50 | bobeksde, draken, hampus, Ro1f, spooke |
|           44 |     3023 | 2024-11-21 | Kappa Bar            | W   | 0.525      | -            | -                | -                | 1 (0.525) |     3.96 | bobeksde, draken, hampus, Ro1f, spooke |
|           43 |     3052 | 2024-11-21 | Alliance             | W   | 0.524      | -            | -                | -                | 1 (0.524) |     7.26 | bobeksde, draken, hampus, Ro1f, spooke |
|           42 |     3659 | 2024-11-10 | OG                   | W   | 0.452      | 0.143        | 0.062 (0.004)    | 1.000 (0.065)    | 0 (0.000) |     7.17 | bobeksde, draken, hampus, Ro1f, spooke |
|           41 |     3791 | 2024-11-08 | Metizport            | L   | 0.439      | -            | -                | -                | -         |    -3.97 | bobeksde, draken, hampus, Ro1f, spooke |
|           40 |     3817 | 2024-11-08 | Zero Tenacity        | L   | 0.437      | -            | -                | -                | -         |    -8.06 | bobeksde, draken, hampus, Ro1f, spooke |
|           39 |     3915 | 2024-11-06 | Dynamo Eclot         | L   | 0.423      | -            | -                | -                | -         |    -4.26 | bobeksde, draken, hampus, Ro1f, spooke |
|           38 |     3954 | 2024-11-05 | Showmakerz           | W   | 0.418      | -            | -                | -                | 0 (0.000) |     1.85 | bobeksde, draken, hampus, Ro1f, spooke |
|           37 |     4017 | 2024-11-04 | HOTU                 | W   | 0.411      | 0.384        | -                | 0.768 (0.121)    | 0 (0.000) |     2.81 | bobeksde, draken, hampus, Ro1f, spooke |
|           36 |     4056 | 2024-11-03 | Insilio              | W   | 0.405      | -            | -                | -                | 0 (0.000) |     2.12 | bobeksde, draken, hampus, Ro1f, spooke |
|           35 |     4212 | 2024-11-01 | OG                   | W   | 0.391      | 0.384        | 0.062 (0.009)    | 1.000 (0.150)    | 0 (0.000) |     6.24 | bobeksde, draken, hampus, Ro1f, spooke |
|           34 |     4249 | 2024-10-31 | ECSTATIC             | L   | 0.386      | -            | -                | -                | -         |    -6.52 | bobeksde, draken, hampus, Ro1f, spooke |
|           33 |     4260 | 2024-10-31 | Metizport            | W   | 0.385      | 0.333        | 0.074 (0.010)    | 0.507 (0.065)    | 0 (0.000) |     8.71 | bobeksde, draken, hampus, Ro1f, spooke |
|           32 |     4337 | 2024-10-30 | 9Pandas              | L   | 0.377      | -            | -                | -                | -         |    -4.78 | bobeksde, draken, hampus, Ro1f, spooke |
|           31 |     4363 | 2024-10-29 | Endpoint             | W   | 0.372      | 0.333        | -                | 0.377 (0.047)    | 0 (0.000) |     4.01 | bobeksde, draken, hampus, Ro1f, spooke |
|           30 |     4374 | 2024-10-29 | Tricked Esport       | L   | 0.372      | -            | -                | -                | -         |    -6.86 | bobeksde, draken, hampus, Ro1f, spooke |
|           29 |     4386 | 2024-10-29 | Rare Atom            | W   | 0.371      | 0.333        | 0.063 (0.008)    | 0.578 (0.071)    | -         |     6.99 | bobeksde, draken, hampus, Ro1f, spooke |
|           28 |     4540 | 2024-10-26 | Nexus Gaming         | W   | 0.350      | 0.143        | 0.187 (0.009)    | -                | -         |     8.42 | bobeksde, draken, hampus, Ro1f, spooke |
|           27 |     4762 | 2024-10-21 | UNiTY esports        | W   | 0.317      | 0.384        | 0.025 (0.003)    | 0.403 (0.049)    | -         |     4.26 | bobeksde, draken, hampus, Ro1f, spooke |
|           26 |     4802 | 2024-10-20 | Wild Lotus           | L   | 0.311      | -            | -                | -                | -         |    -6.89 | bobeksde, draken, hampus, Ro1f, spooke |
|           25 |     5030 | 2024-10-16 | WW Team              | W   | 0.283      | -            | -                | -                | -         |     0.85 | bobeksde, draken, hampus, Ro1f, spooke |
|           24 |     5505 | 2024-10-07 | Preasy Esport        | W   | 0.223      | 0.384        | -                | 0.701 (0.060)    | -         |     2.48 | bobeksde, draken, hampus, Ro1f, spooke |
|           23 |     5530 | 2024-10-06 | EYEBALLERS           | W   | 0.218      | -            | -                | -                | -         |     2.51 | bobeksde, draken, hampus, Ro1f, spooke |
|           22 |     5542 | 2024-10-06 | Fightclub            | W   | 0.217      | -            | -                | -                | -         |     0.58 | bobeksde, draken, hampus, Ro1f, spooke |
|           21 |     5558 | 2024-10-06 | GTZ.ESPORTS          | W   | 0.215      | 0.143        | 0.080 (0.002)    | -                | -         |     5.86 | bobeksde, draken, hampus, Ro1f, spooke |
|           20 |     5615 | 2024-10-05 | Metizport X          | W   | 0.210      | -            | -                | -                | -         |     1.39 | bobeksde, draken, hampus, Ro1f, spooke |
|           19 |     5620 | 2024-10-05 | ENCE Academy         | W   | 0.210      | -            | -                | -                | -         |     2.60 | bobeksde, draken, hampus, Ro1f, spooke |
|           18 |     5683 | 2024-10-04 | Natus Vincere Junior | W   | 0.204      | 0.333        | 0.091 (0.006)    | 0.865 (0.059)    | -         |     3.87 | bobeksde, draken, hampus, Ro1f, spooke |
|           17 |     5730 | 2024-10-03 | Partizan Esports     | W   | 0.198      | 0.333        | 0.083 (0.005)    | 0.757 (0.050)    | -         |     4.68 | bobeksde, draken, hampus, Ro1f, spooke |
|           16 |     5890 | 2024-10-01 | Los kogutos          | L   | 0.182      | -            | -                | -                | -         |    -2.09 | bobeksde, draken, hampus, Ro1f, spooke |
|           15 |     5925 | 2024-09-30 | MOUZ NXT             | W   | 0.178      | -            | -                | -                | -         |     0.78 | bobeksde, draken, hampus, Ro1f, spooke |
|           14 |     5943 | 2024-09-30 | Tricked Esport       | L   | 0.176      | -            | -                | -                | -         |    -3.23 | bobeksde, draken, hampus, Ro1f, spooke |
|           13 |     6050 | 2024-09-28 | ARCRED               | W   | 0.164      | -            | -                | -                | -         |     1.68 | bobeksde, draken, hampus, Ro1f, spooke |
|           12 |     6084 | 2024-09-28 | Wild Lotus           | L   | 0.163      | -            | -                | -                | -         |    -3.52 | bobeksde, draken, hampus, Ro1f, spooke |
|           11 |     6282 | 2024-09-25 | Lazer Cats           | L   | 0.145      | -            | -                | -                | -         |    -3.31 | bobeksde, draken, hampus, Ro1f, spooke |
|           10 |     6473 | 2024-09-23 | Nemiga Gaming        | L   | 0.132      | -            | -                | -                | -         |    -1.42 | bobeksde, draken, hampus, Ro1f, spooke |
|            9 |     6489 | 2024-09-23 | 9INE                 | L   | 0.131      | -            | -                | -                | -         |    -2.81 | bobeksde, draken, hampus, Ro1f, spooke |
|            8 |     6496 | 2024-09-23 | GameAgents           | W   | 0.130      | -            | -                | -                | -         |     0.96 | bobeksde, draken, hampus, Ro1f, spooke |
|            7 |     6655 | 2024-09-20 | Devils.one           | W   | 0.110      | -            | -                | -                | -         |     0.71 | bobeksde, draken, hampus, Ro1f, spooke |
|            6 |     6694 | 2024-09-19 | CYBERSHOKE Esports   | W   | 0.105      | -            | -                | -                | -         |     1.50 | bobeksde, draken, hampus, Ro1f, spooke |
|            5 |     6721 | 2024-09-19 | Alliance             | W   | 0.103      | -            | -                | -                | -         |     1.63 | bobeksde, draken, hampus, Ro1f, spooke |
|            4 |     6953 | 2024-09-15 | 9Pandas              | W   | 0.077      | 0.443        | 0.085 (0.003)    | -                | -         |     1.50 | bobeksde, draken, hampus, Ro1f, spooke |
|            3 |     6964 | 2024-09-15 | K27                  | W   | 0.076      | -            | -                | -                | -         |     1.34 | bobeksde, draken, hampus, Ro1f, spooke |
|            2 |     7115 | 2024-09-13 | Rebels Gaming        | L   | 0.063      | -            | -                | -                | -         |    -1.41 | bobeksde, draken, hampus, Ro1f, spooke |
|            1 |     7675 | 2024-09-04 | Kappa Bar            | W   | 0.005      | -            | -                | -                | -         |     0.04 | bobeksde, draken, hampus, Ro1f, spooke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,955.58)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.544 | $1,864.89      | $1,014.55       |
| 2024-11-23 |      0.538 | $10,873.30     | $5,851.20       |
| 2024-11-09 |      0.445 | $4,623.93      | $2,055.72       |
| 2024-10-31 |      0.386 | $2,000.00      | $771.11         |
| 2024-10-06 |      0.218 | $4,821.41      | $1,050.22       |
| 2024-10-05 |      0.210 | $5,000.00      | $1,049.31       |
| 2024-09-24 |      0.137 | $8,000.00      | $1,092.22       |
| 2024-09-14 |      0.071 | $1,000.00      | $71.25          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
