### Roster Details<br />
Team Name: TROPA DO TACO<br />
Roster: chayJESUS, farias, ponter, TACO, v$m<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [24]( ../standings_americas.md)<br />
<br />
Final Rank Value:  798.5<br />
<br />
Final Rank Value (798.5) = Starting Rank Value (699.6) + Head To Head Adjustments (98.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.6
- 400 + ( ( 0.150 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 699.6


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
|           24 |     1677 | 2024-12-14 | Bounty Hunters Esports   | W   | 0.680      | 0.143        | 0.005 (0.000)    | 0.523 (0.051)    | 0 (0.000) |     8.81 | chayJESUS, farias, ponter, TACO, v$m |
|           23 |     1768 | 2024-12-13 | Game Hunters             | W   | 0.673      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     8.72 | chayJESUS, farias, ponter, TACO, v$m |
|           22 |     1874 | 2024-12-11 | Bounty Hunters Esports   | W   | 0.660      | 0.143        | 0.005 (0.000)    | 0.523 (0.049)    | 0 (0.000) |     8.77 | chayJESUS, farias, ponter, TACO, v$m |
|           21 |     1919 | 2024-12-10 | Floripa Stars            | W   | 0.653      | -            | -                | -                | 0 (0.000) |     6.25 | chayJESUS, farias, ponter, TACO, v$m |
|           20 |     2074 | 2024-12-07 | Yawara E-Sports          | L   | 0.632      | -            | -                | -                | -         |   -11.71 | chayJESUS, farias, ponter, TACO, v$m |
|           19 |     2167 | 2024-12-05 | DB Peek Esports          | W   | 0.619      | 0.262        | -                | 0.236 (0.038)    | 0 (0.000) |     5.65 | chayJESUS, farias, ponter, TACO, v$m |
|           18 |     2206 | 2024-12-04 | ShindeN                  | W   | 0.613      | 0.262        | 0.005 (0.001)    | 0.308 (0.049)    | 0 (0.000) |     7.58 | chayJESUS, farias, ponter, TACO, v$m |
|           17 |     2259 | 2024-12-03 | Floripa Stars Academy    | W   | 0.607      | -            | -                | -                | 0 (0.000) |     3.26 | chayJESUS, farias, ponter, TACO, v$m |
|           16 |     2514 | 2024-11-30 | Game Hunters             | L   | 0.585      | -            | -                | -                | -         |   -10.38 | chayJESUS, farias, ponter, TACO, v$m |
|           15 |     2586 | 2024-11-29 | Fluxo                    | L   | 0.579      | -            | -                | -                | -         |    -4.37 | chayJESUS, farias, ponter, TACO, v$m |
|           14 |     2685 | 2024-11-27 | Bad News Chickens        | W   | 0.564      | 0.371        | 0.002 (0.001)    | 0.234 (0.049)    | 0 (0.000) |     6.58 | chayJESUS, farias, ponter, TACO, v$m |
|           13 |     2839 | 2024-11-23 | Game Hunters             | W   | 0.539      | -            | -                | -                | 0 (0.000) |     3.39 | chayJESUS, farias, ponter, TACO, v$m |
|           12 |     3017 | 2024-11-21 | Players (Brazilian team) | W   | 0.526      | 0.371        | 0.008 (0.002)    | 0.632 (0.123)    | 0 (0.000) |     8.00 | chayJESUS, farias, ponter, TACO, v$m |
|           11 |     3190 | 2024-11-18 | 9z Academy               | W   | 0.507      | 0.371        | -                | 0.384 (0.072)    | -         |     6.39 | chayJESUS, farias, ponter, TACO, v$m |
|           10 |     3234 | 2024-11-17 | Bad News Chickens        | W   | 0.500      | -            | -                | -                | -         |     6.48 | chayJESUS, farias, ponter, TACO, v$m |
|            9 |     3545 | 2024-11-12 | Yawara E-Sports          | W   | 0.465      | -            | -                | -                | -         |     6.97 | chayJESUS, farias, ponter, TACO, v$m |
|            8 |     3655 | 2024-11-10 | Intense Game             | W   | 0.452      | -            | -                | -                | -         |     6.14 | chayJESUS, farias, ponter, TACO, v$m |
|            7 |     3785 | 2024-11-08 | Fluxo                    | L   | 0.440      | -            | -                | -                | -         |    -3.26 | farias, n1ssim, ponter, TACO, v$m    |
|            6 |     3831 | 2024-11-07 | Intense Game             | W   | 0.433      | 0.371        | 0.003 (0.000)    | -                | -         |     6.04 | farias, n1ssim, ponter, TACO, v$m    |
|            5 |     4108 | 2024-11-02 | UNO MILLE                | W   | 0.400      | 0.371        | 0.010 (0.002)    | 0.522 (0.077)    | -         |     6.53 | farias, n1ssim, ponter, TACO, v$m    |
|            4 |     4194 | 2024-11-01 | Players (Brazilian team) | W   | 0.392      | 0.143        | 0.008 (0.000)    | -                | -         |     6.60 | chayJESUS, farias, ponter, TACO, v$m |
|            3 |     4246 | 2024-10-31 | ShindeN                  | W   | 0.386      | 0.371        | 0.005 (0.001)    | 0.308 (0.044)    | -         |     6.39 | farias, n1ssim, ponter, TACO, v$m    |
|            2 |     4368 | 2024-10-29 | MIBR Academy             | W   | 0.372      | 0.371        | -                | 0.464 (0.064)    | -         |     5.57 | farias, n1ssim, ponter, TACO, v$m    |
|            1 |     4428 | 2024-10-28 | América eSports          | W   | 0.365      | -            | -                | -                | -         |     4.48 | chayJESUS, farias, ponter, TACO, v$m |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,378.09)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-30 |      0.586 | $750.00        | $439.84         |
| 2024-11-17 |      0.500 | $1,207.53      | $603.26         |
| 2024-11-09 |      0.447 | $750.00        | $334.98         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
