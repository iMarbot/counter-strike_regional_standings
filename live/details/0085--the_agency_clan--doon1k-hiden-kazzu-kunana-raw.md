### Roster Details<br />
Team Name: The Agency Clan<br />
Roster: doon1k, hiden, kaZzu, Kunana, raW<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
<br />
Final Rank Value:  870.8<br />
<br />
Final Rank Value (870.8) = Starting Rank Value (844.7) + Head To Head Adjustments (26.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.354[<sup>2</sup>](#table1)

The average of these factors is 0.223<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 844.7
- 400 + ( ( 0.223 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 844.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     1235 | 2024-12-30 | Energise Club                    | W   | 0.794      | 0.143        | 0.000 (0.000)    | 0.064 (0.007)    | 0 (0.000) |     3.07 | doon1k, hiden, kaZzu, Kunana, raW    |
|           17 |     1295 | 2024-12-28 | Rhyno Youngsters                 | W   | 0.779      | 0.143        | 0.003 (0.000)    | 0.121 (0.013)    | 0 (0.000) |     7.88 | doon1k, Hiden, kazzu, Kunana, raW    |
|           16 |     1299 | 2024-12-28 | Leça FC Esports                  | W   | 0.779      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.74 | doon1k, Hiden, kazzu, Kunana, raW    |
|           15 |     1381 | 2024-12-22 | GTZ.ESPORTS                      | L   | 0.741      | -            | -                | -                | -         |    -4.50 | doon1k, Hiden, kazzu, Kunana, raW    |
|           14 |     1389 | 2024-12-22 | Rhyno Youngsters                 | W   | 0.740      | 0.143        | 0.003 (0.000)    | 0.121 (0.013)    | 1 (0.740) |     7.46 | doon1k, Hiden, kazzu, Kunana, raW    |
|           13 |     1419 | 2024-12-22 | La Bombonera                     | W   | 0.738      | 0.143        | 0.000 (0.000)    | 0.034 (0.004)    | 1 (0.738) |     5.16 | doon1k, Hiden, kazzu, Kunana, raW    |
|           12 |     1443 | 2024-12-21 | Impulse GW                       | W   | 0.733      | 0.143        | 0.006 (0.001)    | 0.172 (0.018)    | 1 (0.733) |     7.37 | doon1k, Hiden, kazzu, Kunana, raW    |
|           11 |     1524 | 2024-12-19 | THE LAST DANCE (Portuguese team) | W   | 0.721      | 0.143        | 0.000 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     5.27 | doon1k, hiden, kaZzu, Kunana, raW    |
|           10 |     1762 | 2024-12-13 | Macabrienz                       | W   | 0.681      | -            | -                | -                | 0 (0.000) |     1.71 | doon1k, hiden, kaZzu, Kunana, raW    |
|            9 |     3339 | 2024-11-16 | Rhyno Esports                    | L   | 0.498      | -            | -                | -                | -         |    -7.26 | Hiden, kaZzu, Kunana, raW, Werzaide  |
|            8 |     4032 | 2024-11-03 | GOOFYBOYZ                        | L   | 0.414      | -            | -                | -                | -         |    -7.98 | doon1k, Hiden, kazzu, Kunana, raW    |
|            7 |     4048 | 2024-11-03 | Impulse GW                       | W   | 0.413      | 0.143        | 0.006 (0.000)    | 0.172 (0.010)    | 1 (0.413) |     4.38 | doon1k, Hiden, kazzu, Kunana, raW    |
|            6 |     4065 | 2024-11-03 | 1bot +4                          | W   | 0.412      | -            | -                | -                | 1 (0.412) |     0.99 | doon1k, Hiden, kazzu, Kunana, raW    |
|            5 |     4407 | 2024-10-28 | Impulse GW                       | W   | 0.374      | 0.143        | 0.006 (0.000)    | 0.172 (0.009)    | -         |     4.17 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            4 |     4686 | 2024-10-22 | FALKE ESPORTS                    | W   | 0.334      | -            | -                | -                | -         |     0.85 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            3 |     4693 | 2024-10-22 | TGD Pro                          | W   | 0.333      | 0.143        | -                | 0.047 (0.002)    | -         |     0.83 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            2 |     4771 | 2024-10-20 | Energise Club                    | W   | 0.320      | 0.143        | 0.000 (0.000)    | 0.064 (0.003)    | -         |     1.36 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            1 |     4780 | 2024-10-20 | GOOFYBOYZ                        | L   | 0.319      | -            | -                | -                | -         |    -6.41 | doon1k, kaZzu, Kunana, raW, Werzaide |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,167.50)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.794 | $365.01        | $289.78         |
| 2024-12-28 |      0.779 | $730.00        | $568.91         |
| 2024-12-22 |      0.741 | $834.42        | $617.99         |
| 2024-11-17 |      0.506 | $1,054.46      | $533.09         |
| 2024-11-03 |      0.414 | $380.83        | $157.73         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
