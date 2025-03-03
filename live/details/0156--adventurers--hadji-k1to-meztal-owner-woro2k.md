### Roster Details<br />
Team Name: Adventurers<br />
Roster: hAdji, k1to, meztal, OWNER, Woro2k<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [115]( ../standings_europe.md)<br />
<br />
Final Rank Value:  754.6<br />
<br />
Final Rank Value (754.6) = Starting Rank Value (779.6) + Head To Head Adjustments (-25.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.053[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 779.6
- 400 + ( ( 0.190 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 779.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      243 | 2025-02-20 | VOLT (European team)  | L   | 1.000      | -            | -                | -                | -         |   -25.17 | hAdji, maxster, OWNER, Svedjehed, Woro2k  |
|           29 |      923 | 2025-02-05 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |   -10.87 | hAdji, k1to, meztal, OWNER, Woro2k        |
|           28 |      963 | 2025-02-04 | KONO.ECF              | L   | 1.000      | -            | -                | -                | -         |   -21.37 | hAdji, k1to, meztal, OWNER, Woro2k        |
|           27 |     1135 | 2025-01-27 | Zero Tenacity         | L   | 0.970      | -            | -                | -                | -         |   -12.69 | adamS, hAdji, juanflatroo, meztal, Woro2k |
|           26 |     3540 | 2024-11-12 | FlyQuest              | L   | 0.468      | -            | -                | -                | -         |    -2.67 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           25 |     3583 | 2024-11-12 | The MongolZ           | L   | 0.462      | -            | -                | -                | -         |    -0.03 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           24 |     3639 | 2024-11-11 | Lynn Vision Gaming    | W   | 0.456      | -            | -                | -                | 1 (0.456) |     7.91 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           23 |     3958 | 2024-11-05 | Monte                 | L   | 0.418      | -            | -                | -                | -         |    -5.04 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           22 |     4015 | 2024-11-04 | Preasy Esport         | W   | 0.411      | 0.333        | 0.012 (0.002)    | 0.701 (0.096)    | 0 (0.000) |     5.89 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           21 |     4065 | 2024-11-03 | GODSENT               | W   | 0.405      | -            | -                | -                | 0 (0.000) |     4.11 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           20 |     4542 | 2024-10-26 | Leo Team              | W   | 0.350      | 0.333        | 0.026 (0.003)    | 0.748 (0.087)    | 0 (0.000) |     5.90 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           19 |     4619 | 2024-10-25 | Natus Vincere Junior  | L   | 0.343      | -            | -                | -                | -         |    -3.05 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           18 |     4759 | 2024-10-21 | Leo Team              | W   | 0.317      | 0.333        | 0.026 (0.003)    | 0.748 (0.079)    | 0 (0.000) |     5.35 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           17 |     4907 | 2024-10-18 | Monte                 | W   | 0.297      | 0.333        | 0.045 (0.004)    | 0.696 (0.069)    | 0 (0.000) |     6.12 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           16 |     4959 | 2024-10-17 | TEAM NEXT LEVEL       | W   | 0.290      | 0.333        | 0.040 (0.004)    | 0.500 (0.048)    | 0 (0.000) |     5.25 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           15 |     4967 | 2024-10-17 | Ex-9INE Academy       | W   | 0.289      | -            | -                | -                | 0 (0.000) |     2.22 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           14 |     5436 | 2024-10-08 | Monte                 | W   | 0.231      | 0.354        | 0.045 (0.004)    | 0.696 (0.057)    | 0 (0.000) |     4.83 | hAdji, Kvem, meztal, nifee, Woro2k        |
|           13 |     5486 | 2024-10-07 | FAVBET Team           | W   | 0.225      | 0.354        | 0.031 (0.003)    | 0.801 (0.064)    | 0 (0.000) |     4.04 | hAdji, Kvem, meztal, nifee, Woro2k        |
|           12 |     5520 | 2024-10-06 | GamerLegion Academy   | W   | 0.218      | -            | -                | -                | -         |     1.41 | hAdji, Kvem, meztal, nifee, Woro2k        |
|           11 |     5533 | 2024-10-06 | GODSENT               | W   | 0.217      | -            | -                | -                | -         |     2.40 | hAdji, Kvem, meztal, nifee, Woro2k        |
|           10 |     5546 | 2024-10-06 | FAVBET Team           | L   | 0.217      | -            | -                | -                | -         |    -2.97 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            9 |     5623 | 2024-10-05 | Monte                 | L   | 0.210      | -            | -                | -                | -         |    -2.68 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            8 |     5669 | 2024-10-04 | GamerLegion           | L   | 0.205      | -            | -                | -                | -         |    -0.07 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            7 |     5815 | 2024-10-02 | Los kogutos           | W   | 0.189      | 0.435        | 0.032 (0.003)    | 0.515 (0.042)    | -         |     4.53 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            6 |     5926 | 2024-09-30 | ALTERNATE aTTaX       | W   | 0.178      | 0.435        | -                | 0.552 (0.043)    | -         |     3.88 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            5 |     5940 | 2024-09-30 | TSM                   | L   | 0.176      | -            | -                | -                | -         |    -2.99 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            4 |     6053 | 2024-09-28 | Team Spirit Academy   | L   | 0.164      | -            | -                | -                | -         |    -1.61 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            3 |     6229 | 2024-09-26 | FAVBET Team           | W   | 0.150      | 0.435        | 0.031 (0.002)    | 0.801 (0.052)    | -         |     2.74 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            2 |     6286 | 2024-09-25 | RUSTEC                | L   | 0.145      | -            | -                | -                | -         |    -3.83 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            1 |     6400 | 2024-09-24 | Passion UA            | W   | 0.137      | 0.435        | 0.044 (0.003)    | -                | -         |     3.48 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,405.83)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-05 |      0.418 | $3,000.00      | $1,253.75       |
| 2024-10-26 |      0.350 | $3,000.00      | $1,050.42       |
| 2024-10-18 |      0.297 | $5,000.00      | $1,486.81       |
| 2024-10-08 |      0.231 | $7,000.00      | $1,614.86       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
