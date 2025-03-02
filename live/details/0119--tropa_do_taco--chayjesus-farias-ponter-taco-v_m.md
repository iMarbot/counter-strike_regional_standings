### Roster Details<br />
Team Name: TROPA DO TACO<br />
Roster: chayJESUS, farias, ponter, TACO, v$m<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
<br />
Final Rank Value:  800.5<br />
<br />
Final Rank Value (800.5) = Starting Rank Value (700.0) + Head To Head Adjustments (100.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.063[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.0
- 400 + ( ( 0.150 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 700.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |     1665 | 2024-12-14 | Bounty Hunters Esports   | W   | 0.688      | 0.143        | 0.005 (0.000)    | 0.524 (0.051)    | 0 (0.000) |     8.87 | chayJESUS, farias, ponter, TACO, v$m |
|           23 |     1756 | 2024-12-13 | Game Hunters             | W   | 0.681      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     8.80 | chayJESUS, farias, ponter, TACO, v$m |
|           22 |     1862 | 2024-12-11 | Bounty Hunters Esports   | W   | 0.668      | 0.143        | 0.005 (0.000)    | 0.524 (0.050)    | 0 (0.000) |     8.83 | chayJESUS, farias, ponter, TACO, v$m |
|           21 |     1907 | 2024-12-10 | Floripa Stars            | W   | 0.661      | -            | -                | -                | 0 (0.000) |     6.32 | chayJESUS, farias, ponter, TACO, v$m |
|           20 |     2062 | 2024-12-07 | Yawara E-Sports          | L   | 0.640      | -            | -                | -                | -         |   -11.86 | chayJESUS, farias, ponter, TACO, v$m |
|           19 |     2155 | 2024-12-05 | DB Peek Esports          | W   | 0.627      | 0.262        | -                | 0.240 (0.039)    | 0 (0.000) |     5.71 | chayJESUS, farias, ponter, TACO, v$m |
|           18 |     2194 | 2024-12-04 | ShindeN                  | W   | 0.622      | 0.262        | 0.005 (0.001)    | 0.310 (0.050)    | 0 (0.000) |     7.75 | chayJESUS, farias, ponter, TACO, v$m |
|           17 |     2247 | 2024-12-03 | Floripa Stars Academy    | W   | 0.615      | -            | -                | -                | 0 (0.000) |     3.28 | chayJESUS, farias, ponter, TACO, v$m |
|           16 |     2502 | 2024-11-30 | Game Hunters             | L   | 0.593      | -            | -                | -                | -         |   -10.55 | chayJESUS, farias, ponter, TACO, v$m |
|           15 |     2574 | 2024-11-29 | Fluxo                    | L   | 0.587      | -            | -                | -                | -         |    -4.41 | chayJESUS, farias, ponter, TACO, v$m |
|           14 |     2673 | 2024-11-27 | Bad News Chickens        | W   | 0.572      | 0.371        | 0.003 (0.001)    | 0.239 (0.051)    | 0 (0.000) |     6.66 | chayJESUS, farias, ponter, TACO, v$m |
|           13 |     2827 | 2024-11-23 | Game Hunters             | W   | 0.547      | -            | -                | -                | 0 (0.000) |     3.45 | chayJESUS, farias, ponter, TACO, v$m |
|           12 |     3005 | 2024-11-21 | Players (Brazilian team) | W   | 0.534      | 0.371        | 0.008 (0.002)    | 0.637 (0.126)    | 0 (0.000) |     8.12 | chayJESUS, farias, ponter, TACO, v$m |
|           11 |     3178 | 2024-11-18 | 9z Academy               | W   | 0.515      | 0.371        | -                | 0.388 (0.074)    | -         |     6.48 | chayJESUS, farias, ponter, TACO, v$m |
|           10 |     3222 | 2024-11-17 | Bad News Chickens        | W   | 0.508      | -            | -                | -                | -         |     6.59 | chayJESUS, farias, ponter, TACO, v$m |
|            9 |     3533 | 2024-11-12 | Yawara E-Sports          | W   | 0.474      | -            | -                | -                | -         |     7.10 | chayJESUS, farias, ponter, TACO, v$m |
|            8 |     3643 | 2024-11-10 | Intense Game             | W   | 0.460      | -            | -                | -                | -         |     6.24 | chayJESUS, farias, ponter, TACO, v$m |
|            7 |     3773 | 2024-11-08 | Fluxo                    | L   | 0.448      | -            | -                | -                | -         |    -3.30 | farias, n1ssim, ponter, TACO, v$m    |
|            6 |     3819 | 2024-11-07 | Intense Game             | W   | 0.441      | 0.371        | 0.003 (0.000)    | -                | -         |     6.15 | farias, n1ssim, ponter, TACO, v$m    |
|            5 |     4096 | 2024-11-02 | UNO MILLE                | W   | 0.408      | 0.371        | 0.010 (0.002)    | 0.526 (0.080)    | -         |     6.67 | farias, n1ssim, ponter, TACO, v$m    |
|            4 |     4182 | 2024-11-01 | Players (Brazilian team) | W   | 0.400      | 0.143        | 0.008 (0.000)    | -                | -         |     6.72 | chayJESUS, farias, ponter, TACO, v$m |
|            3 |     4234 | 2024-10-31 | ShindeN                  | W   | 0.394      | 0.371        | 0.005 (0.001)    | 0.310 (0.045)    | -         |     6.54 | farias, n1ssim, ponter, TACO, v$m    |
|            2 |     4356 | 2024-10-29 | MIBR Academy             | W   | 0.380      | 0.371        | -                | 0.470 (0.066)    | -         |     5.70 | farias, n1ssim, ponter, TACO, v$m    |
|            1 |     4416 | 2024-10-28 | América eSports          | W   | 0.374      | -            | -                | -                | -         |     4.58 | chayJESUS, farias, ponter, TACO, v$m |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,400.28)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-30 |      0.595 | $750.00        | $445.99         |
| 2024-11-17 |      0.508 | $1,207.53      | $613.16         |
| 2024-11-09 |      0.455 | $750.00        | $341.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
