### Roster Details<br />
Team Name: The Huns Esports<br />
Roster: Bart4k, cobrazera, nin9, Veccil, xerolte<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  887.3<br />
<br />
Final Rank Value (887.3) = Starting Rank Value (949.9) + Head To Head Adjustments (-62.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.364[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 949.9
- 400 + ( ( 0.275 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 949.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           62 |       50 | 2025-02-25 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -7.68 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           61 |       57 | 2025-02-25 | Chinggis Warriors         | L   | 1.000      | -            | -                | -                | -         |   -17.01 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           60 |       84 | 2025-02-24 | Eruption                  | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.551 (0.079)    | 0 (0.000) |    15.91 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           59 |      530 | 2025-02-13 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -7.55 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           58 |      532 | 2025-02-12 | Lynn Vision Gaming        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.365 (0.052)    | 0 (0.000) |    15.79 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           57 |      550 | 2025-02-12 | Lynn Vision Gaming        | L   | 1.000      | -            | -                | -                | -         |   -16.82 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           56 |      553 | 2025-02-11 | Chinggis Warriors         | W   | 1.000      | 0.143        | 0.016 (0.002)    | 0.563 (0.080)    | 0 (0.000) |    14.62 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           55 |      569 | 2025-02-11 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -7.18 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           54 |      576 | 2025-02-11 | Lynn Vision Gaming        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.365 (0.052)    | 0 (0.000) |    13.74 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           53 |      726 | 2025-02-08 | IHC Esports               | W   | 1.000      | 0.143        | -                | 0.247 (0.035)    | -         |     8.69 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           52 |      734 | 2025-02-08 | Vizora Esports            | W   | 1.000      | -            | -                | -                | -         |     3.00 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           51 |      806 | 2025-02-07 | Flashback Gaming          | W   | 1.000      | -            | -                | -                | -         |    12.40 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           50 |     1321 | 2024-12-28 | ATOX Esports              | L   | 0.769      | -            | -                | -                | -         |    -5.00 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           49 |     1331 | 2024-12-27 | IHC Esports               | W   | 0.768      | 0.384        | -                | 0.247 (0.073)    | 1 (0.768) |     7.40 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           48 |     1347 | 2024-12-27 | Rare Atom                 | L   | 0.763      | -            | -                | -                | -         |    -7.66 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           47 |     1353 | 2024-12-26 | Chinggis Warriors         | W   | 0.762      | 0.384        | 0.016 (0.005)    | 0.563 (0.165)    | 1 (0.762) |    13.60 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           46 |     1369 | 2024-12-24 | Eruption                  | L   | 0.749      | -            | -                | -                | -         |   -11.81 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           45 |     1377 | 2024-12-24 | The QUBE Esports          | W   | 0.743      | -            | -                | -                | -         |     3.34 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           44 |     1381 | 2024-12-23 | Clutch Gaming             | W   | 0.741      | -            | -                | -                | -         |     3.56 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           43 |     2304 | 2024-12-03 | Harizma                   | L   | 0.603      | -            | -                | -                | -         |   -12.75 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           42 |     2311 | 2024-12-02 | Flashback Gaming          | L   | 0.602      | -            | -                | -                | -         |   -11.28 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           41 |     2314 | 2024-12-02 | The QUBE Esports          | W   | 0.602      | -            | -                | -                | -         |     2.04 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           40 |     2364 | 2024-12-02 | Bromo                     | L   | 0.597      | -            | -                | -                | -         |   -13.43 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           39 |     2366 | 2024-12-02 | MOLEGAN                   | W   | 0.596      | -            | -                | -                | -         |     1.11 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           38 |     2368 | 2024-12-02 | The QUBE Esports          | W   | 0.596      | -            | -                | -                | -         |     1.94 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           37 |     2376 | 2024-12-02 | Vizora Esports            | W   | 0.596      | -            | -                | -                | -         |     1.70 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           36 |     2385 | 2024-12-01 | Chinggis Warriors         | L   | 0.595      | -            | -                | -                | -         |    -9.42 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           35 |     3003 | 2024-11-22 | IHC Esports               | L   | 0.529      | -            | -                | -                | -         |   -12.62 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           34 |     3070 | 2024-11-21 | Ex-GR Gaming              | W   | 0.523      | 0.333        | 0.012 (0.002)    | -                | -         |     4.32 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           33 |     3075 | 2024-11-20 | Just Swing (Chinese team) | L   | 0.522      | -            | -                | -                | -         |   -12.18 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           32 |     3344 | 2024-11-16 | Metizport                 | L   | 0.490      | -            | -                | -                | -         |    -4.42 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           31 |     3410 | 2024-11-15 | Team Czech Republic       | L   | 0.484      | -            | -                | -                | -         |   -11.53 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           30 |     3417 | 2024-11-15 | Kitsune Esports           | W   | 0.483      | -            | -                | -                | 1 (0.483) |     2.01 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           29 |     3430 | 2024-11-14 | Dusty Roots               | W   | 0.479      | 0.617        | 0.009 (0.003)    | 0.366 (0.108)    | 1 (0.479) |     4.04 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           28 |     3502 | 2024-11-13 | Partizan Esports          | L   | 0.472      | -            | -                | -                | -         |    -4.65 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           27 |     3510 | 2024-11-13 | SINNERS Academy           | W   | 0.471      | -            | -                | -                | 1 (0.471) |     3.61 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           26 |     3825 | 2024-11-07 | IHC Esports               | L   | 0.435      | -            | -                | -                | -         |   -11.24 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           25 |     3918 | 2024-11-05 | DEWA United               | W   | 0.422      | -            | -                | -                | -         |     1.47 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           24 |     3920 | 2024-11-05 | Gods Reign                | W   | 0.422      | 0.333        | 0.018 (0.003)    | 0.407 (0.057)    | -         |     5.89 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           23 |     4648 | 2024-10-23 | Chinggis Warriors         | W   | 0.335      | -            | -                | -                | -         |     5.28 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           22 |     4651 | 2024-10-23 | Clutch Gaming             | W   | 0.335      | -            | -                | -                | -         |     1.16 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           21 |     4956 | 2024-10-17 | Lynn Vision Gaming        | L   | 0.290      | -            | -                | -                | -         |    -5.52 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           20 |     5028 | 2024-10-16 | Harizma                   | W   | 0.283      | 0.417        | -                | 0.428 (0.050)    | -         |     2.12 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           19 |     5088 | 2024-10-15 | Unsettled Resentment      | L   | 0.277      | -            | -                | -                | -         |    -6.56 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           18 |     5745 | 2024-10-03 | Chinggis Warriors         | L   | 0.196      | -            | -                | -                | -         |    -3.15 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|           17 |     5751 | 2024-10-02 | The QUBE Esports          | L   | 0.195      | -            | -                | -                | -         |    -5.33 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|           16 |     5791 | 2024-10-02 | Harizma                   | L   | 0.190      | -            | -                | -                | -         |    -4.78 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           15 |     5796 | 2024-10-02 | Harizma                   | L   | 0.190      | -            | -                | -                | -         |    -4.82 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           14 |     5871 | 2024-10-01 | Gods Reign                | W   | 0.183      | 0.417        | 0.018 (0.001)    | -                | -         |     2.56 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           13 |     5877 | 2024-10-01 | Gods Reign                | W   | 0.183      | 0.417        | 0.018 (0.001)    | -                | -         |     2.60 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           12 |     6071 | 2024-09-28 | ATOX Esports              | W   | 0.163      | -            | -                | -                | -         |     1.11 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           11 |     6074 | 2024-09-28 | ATOX Esports              | W   | 0.163      | -            | -                | -                | -         |     1.12 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           10 |     6174 | 2024-09-26 | Chinggis Warriors         | L   | 0.154      | -            | -                | -                | -         |    -2.55 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|            9 |     6236 | 2024-09-26 | ATOX Esports              | L   | 0.149      | -            | -                | -                | -         |    -1.43 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|            8 |     6249 | 2024-09-25 | The QUBE Esports          | W   | 0.148      | -            | -                | -                | 1 (0.148) |     0.62 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|            7 |     6311 | 2024-09-25 | -72C                      | W   | 0.143      | -            | -                | -                | -         |     0.39 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            6 |     6317 | 2024-09-25 | -72C                      | W   | 0.143      | -            | -                | -                | -         |     0.40 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            5 |     6409 | 2024-09-24 | TYLOO                     | W   | 0.137      | -            | -                | -                | -         |     1.13 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            4 |     6417 | 2024-09-24 | TYLOO                     | L   | 0.137      | -            | -                | -                | -         |    -3.20 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            3 |     7464 | 2024-09-07 | HXG Esports               | W   | 0.023      | -            | -                | -                | -         |     0.03 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            2 |     7541 | 2024-09-06 | Gods Reign                | W   | 0.017      | -            | -                | -                | -         |     0.23 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            1 |     7629 | 2024-09-05 | Come Mid                  | W   | 0.010      | -            | -                | -                | -         |     0.01 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,194.63)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.776 | $1,500.00      | $1,163.75       |
| 2024-11-17 |      0.498 | $12,500.00     | $6,225.69       |
| 2024-11-03 |      0.403 | $2,000.00      | $805.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
