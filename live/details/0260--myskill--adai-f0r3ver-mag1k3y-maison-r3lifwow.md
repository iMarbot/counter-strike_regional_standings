### Roster Details<br />
Team Name: MYSKILL<br />
Roster: adai, F0R3VER, mag1k3Y, Maison, R3LiFwOw<br />
Global Rank: [260](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [181]( ../standings_europe.md)<br />
<br />
Final Rank Value:  673.0<br />
<br />
Final Rank Value (673.0) = Starting Rank Value (670.6) + Head To Head Adjustments (2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.044[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.6
- 400 + ( ( 0.135 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 670.6


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
|           20 |     1436 | 2024-12-21 | Hesta                      | L   | 0.734      | -            | -                | -                | -         |    -9.52 | adai, F0R3VER, mag1k3Y, Maison, R3LiFwOw |
|           19 |     2326 | 2024-12-02 | NEVERMORE (Ukrainian team) | L   | 0.607      | -            | -                | -                | -         |    -7.24 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           18 |     2394 | 2024-12-01 | Team Novaq                 | L   | 0.600      | -            | -                | -                | -         |    -1.65 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           17 |     2401 | 2024-12-01 | PUGSTAR5                   | W   | 0.600      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.08 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           16 |     2428 | 2024-12-01 | AimAssassins               | L   | 0.599      | -            | -                | -                | -         |    -3.86 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           15 |     2503 | 2024-11-30 | The Last Resort            | W   | 0.593      | 0.333        | 0.001 (0.000)    | 0.161 (0.032)    | 0 (0.000) |    10.03 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           14 |     2706 | 2024-11-26 | Donstu Esports             | L   | 0.567      | -            | -                | -                | -         |   -13.53 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           13 |     3243 | 2024-11-17 | DEPO                       | W   | 0.506      | 0.143        | 0.006 (0.000)    | 0.297 (0.021)    | 0 (0.000) |     9.74 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           12 |     3283 | 2024-11-17 | ALLINNERS                  | W   | 0.504      | 0.143        | 0.002 (0.000)    | 0.151 (0.011)    | 0 (0.000) |     9.27 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           11 |     3337 | 2024-11-16 | DEPO                       | W   | 0.498      | 0.143        | 0.006 (0.000)    | 0.297 (0.021)    | 0 (0.000) |     9.99 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|           10 |     3849 | 2024-11-07 | RAGE (Kazakh team)         | L   | 0.439      | -            | -                | -                | -         |    -4.02 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            9 |     3895 | 2024-11-06 | AK BARS                    | L   | 0.432      | -            | -                | -                | -         |    -3.81 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            8 |     4151 | 2024-11-02 | BERMOOD                    | W   | 0.405      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     2.37 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            7 |     5548 | 2024-10-05 | AK BARS                    | L   | 0.223      | -            | -                | -                | -         |    -1.98 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            6 |     5617 | 2024-10-05 | RAGE (Kazakh team)         | L   | 0.218      | -            | -                | -                | -         |    -2.03 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            5 |     5631 | 2024-10-04 | DEPO                       | W   | 0.217      | 0.333        | 0.006 (0.000)    | 0.297 (0.021)    | 1 (0.217) |     4.41 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            4 |     6516 | 2024-09-22 | AK BARS                    | L   | 0.132      | -            | -                | -                | -         |    -1.17 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            3 |     6933 | 2024-09-15 | Kvartira36                 | W   | 0.085      | 0.143        | 0.000 (0.000)    | 0.004 (0.000)    | 1 (0.085) |     0.78 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            2 |     7034 | 2024-09-14 | Team Novaq                 | L   | 0.078      | -            | -                | -                | -         |    -0.18 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |
|            1 |     7052 | 2024-09-13 | AK BARS                    | W   | 0.077      | 0.143        | 0.008 (0.000)    | 0.212 (0.002)    | 1 (0.077) |     1.75 | adai, F0R3VER, mag1k3Y, Maison, OxygeN   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($798.43)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-17 |      0.506 | $702.18        | $354.99         |
| 2024-10-06 |      0.224 | $1,500.00      | $336.67         |
| 2024-09-15 |      0.085 | $1,249.98      | $106.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
