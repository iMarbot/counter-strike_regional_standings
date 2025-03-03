### Roster Details<br />
Team Name: LEON Esports<br />
Roster: facecrack, Raijin, RaY5ive, w1sely, yngsamurai<br />
Global Rank: [139](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  774.8<br />
<br />
Final Rank Value (774.8) = Starting Rank Value (774.6) + Head To Head Adjustments (0.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.067[<sup>2</sup>](#table1)
- LAN Wins: 0.079[<sup>2</sup>](#table1)

The average of these factors is 0.187<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 774.6
- 400 + ( ( 0.187 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 774.6


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
|           28 |     1642 | 2024-12-15 | Chimera Esports                | L   | 0.684      | -            | -                | -                | -         |    -5.94 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           27 |     1715 | 2024-12-14 | K27                            | W   | 0.677      | 0.143        | 0.008 (0.001)    | 0.769 (0.074)    | 1 (0.677) |    13.19 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           26 |     1739 | 2024-12-13 | FORZE Reload                   | L   | 0.675      | -            | -                | -                | -         |    -7.37 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           25 |     1778 | 2024-12-13 | WOPA Esport                    | W   | 0.672      | 0.333        | 0.032 (0.007)    | 0.777 (0.174)    | 0 (0.000) |    13.02 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           24 |     1798 | 2024-12-13 | FORZE Reload                   | L   | 0.671      | -            | -                | -                | -         |    -7.03 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           23 |     1995 | 2024-12-08 | PCIFIC Espor                   | L   | 0.639      | -            | -                | -                | -         |   -11.17 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           22 |     2144 | 2024-12-06 | Chimera Esports                | L   | 0.624      | -            | -                | -                | -         |    -7.02 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           21 |     2220 | 2024-12-04 | WOPA Esport                    | W   | 0.612      | 0.333        | 0.032 (0.006)    | 0.777 (0.158)    | 0 (0.000) |    11.22 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           20 |     2354 | 2024-12-02 | SINNERS Academy                | W   | 0.598      | 0.333        | 0.001 (0.000)    | 0.101 (0.020)    | 0 (0.000) |     8.26 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           19 |     2538 | 2024-11-30 | Maestro Esports (Belgian team) | W   | 0.584      | 0.333        | 0.000 (0.000)    | 0.100 (0.019)    | 0 (0.000) |     3.56 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           18 |     2651 | 2024-11-28 | VP.Prodigy                     | W   | 0.571      | 0.333        | 0.000 (0.000)    | 0.204 (0.039)    | 0 (0.000) |     3.13 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           17 |     2866 | 2024-11-23 | FLuffy Gangsters               | L   | 0.538      | -            | -                | -                | -         |    -6.84 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           16 |     2921 | 2024-11-23 | FLuffy Gangsters               | W   | 0.536      | 0.143        | 0.014 (0.001)    | 0.909 (0.070)    | 0 (0.000) |    10.33 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           15 |     3260 | 2024-11-17 | XP Academy                     | W   | 0.497      | -            | -                | -                | 0 (0.000) |     4.65 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           14 |     3273 | 2024-11-17 | RUSH B (Russian team)          | W   | 0.497      | 0.143        | 0.028 (0.002)    | 0.915 (0.065)    | 0 (0.000) |    10.88 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           13 |     3288 | 2024-11-17 | INDINDA                        | L   | 0.496      | -            | -                | -                | -         |   -12.22 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           12 |     4269 | 2024-10-31 | ARCRED                         | L   | 0.383      | -            | -                | -                | -         |    -5.73 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           11 |     4662 | 2024-10-23 | QUAZAR                         | L   | 0.332      | -            | -                | -                | -         |    -5.82 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           10 |     4777 | 2024-10-20 | ENJOY (Russian team)           | L   | 0.312      | -            | -                | -                | -         |    -8.08 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            9 |     4817 | 2024-10-20 | ПuBo3aBpbI                     | W   | 0.310      | -            | -                | -                | 0 (0.000) |     1.11 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            8 |     4820 | 2024-10-20 | Donstu Esports                 | W   | 0.310      | -            | -                | -                | -         |     1.71 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            7 |     5211 | 2024-10-12 | NOTTODAY                       | L   | 0.257      | -            | -                | -                | -         |    -5.80 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            6 |     5224 | 2024-10-12 | Nuclear TigeRES                | W   | 0.257      | 0.215        | 0.004 (0.000)    | 0.580 (0.032)    | -         |     4.66 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            5 |     5236 | 2024-10-12 | Dragon Esports Club            | W   | 0.257      | 0.215        | 0.007 (0.000)    | 0.309 (0.017)    | -         |     3.14 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            4 |     5916 | 2024-09-30 | Ex-ESC Gaming                  | L   | 0.178      | -            | -                | -                | -         |    -3.72 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            3 |     7030 | 2024-09-14 | EC BANGA                       | L   | 0.070      | -            | -                | -                | -         |    -1.82 | Chill, facecrack, Raijin, w1sely, znxxX        |
|            2 |     7659 | 2024-09-04 | Devils.one                     | L   | 0.005      | -            | -                | -                | -         |    -0.11 | eightz, facecrack, JIaYm, Raijin, w1sely       |
|            1 |     7674 | 2024-09-04 | T0X1CandCR1T1C                 | W   | 0.005      | -            | -                | -                | -         |     0.02 | eightz, facecrack, JIaYm, Raijin, w1sely       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,451.82)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.685 | $1,936.87      | $1,326.04       |
| 2024-12-15 |      0.684 | $2,200.00      | $1,504.86       |
| 2024-11-03 |      0.405 | $1,532.61      | $620.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
