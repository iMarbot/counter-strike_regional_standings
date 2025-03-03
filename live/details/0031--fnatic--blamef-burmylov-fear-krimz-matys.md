### Roster Details<br />
Team Name: Fnatic<br />
Roster: blameF, Burmylov, fear, KRIMZ, matys<br />
Global Rank: [31](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1052.7<br />
<br />
Final Rank Value (1052.7) = Starting Rank Value (1064.7) + Head To Head Adjustments (-12.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.466[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.250[<sup>2</sup>](#table1)

The average of these factors is 0.332<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1064.7
- 400 + ( ( 0.332 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1064.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      260 | 2025-02-20 | Dynamo Eclot           | L   | 1.000      | -            | -                | -                | -         |   -17.14 | blameF, Burmylov, fear, KRIMZ, matys |
|           32 |      319 | 2025-02-17 | RUSH B (Russian team)  | W   | 1.000      | 0.435        | 0.028 (0.012)    | 0.915 (0.398)    | 0 (0.000) |    10.47 | blameF, Burmylov, fear, KRIMZ, matys |
|           31 |      417 | 2025-02-15 | Monte                  | L   | 1.000      | -            | -                | -                | -         |   -21.34 | blameF, Burmylov, fear, KRIMZ, matys |
|           30 |      527 | 2025-02-13 | 500                    | W   | 1.000      | 0.435        | 0.093 (0.040)    | 1.000 (0.435)    | 0 (0.000) |    16.75 | blameF, Burmylov, fear, KRIMZ, matys |
|           29 |      549 | 2025-02-12 | Partizan Esports       | L   | 1.000      | -            | -                | -                | -         |   -18.64 | blameF, Burmylov, fear, KRIMZ, matys |
|           28 |      612 | 2025-02-10 | ECSTATIC               | W   | 1.000      | 0.435        | 0.033 (0.014)    | 0.820 (0.356)    | 0 (0.000) |     7.38 | blameF, Burmylov, fear, KRIMZ, matys |
|           27 |      707 | 2025-02-08 | Team Novaq             | L   | 1.000      | -            | -                | -                | -         |   -14.01 | blameF, Burmylov, fear, KRIMZ, matys |
|           26 |      788 | 2025-02-07 | Permitta Esports       | W   | 1.000      | 0.143        | -                | 0.487 (0.070)    | 0 (0.000) |     6.35 | blameF, Burmylov, fear, KRIMZ, matys |
|           25 |      842 | 2025-02-06 | Team Spirit Academy    | W   | 1.000      | 0.435        | 0.068 (0.030)    | 0.702 (0.305)    | -         |    12.93 | blameF, Burmylov, fear, KRIMZ, matys |
|           24 |      997 | 2025-02-04 | Betclic Apogee Esports | W   | 1.000      | 0.435        | -                | 0.513 (0.223)    | -         |     9.57 | blameF, Burmylov, fear, KRIMZ, matys |
|           23 |     1079 | 2025-02-01 | OG                     | W   | 1.000      | 0.435        | 0.062 (0.027)    | 1.000 (0.435)    | -         |     9.59 | blameF, Burmylov, fear, KRIMZ, matys |
|           22 |     1197 | 2025-01-14 | Team Spirit            | L   | 0.885      | -            | -                | -                | -         |    -0.16 | blameF, Burmylov, fear, KRIMZ, matys |
|           21 |     2461 | 2024-11-30 | Rare Atom              | L   | 0.588      | -            | -                | -                | -         |   -11.44 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           20 |     2562 | 2024-11-30 | Cloud9                 | L   | 0.583      | -            | -                | -                | -         |   -12.83 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           19 |     2569 | 2024-11-29 | Wildcard               | L   | 0.582      | -            | -                | -                | -         |    -3.51 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           18 |     3147 | 2024-11-19 | Dynamo Eclot           | W   | 0.515      | 0.143        | 0.128 (0.009)    | 0.692 (0.051)    | 1 (0.515) |     7.68 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           17 |     3181 | 2024-11-19 | FaZe Clan              | L   | 0.509      | -            | -                | -                | -         |    -0.16 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           16 |     3228 | 2024-11-17 | BetBoom Team           | W   | 0.502      | 0.143        | 0.104 (0.007)    | -                | 1 (0.502) |     7.20 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           15 |     3276 | 2024-11-17 | Rebels Gaming          | W   | 0.496      | -            | -                | -                | 1 (0.496) |     2.19 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           14 |     3310 | 2024-11-16 | Natus Vincere          | L   | 0.495      | -            | -                | -                | -         |    -0.40 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           13 |     4539 | 2024-10-26 | Team Falcons           | L   | 0.350      | -            | -                | -                | -         |    -0.10 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           12 |     4621 | 2024-10-25 | Cloud9                 | W   | 0.343      | 0.934        | 0.022 (0.007)    | 0.115 (0.037)    | -         |     3.00 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           11 |     4706 | 2024-10-22 | The MongolZ            | L   | 0.325      | -            | -                | -                | -         |    -0.08 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           10 |     4723 | 2024-10-22 | 9z Team                | W   | 0.323      | -            | -                | -                | -         |     1.79 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            9 |     4873 | 2024-10-19 | Nemiga Gaming          | L   | 0.303      | -            | -                | -                | -         |    -5.29 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            8 |     4942 | 2024-10-17 | PARIVISION             | W   | 0.291      | -            | -                | -                | 1 (0.291) |     1.23 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            7 |     4999 | 2024-10-16 | BC.Game Esports        | W   | 0.285      | 0.624        | 0.078 (0.014)    | 0.945 (0.168)    | 1 (0.285) |     4.17 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            6 |     5306 | 2024-10-10 | Metizport              | L   | 0.243      | -            | -                | -                | -         |    -3.57 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            5 |     6405 | 2024-09-24 | Wild Lotus             | L   | 0.137      | -            | -                | -                | -         |    -3.70 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            4 |     7042 | 2024-09-14 | MOUZ                   | L   | 0.070      | -            | -                | -                | -         |    -0.01 | afro, blameF, bodyy, KRIMZ, matys    |
|            3 |     7142 | 2024-09-12 | BIG                    | L   | 0.058      | -            | -                | -                | -         |    -0.14 | afro, blameF, bodyy, KRIMZ, matys    |
|            2 |     7194 | 2024-09-11 | M80                    | L   | 0.051      | -            | -                | -                | -         |    -1.13 | afro, blameF, bodyy, KRIMZ, matys    |
|            1 |     7268 | 2024-09-10 | Astralis               | W   | 0.043      | 0.889        | 0.619 (0.024)    | -                | 1 (0.043) |     1.34 | afro, blameF, bodyy, KRIMZ, matys    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,564.24)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.683 | $10,000.00     | $6,827.55       |
| 2024-11-03 |      0.405 | $20,000.00     | $8,094.44       |
| 2024-10-19 |      0.305 | $25,000.00     | $7,623.26       |
| 2024-09-26 |      0.151 | $1,000.00      | $150.79         |
| 2024-09-22 |      0.124 | $7,000.00      | $868.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
