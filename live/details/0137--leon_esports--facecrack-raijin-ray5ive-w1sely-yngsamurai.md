### Roster Details<br />
Team Name: LEON Esports<br />
Roster: facecrack, Raijin, RaY5ive, w1sely, yngsamurai<br />
Global Rank: [137](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  775.3<br />
<br />
Final Rank Value (775.3) = Starting Rank Value (775.2) + Head To Head Adjustments (0.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.268[<sup>2</sup>](#table1)
- Opponent Network: 0.069[<sup>2</sup>](#table1)
- LAN Wins: 0.080[<sup>2</sup>](#table1)

The average of these factors is 0.188<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.2
- 400 + ( ( 0.188 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 775.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |     1630 | 2024-12-15 | Chimera Esports                | L   | 0.692      | -            | -                | -                | -         |    -5.95 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           27 |     1703 | 2024-12-14 | K27                            | W   | 0.686      | 0.143        | 0.008 (0.001)    | 0.776 (0.076)    | 1 (0.686) |    13.32 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           26 |     1727 | 2024-12-13 | FORZE Reload                   | L   | 0.684      | -            | -                | -                | -         |    -7.43 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           25 |     1766 | 2024-12-13 | WOPA Esport                    | W   | 0.680      | 0.333        | 0.031 (0.007)    | 0.785 (0.178)    | 0 (0.000) |    13.20 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           24 |     1786 | 2024-12-13 | FORZE Reload                   | L   | 0.680      | -            | -                | -                | -         |    -7.07 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           23 |     1983 | 2024-12-08 | PCIFIC Espor                   | L   | 0.647      | -            | -                | -                | -         |   -11.31 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           22 |     2132 | 2024-12-06 | Chimera Esports                | L   | 0.632      | -            | -                | -                | -         |    -7.06 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           21 |     2208 | 2024-12-04 | WOPA Esport                    | W   | 0.620      | 0.333        | 0.031 (0.006)    | 0.785 (0.162)    | 0 (0.000) |    11.39 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           20 |     2342 | 2024-12-02 | SINNERS Academy                | W   | 0.606      | 0.333        | 0.001 (0.000)    | 0.102 (0.021)    | 0 (0.000) |     8.38 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           19 |     2526 | 2024-11-30 | Maestro Esports (Belgian team) | W   | 0.593      | 0.333        | 0.000 (0.000)    | 0.100 (0.020)    | 0 (0.000) |     3.61 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           18 |     2639 | 2024-11-28 | VP.Prodigy                     | W   | 0.579      | 0.333        | 0.000 (0.000)    | 0.206 (0.040)    | 0 (0.000) |     3.18 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           17 |     2854 | 2024-11-23 | FLuffy Gangsters               | L   | 0.547      | -            | -                | -                | -         |    -6.89 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           16 |     2909 | 2024-11-23 | FLuffy Gangsters               | W   | 0.544      | 0.143        | 0.014 (0.001)    | 0.925 (0.072)    | 0 (0.000) |    10.55 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           15 |     3248 | 2024-11-17 | XP Academy                     | W   | 0.505      | -            | -                | -                | 0 (0.000) |     4.76 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           14 |     3261 | 2024-11-17 | RUSH B (Russian team)          | W   | 0.505      | 0.143        | 0.028 (0.002)    | 0.921 (0.066)    | 0 (0.000) |    11.07 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           13 |     3276 | 2024-11-17 | INDINDA                        | L   | 0.504      | -            | -                | -                | -         |   -12.42 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           12 |     4257 | 2024-10-31 | ARCRED                         | L   | 0.392      | -            | -                | -                | -         |    -5.83 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           11 |     4650 | 2024-10-23 | QUAZAR                         | L   | 0.340      | -            | -                | -                | -         |    -5.94 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           10 |     4765 | 2024-10-20 | ENJOY (Russian team)           | L   | 0.320      | -            | -                | -                | -         |    -8.29 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            9 |     4805 | 2024-10-20 | ПuBo3aBpbI                     | W   | 0.318      | -            | -                | -                | 0 (0.000) |     1.14 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            8 |     4808 | 2024-10-20 | Donstu Esports                 | W   | 0.318      | -            | -                | -                | -         |     1.75 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            7 |     5199 | 2024-10-12 | NOTTODAY                       | L   | 0.266      | -            | -                | -                | -         |    -5.98 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            6 |     5212 | 2024-10-12 | Nuclear TigeRES                | W   | 0.265      | 0.215        | 0.004 (0.000)    | 0.586 (0.033)    | -         |     4.80 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            5 |     5224 | 2024-10-12 | Dragon Esports Club            | W   | 0.265      | 0.215        | 0.007 (0.000)    | 0.312 (0.018)    | -         |     3.24 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            4 |     5904 | 2024-09-30 | Ex-ESC Gaming                  | L   | 0.187      | -            | -                | -                | -         |    -3.89 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            3 |     7018 | 2024-09-14 | EC BANGA                       | L   | 0.078      | -            | -                | -                | -         |    -2.04 | Chill, facecrack, Raijin, w1sely, znxxX        |
|            2 |     7647 | 2024-09-04 | Devils.one                     | L   | 0.013      | -            | -                | -                | -         |    -0.28 | eightz, facecrack, JIaYm, Raijin, w1sely       |
|            1 |     7662 | 2024-09-04 | T0X1CandCR1T1C                 | W   | 0.013      | -            | -                | -                | -         |     0.04 | eightz, facecrack, JIaYm, Raijin, w1sely       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,498.27)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.693 | $1,936.87      | $1,341.91       |
| 2024-12-15 |      0.692 | $2,200.00      | $1,522.89       |
| 2024-11-03 |      0.413 | $1,532.61      | $633.48         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
