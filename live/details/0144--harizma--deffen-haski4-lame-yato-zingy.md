### Roster Details<br />
Team Name: Harizma<br />
Roster: deffen, Haski4, lame, yato, ZinGY<br />
Global Rank: [144](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  770.4<br />
<br />
Final Rank Value (770.4) = Starting Rank Value (697.2) + Head To Head Adjustments (73.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.273[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 697.2
- 400 + ( ( 0.149 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 697.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      732 | 2025-02-08 | TYLOO                     | L   | 1.000      | -            | -                | -                | -         |   -14.15 | deffen, Haski4, lame, yato, ZinGY   |
|           35 |      810 | 2025-02-07 | Boring Players            | W   | 1.000      | 0.143        | -                | 0.344 (0.049)    | 0 (0.000) |     5.63 | deffen, Haski4, lame, yato, ZinGY   |
|           34 |     2180 | 2024-12-05 | Chinggis Warriors         | W   | 0.617      | 0.333        | 0.016 (0.003)    | 0.563 (0.116)    | 0 (0.000) |    12.86 | deffen, Geneka, Haski4, lame, ZinGY |
|           33 |     2191 | 2024-12-05 | DogEvil                   | L   | 0.616      | -            | -                | -                | -         |    -8.19 | deffen, Geneka, Haski4, lame, ZinGY |
|           32 |     2194 | 2024-12-04 | Chinggis Warriors         | W   | 0.615      | 0.333        | 0.016 (0.003)    | 0.563 (0.115)    | 0 (0.000) |    13.15 | deffen, Geneka, Haski4, lame, ZinGY |
|           31 |     2290 | 2024-12-03 | Flashback Gaming          | W   | 0.603      | -            | -                | -                | 0 (0.000) |    10.82 | deffen, Geneka, Haski4, lame, ZinGY |
|           30 |     2293 | 2024-12-03 | The QUBE Esports          | W   | 0.603      | -            | -                | -                | 0 (0.000) |     4.39 | deffen, Geneka, Haski4, lame, ZinGY |
|           29 |     2304 | 2024-12-03 | The Huns Esports          | W   | 0.603      | 0.143        | 0.025 (0.002)    | 0.553 (0.048)    | 0 (0.000) |    12.75 | deffen, Geneka, Haski4, lame, ZinGY |
|           28 |     2305 | 2024-12-03 | Victores Sumus            | W   | 0.602      | -            | -                | -                | 0 (0.000) |     9.65 | deffen, Geneka, Haski4, lame, ZinGY |
|           27 |     2308 | 2024-12-02 | Tsegtaslal                | W   | 0.602      | -            | -                | -                | 0 (0.000) |     2.49 | deffen, Geneka, Haski4, lame, ZinGY |
|           26 |     2315 | 2024-12-02 | DogEvil                   | L   | 0.602      | -            | -                | -                | -         |    -7.56 | deffen, Geneka, Haski4, lame, ZinGY |
|           25 |     3009 | 2024-11-21 | CatEvil                   | L   | 0.529      | -            | -                | -                | -         |    -9.88 | deffen, Geneka, Haski4, lame, ZinGY |
|           24 |     3072 | 2024-11-20 | Just Swing (Chinese team) | L   | 0.522      | -            | -                | -                | -         |    -8.40 | deffen, Geneka, Haski4, lame, ZinGY |
|           23 |     3078 | 2024-11-20 | Ex-GR Gaming              | W   | 0.522      | 0.333        | 0.012 (0.002)    | -                | 0 (0.000) |     7.92 | deffen, Geneka, Haski4, lame, ZinGY |
|           22 |     3265 | 2024-11-17 | Nomads (Mongolian team)   | W   | 0.497      | -            | -                | -                | 0 (0.000) |     3.60 | deffen, Geneka, Haski4, lame, ZinGY |
|           21 |     3266 | 2024-11-17 | DEWA United               | W   | 0.497      | -            | -                | -                | -         |     4.75 | deffen, Geneka, Haski4, lame, ZinGY |
|           20 |     3275 | 2024-11-17 | FengDa Gaming             | W   | 0.497      | 0.143        | -                | 0.550 (0.039)    | -         |     7.32 | deffen, Geneka, Haski4, lame, ZinGY |
|           19 |     3279 | 2024-11-17 | Northwest                 | W   | 0.496      | -            | -                | -                | -         |     2.23 | deffen, Geneka, Haski4, lame, ZinGY |
|           18 |     3280 | 2024-11-17 | -72C                      | W   | 0.496      | -            | -                | -                | -         |     3.47 | deffen, Geneka, Haski4, lame, ZinGY |
|           17 |     3304 | 2024-11-16 | Eruption                  | L   | 0.495      | -            | -                | -                | -         |    -3.93 | deffen, Geneka, Haski4, lame, ZinGY |
|           16 |     3347 | 2024-11-16 | CatEvil                   | L   | 0.490      | -            | -                | -                | -         |    -9.32 | deffen, Geneka, Haski4, lame, ZinGY |
|           15 |     3352 | 2024-11-16 | THE (Russian team)        | W   | 0.490      | -            | -                | -                | -         |     6.48 | deffen, Geneka, Haski4, lame, ZinGY |
|           14 |     3357 | 2024-11-16 | Eruption                  | W   | 0.489      | 0.143        | -                | 0.551 (0.038)    | -         |    11.74 | deffen, Geneka, Haski4, lame, ZinGY |
|           13 |     3374 | 2024-11-15 | CatEvil                   | L   | 0.489      | -            | -                | -                | -         |    -9.17 | deffen, Geneka, Haski4, lame, ZinGY |
|           12 |     3375 | 2024-11-15 | The QUBE Esports          | W   | 0.489      | -            | -                | -                | -         |     3.56 | deffen, Geneka, Haski4, lame, ZinGY |
|           11 |     5028 | 2024-10-16 | The Huns Esports          | L   | 0.283      | -            | -                | -                | -         |    -2.12 | deffen, Haski4, lame, Sange, ZinGY  |
|           10 |     5090 | 2024-10-15 | Gods Reign                | W   | 0.277      | 0.417        | 0.018 (0.002)    | 0.407 (0.047)    | -         |     6.37 | deffen, Haski4, lame, Sange, ZinGY  |
|            9 |     5251 | 2024-10-12 | Eternal prem              | L   | 0.256      | -            | -                | -                | -         |    -5.29 | deffen, Haski4, lame, Sange, ZinGY  |
|            8 |     5366 | 2024-10-09 | Ex-GR Gaming              | L   | 0.237      | -            | -                | -                | -         |    -3.98 | deffen, Haski4, lame, Sange, ZinGY  |
|            7 |     5372 | 2024-10-09 | Ex-GR Gaming              | L   | 0.237      | -            | -                | -                | -         |    -4.05 | deffen, Haski4, lame, Sange, ZinGY  |
|            6 |     5442 | 2024-10-08 | Lynn Vision Gaming        | W   | 0.230      | 0.417        | 0.017 (0.002)    | -                | -         |     4.93 | deffen, Haski4, lame, Sange, ZinGY  |
|            5 |     5448 | 2024-10-08 | Lynn Vision Gaming        | W   | 0.230      | -            | -                | -                | -         |     5.01 | deffen, Haski4, lame, Sange, ZinGY  |
|            4 |     5502 | 2024-10-07 | Gods Reign                | W   | 0.223      | 0.417        | 0.018 (0.002)    | 0.407 (0.038)    | -         |     5.24 | deffen, Haski4, lame, Sange, ZinGY  |
|            3 |     5504 | 2024-10-07 | Gods Reign                | W   | 0.223      | 0.417        | 0.018 (0.002)    | -                | -         |     5.31 | deffen, Haski4, lame, Sange, ZinGY  |
|            2 |     5791 | 2024-10-02 | The Huns Esports          | W   | 0.190      | 0.417        | 0.025 (0.002)    | 0.553 (0.044)    | -         |     4.78 | deffen, Haski4, lame, Sange, ZinGY  |
|            1 |     5796 | 2024-10-02 | The Huns Esports          | W   | 0.190      | 0.417        | 0.025 (0.002)    | 0.553 (0.044)    | -         |     4.82 | deffen, Haski4, lame, Sange, ZinGY  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($523.37)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.403 | $1,300.00      | $523.37         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
