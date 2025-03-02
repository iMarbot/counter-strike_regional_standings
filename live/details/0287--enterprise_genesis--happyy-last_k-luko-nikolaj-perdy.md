### Roster Details<br />
Team Name: ENTERPRISE Genesis<br />
Roster: Happyy, Lastík, luko, NIKOLAJ, PerdY<br />
Global Rank: [287](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [196]( ../standings_europe.md)<br />
<br />
Final Rank Value:  658.2<br />
<br />
Final Rank Value (658.2) = Starting Rank Value (646.9) + Head To Head Adjustments (11.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.9
- 400 + ( ( 0.124 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 646.9


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
|           28 |     2203 | 2024-12-04 | NEVERMORE (Ukrainian team) | L   | 0.620      | -            | -                | -                | -         |    -6.41 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           27 |     2520 | 2024-11-30 | Chimera Esports            | L   | 0.593      | -            | -                | -                | -         |    -4.33 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           26 |     2613 | 2024-11-28 | Eternal premium            | W   | 0.580      | 0.333        | 0.002 (0.000)    | 0.215 (0.042)    | 0 (0.000) |    10.24 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           25 |     2709 | 2024-11-26 | Rhyno Youngsters           | W   | 0.567      | 0.333        | 0.003 (0.001)    | 0.121 (0.023)    | 0 (0.000) |    11.04 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           24 |     2963 | 2024-11-22 | Team Sampi                 | L   | 0.540      | -            | -                | -                | -         |    -5.14 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           23 |     3148 | 2024-11-19 | Ins (Polish team)          | L   | 0.520      | -            | -                | -                | -         |    -7.32 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           22 |     3193 | 2024-11-18 | Mission Possible           | W   | 0.514      | 0.278        | 0.000 (0.000)    | 0.295 (0.042)    | 0 (0.000) |     6.23 | Happyy, Lastík, luko, MahaR, NIKOLAJ     |
|           21 |     3239 | 2024-11-17 | GamerLegion Academy        | W   | 0.506      | 0.278        | 0.000 (0.000)    | 0.223 (0.031)    | 0 (0.000) |     6.44 | Happyy, Lastík, luko, NIKOLAJ, woozzzi   |
|           20 |     3390 | 2024-11-15 | DUSTY                      | W   | 0.492      | 0.278        | 0.006 (0.001)    | 0.071 (0.010)    | 0 (0.000) |     8.79 | Happyy, Lastík, luko, NIKOLAJ, Snaxiee   |
|           19 |     3497 | 2024-11-13 | BRUTE                      | L   | 0.480      | -            | -                | -                | -         |    -6.05 | Happyy, Lastík, luko, MahaR, NIKOLAJ     |
|           18 |     3797 | 2024-11-08 | Mission Possible           | W   | 0.446      | 0.278        | -                | 0.295 (0.037)    | 0 (0.000) |     5.37 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           17 |     4007 | 2024-11-04 | Daystar                    | W   | 0.419      | 0.278        | 0.000 (0.000)    | 0.135 (0.016)    | 0 (0.000) |     6.97 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           16 |     4432 | 2024-10-28 | Kubix Esports              | L   | 0.373      | -            | -                | -                | -         |    -1.97 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|           15 |     5067 | 2024-10-15 | Devils.one                 | L   | 0.286      | -            | -                | -                | -         |    -4.21 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|           14 |     5218 | 2024-10-12 | NOTTODAY                   | L   | 0.265      | -            | -                | -                | -         |    -4.65 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           13 |     5255 | 2024-10-11 | 777 Esports                | L   | 0.259      | -            | -                | -                | -         |    -4.01 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           12 |     5340 | 2024-10-09 | SINNERS Academy            | W   | 0.246      | 0.278        | 0.001 (0.000)    | 0.102 (0.007)    | 0 (0.000) |     4.81 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|           11 |     5421 | 2024-10-08 | GameAgents                 | W   | 0.239      | 0.143        | 0.003 (0.000)    | 0.119 (0.004)    | 0 (0.000) |     4.57 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|           10 |     5582 | 2024-10-05 | Devils.one                 | L   | 0.219      | -            | -                | -                | -         |    -3.25 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|            9 |     5947 | 2024-09-29 | GOSTIVAR                   | L   | 0.180      | -            | -                | -                | -         |    -3.93 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            8 |     6022 | 2024-09-28 | Fire Flux Esports          | L   | 0.173      | -            | -                | -                | -         |    -1.27 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|            7 |     6108 | 2024-09-27 | Asian fetish               | L   | 0.167      | -            | -                | -                | -         |    -3.03 | Happyy, Lastík, luko, NIKOLAJ, PerdY     |
|            6 |     6365 | 2024-09-24 | Illuminar Gaming           | L   | 0.146      | -            | -                | -                | -         |    -1.08 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            5 |     6379 | 2024-09-24 | GardenGarage               | W   | 0.146      | 0.143        | 0.001 (0.000)    | 0.413 (0.009)    | 0 (0.000) |     2.95 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            4 |     7226 | 2024-09-10 | AVEZ                       | W   | 0.054      | -            | -                | -                | -         |     0.34 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            3 |     7236 | 2024-09-10 | JiJieHao                   | W   | 0.053      | 0.143        | 0.000 (0.000)    | -                | -         |     0.83 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            2 |     7416 | 2024-09-07 | BRUTE                      | L   | 0.033      | -            | -                | -                | -         |    -0.41 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |
|            1 |     7597 | 2024-09-05 | Team Sampi                 | L   | 0.019      | -            | -                | -                | -         |    -0.17 | fajrness, Happyy, Lastík, NIKOLAJ, PerdY |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($471.89)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.552 | $616.62        | $340.25         |
| 2024-11-20 |      0.527 | $250.00        | $131.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
