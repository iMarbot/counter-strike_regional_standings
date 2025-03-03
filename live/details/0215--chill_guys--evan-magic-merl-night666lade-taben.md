### Roster Details<br />
Team Name: Chill Guys<br />
Roster: Evan, MagiC, MERL, NIGHT666LADE, TABEN<br />
Global Rank: [215](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [41]( ../standings_americas.md)<br />
<br />
Final Rank Value:  703.3<br />
<br />
Final Rank Value (703.3) = Starting Rank Value (666.0) + Head To Head Adjustments (37.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.223[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.0
- 400 + ( ( 0.133 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 666.0


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
|           32 |      582 | 2025-02-10 | Exceritus                  | L   | 1.000      | -            | -                | -                | -         |   -18.23 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           31 |      626 | 2025-02-09 | InControl                  | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.084 (0.012)    | 0 (0.000) |    12.47 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           30 |      667 | 2025-02-08 | Party Astronauts           | L   | 1.000      | -            | -                | -                | -         |   -11.56 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           29 |      683 | 2025-02-08 | Exceritus                  | W   | 1.000      | 0.143        | -                | 0.238 (0.034)    | 0 (0.000) |    11.72 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           28 |      744 | 2025-02-07 | Immigrants Peek            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.366 (0.052)    | 0 (0.000) |    13.31 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           27 |     1679 | 2024-12-14 | Drugs n pugs               | W   | 0.680      | -            | -                | -                | 0 (0.000) |     3.32 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           26 |     2833 | 2024-11-23 | NRG                        | L   | 0.540      | -            | -                | -                | -         |    -2.55 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           25 |     2937 | 2024-11-22 | Blahaj                     | W   | 0.534      | 0.143        | -                | 0.144 (0.011)    | 0 (0.000) |     4.98 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           24 |     2941 | 2024-11-22 | Diablos                    | W   | 0.534      | -            | -                | -                | 0 (0.000) |     2.90 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           23 |     2944 | 2024-11-22 | Hite Gaming                | W   | 0.534      | 0.143        | 0.005 (0.000)    | -                | 0 (0.000) |     7.62 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           22 |     3315 | 2024-11-16 | Timbermen                  | W   | 0.493      | 0.233        | 0.002 (0.000)    | -                | 0 (0.000) |     7.86 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           21 |     5315 | 2024-10-09 | FLUFFY AIMERS              | W   | 0.240      | 0.477        | 0.005 (0.001)    | 0.213 (0.024)    | 0 (0.000) |     5.27 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           20 |     5321 | 2024-10-09 | FLUFFY AIMERS              | W   | 0.240      | 0.477        | 0.005 (0.001)    | 0.213 (0.024)    | 0 (0.000) |     5.36 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           19 |     5388 | 2024-10-08 | Party Astronauts           | L   | 0.234      | -            | -                | -                | -         |    -2.50 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           18 |     5394 | 2024-10-08 | Party Astronauts           | L   | 0.233      | -            | -                | -                | -         |    -2.54 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           17 |     5457 | 2024-10-07 | Familia Maquininha         | L   | 0.227      | -            | -                | -                | -         |    -3.49 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           16 |     5459 | 2024-10-07 | Familia Maquininha         | W   | 0.227      | 0.477        | 0.003 (0.000)    | 0.202 (0.022)    | -         |     3.71 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           15 |     5705 | 2024-10-03 | LAG Gaming                 | W   | 0.200      | 0.477        | 0.004 (0.000)    | 0.120 (0.011)    | -         |     3.99 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           14 |     5710 | 2024-10-03 | LAG Gaming                 | W   | 0.200      | 0.477        | 0.004 (0.000)    | 0.120 (0.011)    | -         |     4.05 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           13 |     5829 | 2024-10-01 | FLUFFY AIMERS              | L   | 0.187      | -            | -                | -                | -         |    -1.76 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           12 |     5844 | 2024-10-01 | Nouns Esports              | L   | 0.186      | -            | -                | -                | -         |    -2.36 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           11 |     5848 | 2024-10-01 | Nouns Esports              | L   | 0.185      | -            | -                | -                | -         |    -2.40 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           10 |     5896 | 2024-09-30 | M80                        | L   | 0.180      | -            | -                | -                | -         |    -1.08 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            9 |     5898 | 2024-09-30 | M80                        | L   | 0.180      | -            | -                | -                | -         |    -1.09 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            8 |     6346 | 2024-09-24 | Legacy                     | L   | 0.140      | -            | -                | -                | -         |    -1.08 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            7 |     6353 | 2024-09-24 | Legacy                     | L   | 0.140      | -            | -                | -                | -         |    -1.09 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            6 |     6436 | 2024-09-23 | InControl                  | W   | 0.134      | 0.371        | 0.001 (0.000)    | -                | -         |     1.89 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            5 |     6687 | 2024-09-19 | Vagrants                   | W   | 0.106      | 0.371        | -                | 0.276 (0.011)    | -         |     1.64 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            4 |     6743 | 2024-09-18 | Wildcard                   | L   | 0.100      | -            | -                | -                | -         |    -0.06 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            3 |     6747 | 2024-09-18 | Wildcard                   | L   | 0.099      | -            | -                | -                | -         |    -0.06 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            2 |     6977 | 2024-09-14 | Dangerous (Ukrainian team) | W   | 0.073      | -            | -                | -                | -         |     0.42 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            1 |     7130 | 2024-09-12 | Jahsdnmasjdm v2            | L   | 0.059      | -            | -                | -                | -         |    -1.37 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,086.93)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.680 | $500.00        | $339.76         |
| 2024-11-16 |      0.493 | $500.00        | $246.50         |
| 2024-10-20 |      0.313 | $1,600.00      | $500.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
