### Roster Details<br />
Team Name: Metizport X<br />
Roster: Kronkzz, macke, Straxy, zame, ZapR<br />
Global Rank: [301](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [201]( ../standings_europe.md)<br />
<br />
Final Rank Value:  649.5<br />
<br />
Final Rank Value (649.5) = Starting Rank Value (660.5) + Head To Head Adjustments (-11.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.261[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.5
- 400 + ( ( 0.130 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 660.5


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
|           22 |     2097 | 2024-12-07 | Ex-ESC Gaming              | L   | 0.631      | -            | -                | -                | -         |    -9.43 | Kronkzz, macke, Straxy, zame, ZapR |
|           21 |     2230 | 2024-12-04 | Ex-UHKA eSports            | L   | 0.612      | -            | -                | -                | -         |   -13.30 | Kronkzz, macke, Straxy, zame, ZapR |
|           20 |     2348 | 2024-12-02 | GardenGarage               | W   | 0.598      | 0.143        | 0.001 (0.000)    | 0.408 (0.035)    | 0 (0.000) |    11.34 | Kronkzz, macke, Straxy, zame, ZapR |
|           19 |     2449 | 2024-12-01 | Chroma                     | L   | 0.590      | -            | -                | -                | -         |    -8.86 | Kronkzz, macke, Straxy, zame, ZapR |
|           18 |     2521 | 2024-11-30 | SINNERS Academy            | L   | 0.585      | -            | -                | -                | -         |    -7.99 | Kronkzz, macke, Straxy, zame, ZapR |
|           17 |     2540 | 2024-11-30 | Mission Possible           | W   | 0.584      | 0.303        | 0.000 (0.000)    | 0.292 (0.052)    | 0 (0.000) |     6.33 | Kronkzz, macke, Straxy, zame, ZapR |
|           16 |     2635 | 2024-11-28 | ALLINNERS                  | W   | 0.572      | 0.333        | 0.002 (0.000)    | 0.149 (0.028)    | 0 (0.000) |    10.45 | Kronkzz, macke, Straxy, zame, ZapR |
|           15 |     2653 | 2024-11-28 | Rhyno Youngsters           | W   | 0.571      | 0.143        | 0.003 (0.000)    | 0.118 (0.010)    | 0 (0.000) |    10.78 | Kronkzz, macke, Straxy, zame, ZapR |
|           14 |     2684 | 2024-11-27 | NEVERMORE (Ukrainian team) | L   | 0.564      | -            | -                | -                | -         |    -6.27 | Kronkzz, macke, Straxy, zame, ZapR |
|           13 |     2727 | 2024-11-26 | BRODA                      | W   | 0.559      | 0.333        | 0.000 (0.000)    | 0.056 (0.010)    | 0 (0.000) |     5.12 | Kronkzz, macke, Straxy, zame, ZapR |
|           12 |     3551 | 2024-11-12 | DUSTY                      | L   | 0.465      | -            | -                | -                | -         |    -6.72 | Kronkzz, Macke, Straxy, zame, ZapR |
|           11 |     3668 | 2024-11-10 | ROUNDS                     | W   | 0.452      | 0.278        | 0.000 (0.000)    | 0.060 (0.007)    | 0 (0.000) |     4.60 | Kronkzz, Macke, Straxy, zame, ZapR |
|           10 |     3893 | 2024-11-06 | DUSTY                      | L   | 0.425      | -            | -                | -                | -         |    -6.12 | Kronkzz, Macke, Straxy, zame, ZapR |
|            9 |     4148 | 2024-11-02 | INFURITY Gaming            | W   | 0.398      | 0.143        | 0.001 (0.000)    | 0.028 (0.002)    | 1 (0.398) |     5.30 | Brave, Macke, Straxy, zame, ZapR   |
|            8 |     4805 | 2024-10-20 | Nordix Esport              | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.014 (0.001)    | 0 (0.000) |     4.15 | Brave, Macke, Straxy, zame, ZapR   |
|            7 |     4819 | 2024-10-20 | Vanir                      | W   | 0.310      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.92 | Brave, Macke, Straxy, zame, ZapR   |
|            6 |     4869 | 2024-10-19 | Nordix Esport              | L   | 0.303      | -            | -                | -                | -         |    -5.52 | Brave, Macke, Straxy, zame, ZapR   |
|            5 |     5302 | 2024-10-10 | XI Esport                  | L   | 0.244      | -            | -                | -                | -         |    -5.36 | Kronkzz, Macke, Straxy, zame, ZapR |
|            4 |     5615 | 2024-10-05 | Johnny Speeds              | L   | 0.210      | -            | -                | -                | -         |    -1.39 | Kronkzz, Macke, Straxy, zame, ZapR |
|            3 |     5784 | 2024-10-02 | XI Esport                  | W   | 0.191      | 0.278        | 0.000 (0.000)    | 0.124 (0.007)    | 0 (0.000) |     1.81 | Kronkzz, Macke, Straxy, zame, ZapR |
|            2 |     6707 | 2024-09-19 | Venom (Swedish team)       | L   | 0.104      | -            | -                | -                | -         |    -2.42 | Kronkzz, Macke, Straxy, zame, ZapR |
|            1 |     6761 | 2024-09-18 | Jane Doe Bar               | W   | 0.098      | -            | -                | -                | -         |     0.58 | Kronkzz, Macke, Straxy, zame, ZapR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($486.98)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-07 |      0.631 | $198.30        | $125.12         |
| 2024-11-02 |      0.398 | $909.71        | $361.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
