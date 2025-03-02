### Roster Details<br />
Team Name: Chill Guys<br />
Roster: Evan, MagiC, MERL, NIGHT666LADE, TABEN<br />
Global Rank: [214](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
<br />
Final Rank Value:  699.9<br />
<br />
Final Rank Value (699.9) = Starting Rank Value (663.6) + Head To Head Adjustments (36.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.6
- 400 + ( ( 0.132 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 663.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      570 | 2025-02-10 | Exceritus                  | L   | 1.000      | -            | -                | -                | -         |   -18.09 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           31 |      614 | 2025-02-09 | InControl                  | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.086 (0.012)    | 0 (0.000) |    12.62 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           30 |      655 | 2025-02-08 | Party Astronauts           | L   | 1.000      | -            | -                | -                | -         |   -11.72 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           29 |      671 | 2025-02-08 | Exceritus                  | W   | 1.000      | 0.143        | -                | 0.238 (0.034)    | 0 (0.000) |    11.86 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           28 |      732 | 2025-02-07 | Immigrants Peek            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.366 (0.052)    | 0 (0.000) |    13.38 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           27 |     1667 | 2024-12-14 | Drugs n pugs               | W   | 0.688      | -            | -                | -                | 0 (0.000) |     3.42 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           26 |     2821 | 2024-11-23 | NRG                        | L   | 0.548      | -            | -                | -                | -         |    -2.60 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           25 |     2925 | 2024-11-22 | Blahaj                     | W   | 0.542      | 0.143        | -                | 0.144 (0.011)    | 0 (0.000) |     5.18 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           24 |     2929 | 2024-11-22 | Diablos                    | W   | 0.542      | -            | -                | -                | 0 (0.000) |     3.00 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           23 |     2932 | 2024-11-22 | Hite Gaming                | W   | 0.542      | 0.143        | 0.005 (0.000)    | 0.063 (0.005)    | 0 (0.000) |     7.83 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           22 |     3303 | 2024-11-16 | Timbermen                  | W   | 0.501      | 0.233        | 0.002 (0.000)    | -                | 0 (0.000) |     8.08 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           21 |     5303 | 2024-10-09 | FLUFFY AIMERS              | W   | 0.249      | 0.477        | 0.005 (0.001)    | 0.228 (0.027)    | 0 (0.000) |     5.43 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           20 |     5309 | 2024-10-09 | FLUFFY AIMERS              | W   | 0.248      | 0.477        | 0.005 (0.001)    | 0.228 (0.027)    | 0 (0.000) |     5.52 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           19 |     5376 | 2024-10-08 | Party Astronauts           | L   | 0.242      | -            | -                | -                | -         |    -2.56 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           18 |     5382 | 2024-10-08 | Party Astronauts           | L   | 0.242      | -            | -                | -                | -         |    -2.60 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           17 |     5445 | 2024-10-07 | Familia Maquininha         | L   | 0.235      | -            | -                | -                | -         |    -3.49 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           16 |     5447 | 2024-10-07 | Familia Maquininha         | W   | 0.235      | 0.477        | 0.003 (0.000)    | 0.205 (0.023)    | -         |     3.98 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           15 |     5693 | 2024-10-03 | LAG Gaming                 | W   | 0.209      | 0.477        | 0.001 (0.000)    | -                | -         |     2.79 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           14 |     5698 | 2024-10-03 | LAG Gaming                 | W   | 0.208      | 0.477        | 0.001 (0.000)    | -                | -         |     2.84 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           13 |     5817 | 2024-10-01 | FLUFFY AIMERS              | L   | 0.195      | -            | -                | -                | -         |    -1.83 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           12 |     5832 | 2024-10-01 | Nouns Esports              | L   | 0.194      | -            | -                | -                | -         |    -2.45 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           11 |     5836 | 2024-10-01 | Nouns Esports              | L   | 0.194      | -            | -                | -                | -         |    -2.48 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           10 |     5884 | 2024-09-30 | M80                        | L   | 0.188      | -            | -                | -                | -         |    -1.10 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            9 |     5886 | 2024-09-30 | M80                        | L   | 0.188      | -            | -                | -                | -         |    -1.11 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            8 |     6334 | 2024-09-24 | Legacy                     | L   | 0.149      | -            | -                | -                | -         |    -1.14 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            7 |     6341 | 2024-09-24 | Legacy                     | L   | 0.148      | -            | -                | -                | -         |    -1.14 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            6 |     6424 | 2024-09-23 | InControl                  | W   | 0.142      | 0.371        | 0.001 (0.000)    | 0.086 (0.005)    | -         |     2.02 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            5 |     6675 | 2024-09-19 | Vagrants                   | W   | 0.114      | 0.371        | -                | 0.278 (0.012)    | -         |     1.79 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            4 |     6731 | 2024-09-18 | Wildcard                   | L   | 0.108      | -            | -                | -                | -         |    -0.06 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            3 |     6735 | 2024-09-18 | Wildcard                   | L   | 0.107      | -            | -                | -                | -         |    -0.06 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            2 |     6965 | 2024-09-14 | Dangerous (Ukrainian team) | W   | 0.081      | -            | -                | -                | -         |     0.48 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            1 |     7118 | 2024-09-12 | Jahsdnmasjdm v2            | L   | 0.068      | -            | -                | -                | -         |    -1.55 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,108.23)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.688 | $500.00        | $343.85         |
| 2024-11-16 |      0.501 | $500.00        | $250.60         |
| 2024-10-20 |      0.321 | $1,600.00      | $513.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
