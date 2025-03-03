### Roster Details<br />
Team Name: G2 Ares<br />
Roster: fNk, hitori, ketsuo, kl1m, tAk<br />
Global Rank: [255](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [175]( ../standings_europe.md)<br />
<br />
Final Rank Value:  676.5<br />
<br />
Final Rank Value (676.5) = Starting Rank Value (680.3) + Head To Head Adjustments (-3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.240[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 680.3
- 400 + ( ( 0.140 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 680.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |     1601 | 2024-12-16 | BC.Game Esports                           | L   | 0.691      | -            | -                | -                | -         |    -5.45 | fNk, hitori, ketsuo, kl1m, tAk |
|           36 |     1628 | 2024-12-15 | ALASKA                                    | L   | 0.685      | -            | -                | -                | -         |    -4.26 | fNk, hitori, ketsuo, kl1m, tAk |
|           35 |     1684 | 2024-12-14 | FORZE Reload                              | L   | 0.679      | -            | -                | -                | -         |    -5.20 | fNk, hitori, ketsuo, kl1m, tAk |
|           34 |     1714 | 2024-12-14 | ESC Gaming                                | W   | 0.678      | 0.333        | -                | 0.226 (0.051)    | 0 (0.000) |     6.80 | fNk, hitori, ketsuo, kl1m, tAk |
|           33 |     1773 | 2024-12-13 | Wu-Tang Clan                              | L   | 0.672      | -            | -                | -                | -         |   -11.49 | fNk, hitori, ketsuo, kl1m, tAk |
|           32 |     1852 | 2024-12-12 | Monte                                     | L   | 0.664      | -            | -                | -                | -         |    -4.06 | fNk, hitori, ketsuo, kl1m, tAk |
|           31 |     1938 | 2024-12-10 | Viperio                                   | L   | 0.651      | -            | -                | -                | -         |    -9.50 | fNk, hitori, ketsuo, kl1m, tAk |
|           30 |     1955 | 2024-12-09 | Illuminar Gaming                          | W   | 0.646      | 0.333        | 0.007 (0.001)    | 0.581 (0.125)    | 0 (0.000) |    13.30 | fNk, hitori, ketsuo, kl1m, tAk |
|           29 |     2139 | 2024-12-06 | AMKAL ESPORTS                             | L   | 0.625      | -            | -                | -                | -         |    -7.15 | fNk, hitori, ketsuo, kl1m, tAk |
|           28 |     2223 | 2024-12-04 | XGOD ARENA                                | W   | 0.612      | 0.274        | 0.000 (0.000)    | -                | 0 (0.000) |     6.83 | fNk, hitori, ketsuo, kl1m, tAk |
|           27 |     2608 | 2024-11-29 | Monte                                     | L   | 0.577      | -            | -                | -                | -         |    -4.40 | fNk, hitori, ketsuo, kl1m, tAk |
|           26 |     2661 | 2024-11-28 | RUSTEC                                    | W   | 0.570      | 0.333        | -                | 0.216 (0.041)    | 0 (0.000) |     6.04 | fNk, hitori, ketsuo, kl1m, tAk |
|           25 |     2764 | 2024-11-25 | 777 Esports                               | W   | 0.551      | 0.333        | 0.002 (0.000)    | 0.235 (0.043)    | 0 (0.000) |     7.76 | fNk, hitori, ketsuo, kl1m, tAk |
|           24 |     2806 | 2024-11-24 | BC.Game Esports                           | L   | 0.544      | -            | -                | -                | -         |    -5.29 | fNk, hitori, ketsuo, kl1m, tAk |
|           23 |     3054 | 2024-11-21 | JANO Esports                              | L   | 0.524      | -            | -                | -                | -         |    -3.72 | fNk, hitori, ketsuo, kl1m, tAk |
|           22 |     3071 | 2024-11-21 | GenOne                                    | L   | 0.523      | -            | -                | -                | -         |    -4.99 | fNk, hitori, ketsuo, kl1m, tAk |
|           21 |     3319 | 2024-11-16 | FLuffy Gangsters                          | L   | 0.492      | -            | -                | -                | -         |    -5.39 | fNk, hitori, ketsuo, kl1m, tAk |
|           20 |     3365 | 2024-11-16 | WOPA Esport                               | W   | 0.489      | 0.333        | 0.032 (0.005)    | 0.777 (0.127)    | 0 (0.000) |    10.50 | fNk, hitori, ketsuo, kl1m, tAk |
|           19 |     3463 | 2024-11-14 | WOPA Esport                               | W   | 0.478      | 0.143        | 0.032 (0.002)    | 0.777 (0.053)    | 0 (0.000) |    10.63 | fNk, hitori, ketsuo, kl1m, tAk |
|           18 |     3526 | 2024-11-13 | Daystar                                   | W   | 0.470      | 0.143        | -                | 0.131 (0.009)    | 0 (0.000) |     6.23 | fNk, hitori, ketsuo, kl1m, tAk |
|           17 |     3558 | 2024-11-12 | BRUTE                                     | L   | 0.464      | -            | -                | -                | -         |    -6.82 | fNk, hitori, ketsuo, kl1m, tAk |
|           16 |     3568 | 2024-11-12 | Tricked Esport                            | L   | 0.463      | -            | -                | -                | -         |    -4.05 | fNk, hitori, ketsuo, kl1m, tAk |
|           15 |     3735 | 2024-11-09 | Lazer Cats                                | L   | 0.444      | -            | -                | -                | -         |    -6.20 | fNk, hitori, ketsuo, kl1m, tAk |
|           14 |     3960 | 2024-11-05 | BRUTE                                     | W   | 0.418      | 0.278        | 0.004 (0.000)    | 0.341 (0.040)    | 0 (0.000) |     6.94 | fNk, hitori, ketsuo, kl1m, tAk |
|           13 |     5534 | 2024-10-06 | TSM                                       | L   | 0.217      | -            | -                | -                | -         |    -2.80 | fNk, hitori, kl1m, tAk, xezr   |
|           12 |     5701 | 2024-10-04 | Los kogutos                               | W   | 0.202      | 0.435        | 0.032 (0.003)    | 0.515 (0.045)    | 0 (0.000) |     5.35 | fNk, hitori, kl1m, tAk, xezr   |
|           11 |     5774 | 2024-10-02 | TEAM NEXT LEVEL                           | L   | 0.192      | -            | -                | -                | -         |    -1.72 | fNk, hitori, kl1m, tAk, xezr   |
|           10 |     5802 | 2024-10-02 | CYBERSHOKE Esports                        | L   | 0.190      | -            | -                | -                | -         |    -1.71 | fNk, hitori, kl1m, tAk, xezr   |
|            9 |     5857 | 2024-10-01 | Metizport                                 | L   | 0.185      | -            | -                | -                | -         |    -0.57 | fNk, hitori, kl1m, tAk, xezr   |
|            8 |     5899 | 2024-09-30 | GameAgents                                | L   | 0.179      | -            | -                | -                | -         |    -3.49 | fNk, hitori, kl1m, tAk, xezr   |
|            7 |     5905 | 2024-09-30 | NOTTODAY                                  | W   | 0.179      | -            | -                | -                | -         |     2.12 | fNk, hitori, kl1m, tAk, xezr   |
|            6 |     5913 | 2024-09-30 | NewBALLS                                  | W   | 0.178      | 0.143        | 0.001 (0.000)    | -                | -         |     2.61 | fNk, hitori, kl1m, tAk, xezr   |
|            5 |     5968 | 2024-09-29 | Copenhagen Wolves (American organization) | W   | 0.171      | -            | -                | -                | -         |     1.76 | fNk, hitori, kl1m, tAk, xezr   |
|            4 |     6138 | 2024-09-27 | Nexus Gaming                              | W   | 0.158      | 0.143        | 0.187 (0.004)    | 0.795 (0.018)    | -         |     4.67 | fNk, hitori, kl1m, tAk, xezr   |
|            3 |     6225 | 2024-09-26 | EYEBALLERS                                | W   | 0.150      | 0.143        | 0.019 (0.000)    | -                | -         |     3.15 | fNk, hitori, kl1m, tAk, xezr   |
|            2 |     7527 | 2024-09-06 | Preasy Esport                             | L   | 0.018      | -            | -                | -                | -         |    -0.18 | d0jca, fNk, hitori, tAk, xezr  |
|            1 |     7680 | 2024-09-04 | Young Ninjas                              | L   | 0.005      | -            | -                | -                | -         |    -0.11 | d0jca, fNk, hitori, tAk, xezr  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($222.83)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.686 | $325.00        | $222.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
