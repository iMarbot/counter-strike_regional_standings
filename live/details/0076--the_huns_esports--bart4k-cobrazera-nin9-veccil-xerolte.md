### Roster Details<br />
Team Name: The Huns Esports<br />
Roster: Bart4k, cobrazera, nin9, Veccil, xerolte<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  888.0<br />
<br />
Final Rank Value (888.0) = Starting Rank Value (951.9) + Head To Head Adjustments (-63.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.369[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 951.9
- 400 + ( ( 0.276 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 951.9


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
|           62 |       35 | 2025-02-25 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -7.63 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           61 |       42 | 2025-02-25 | Chinggis Warriors         | L   | 1.000      | -            | -                | -                | -         |   -16.96 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           60 |       69 | 2025-02-24 | Eruption                  | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.552 (0.079)    | 0 (0.000) |    15.90 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           59 |      518 | 2025-02-13 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -7.48 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           58 |      520 | 2025-02-12 | Lynn Vision Gaming        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.368 (0.053)    | 0 (0.000) |    15.82 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           57 |      538 | 2025-02-12 | Lynn Vision Gaming        | L   | 1.000      | -            | -                | -                | -         |   -16.80 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           56 |      541 | 2025-02-11 | Chinggis Warriors         | W   | 1.000      | 0.143        | 0.016 (0.002)    | 0.567 (0.081)    | 0 (0.000) |    14.68 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           55 |      557 | 2025-02-11 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -7.10 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           54 |      564 | 2025-02-11 | Lynn Vision Gaming        | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.368 (0.053)    | 0 (0.000) |    13.78 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           53 |      714 | 2025-02-08 | IHC Esports               | W   | 1.000      | 0.143        | -                | 0.248 (0.035)    | -         |     8.69 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           52 |      722 | 2025-02-08 | Vizora Esports            | W   | 1.000      | -            | -                | -                | -         |     2.99 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           51 |      794 | 2025-02-07 | Flashback Gaming          | W   | 1.000      | -            | -                | -                | -         |    12.38 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           50 |     1309 | 2024-12-28 | ATOX Esports              | L   | 0.777      | -            | -                | -                | -         |    -4.98 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           49 |     1319 | 2024-12-27 | IHC Esports               | W   | 0.776      | 0.384        | -                | 0.248 (0.074)    | 1 (0.776) |     7.48 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           48 |     1335 | 2024-12-27 | Rare Atom                 | L   | 0.771      | -            | -                | -                | -         |    -7.72 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           47 |     1341 | 2024-12-26 | Chinggis Warriors         | W   | 0.770      | 0.384        | 0.016 (0.005)    | 0.567 (0.168)    | 1 (0.770) |    13.81 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           46 |     1357 | 2024-12-24 | Eruption                  | L   | 0.757      | -            | -                | -                | -         |   -11.96 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           45 |     1365 | 2024-12-24 | The QUBE Esports          | W   | 0.751      | -            | -                | -                | -         |     3.38 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           44 |     1369 | 2024-12-23 | Clutch Gaming             | W   | 0.749      | -            | -                | -                | -         |     3.62 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           43 |     2292 | 2024-12-03 | Harizma                   | L   | 0.611      | -            | -                | -                | -         |   -12.90 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           42 |     2299 | 2024-12-02 | Flashback Gaming          | L   | 0.610      | -            | -                | -                | -         |   -11.43 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           41 |     2302 | 2024-12-02 | The QUBE Esports          | W   | 0.610      | -            | -                | -                | -         |     2.07 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           40 |     2352 | 2024-12-02 | Bromo                     | L   | 0.605      | -            | -                | -                | -         |   -13.63 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           39 |     2354 | 2024-12-02 | MOLEGAN                   | W   | 0.605      | -            | -                | -                | -         |     1.12 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           38 |     2356 | 2024-12-02 | The QUBE Esports          | W   | 0.604      | -            | -                | -                | -         |     1.96 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           37 |     2364 | 2024-12-02 | Vizora Esports            | W   | 0.604      | -            | -                | -                | -         |     1.72 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           36 |     2373 | 2024-12-01 | Chinggis Warriors         | L   | 0.603      | -            | -                | -                | -         |    -9.49 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           35 |     2991 | 2024-11-22 | IHC Esports               | L   | 0.538      | -            | -                | -                | -         |   -12.82 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           34 |     3058 | 2024-11-21 | Ex-GR Gaming              | W   | 0.531      | 0.333        | 0.011 (0.002)    | -                | -         |     4.39 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           33 |     3063 | 2024-11-20 | Just Swing (Chinese team) | L   | 0.530      | -            | -                | -                | -         |   -12.38 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           32 |     3332 | 2024-11-16 | Metizport                 | L   | 0.499      | -            | -                | -                | -         |    -4.46 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           31 |     3398 | 2024-11-15 | Team Czech Republic       | L   | 0.492      | -            | -                | -                | -         |   -11.73 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           30 |     3405 | 2024-11-15 | Kitsune Esports           | W   | 0.491      | -            | -                | -                | 1 (0.491) |     2.04 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           29 |     3418 | 2024-11-14 | Dusty Roots               | W   | 0.488      | 0.617        | 0.008 (0.003)    | 0.371 (0.112)    | 1 (0.488) |     4.09 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           28 |     3490 | 2024-11-13 | Partizan Esports          | L   | 0.480      | -            | -                | -                | -         |    -4.72 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           27 |     3498 | 2024-11-13 | SINNERS Academy           | W   | 0.480      | -            | -                | -                | 1 (0.480) |     3.66 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           26 |     3813 | 2024-11-07 | IHC Esports               | L   | 0.443      | -            | -                | -                | -         |   -11.47 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           25 |     3906 | 2024-11-05 | DEWA United               | W   | 0.430      | -            | -                | -                | -         |     1.50 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           24 |     3908 | 2024-11-05 | Gods Reign                | W   | 0.430      | 0.333        | 0.018 (0.003)    | 0.412 (0.059)    | -         |     5.95 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           23 |     4636 | 2024-10-23 | Chinggis Warriors         | W   | 0.343      | -            | -                | -                | -         |     5.44 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           22 |     4639 | 2024-10-23 | Clutch Gaming             | W   | 0.343      | -            | -                | -                | -         |     1.19 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           21 |     4944 | 2024-10-17 | Lynn Vision Gaming        | L   | 0.298      | -            | -                | -                | -         |    -5.67 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           20 |     5016 | 2024-10-16 | Harizma                   | W   | 0.291      | 0.417        | -                | 0.433 (0.053)    | -         |     2.18 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           19 |     5076 | 2024-10-15 | Unsettled Resentment      | L   | 0.285      | -            | -                | -                | -         |    -6.76 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           18 |     5733 | 2024-10-03 | Chinggis Warriors         | L   | 0.204      | -            | -                | -                | -         |    -3.26 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|           17 |     5739 | 2024-10-02 | The QUBE Esports          | L   | 0.203      | -            | -                | -                | -         |    -5.56 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|           16 |     5779 | 2024-10-02 | Harizma                   | L   | 0.198      | -            | -                | -                | -         |    -4.99 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           15 |     5784 | 2024-10-02 | Harizma                   | L   | 0.198      | -            | -                | -                | -         |    -5.04 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           14 |     5859 | 2024-10-01 | Gods Reign                | W   | 0.192      | 0.417        | 0.018 (0.001)    | -                | -         |     2.65 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           13 |     5865 | 2024-10-01 | Gods Reign                | W   | 0.191      | 0.417        | 0.018 (0.001)    | -                | -         |     2.69 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           12 |     6059 | 2024-09-28 | ATOX Esports              | W   | 0.172      | -            | -                | -                | -         |     1.16 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           11 |     6062 | 2024-09-28 | ATOX Esports              | W   | 0.171      | -            | -                | -                | -         |     1.17 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           10 |     6162 | 2024-09-26 | Chinggis Warriors         | L   | 0.163      | -            | -                | -                | -         |    -2.68 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|            9 |     6224 | 2024-09-26 | ATOX Esports              | L   | 0.158      | -            | -                | -                | -         |    -1.49 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|            8 |     6237 | 2024-09-25 | The QUBE Esports          | W   | 0.156      | -            | -                | -                | 1 (0.156) |     0.65 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|            7 |     6299 | 2024-09-25 | -72C                      | W   | 0.152      | -            | -                | -                | -         |     0.41 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            6 |     6305 | 2024-09-25 | -72C                      | W   | 0.151      | -            | -                | -                | -         |     0.41 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            5 |     6397 | 2024-09-24 | TYLOO                     | W   | 0.145      | -            | -                | -                | -         |     1.19 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            4 |     6405 | 2024-09-24 | TYLOO                     | L   | 0.145      | -            | -                | -                | -         |    -3.40 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            3 |     7452 | 2024-09-07 | HXG Esports               | W   | 0.031      | -            | -                | -                | -         |     0.04 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            2 |     7529 | 2024-09-06 | Gods Reign                | W   | 0.025      | -            | -                | -                | -         |     0.34 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            1 |     7617 | 2024-09-05 | Come Mid                  | W   | 0.018      | -            | -                | -                | -         |     0.03 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,325.74)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.784 | $1,500.00      | $1,176.04       |
| 2024-11-17 |      0.506 | $12,500.00     | $6,328.13       |
| 2024-11-03 |      0.411 | $2,000.00      | $821.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
