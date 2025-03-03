### Roster Details<br />
Team Name: ROYALS<br />
Roster: Lake, oskvr, shateri, Swaggy, waZz<br />
Global Rank: [281](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [190]( ../standings_europe.md)<br />
<br />
Final Rank Value:  661.9<br />
<br />
Final Rank Value (661.9) = Starting Rank Value (682.0) + Head To Head Adjustments (-20.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 682.0
- 400 + ( ( 0.141 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 682.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |     1384 | 2024-12-23 | NEVERMORE (Ukrainian team) | L   | 0.738      | -            | -                | -                | -         |    -8.17 | Lake, oskvr, shateri, Swaggy, waZz  |
|           32 |     1429 | 2024-12-22 | SkyFury                    | L   | 0.730      | -            | -                | -                | -         |   -11.48 | jeyN, oskvr, shateri, Swaggy, waZz  |
|           31 |     1538 | 2024-12-19 | VOLT (European team)       | L   | 0.712      | -            | -                | -                | -         |   -10.86 | ERSIN, jeyN, shateri, Swaggy, waZz  |
|           30 |     1790 | 2024-12-13 | P0RTUGAL                   | L   | 0.672      | -            | -                | -                | -         |    -7.13 | d1maje, jeyN, shateri, Swaggy, waZz |
|           29 |     1793 | 2024-12-13 | PULSE Esports              | W   | 0.671      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     6.27 | d1maje, jeyN, shateri, Swaggy, waZz |
|           28 |     2362 | 2024-12-02 | NEVERMORE (Ukrainian team) | L   | 0.597      | -            | -                | -                | -         |    -7.59 | ERSIN, jeyN, shateri, Swaggy, waZz  |
|           27 |     2454 | 2024-12-01 | SkyFury                    | W   | 0.590      | 0.303        | 0.004 (0.001)    | 0.338 (0.060)    | 0 (0.000) |     9.08 | ERSIN, jeyN, shateri, Swaggy, waZz  |
|           26 |     2554 | 2024-11-30 | Fragmatic                  | W   | 0.583      | 0.303        | -                | 0.068 (0.012)    | 0 (0.000) |     6.07 | ERSIN, jeyN, shateri, Swaggy, waZz  |
|           25 |     3552 | 2024-11-12 | ALASKA                     | L   | 0.465      | -            | -                | -                | -         |    -1.74 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           24 |     3674 | 2024-11-10 | Endpoint                   | L   | 0.452      | -            | -                | -                | -         |    -5.40 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           23 |     3835 | 2024-11-07 | Glitchtech Esports         | W   | 0.432      | -            | -                | -                | 0 (0.000) |     4.21 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           22 |     3929 | 2024-11-05 | Dreams To Legends          | L   | 0.419      | -            | -                | -                | -         |    -8.16 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           21 |     3933 | 2024-11-05 | 8Sins                      | L   | 0.419      | -            | -                | -                | -         |    -3.09 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           20 |     4255 | 2024-10-31 | ALASKA                     | L   | 0.385      | -            | -                | -                | -         |    -1.35 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           19 |     4310 | 2024-10-30 | TRAXXXMANIA                | L   | 0.378      | -            | -                | -                | -         |    -6.38 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           18 |     4366 | 2024-10-29 | Annex Esports              | W   | 0.372      | -            | -                | -                | 0 (0.000) |     4.57 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           17 |     4751 | 2024-10-21 | The Last Resort            | W   | 0.318      | 0.143        | 0.001 (0.000)    | 0.159 (0.007)    | 0 (0.000) |     5.35 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           16 |     4947 | 2024-10-17 | Monte                      | L   | 0.291      | -            | -                | -                | -         |    -2.12 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           15 |     4992 | 2024-10-16 | MOUZ NXT                   | W   | 0.285      | 0.333        | -                | 0.183 (0.017)    | 0 (0.000) |     3.02 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           14 |     5419 | 2024-10-08 | Belfast Storm              | W   | 0.232      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     3.81 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           13 |     5813 | 2024-10-02 | Monte                      | L   | 0.189      | -            | -                | -                | -         |    -1.39 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           12 |     6037 | 2024-09-28 | Astralis Talent            | W   | 0.165      | 0.354        | 0.002 (0.000)    | 0.724 (0.042)    | 0 (0.000) |     3.18 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           11 |     6160 | 2024-09-27 | GenOne                     | W   | 0.156      | 0.333        | 0.012 (0.001)    | 0.837 (0.044)    | 0 (0.000) |     3.43 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           10 |     6246 | 2024-09-26 | GenOne                     | W   | 0.149      | 0.333        | 0.012 (0.001)    | 0.837 (0.041)    | -         |     3.28 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            9 |     6290 | 2024-09-25 | EYEBALLERS                 | L   | 0.145      | -            | -                | -                | -         |    -1.57 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            8 |     6322 | 2024-09-25 | PCIFIC Espor               | W   | 0.143      | 0.354        | 0.004 (0.000)    | 0.251 (0.013)    | -         |     2.79 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            7 |     6526 | 2024-09-22 | Astralis Talent            | L   | 0.124      | -            | -                | -                | -         |    -1.45 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            6 |     6548 | 2024-09-22 | Partizan Esports           | W   | 0.122      | 0.333        | 0.083 (0.003)    | 0.757 (0.031)    | -         |     3.50 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            5 |     6647 | 2024-09-20 | Natus Vincere Youth        | W   | 0.111      | -            | -                | -                | -         |     0.88 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            4 |     6755 | 2024-09-18 | LOADING (French team)      | L   | 0.098      | -            | -                | -                | -         |    -2.23 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            3 |     6869 | 2024-09-17 | Preasy Esport              | W   | 0.089      | 0.333        | 0.012 (0.000)    | 0.701 (0.021)    | -         |     1.88 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            2 |     6912 | 2024-09-16 | GenOne                     | L   | 0.083      | -            | -                | -                | -         |    -0.80 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            1 |     7038 | 2024-09-14 | FORZE Reload               | L   | 0.070      | -            | -                | -                | -         |    -0.63 | ERSIN, oskvr, shateri, Swaggy, waZz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,381.81)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-03 |      0.605 | $500.00        | $302.50         |
| 2024-10-18 |      0.297 | $1,000.00      | $297.36         |
| 2024-09-27 |      0.156 | $5,000.00      | $781.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
