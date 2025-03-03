### Roster Details<br />
Team Name: FengDa Gaming<br />
Roster: 1337x9, 3gl, chengking, Jung1e, p5p<br />
Global Rank: [232](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [28]( ../standings_asia.md)<br />
<br />
Final Rank Value:  688.7<br />
<br />
Final Rank Value (688.7) = Starting Rank Value (701.1) + Head To Head Adjustments (-12.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.1
- 400 + ( ( 0.151 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 701.1


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
|           35 |       48 | 2025-02-25 | Change The Game           | L   | 1.000      | -            | -                | -                | -         |   -15.11 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           34 |       66 | 2025-02-24 | T.Beast                   | W   | 1.000      | 0.143        | -                | 0.094 (0.013)    | 0 (0.000) |     5.61 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           33 |       85 | 2025-02-23 | DogEvil                   | L   | 1.000      | -            | -                | -                | -         |    -8.93 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           32 |      331 | 2025-02-16 | Magic Cape                | L   | 1.000      | -            | -                | -                | -         |   -15.45 | 1337x9, 3gl, chengking, p5p, yoi    |
|           31 |      445 | 2025-02-14 | Team XDM                  | L   | 1.000      | -            | -                | -                | -         |   -23.75 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           30 |      453 | 2025-02-14 | PA Esports                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.96 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           29 |      863 | 2025-02-06 | DogEvil                   | L   | 1.000      | -            | -                | -                | -         |   -11.63 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           28 |      868 | 2025-02-06 | TakeMeAway Gaming         | W   | 1.000      | 0.143        | -                | 0.094 (0.013)    | 0 (0.000) |     4.11 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           27 |      873 | 2025-02-05 | Team XDM                  | W   | 1.000      | 0.143        | -                | 0.094 (0.013)    | 0 (0.000) |     7.13 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           26 |     1279 | 2024-12-28 | Teamwork (Chinese team)   | W   | 0.776      | 0.143        | 0.032 (0.004)    | 0.136 (0.015)    | 0 (0.000) |    10.74 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           25 |     1282 | 2024-12-28 | Secret (Chinese team)     | W   | 0.775      | -            | -                | -                | 0 (0.000) |     3.30 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           24 |     1324 | 2024-12-28 | Magic Cape                | L   | 0.769      | -            | -                | -                | -         |   -13.16 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           23 |     1329 | 2024-12-27 | Change The Game           | W   | 0.768      | 0.143        | 0.061 (0.007)    | 0.221 (0.024)    | 0 (0.000) |    13.22 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           22 |     1360 | 2024-12-26 | OverWhelMing eSport       | W   | 0.757      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     9.65 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           21 |     1385 | 2024-12-23 | TREMOR-                   | W   | 0.737      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     8.95 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           20 |     1388 | 2024-12-23 | Teamwork (Chinese team)   | W   | 0.737      | 0.143        | 0.032 (0.003)    | 0.136 (0.014)    | 0 (0.000) |    11.03 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           19 |     1435 | 2024-12-22 | Nalakuvara Gaming         | W   | 0.729      | -            | -                | -                | -         |     6.82 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           18 |     1649 | 2024-12-15 | THE (Russian team)        | L   | 0.683      | -            | -                | -                | -         |   -11.04 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           17 |     1723 | 2024-12-14 | DEWA United               | W   | 0.677      | 0.143        | -                | 0.158 (0.015)    | -         |     6.93 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           16 |     1812 | 2024-12-13 | Rare Atom                 | L   | 0.670      | -            | -                | -                | -         |    -3.50 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           15 |     1977 | 2024-12-09 | Just Swing (Chinese team) | L   | 0.643      | -            | -                | -                | -         |    -8.64 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           14 |     2102 | 2024-12-07 | Never Say Never-          | W   | 0.630      | 0.250        | 0.002 (0.000)    | 0.119 (0.019)    | -         |     7.88 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           13 |     2284 | 2024-12-03 | Just Swing (Chinese team) | L   | 0.604      | -            | -                | -                | -         |    -8.12 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           12 |     2358 | 2024-12-02 | Never Say Never-          | W   | 0.597      | 0.250        | 0.002 (0.000)    | 0.119 (0.018)    | -         |     7.29 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           11 |     2541 | 2024-11-30 | SUBUTAI                   | W   | 0.584      | 0.250        | 0.001 (0.000)    | -                | -         |     4.88 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           10 |     3275 | 2024-11-17 | Harizma                   | L   | 0.497      | -            | -                | -                | -         |    -7.32 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            9 |     3298 | 2024-11-16 | ATOX Esports              | L   | 0.496      | -            | -                | -                | -         |    -1.56 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            8 |     3302 | 2024-11-16 | DEWA United               | W   | 0.495      | 0.143        | -                | 0.158 (0.011)    | -         |     4.93 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            7 |     3700 | 2024-11-09 | Inner Mongolia Gaming     | L   | 0.448      | -            | -                | -                | -         |    -8.54 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            6 |     3763 | 2024-11-09 | Five Handsome Guys        | W   | 0.443      | 0.143        | 0.001 (0.000)    | -                | -         |     6.79 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            5 |     3771 | 2024-11-09 | E9 Esports                | W   | 0.442      | -            | -                | -                | -         |     3.42 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            4 |     5556 | 2024-10-06 | CatEvil                   | L   | 0.216      | -            | -                | -                | -         |    -3.97 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            3 |     5624 | 2024-10-05 | StudFarm                  | W   | 0.210      | -            | -                | -                | -         |     2.50 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            2 |     5687 | 2024-10-04 | CatEvil                   | L   | 0.203      | -            | -                | -                | -         |    -3.78 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            1 |     5692 | 2024-10-04 | Magic Cape                | W   | 0.203      | 0.143        | 0.004 (0.000)    | -                | -         |     3.03 | 1337x9, 3gl, chengking, Jung1e, p5p |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,753.99)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.769 | $1,096.07      | $842.91         |
| 2024-12-26 |      0.757 | $2,055.30      | $1,556.32       |
| 2024-12-09 |      0.643 | $300.00        | $192.79         |
| 2024-11-10 |      0.449 | $278.58        | $125.09         |
| 2024-10-06 |      0.216 | $170.98        | $36.88          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
