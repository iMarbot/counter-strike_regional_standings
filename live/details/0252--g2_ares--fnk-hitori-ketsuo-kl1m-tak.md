### Roster Details<br />
Team Name: G2 Ares<br />
Roster: fNk, hitori, ketsuo, kl1m, tAk<br />
Global Rank: [252](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [176]( ../standings_europe.md)<br />
<br />
Final Rank Value:  677.4<br />
<br />
Final Rank Value (677.4) = Starting Rank Value (681.1) + Head To Head Adjustments (-3.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.240[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.057[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.1
- 400 + ( ( 0.141 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 681.1


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
|           38 |     1589 | 2024-12-16 | BC.Game Esports                           | L   | 0.699      | -            | -                | -                | -         |    -5.50 | fNk, hitori, ketsuo, kl1m, tAk |
|           37 |     1616 | 2024-12-15 | ALASKA                                    | L   | 0.694      | -            | -                | -                | -         |    -4.39 | fNk, hitori, ketsuo, kl1m, tAk |
|           36 |     1672 | 2024-12-14 | FORZE Reload                              | L   | 0.687      | -            | -                | -                | -         |    -5.25 | fNk, hitori, ketsuo, kl1m, tAk |
|           35 |     1702 | 2024-12-14 | ESC Gaming                                | W   | 0.686      | 0.333        | -                | 0.227 (0.052)    | 0 (0.000) |     6.86 | fNk, hitori, ketsuo, kl1m, tAk |
|           34 |     1761 | 2024-12-13 | Wu-Tang Clan                              | L   | 0.681      | -            | -                | -                | -         |   -11.66 | fNk, hitori, ketsuo, kl1m, tAk |
|           33 |     1840 | 2024-12-12 | Monte                                     | L   | 0.672      | -            | -                | -                | -         |    -4.08 | fNk, hitori, ketsuo, kl1m, tAk |
|           32 |     1926 | 2024-12-10 | Viperio                                   | L   | 0.659      | -            | -                | -                | -         |    -9.59 | fNk, hitori, ketsuo, kl1m, tAk |
|           31 |     1943 | 2024-12-09 | Illuminar Gaming                          | W   | 0.654      | 0.333        | 0.007 (0.001)    | 0.593 (0.129)    | 0 (0.000) |    13.46 | fNk, hitori, ketsuo, kl1m, tAk |
|           30 |     2127 | 2024-12-06 | AMKAL ESPORTS                             | L   | 0.633      | -            | -                | -                | -         |    -7.23 | fNk, hitori, ketsuo, kl1m, tAk |
|           29 |     2211 | 2024-12-04 | XGOD ARENA                                | W   | 0.620      | 0.274        | 0.000 (0.000)    | -                | 0 (0.000) |     6.88 | fNk, hitori, ketsuo, kl1m, tAk |
|           28 |     2596 | 2024-11-29 | Monte                                     | L   | 0.585      | -            | -                | -                | -         |    -4.44 | fNk, hitori, ketsuo, kl1m, tAk |
|           27 |     2649 | 2024-11-28 | RUSTEC                                    | W   | 0.578      | 0.333        | -                | 0.217 (0.042)    | 0 (0.000) |     6.13 | fNk, hitori, ketsuo, kl1m, tAk |
|           26 |     2752 | 2024-11-25 | 777 Esports                               | W   | 0.560      | 0.333        | 0.002 (0.000)    | 0.239 (0.045)    | 0 (0.000) |     7.90 | fNk, hitori, ketsuo, kl1m, tAk |
|           25 |     2794 | 2024-11-24 | BC.Game Esports                           | L   | 0.552      | -            | -                | -                | -         |    -5.37 | fNk, hitori, ketsuo, kl1m, tAk |
|           24 |     3042 | 2024-11-21 | JANO Esports                              | L   | 0.532      | -            | -                | -                | -         |    -3.80 | fNk, hitori, ketsuo, kl1m, tAk |
|           23 |     3059 | 2024-11-21 | GenOne                                    | L   | 0.531      | -            | -                | -                | -         |    -5.05 | fNk, hitori, ketsuo, kl1m, tAk |
|           22 |     3307 | 2024-11-16 | FLuffy Gangsters                          | L   | 0.500      | -            | -                | -                | -         |    -5.46 | fNk, hitori, ketsuo, kl1m, tAk |
|           21 |     3353 | 2024-11-16 | WOPA Esport                               | W   | 0.497      | 0.333        | 0.031 (0.005)    | 0.785 (0.130)    | 0 (0.000) |    10.67 | fNk, hitori, ketsuo, kl1m, tAk |
|           20 |     3451 | 2024-11-14 | WOPA Esport                               | W   | 0.486      | 0.143        | 0.031 (0.002)    | 0.785 (0.055)    | 0 (0.000) |    10.81 | fNk, hitori, ketsuo, kl1m, tAk |
|           19 |     3514 | 2024-11-13 | Daystar                                   | W   | 0.478      | 0.143        | -                | 0.135 (0.009)    | 0 (0.000) |     6.36 | fNk, hitori, ketsuo, kl1m, tAk |
|           18 |     3546 | 2024-11-12 | BRUTE                                     | L   | 0.472      | -            | -                | -                | -         |    -6.96 | fNk, hitori, ketsuo, kl1m, tAk |
|           17 |     3556 | 2024-11-12 | Tricked Esport                            | L   | 0.472      | -            | -                | -                | -         |    -4.11 | fNk, hitori, ketsuo, kl1m, tAk |
|           16 |     3723 | 2024-11-09 | Lazer Cats                                | L   | 0.453      | -            | -                | -                | -         |    -6.30 | fNk, hitori, ketsuo, kl1m, tAk |
|           15 |     3948 | 2024-11-05 | BRUTE                                     | W   | 0.426      | 0.278        | 0.004 (0.000)    | 0.345 (0.041)    | 0 (0.000) |     7.06 | fNk, hitori, ketsuo, kl1m, tAk |
|           14 |     5522 | 2024-10-06 | TSM                                       | L   | 0.226      | -            | -                | -                | -         |    -2.89 | fNk, hitori, kl1m, tAk, xezr   |
|           13 |     5689 | 2024-10-04 | Los kogutos                               | W   | 0.210      | 0.435        | 0.032 (0.003)    | 0.527 (0.048)    | 0 (0.000) |     5.58 | fNk, hitori, kl1m, tAk, xezr   |
|           12 |     5762 | 2024-10-02 | TEAM NEXT LEVEL                           | L   | 0.200      | -            | -                | -                | -         |    -1.79 | fNk, hitori, kl1m, tAk, xezr   |
|           11 |     5790 | 2024-10-02 | CYBERSHOKE Esports                        | L   | 0.198      | -            | -                | -                | -         |    -1.79 | fNk, hitori, kl1m, tAk, xezr   |
|           10 |     5845 | 2024-10-01 | Metizport                                 | L   | 0.193      | -            | -                | -                | -         |    -0.59 | fNk, hitori, kl1m, tAk, xezr   |
|            9 |     5887 | 2024-09-30 | GameAgents                                | L   | 0.188      | -            | -                | -                | -         |    -3.64 | fNk, hitori, kl1m, tAk, xezr   |
|            8 |     5893 | 2024-09-30 | NOTTODAY                                  | W   | 0.187      | -            | -                | -                | -         |     2.21 | fNk, hitori, kl1m, tAk, xezr   |
|            7 |     5901 | 2024-09-30 | NewBALLS                                  | W   | 0.187      | 0.143        | 0.001 (0.000)    | -                | -         |     2.73 | fNk, hitori, kl1m, tAk, xezr   |
|            6 |     5956 | 2024-09-29 | Copenhagen Wolves (American organization) | W   | 0.179      | -            | -                | -                | -         |     1.87 | fNk, hitori, kl1m, tAk, xezr   |
|            5 |     6126 | 2024-09-27 | Nexus Gaming                              | W   | 0.166      | 0.143        | 0.186 (0.004)    | 0.808 (0.019)    | -         |     4.92 | fNk, hitori, kl1m, tAk, xezr   |
|            4 |     6213 | 2024-09-26 | EYEBALLERS                                | W   | 0.159      | 0.143        | 0.019 (0.000)    | -                | -         |     3.32 | fNk, hitori, kl1m, tAk, xezr   |
|            3 |     7515 | 2024-09-06 | Preasy Esport                             | L   | 0.026      | -            | -                | -                | -         |    -0.27 | d0jca, fNk, hitori, tAk, xezr  |
|            2 |     7668 | 2024-09-04 | Young Ninjas                              | L   | 0.013      | -            | -                | -                | -         |    -0.30 | d0jca, fNk, hitori, tAk, xezr  |
|            1 |     7732 | 2024-09-03 | Revenant Esports                          | W   | 0.006      | -            | -                | -                | -         |     0.05 | d0jca, fNk, hitori, tAk, xezr  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($225.49)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.694 | $325.00        | $225.49         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
