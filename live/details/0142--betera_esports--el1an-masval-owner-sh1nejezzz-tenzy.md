### Roster Details<br />
Team Name: Betera Esports<br />
Roster: El1an, MaSvAl, OWNER, sh1nejezzz, tENZY<br />
Global Rank: [142](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [102]( ../standings_europe.md)<br />
<br />
Final Rank Value:  770.7<br />
<br />
Final Rank Value (770.7) = Starting Rank Value (736.4) + Head To Head Adjustments (34.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.275[<sup>2</sup>](#table1)
- Opponent Network: 0.085[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.168<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.4
- 400 + ( ( 0.168 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 736.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     1544 | 2024-12-19 | Monte             | L   | 0.711      | -            | -                | -                | -         |    -5.92 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           25 |     1605 | 2024-12-16 | Illuminar Gaming  | W   | 0.690      | 0.333        | 0.007 (0.002)    | 0.581 (0.133)    | 0 (0.000) |    12.46 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           24 |     1627 | 2024-12-15 | FAVBET Team       | L   | 0.685      | -            | -                | -                | -         |    -7.55 | El1an, MaSvAl, OWNER, sh1nejezzz, supra    |
|           23 |     1644 | 2024-12-15 | GenOne            | W   | 0.684      | 0.333        | 0.012 (0.003)    | 0.837 (0.191)    | 0 (0.000) |    13.14 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           22 |     1688 | 2024-12-14 | JiJieHao          | W   | 0.679      | 0.143        | -                | 0.254 (0.025)    | 0 (0.000) |     8.32 | El1an, MaSvAl, OWNER, sh1nejezzz, supra    |
|           21 |     1782 | 2024-12-13 | Fire Flux Esports | L   | 0.672      | -            | -                | -                | -         |    -5.87 | El1an, MaSvAl, OWNER, sh1nejezzz, supra    |
|           20 |     1807 | 2024-12-13 | FLuffy Gangsters  | L   | 0.671      | -            | -                | -                | -         |    -8.40 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           19 |     1896 | 2024-12-11 | BC.Game Esports   | W   | 0.657      | 0.333        | 0.022 (0.005)    | 0.551 (0.121)    | 0 (0.000) |    13.48 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           18 |     1956 | 2024-12-09 | JANO Esports      | L   | 0.646      | -            | -                | -                | -         |    -6.85 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           17 |     2352 | 2024-12-02 | FLuffy Gangsters  | L   | 0.598      | -            | -                | -                | -         |    -6.65 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           16 |     2483 | 2024-11-30 | K27               | L   | 0.586      | -            | -                | -                | -         |    -6.70 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           15 |     2509 | 2024-11-30 | RUSTEC            | W   | 0.585      | 0.262        | -                | 0.216 (0.033)    | 0 (0.000) |     4.57 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           14 |     2769 | 2024-11-25 | Monte             | W   | 0.551      | 0.333        | 0.045 (0.008)    | 0.696 (0.128)    | 0 (0.000) |    12.45 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           13 |     2900 | 2024-11-23 | Illuminar Gaming  | W   | 0.537      | -            | -                | -                | 0 (0.000) |     2.06 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           12 |     2973 | 2024-11-22 | GODSENT           | W   | 0.531      | 0.333        | 0.001 (0.000)    | 0.269 (0.048)    | 0 (0.000) |     6.85 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           11 |     3670 | 2024-11-10 | Monte             | L   | 0.452      | -            | -                | -                | -         |    -3.90 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           10 |     3724 | 2024-11-09 | Leo Team          | W   | 0.445      | 0.354        | 0.026 (0.004)    | 0.748 (0.118)    | 0 (0.000) |     8.95 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|            9 |     3805 | 2024-11-08 | PCIFIC Espor      | W   | 0.438      | 0.354        | 0.004 (0.001)    | 0.251 (0.039)    | 0 (0.000) |     7.59 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|            8 |     5218 | 2024-10-12 | NOTTODAY          | L   | 0.257      | -            | -                | -                | -         |    -5.47 | El1an, MaSvAl, OWNER, Polt, sh1nejezzz     |
|            7 |     5238 | 2024-10-12 | Poslednii3ae3d    | W   | 0.257      | -            | -                | -                | -         |     3.04 | El1an, MaSvAl, OWNER, Polt, sh1nejezzz     |
|            6 |     5776 | 2024-10-02 | GameAgents        | L   | 0.192      | -            | -                | -                | -         |    -3.24 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |
|            5 |     6020 | 2024-09-28 | Fire Flux Esports | L   | 0.165      | -            | -                | -                | -         |    -1.76 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |
|            4 |     6043 | 2024-09-28 | Permitta Esports  | W   | 0.165      | 0.143        | 0.013 (0.000)    | 0.487 (0.011)    | -         |     3.05 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |
|            3 |     7145 | 2024-09-12 | Rebels Gaming     | W   | 0.058      | 0.500        | 0.009 (0.000)    | -                | -         |     0.90 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |
|            2 |     7348 | 2024-09-08 | Preasy Esport     | L   | 0.032      | -            | -                | -                | -         |    -0.40 | El1an, MaSvAl, OWNER, sh1nejezzz, supra    |
|            1 |     7619 | 2024-09-05 | EYEBALLERS        | W   | 0.010      | 0.500        | 0.019 (0.000)    | -                | -         |     0.20 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,116.81)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.452 | $4,000.00      | $1,806.11       |
| 2024-10-20 |      0.311 | $1,000.00      | $310.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
