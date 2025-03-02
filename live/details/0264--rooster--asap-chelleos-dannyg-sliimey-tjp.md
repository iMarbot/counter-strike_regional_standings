### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, DannyG, Sliimey, TjP<br />
Global Rank: [264](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [35]( ../standings_asia.md)<br />
<br />
Final Rank Value:  672.0<br />
<br />
Final Rank Value (672.0) = Starting Rank Value (672.5) + Head To Head Adjustments (-0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.300[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 672.5
- 400 + ( ( 0.136 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 672.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |       54 | 2025-02-24 | MANTRA                    | L   | 1.000      | -            | -                | -                | -         |   -19.71 | asap, chelleos, DannyG, Sliimey, TjP |
|           22 |       80 | 2025-02-23 | Vantage Esports           | L   | 1.000      | -            | -                | -                | -         |   -16.38 | asap, chelleos, DannyG, Sliimey, TjP |
|           21 |      568 | 2025-02-10 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -3.12 | asap, chelleos, dpr, Sliimey, TjP    |
|           20 |      601 | 2025-02-10 | SemperFi Esports          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.665 (0.095)    | 0 (0.000) |    13.41 | asap, chelleos, dpr, Sliimey, TjP    |
|           19 |      606 | 2025-02-09 | Just Swing (Chinese team) | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.351 (0.050)    | 0 (0.000) |    15.41 | asap, chelleos, dpr, Sliimey, TjP    |
|           18 |      647 | 2025-02-08 | DXA Esports               | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.25 | asap, chelleos, dpr, Sliimey, TjP    |
|           17 |      718 | 2025-02-08 | SemperFi Esports          | L   | 1.000      | -            | -                | -                | -         |   -18.18 | asap, chelleos, dpr, Sliimey, TjP    |
|           16 |     2815 | 2024-11-23 | Justice For Tomorrow      | W   | 0.550      | 0.264        | 0.001 (0.000)    | 0.427 (0.062)    | 0 (0.000) |     7.83 | asap, chelleos, dpr, Sliimey, TjP    |
|           15 |     2917 | 2024-11-22 | Vantage Esports           | W   | 0.543      | 0.264        | 0.003 (0.000)    | 0.337 (0.048)    | 0 (0.000) |     7.85 | asap, chelleos, dpr, Sliimey, TjP    |
|           14 |     2923 | 2024-11-22 | Justice For Tomorrow      | W   | 0.543      | 0.264        | 0.001 (0.000)    | 0.427 (0.061)    | 0 (0.000) |     7.70 | asap, chelleos, dpr, Sliimey, TjP    |
|           13 |     5297 | 2024-10-10 | MANTRA                    | W   | 0.251      | 0.333        | 0.000 (0.000)    | 0.175 (0.015)    | 0 (0.000) |     3.29 | asap, chelleos, Rackem, Sliimey, TjP |
|           12 |     5298 | 2024-10-10 | MANTRA                    | L   | 0.251      | -            | -                | -                | -         |    -4.69 | asap, chelleos, Rackem, Sliimey, TjP |
|           11 |     5361 | 2024-10-09 | KZG                       | L   | 0.244      | -            | -                | -                | -         |    -4.49 | asap, chelleos, Rackem, Sliimey, TjP |
|           10 |     5367 | 2024-10-09 | KZG                       | W   | 0.244      | 0.333        | 0.001 (0.000)    | 0.165 (0.013)    | 0 (0.000) |     3.25 | asap, chelleos, Rackem, Sliimey, TjP |
|            9 |     5596 | 2024-10-05 | BetBoom Team              | L   | 0.219      | -            | -                | -                | -         |    -0.84 | asap, chelleos, jhd, Sliimey, TjP    |
|            8 |     5666 | 2024-10-04 | SAW                       | L   | 0.212      | -            | -                | -                | -         |    -0.16 | asap, chelleos, jhd, Sliimey, TjP    |
|            7 |     5934 | 2024-09-30 | FlyQuest                  | L   | 0.184      | -            | -                | -                | -         |    -0.48 | asap, chelleos, Rackem, Sliimey, TjP |
|            6 |     5935 | 2024-09-30 | FlyQuest                  | L   | 0.184      | -            | -                | -                | -         |    -0.48 | asap, chelleos, Rackem, Sliimey, TjP |
|            5 |     6317 | 2024-09-25 | Housebets                 | W   | 0.151      | 0.333        | 0.001 (0.000)    | 0.123 (0.006)    | 0 (0.000) |     2.04 | asap, chelleos, Rackem, Sliimey, TjP |
|            4 |     6326 | 2024-09-25 | Housebets                 | W   | 0.151      | 0.333        | 0.001 (0.000)    | 0.123 (0.006)    | 0 (0.000) |     2.07 | asap, chelleos, Rackem, Sliimey, TjP |
|            3 |     7091 | 2024-09-13 | Astralis                  | L   | 0.072      | -            | -                | -                | -         |    -0.00 | asap, chelleos, dangeR, Sliimey, TjP |
|            2 |     7190 | 2024-09-11 | BIG                       | L   | 0.059      | -            | -                | -                | -         |    -0.02 | asap, chelleos, dangeR, Sliimey, TjP |
|            1 |     7257 | 2024-09-10 | MOUZ                      | L   | 0.051      | -            | -                | -                | -         |    -0.00 | asap, chelleos, dangeR, Sliimey, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,572.32)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-23 |      0.550 | $845.00        | $465.12         |
| 2024-10-19 |      0.316 | $600.00        | $189.83         |
| 2024-10-06 |      0.227 | $2,000.00      | $454.58         |
| 2024-09-22 |      0.132 | $3,500.00      | $462.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
