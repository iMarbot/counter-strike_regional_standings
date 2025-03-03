### Roster Details<br />
Team Name: The Agency Clan<br />
Roster: doon1k, hiden, kaZzu, Kunana, raW<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  869.7<br />
<br />
Final Rank Value (869.7) = Starting Rank Value (843.6) + Head To Head Adjustments (26.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.351[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 843.6
- 400 + ( ( 0.222 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 843.6


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
|           18 |     1247 | 2024-12-30 | Energise Club                    | W   | 0.786      | 0.143        | 0.000 (0.000)    | 0.064 (0.007)    | 0 (0.000) |     3.06 | doon1k, hiden, kaZzu, Kunana, raW    |
|           17 |     1307 | 2024-12-28 | Rhyno Youngsters                 | W   | 0.771      | 0.143        | 0.003 (0.000)    | 0.118 (0.013)    | 0 (0.000) |     7.82 | doon1k, Hiden, kazzu, Kunana, raW    |
|           16 |     1311 | 2024-12-28 | Leça FC Esports                  | W   | 0.771      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.73 | doon1k, Hiden, kazzu, Kunana, raW    |
|           15 |     1393 | 2024-12-22 | GTZ.ESPORTS                      | L   | 0.732      | -            | -                | -                | -         |    -4.44 | doon1k, Hiden, kazzu, Kunana, raW    |
|           14 |     1401 | 2024-12-22 | Rhyno Youngsters                 | W   | 0.732      | 0.143        | 0.003 (0.000)    | 0.118 (0.012)    | 1 (0.732) |     7.40 | doon1k, Hiden, kazzu, Kunana, raW    |
|           13 |     1431 | 2024-12-22 | La Bombonera                     | W   | 0.730      | 0.143        | 0.000 (0.000)    | 0.034 (0.004)    | 1 (0.730) |     5.13 | doon1k, Hiden, kazzu, Kunana, raW    |
|           12 |     1455 | 2024-12-21 | Impulse GW                       | W   | 0.725      | 0.143        | 0.006 (0.001)    | 0.169 (0.017)    | 1 (0.725) |     7.33 | doon1k, Hiden, kazzu, Kunana, raW    |
|           11 |     1536 | 2024-12-19 | THE LAST DANCE (Portuguese team) | W   | 0.713      | 0.143        | 0.000 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     5.23 | doon1k, hiden, kaZzu, Kunana, raW    |
|           10 |     1774 | 2024-12-13 | Macabrienz                       | W   | 0.672      | -            | -                | -                | 0 (0.000) |     1.70 | doon1k, hiden, kaZzu, Kunana, raW    |
|            9 |     3351 | 2024-11-16 | Rhyno Esports                    | L   | 0.490      | -            | -                | -                | -         |    -7.18 | Hiden, kaZzu, Kunana, raW, Werzaide  |
|            8 |     4044 | 2024-11-03 | GOOFYBOYZ                        | L   | 0.406      | -            | -                | -                | -         |    -7.82 | doon1k, Hiden, kazzu, Kunana, raW    |
|            7 |     4060 | 2024-11-03 | Impulse GW                       | W   | 0.405      | 0.143        | 0.006 (0.000)    | 0.169 (0.010)    | 1 (0.405) |     4.32 | doon1k, Hiden, kazzu, Kunana, raW    |
|            6 |     4077 | 2024-11-03 | 1bot +4                          | W   | 0.404      | -            | -                | -                | 1 (0.404) |     0.97 | doon1k, Hiden, kazzu, Kunana, raW    |
|            5 |     4419 | 2024-10-28 | Impulse GW                       | W   | 0.366      | 0.143        | 0.006 (0.000)    | 0.169 (0.009)    | -         |     4.09 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            4 |     4698 | 2024-10-22 | FALKE ESPORTS                    | W   | 0.326      | -            | -                | -                | -         |     0.83 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            3 |     4705 | 2024-10-22 | TGD Pro                          | W   | 0.325      | 0.143        | -                | 0.046 (0.002)    | -         |     0.81 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            2 |     4783 | 2024-10-20 | Energise Club                    | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.064 (0.003)    | -         |     1.34 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            1 |     4792 | 2024-10-20 | GOOFYBOYZ                        | L   | 0.311      | -            | -                | -                | -         |    -6.23 | doon1k, kaZzu, Kunana, raW, Werzaide |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,139.92)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.786 | $365.01        | $286.79         |
| 2024-12-28 |      0.771 | $730.00        | $562.93         |
| 2024-12-22 |      0.732 | $834.42        | $611.15         |
| 2024-11-17 |      0.497 | $1,054.46      | $524.45         |
| 2024-11-03 |      0.406 | $380.83        | $154.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
