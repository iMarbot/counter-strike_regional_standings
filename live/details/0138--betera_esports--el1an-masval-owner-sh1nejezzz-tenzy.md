### Roster Details<br />
Team Name: Betera Esports<br />
Roster: El1an, MaSvAl, OWNER, sh1nejezzz, tENZY<br />
Global Rank: [138](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
<br />
Final Rank Value:  772.5<br />
<br />
Final Rank Value (772.5) = Starting Rank Value (737.4) + Head To Head Adjustments (35.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.275[<sup>2</sup>](#table1)
- Opponent Network: 0.087[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 737.4
- 400 + ( ( 0.169 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 737.4


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
|           26 |     1532 | 2024-12-19 | Monte             | L   | 0.720      | -            | -                | -                | -         |    -5.96 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           25 |     1593 | 2024-12-16 | Illuminar Gaming  | W   | 0.698      | 0.333        | 0.007 (0.002)    | 0.593 (0.138)    | 0 (0.000) |    12.63 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           24 |     1615 | 2024-12-15 | FAVBET Team       | L   | 0.694      | -            | -                | -                | -         |    -7.62 | El1an, MaSvAl, OWNER, sh1nejezzz, supra    |
|           23 |     1632 | 2024-12-15 | GenOne            | W   | 0.692      | 0.333        | 0.012 (0.003)    | 0.848 (0.196)    | 0 (0.000) |    13.30 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           22 |     1676 | 2024-12-14 | JiJieHao          | W   | 0.687      | 0.143        | -                | 0.255 (0.025)    | 0 (0.000) |     8.40 | El1an, MaSvAl, OWNER, sh1nejezzz, supra    |
|           21 |     1770 | 2024-12-13 | Fire Flux Esports | L   | 0.680      | -            | -                | -                | -         |    -5.91 | El1an, MaSvAl, OWNER, sh1nejezzz, supra    |
|           20 |     1795 | 2024-12-13 | FLuffy Gangsters  | L   | 0.679      | -            | -                | -                | -         |    -8.46 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           19 |     1884 | 2024-12-11 | BC.Game Esports   | W   | 0.665      | 0.333        | 0.022 (0.005)    | 0.559 (0.124)    | 0 (0.000) |    13.65 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           18 |     1944 | 2024-12-09 | JANO Esports      | L   | 0.654      | -            | -                | -                | -         |    -6.96 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           17 |     2340 | 2024-12-02 | FLuffy Gangsters  | L   | 0.606      | -            | -                | -                | -         |    -6.68 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           16 |     2471 | 2024-11-30 | K27               | L   | 0.594      | -            | -                | -                | -         |    -6.85 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           15 |     2497 | 2024-11-30 | RUSTEC            | W   | 0.594      | 0.262        | -                | 0.217 (0.034)    | 0 (0.000) |     4.63 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           14 |     2757 | 2024-11-25 | Monte             | W   | 0.559      | 0.333        | 0.045 (0.008)    | 0.704 (0.131)    | 0 (0.000) |    12.66 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           13 |     2888 | 2024-11-23 | Illuminar Gaming  | W   | 0.545      | -            | -                | -                | 0 (0.000) |     2.07 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           12 |     2961 | 2024-11-22 | GODSENT           | W   | 0.540      | 0.333        | 0.001 (0.000)    | 0.275 (0.049)    | 0 (0.000) |     6.99 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           11 |     3658 | 2024-11-10 | Monte             | L   | 0.460      | -            | -                | -                | -         |    -3.96 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|           10 |     3712 | 2024-11-09 | Leo Team          | W   | 0.453      | 0.354        | 0.026 (0.004)    | 0.758 (0.122)    | 0 (0.000) |     9.13 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|            9 |     3793 | 2024-11-08 | PCIFIC Espor      | W   | 0.446      | 0.354        | 0.004 (0.001)    | 0.254 (0.040)    | 0 (0.000) |     7.73 | El1an, MaSvAl, OWNER, sh1nejezzz, tENZY    |
|            8 |     5206 | 2024-10-12 | NOTTODAY          | L   | 0.265      | -            | -                | -                | -         |    -5.66 | El1an, MaSvAl, OWNER, Polt, sh1nejezzz     |
|            7 |     5226 | 2024-10-12 | Poslednii3ae3d    | W   | 0.265      | -            | -                | -                | -         |     3.12 | El1an, MaSvAl, OWNER, Polt, sh1nejezzz     |
|            6 |     5764 | 2024-10-02 | GameAgents        | L   | 0.200      | -            | -                | -                | -         |    -3.35 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |
|            5 |     6008 | 2024-09-28 | Fire Flux Esports | L   | 0.173      | -            | -                | -                | -         |    -1.85 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |
|            4 |     6031 | 2024-09-28 | Permitta Esports  | W   | 0.173      | 0.143        | 0.013 (0.000)    | 0.494 (0.012)    | -         |     3.20 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |
|            3 |     7133 | 2024-09-12 | Rebels Gaming     | W   | 0.066      | 0.500        | 0.009 (0.000)    | -                | -         |     1.02 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |
|            2 |     7336 | 2024-09-08 | Preasy Esport     | L   | 0.040      | -            | -                | -                | -         |    -0.50 | El1an, MaSvAl, OWNER, sh1nejezzz, supra    |
|            1 |     7607 | 2024-09-05 | EYEBALLERS        | W   | 0.019      | 0.500        | 0.019 (0.000)    | -                | -         |     0.35 | El1an, MaSvAl, OWNER, sh1nejezzz, tripex17 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,157.78)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.460 | $4,000.00      | $1,838.89       |
| 2024-10-20 |      0.319 | $1,000.00      | $318.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
