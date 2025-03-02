### Roster Details<br />
Team Name: FengDa Gaming<br />
Roster: 1337x9, 3gl, chengking, Jung1e, p5p<br />
Global Rank: [229](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [28]( ../standings_asia.md)<br />
<br />
Final Rank Value:  688.8<br />
<br />
Final Rank Value (688.8) = Starting Rank Value (700.6) + Head To Head Adjustments (-11.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.6
- 400 + ( ( 0.150 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 700.6


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
|           35 |       33 | 2025-02-25 | Change The Game           | L   | 1.000      | -            | -                | -                | -         |   -15.15 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           34 |       51 | 2025-02-24 | T.Beast                   | W   | 1.000      | 0.143        | -                | 0.093 (0.013)    | 0 (0.000) |     5.61 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           33 |       70 | 2025-02-23 | DogEvil                   | L   | 1.000      | -            | -                | -                | -         |    -8.92 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           32 |      319 | 2025-02-16 | Magic Cape                | L   | 1.000      | -            | -                | -                | -         |   -15.45 | 1337x9, 3gl, chengking, p5p, yoi    |
|           31 |      433 | 2025-02-14 | Team XDM                  | L   | 1.000      | -            | -                | -                | -         |   -23.77 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           30 |      441 | 2025-02-14 | PA Esports                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.96 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           29 |      851 | 2025-02-06 | DogEvil                   | L   | 1.000      | -            | -                | -                | -         |   -11.61 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           28 |      856 | 2025-02-06 | TakeMeAway Gaming         | W   | 1.000      | 0.143        | -                | 0.093 (0.013)    | 0 (0.000) |     4.10 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           27 |      861 | 2025-02-05 | Team XDM                  | W   | 1.000      | 0.143        | -                | 0.093 (0.013)    | 0 (0.000) |     7.12 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           26 |     1267 | 2024-12-28 | Teamwork (Chinese team)   | W   | 0.784      | 0.143        | 0.031 (0.004)    | 0.137 (0.015)    | 0 (0.000) |    10.83 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           25 |     1270 | 2024-12-28 | Secret (Chinese team)     | W   | 0.783      | -            | -                | -                | 0 (0.000) |     3.33 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           24 |     1313 | 2024-12-28 | Magic Cape                | L   | 0.777      | -            | -                | -                | -         |   -13.30 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           23 |     1317 | 2024-12-27 | Change The Game           | W   | 0.776      | 0.143        | 0.061 (0.007)    | 0.221 (0.024)    | 0 (0.000) |    13.32 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           22 |     1348 | 2024-12-26 | OverWhelMing eSport       | W   | 0.765      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     9.74 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           21 |     1373 | 2024-12-23 | TREMOR-                   | W   | 0.745      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     9.03 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           20 |     1376 | 2024-12-23 | Teamwork (Chinese team)   | W   | 0.745      | 0.143        | 0.031 (0.003)    | 0.137 (0.015)    | 0 (0.000) |    11.13 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           19 |     1423 | 2024-12-22 | Nalakuvara Gaming         | W   | 0.737      | -            | -                | -                | -         |     6.91 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           18 |     1637 | 2024-12-15 | THE (Russian team)        | L   | 0.692      | -            | -                | -                | -         |   -11.16 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           17 |     1711 | 2024-12-14 | DEWA United               | W   | 0.685      | 0.143        | -                | 0.161 (0.016)    | -         |     7.05 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           16 |     1800 | 2024-12-13 | Rare Atom                 | L   | 0.678      | -            | -                | -                | -         |    -3.52 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           15 |     1965 | 2024-12-09 | Just Swing (Chinese team) | L   | 0.651      | -            | -                | -                | -         |    -8.72 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           14 |     2090 | 2024-12-07 | Never Say Never-          | W   | 0.638      | 0.250        | 0.002 (0.000)    | 0.120 (0.019)    | -         |     7.98 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           13 |     2272 | 2024-12-03 | Just Swing (Chinese team) | L   | 0.612      | -            | -                | -                | -         |    -8.19 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           12 |     2346 | 2024-12-02 | Never Say Never-          | W   | 0.605      | 0.250        | 0.002 (0.000)    | 0.120 (0.018)    | -         |     7.39 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           11 |     2529 | 2024-11-30 | SUBUTAI                   | W   | 0.592      | 0.250        | 0.001 (0.000)    | -                | -         |     4.94 | 1337x9, 3gl, chengking, Jung1e, p5p |
|           10 |     3263 | 2024-11-17 | Harizma                   | L   | 0.505      | -            | -                | -                | -         |    -7.40 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            9 |     3286 | 2024-11-16 | ATOX Esports              | L   | 0.504      | -            | -                | -                | -         |    -1.56 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            8 |     3290 | 2024-11-16 | DEWA United               | W   | 0.503      | 0.143        | -                | 0.161 (0.012)    | -         |     5.04 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            7 |     3688 | 2024-11-09 | Inner Mongolia Gaming     | L   | 0.456      | -            | -                | -                | -         |    -8.69 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            6 |     3751 | 2024-11-09 | Five Handsome Guys        | W   | 0.451      | 0.143        | 0.001 (0.000)    | -                | -         |     6.93 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            5 |     3759 | 2024-11-09 | E9 Esports                | W   | 0.451      | -            | -                | -                | -         |     3.48 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            4 |     5544 | 2024-10-06 | CatEvil                   | L   | 0.224      | -            | -                | -                | -         |    -4.11 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            3 |     5612 | 2024-10-05 | StudFarm                  | W   | 0.218      | -            | -                | -                | -         |     2.60 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            2 |     5675 | 2024-10-04 | CatEvil                   | L   | 0.211      | -            | -                | -                | -         |    -3.93 | 1337x9, 3gl, chengking, Jung1e, p5p |
|            1 |     5680 | 2024-10-04 | Magic Cape                | W   | 0.211      | 0.143        | 0.004 (0.000)    | -                | -         |     3.15 | 1337x9, 3gl, chengking, Jung1e, p5p |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,785.96)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.777 | $1,096.07      | $851.89         |
| 2024-12-26 |      0.765 | $2,055.30      | $1,573.16       |
| 2024-12-09 |      0.651 | $300.00        | $195.25         |
| 2024-11-10 |      0.457 | $278.58        | $127.37         |
| 2024-10-06 |      0.224 | $170.98        | $38.28          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
