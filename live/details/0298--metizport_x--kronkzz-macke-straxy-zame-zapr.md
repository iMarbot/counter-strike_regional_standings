### Roster Details<br />
Team Name: Metizport X<br />
Roster: Kronkzz, macke, Straxy, zame, ZapR<br />
Global Rank: [298](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [201]( ../standings_europe.md)<br />
<br />
Final Rank Value:  649.6<br />
<br />
Final Rank Value (649.6) = Starting Rank Value (660.8) + Head To Head Adjustments (-11.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.261[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.8
- 400 + ( ( 0.131 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 660.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |     2085 | 2024-12-07 | Ex-ESC Gaming              | L   | 0.639      | -            | -                | -                | -         |    -9.55 | Kronkzz, macke, Straxy, zame, ZapR |
|           21 |     2218 | 2024-12-04 | Ex-UHKA eSports            | L   | 0.620      | -            | -                | -                | -         |   -13.47 | Kronkzz, macke, Straxy, zame, ZapR |
|           20 |     2336 | 2024-12-02 | GardenGarage               | W   | 0.606      | 0.143        | 0.001 (0.000)    | 0.413 (0.036)    | 0 (0.000) |    11.49 | Kronkzz, macke, Straxy, zame, ZapR |
|           19 |     2437 | 2024-12-01 | Chroma                     | L   | 0.599      | -            | -                | -                | -         |    -8.98 | Kronkzz, macke, Straxy, zame, ZapR |
|           18 |     2509 | 2024-11-30 | SINNERS Academy            | L   | 0.593      | -            | -                | -                | -         |    -8.11 | Kronkzz, macke, Straxy, zame, ZapR |
|           17 |     2528 | 2024-11-30 | Mission Possible           | W   | 0.592      | 0.303        | 0.000 (0.000)    | 0.295 (0.053)    | 0 (0.000) |     6.43 | Kronkzz, macke, Straxy, zame, ZapR |
|           16 |     2623 | 2024-11-28 | ALLINNERS                  | W   | 0.580      | 0.333        | 0.002 (0.000)    | 0.151 (0.029)    | 0 (0.000) |    10.61 | Kronkzz, macke, Straxy, zame, ZapR |
|           15 |     2641 | 2024-11-28 | Rhyno Youngsters           | W   | 0.579      | 0.143        | 0.003 (0.000)    | 0.121 (0.010)    | 0 (0.000) |    10.94 | Kronkzz, macke, Straxy, zame, ZapR |
|           14 |     2672 | 2024-11-27 | NEVERMORE (Ukrainian team) | L   | 0.573      | -            | -                | -                | -         |    -6.35 | Kronkzz, macke, Straxy, zame, ZapR |
|           13 |     2715 | 2024-11-26 | BRODA                      | W   | 0.567      | 0.333        | 0.000 (0.000)    | 0.056 (0.011)    | 0 (0.000) |     5.19 | Kronkzz, macke, Straxy, zame, ZapR |
|           12 |     3539 | 2024-11-12 | DUSTY                      | L   | 0.473      | -            | -                | -                | -         |    -6.84 | Kronkzz, Macke, Straxy, zame, ZapR |
|           11 |     3656 | 2024-11-10 | ROUNDS                     | W   | 0.460      | 0.278        | 0.000 (0.000)    | 0.061 (0.008)    | 0 (0.000) |     4.69 | Kronkzz, Macke, Straxy, zame, ZapR |
|           10 |     3881 | 2024-11-06 | DUSTY                      | L   | 0.433      | -            | -                | -                | -         |    -6.24 | Kronkzz, Macke, Straxy, zame, ZapR |
|            9 |     4136 | 2024-11-02 | INFURITY Gaming            | W   | 0.406      | 0.143        | 0.001 (0.000)    | 0.029 (0.002)    | 1 (0.406) |     5.41 | Brave, Macke, Straxy, zame, ZapR   |
|            8 |     4793 | 2024-10-20 | Nordix Esport              | W   | 0.319      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     4.26 | Brave, Macke, Straxy, zame, ZapR   |
|            7 |     4807 | 2024-10-20 | Vanir                      | W   | 0.318      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.97 | Brave, Macke, Straxy, zame, ZapR   |
|            6 |     4857 | 2024-10-19 | Nordix Esport              | L   | 0.311      | -            | -                | -                | -         |    -5.67 | Brave, Macke, Straxy, zame, ZapR   |
|            5 |     5290 | 2024-10-10 | XI Esport                  | L   | 0.252      | -            | -                | -                | -         |    -5.53 | Kronkzz, Macke, Straxy, zame, ZapR |
|            4 |     5600 | 2024-10-05 | Johnny Speeds              | L   | 0.219      | -            | -                | -                | -         |    -1.43 | Kronkzz, Macke, Straxy, zame, ZapR |
|            3 |     5772 | 2024-10-02 | XI Esport                  | W   | 0.199      | 0.278        | 0.000 (0.000)    | 0.127 (0.007)    | 0 (0.000) |     1.89 | Kronkzz, Macke, Straxy, zame, ZapR |
|            2 |     6695 | 2024-09-19 | Venom (Swedish team)       | L   | 0.113      | -            | -                | -                | -         |    -2.61 | Kronkzz, Macke, Straxy, zame, ZapR |
|            1 |     6749 | 2024-09-18 | Jane Doe Bar               | W   | 0.107      | -            | -                | -                | -         |     0.63 | Kronkzz, Macke, Straxy, zame, ZapR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($496.06)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-07 |      0.639 | $198.30        | $126.75         |
| 2024-11-02 |      0.406 | $909.71        | $369.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
