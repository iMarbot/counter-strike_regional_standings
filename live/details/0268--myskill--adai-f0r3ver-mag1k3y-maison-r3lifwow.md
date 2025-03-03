### Roster Details<br />
Team Name: MYSKILL<br />
Roster: adai, F0R3VER, mag1k3Y, Maison, R3LiFwOw<br />
Global Rank: [268](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [184]( ../standings_europe.md)<br />
<br />
Final Rank Value:  671.2<br />
<br />
Final Rank Value (671.2) = Starting Rank Value (668.9) + Head To Head Adjustments (2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.041[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 668.9
- 400 + ( ( 0.134 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 668.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     1448 | 2024-12-21 | Hesta                      | L   | 0.725      | -            | -                | -                | -         |    -9.36 | adai, F0R3VER, mag1k3Y, Maison, R3LiFwOw |
|           19 |     2338 | 2024-12-02 | NEVERMORE (Ukrainian team) | L   | 0.599      | -            | -                | -                | -         |    -7.10 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           18 |     2406 | 2024-12-01 | Team Novaq                 | L   | 0.592      | -            | -                | -                | -         |    -1.64 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           17 |     2413 | 2024-12-01 | PUGSTAR5                   | W   | 0.592      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.07 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           16 |     2440 | 2024-12-01 | AimAssassins               | L   | 0.591      | -            | -                | -                | -         |    -3.80 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           15 |     2515 | 2024-11-30 | The Last Resort            | W   | 0.585      | 0.333        | 0.001 (0.000)    | 0.159 (0.031)    | 0 (0.000) |     9.94 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           14 |     2718 | 2024-11-26 | Donstu Esports             | L   | 0.559      | -            | -                | -                | -         |   -13.29 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           13 |     3255 | 2024-11-17 | DEPO                       | W   | 0.497      | 0.143        | 0.006 (0.000)    | 0.291 (0.021)    | 0 (0.000) |     9.57 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           12 |     3295 | 2024-11-17 | ALLINNERS                  | W   | 0.496      | 0.143        | 0.002 (0.000)    | 0.149 (0.011)    | 0 (0.000) |     9.14 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           11 |     3349 | 2024-11-16 | DEPO                       | W   | 0.490      | 0.143        | 0.006 (0.000)    | 0.291 (0.020)    | 0 (0.000) |     9.81 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           10 |     3861 | 2024-11-07 | RAGE (Kazakh team)         | L   | 0.431      | -            | -                | -                | -         |    -3.96 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            9 |     3907 | 2024-11-06 | AK BARS                    | L   | 0.424      | -            | -                | -                | -         |    -3.73 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            8 |     4163 | 2024-11-02 | BERMOOD                    | W   | 0.397      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     2.34 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            7 |     5560 | 2024-10-05 | AK BARS                    | L   | 0.215      | -            | -                | -                | -         |    -1.90 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            6 |     5629 | 2024-10-05 | RAGE (Kazakh team)         | L   | 0.209      | -            | -                | -                | -         |    -1.96 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            5 |     5643 | 2024-10-04 | DEPO                       | W   | 0.208      | 0.333        | 0.006 (0.000)    | 0.291 (0.020)    | 1 (0.208) |     4.23 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            4 |     6528 | 2024-09-22 | AK BARS                    | L   | 0.124      | -            | -                | -                | -         |    -1.09 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            3 |     6945 | 2024-09-15 | Kvartira36                 | W   | 0.077      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 1 (0.077) |     0.71 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            2 |     7046 | 2024-09-14 | Team Novaq                 | L   | 0.070      | -            | -                | -                | -         |    -0.17 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            1 |     7064 | 2024-09-13 | AK BARS                    | W   | 0.068      | 0.143        | 0.008 (0.000)    | 0.209 (0.002)    | 1 (0.068) |     1.56 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($770.14)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-17 |      0.497 | $702.18        | $349.24         |
| 2024-10-06 |      0.216 | $1,500.00      | $324.38         |
| 2024-09-15 |      0.077 | $1,249.98      | $96.53          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
