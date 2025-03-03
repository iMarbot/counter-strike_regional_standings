### Roster Details<br />
Team Name: LaChampionsLiga<br />
Roster: dott1, Hezz, lenci, pavv+, rzk<br />
Global Rank: [333](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [69]( ../standings_americas.md)<br />
<br />
Final Rank Value:  633.3<br />
<br />
Final Rank Value (633.3) = Starting Rank Value (673.5) + Head To Head Adjustments (-40.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 673.5
- 400 + ( ( 0.137 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 673.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      404 | 2025-02-15 | Tropa do VSM             | L   | 1.000      | -            | -                | -                | -         |   -20.63 | dott1, Hezz, lenci, pavv+, rzk   |
|           35 |      407 | 2025-02-15 | América eSports          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.426 (0.061)    | 0 (0.000) |    13.41 | dott1, Hezz, lenci, pavv+, rzk   |
|           34 |      411 | 2025-02-15 | 7REX                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     6.50 | dott1, Hezz, lenci, pavv+, rzk   |
|           33 |      672 | 2025-02-08 | Legacy                   | L   | 1.000      | -            | -                | -                | -         |    -4.97 | dott1, Hezz, lenci, pavv+, rzk   |
|           32 |      750 | 2025-02-07 | Tropa do KinGui          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.094 (0.013)    | 0 (0.000) |     6.54 | dott1, Hezz, lenci, pavv+, rzk   |
|           31 |      944 | 2025-02-04 | Familia Maquininha       | L   | 1.000      | -            | -                | -                | -         |   -13.77 | dott1, Hezz, lenci, pavv+, rzk   |
|           30 |     1443 | 2024-12-21 | Game Hunters             | L   | 0.726      | -            | -                | -                | -         |    -9.60 | dott1, Hezz, lenci, nacho, pavv+ |
|           29 |     1537 | 2024-12-19 | Team Solid               | L   | 0.712      | -            | -                | -                | -         |    -5.54 | dott1, Hezz, lenci, nacho, pavv+ |
|           28 |     1562 | 2024-12-18 | Bad News Chickens        | L   | 0.705      | -            | -                | -                | -         |   -10.09 | dott1, Hezz, lenci, nacho, pavv+ |
|           27 |     1590 | 2024-12-16 | 20/70                    | W   | 0.693      | 0.384        | 0.001 (0.000)    | 0.286 (0.076)    | 0 (0.000) |    10.83 | dott1, Hezz, lenci, nacho, pavv+ |
|           26 |     1673 | 2024-12-14 | Players (Brazilian team) | W   | 0.680      | 0.384        | 0.008 (0.002)    | 0.632 (0.165)    | 0 (0.000) |    14.68 | dott1, Hezz, lenci, nacho, pavv+ |
|           25 |     1921 | 2024-12-10 | 9z Academy               | L   | 0.653      | -            | -                | -                | -         |    -9.51 | dott1, Hezz, lenci, nacho, pavv+ |
|           24 |     1954 | 2024-12-09 | Floripa Stars            | W   | 0.646      | 0.143        | 0.001 (0.000)    | 0.296 (0.027)    | 0 (0.000) |     9.58 | dott1, Hezz, lenci, nacho, pavv+ |
|           23 |     2133 | 2024-12-06 | MIBR Academy             | L   | 0.625      | -            | -                | -                | -         |    -8.47 | dott1, Hezz, lenci, nacho, pavv+ |
|           22 |     2263 | 2024-12-03 | Nitro.GG                 | W   | 0.606      | 0.143        | 0.002 (0.000)    | 0.512 (0.044)    | 0 (0.000) |    10.84 | dott1, Hezz, lenci, nacho, pavv+ |
|           21 |     2480 | 2024-11-30 | Team Leveling            | W   | 0.586      | 0.143        | -                | 0.155 (0.013)    | 0 (0.000) |     6.13 | dott1, Hezz, lenci, nacho, pavv+ |
|           20 |     2504 | 2024-11-30 | 9z Academy               | W   | 0.585      | 0.143        | 0.001 (0.000)    | 0.384 (0.032)    | 0 (0.000) |     9.62 | dott1, Hezz, lenci, nacho, pavv+ |
|           19 |     2790 | 2024-11-24 | América eSports          | L   | 0.545      | -            | -                | -                | -         |    -9.51 | dott1, Hezz, lenci, pavv+, rzk   |
|           18 |     2794 | 2024-11-24 | Patins da Ferrari        | L   | 0.545      | -            | -                | -                | -         |   -11.35 | dott1, Hezz, lenci, pavv+, rzk   |
|           17 |     2841 | 2024-11-23 | PURPLE RAIN              | W   | 0.539      | -            | -                | -                | 0 (0.000) |     5.30 | dott1, Hezz, lenci, pavv+, rzk   |
|           16 |     2860 | 2024-11-23 | WiSe.Black               | W   | 0.538      | -            | -                | -                | -         |     3.48 | dott1, Hezz, lenci, pavv+, rzk   |
|           15 |     2991 | 2024-11-22 | BESTIA Academy           | W   | 0.531      | -            | -                | -                | -         |     3.29 | dott1, Hezz, lenci, pavv+, rzk   |
|           14 |     3118 | 2024-11-20 | Floripa Stars            | L   | 0.518      | -            | -                | -                | -         |    -7.82 | dott1, Hezz, lenci, pavv+, rzk   |
|           13 |     3191 | 2024-11-18 | ShindeN                  | L   | 0.506      | -            | -                | -                | -         |    -6.26 | dott1, Hezz, lenci, pavv+, rzk   |
|           12 |     3828 | 2024-11-07 | PaiN Gaming Academy      | L   | 0.433      | -            | -                | -                | -         |    -9.72 | dott1, Hezz, lenci, pavv+, rzk   |
|           11 |     4046 | 2024-11-03 | 9z Academy               | L   | 0.406      | -            | -                | -                | -         |    -6.25 | dott1, Hezz, lenci, pavv+, rzk   |
|           10 |     4214 | 2024-11-01 | BeBold.gg                | W   | 0.391      | 0.371        | 0.000 (0.000)    | -                | -         |     4.14 | dott1, Hezz, lenci, pavv+, rzk   |
|            9 |     4332 | 2024-10-30 | Yawara E-Sports          | L   | 0.378      | -            | -                | -                | -         |    -5.42 | dott1, Hezz, lenci, pavv+, rzk   |
|            8 |     4393 | 2024-10-29 | VELOX Argentina          | L   | 0.371      | -            | -                | -                | -         |    -8.03 | dott1, Hezz, lenci, pavv+, rzk   |
|            7 |     5259 | 2024-10-11 | ShindeN                  | L   | 0.254      | -            | -                | -                | -         |    -3.51 | dott1, Hezz, lenci, pavv+, rzk   |
|            6 |     5954 | 2024-09-29 | Dusty Roots              | W   | 0.173      | 0.143        | 0.009 (0.000)    | 0.366 (0.009)    | -         |     3.59 | dott1, Hezz, lenci, pavv+, rzk   |
|            5 |     6011 | 2024-09-28 | VELOX Argentina          | W   | 0.166      | 0.143        | -                | 0.262 (0.006)    | -         |     1.55 | dott1, Hezz, lenci, pavv+, rzk   |
|            4 |     6026 | 2024-09-28 | BESTIA Academy           | W   | 0.165      | -            | -                | -                | -         |     0.92 | dott1, Hezz, lenci, pavv+, rzk   |
|            3 |     6508 | 2024-09-22 | ShindeN                  | L   | 0.127      | -            | -                | -                | -         |    -1.73 | dott1, Hezz, lenci, pavv+, rzk   |
|            2 |     6511 | 2024-09-22 | Romanos                  | W   | 0.125      | -            | -                | -                | -         |     0.99 | dott1, Hezz, lenci, pavv+, rzk   |
|            1 |     6566 | 2024-09-21 | BOSKIANS                 | W   | 0.119      | -            | -                | -                | -         |     0.67 | dott1, Hezz, lenci, pavv+, rzk   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($910.88)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-11 |      0.254 | $3,590.65      | $910.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
