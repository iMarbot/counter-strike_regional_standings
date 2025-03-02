### Roster Details<br />
Team Name: Fnatic<br />
Roster: blameF, Burmylov, fear, KRIMZ, matys<br />
Global Rank: [30](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1055.1<br />
<br />
Final Rank Value (1055.1) = Starting Rank Value (1067.9) + Head To Head Adjustments (-12.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.466[<sup>1</sup>](#table2)
- Bounty Collected: 0.367[<sup>2</sup>](#table1)
- Opponent Network: 0.250[<sup>2</sup>](#table1)
- LAN Wins: 0.254[<sup>2</sup>](#table1)

The average of these factors is 0.334<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1067.9
- 400 + ( ( 0.334 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1067.9


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
|           33 |      248 | 2025-02-20 | Dynamo Eclot           | L   | 1.000      | -            | -                | -                | -         |   -17.17 | blameF, Burmylov, fear, KRIMZ, matys |
|           32 |      307 | 2025-02-17 | RUSH B (Russian team)  | W   | 1.000      | 0.435        | 0.028 (0.012)    | 0.921 (0.400)    | 0 (0.000) |    10.43 | blameF, Burmylov, fear, KRIMZ, matys |
|           31 |      405 | 2025-02-15 | Monte                  | L   | 1.000      | -            | -                | -                | -         |   -21.35 | blameF, Burmylov, fear, KRIMZ, matys |
|           30 |      515 | 2025-02-13 | 500                    | W   | 1.000      | 0.435        | 0.091 (0.040)    | 1.000 (0.435)    | 0 (0.000) |    16.68 | blameF, Burmylov, fear, KRIMZ, matys |
|           29 |      537 | 2025-02-12 | Partizan Esports       | L   | 1.000      | -            | -                | -                | -         |   -18.70 | blameF, Burmylov, fear, KRIMZ, matys |
|           28 |      600 | 2025-02-10 | ECSTATIC               | W   | 1.000      | 0.435        | 0.033 (0.014)    | 0.828 (0.360)    | 0 (0.000) |     7.36 | blameF, Burmylov, fear, KRIMZ, matys |
|           27 |      695 | 2025-02-08 | Team Novaq             | L   | 1.000      | -            | -                | -                | -         |   -13.99 | blameF, Burmylov, fear, KRIMZ, matys |
|           26 |      776 | 2025-02-07 | Permitta Esports       | W   | 1.000      | 0.143        | -                | 0.494 (0.071)    | 0 (0.000) |     6.35 | blameF, Burmylov, fear, KRIMZ, matys |
|           25 |      830 | 2025-02-06 | Team Spirit Academy    | W   | 1.000      | 0.435        | 0.068 (0.030)    | 0.714 (0.310)    | -         |    12.96 | blameF, Burmylov, fear, KRIMZ, matys |
|           24 |      985 | 2025-02-04 | Betclic Apogee Esports | W   | 1.000      | 0.435        | -                | 0.515 (0.224)    | -         |     9.53 | blameF, Burmylov, fear, KRIMZ, matys |
|           23 |     1067 | 2025-02-01 | OG                     | W   | 1.000      | 0.435        | 0.062 (0.027)    | 1.000 (0.435)    | -         |     9.54 | blameF, Burmylov, fear, KRIMZ, matys |
|           22 |     1185 | 2025-01-14 | Team Spirit            | L   | 0.894      | -            | -                | -                | -         |    -0.17 | blameF, Burmylov, fear, KRIMZ, matys |
|           21 |     2449 | 2024-11-30 | Rare Atom              | L   | 0.597      | -            | -                | -                | -         |   -11.64 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           20 |     2550 | 2024-11-30 | Cloud9                 | L   | 0.591      | -            | -                | -                | -         |   -13.01 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           19 |     2557 | 2024-11-29 | Wildcard               | L   | 0.590      | -            | -                | -                | -         |    -3.67 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           18 |     3135 | 2024-11-19 | Dynamo Eclot           | W   | 0.523      | 0.143        | 0.127 (0.010)    | 0.703 (0.053)    | 1 (0.523) |     7.78 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           17 |     3169 | 2024-11-19 | FaZe Clan              | L   | 0.517      | -            | -                | -                | -         |    -0.17 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           16 |     3216 | 2024-11-17 | BetBoom Team           | W   | 0.510      | 0.143        | 0.103 (0.008)    | -                | 1 (0.510) |     7.29 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           15 |     3264 | 2024-11-17 | Rebels Gaming          | W   | 0.505      | -            | -                | -                | 1 (0.505) |     2.21 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           14 |     3298 | 2024-11-16 | Natus Vincere          | L   | 0.503      | -            | -                | -                | -         |    -0.40 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           13 |     4527 | 2024-10-26 | Team Falcons           | L   | 0.358      | -            | -                | -                | -         |    -0.10 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           12 |     4609 | 2024-10-25 | Cloud9                 | W   | 0.351      | 0.934        | 0.022 (0.007)    | 0.117 (0.038)    | -         |     3.06 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           11 |     4694 | 2024-10-22 | The MongolZ            | L   | 0.333      | -            | -                | -                | -         |    -0.08 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           10 |     4711 | 2024-10-22 | 9z Team                | W   | 0.332      | -            | -                | -                | -         |     1.85 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            9 |     4861 | 2024-10-19 | Nemiga Gaming          | L   | 0.311      | -            | -                | -                | -         |    -5.43 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            8 |     4930 | 2024-10-17 | PARIVISION             | W   | 0.299      | -            | -                | -                | 1 (0.299) |     1.26 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            7 |     4987 | 2024-10-16 | BC.Game Esports        | W   | 0.293      | 0.624        | 0.077 (0.014)    | 0.945 (0.173)    | 1 (0.293) |     4.26 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            6 |     5294 | 2024-10-10 | Metizport              | L   | 0.251      | -            | -                | -                | -         |    -3.69 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            5 |     6393 | 2024-09-24 | Wild Lotus             | L   | 0.145      | -            | -                | -                | -         |    -3.92 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            4 |     7030 | 2024-09-14 | MOUZ                   | L   | 0.078      | -            | -                | -                | -         |    -0.01 | afro, blameF, bodyy, KRIMZ, matys    |
|            3 |     7130 | 2024-09-12 | BIG                    | L   | 0.066      | -            | -                | -                | -         |    -0.16 | afro, blameF, bodyy, KRIMZ, matys    |
|            2 |     7182 | 2024-09-11 | M80                    | L   | 0.060      | -            | -                | -                | -         |    -1.31 | afro, blameF, bodyy, KRIMZ, matys    |
|            1 |     7256 | 2024-09-10 | Astralis               | W   | 0.051      | 0.889        | 0.609 (0.028)    | -                | 1 (0.051) |     1.59 | afro, blameF, bodyy, KRIMZ, matys    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,080.49)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.691 | $10,000.00     | $6,909.49       |
| 2024-11-03 |      0.413 | $20,000.00     | $8,258.33       |
| 2024-10-19 |      0.313 | $25,000.00     | $7,828.13       |
| 2024-09-26 |      0.159 | $1,000.00      | $158.98         |
| 2024-09-22 |      0.132 | $7,000.00      | $925.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
