### Roster Details<br />
Team Name: ENTERPRISE Genesis<br />
Roster: Happyy, Lastík, luko, NIKOLAJ, PerdY<br />
Global Rank: [290](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [195]( ../standings_europe.md)<br />
<br />
Final Rank Value:  657.8<br />
<br />
Final Rank Value (657.8) = Starting Rank Value (646.8) + Head To Head Adjustments (11.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.8
- 400 + ( ( 0.123 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 646.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |     2215 | 2024-12-04 | NEVERMORE (Ukrainian team) | L   | 0.612      | -            | -                | -                | -         |    -6.33 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           27 |     2532 | 2024-11-30 | Chimera Esports            | L   | 0.585      | -            | -                | -                | -         |    -4.30 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           26 |     2625 | 2024-11-28 | Eternal premium            | W   | 0.572      | 0.333        | 0.002 (0.000)    | 0.215 (0.041)    | 0 (0.000) |    10.13 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           25 |     2721 | 2024-11-26 | Rhyno Youngsters           | W   | 0.559      | 0.333        | 0.003 (0.001)    | 0.118 (0.022)    | 0 (0.000) |    10.88 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           24 |     2975 | 2024-11-22 | Team Sampi                 | L   | 0.531      | -            | -                | -                | -         |    -5.12 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           23 |     3160 | 2024-11-19 | Ins (Polish team)          | L   | 0.512      | -            | -                | -                | -         |    -7.22 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           22 |     3205 | 2024-11-18 | Mission Possible           | W   | 0.505      | 0.278        | 0.000 (0.000)    | 0.292 (0.041)    | 0 (0.000) |     6.11 | Happyy, Lastík, luko, MahaR, NIKOLAJ     |
|           21 |     3249 | 2024-11-17 | GamerLegion Academy        | W   | 0.498      | 0.278        | 0.000 (0.000)    | 0.219 (0.030)    | 0 (0.000) |     6.30 | Happyy, Lastík, luko, NIKOLAJ, woozzzi   |
|           20 |     3402 | 2024-11-15 | DUSTY                      | W   | 0.484      | 0.278        | 0.007 (0.001)    | 0.070 (0.009)    | 0 (0.000) |     8.65 | Happyy, Lastík, luko, NIKOLAJ, Snaxiee   |
|           19 |     3509 | 2024-11-13 | BRUTE                      | L   | 0.471      | -            | -                | -                | -         |    -5.95 | Happyy, Lastík, luko, MahaR, NIKOLAJ     |
|           18 |     3809 | 2024-11-08 | Mission Possible           | W   | 0.438      | 0.278        | -                | 0.292 (0.035)    | 0 (0.000) |     5.25 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           17 |     4019 | 2024-11-04 | Daystar                    | W   | 0.411      | 0.278        | 0.000 (0.000)    | 0.131 (0.015)    | 0 (0.000) |     6.79 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           16 |     4444 | 2024-10-28 | Kubix Esports              | L   | 0.365      | -            | -                | -                | -         |    -1.94 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|           15 |     5079 | 2024-10-15 | Devils.one                 | L   | 0.278      | -            | -                | -                | -         |    -4.13 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|           14 |     5230 | 2024-10-12 | NOTTODAY                   | L   | 0.257      | -            | -                | -                | -         |    -4.51 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           13 |     5267 | 2024-10-11 | 777 Esports                | L   | 0.251      | -            | -                | -                | -         |    -3.89 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           12 |     5352 | 2024-10-09 | SINNERS Academy            | W   | 0.238      | 0.278        | 0.001 (0.000)    | 0.101 (0.007)    | 0 (0.000) |     4.65 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           11 |     5433 | 2024-10-08 | GameAgents                 | W   | 0.231      | 0.143        | 0.003 (0.000)    | 0.111 (0.004)    | 0 (0.000) |     4.36 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|           10 |     5594 | 2024-10-05 | Devils.one                 | L   | 0.211      | -            | -                | -                | -         |    -3.16 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|            9 |     5959 | 2024-09-29 | GOSTIVAR                   | L   | 0.172      | -            | -                | -                | -         |    -3.76 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            8 |     6034 | 2024-09-28 | Fire Flux Esports          | L   | 0.165      | -            | -                | -                | -         |    -1.22 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|            7 |     6120 | 2024-09-27 | Asian fetish               | L   | 0.159      | -            | -                | -                | -         |    -2.89 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|            6 |     6377 | 2024-09-24 | Illuminar Gaming           | L   | 0.138      | -            | -                | -                | -         |    -1.03 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            5 |     6391 | 2024-09-24 | GardenGarage               | W   | 0.138      | 0.143        | 0.001 (0.000)    | 0.408 (0.008)    | 0 (0.000) |     2.78 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            4 |     7238 | 2024-09-10 | AVEZ                       | W   | 0.046      | -            | -                | -                | -         |     0.29 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            3 |     7248 | 2024-09-10 | JiJieHao                   | W   | 0.045      | 0.143        | 0.000 (0.000)    | -                | -         |     0.70 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            2 |     7428 | 2024-09-07 | BRUTE                      | L   | 0.024      | -            | -                | -                | -         |    -0.31 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            1 |     7609 | 2024-09-05 | Team Sampi                 | L   | 0.011      | -            | -                | -                | -         |    -0.10 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($464.78)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.544 | $616.62        | $335.20         |
| 2024-11-20 |      0.518 | $250.00        | $129.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
