### Roster Details<br />
Team Name: Kitsune Kenko<br />
Roster: KayC, nAAtz, Pixar, Queen_za, scorpz<br />
Global Rank: [271](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [37]( ../standings_asia.md)<br />
<br />
Final Rank Value:  667.2<br />
<br />
Final Rank Value (667.2) = Starting Rank Value (643.1) + Head To Head Adjustments (24.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.193[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 643.1
- 400 + ( ( 0.122 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 643.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1297 | 2024-12-28 | Boo Bees               | W   | 0.779      | 0.233        | 0.001 (0.000)    | 0.053 (0.010)    | 0 (0.000) |    11.36 | KayC, nAAtz, Pixar, Queen_za, scorpz |
|           11 |     1697 | 2024-12-14 | Boo Bees               | L   | 0.686      | -            | -                | -                | -         |   -12.15 | Cjay, KayC, Pixar, Queen_za, S1R3N   |
|           10 |     2087 | 2024-12-07 | Boo Bees               | W   | 0.639      | 0.233        | 0.001 (0.000)    | 0.053 (0.008)    | 0 (0.000) |     9.60 | KayC, mu, nAAtz, Pixar, scorpz       |
|            9 |     2527 | 2024-11-30 | Boo Bees               | L   | 0.592      | -            | -                | -                | -         |    -9.97 | KayC, mu, nAAtz, Pixar, scorpz       |
|            8 |     3317 | 2024-11-16 | INVICTTA               | W   | 0.500      | 0.233        | 0.000 (0.000)    | 0.023 (0.003)    | 0 (0.000) |     4.61 | KayC, mu, nAAtz, Pixar, scorpz       |
|            7 |     3326 | 2024-11-16 | Aperture Gaming Female | W   | 0.499      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.94 | KayC, mu, nAAtz, Pixar, scorpz       |
|            6 |     4127 | 2024-11-02 | Team queenza           | W   | 0.406      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.81 | KayC, nAAtz, Pixar, Queen_za, scorpz |
|            5 |     4506 | 2024-10-26 | Boo Bees               | W   | 0.359      | 0.233        | 0.001 (0.000)    | 0.049 (0.004)    | 0 (0.000) |     5.13 | Cjay, mu, nAAtz, Pixar, scorpz       |
|            4 |     4517 | 2024-10-26 | INVICTTA               | W   | 0.359      | 0.233        | 0.000 (0.000)    | 0.023 (0.002)    | 0 (0.000) |     3.50 | Cjay, mu, nAAtz, Pixar, scorpz       |
|            3 |     5585 | 2024-10-05 | Boo Bees               | W   | 0.219      | 0.233        | 0.001 (0.000)    | 0.049 (0.002)    | 0 (0.000) |     3.21 | Graceyy, KayC, mu, nAAtz, scorpz     |
|            2 |     6990 | 2024-09-14 | Boo Bees               | W   | 0.079      | 0.233        | 0.001 (0.000)    | 0.053 (0.001)    | 0 (0.000) |     1.28 | KayC, mu, nAAtz, Pixar, scorpz       |
|            1 |     7005 | 2024-09-14 | INVICTTA               | W   | 0.079      | 0.233        | 0.000 (0.000)    | 0.023 (0.000)    | 0 (0.000) |     0.79 | KayC, mu, nAAtz, Pixar, scorpz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,235.53)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.779 | $350.00        | $272.68         |
| 2024-12-14 |      0.686 | $150.00        | $102.91         |
| 2024-12-07 |      0.639 | $350.00        | $223.71         |
| 2024-11-30 |      0.592 | $150.00        | $88.83          |
| 2024-11-16 |      0.500 | $350.00        | $174.86         |
| 2024-11-02 |      0.406 | $350.00        | $142.20         |
| 2024-10-26 |      0.359 | $350.00        | $125.81         |
| 2024-10-05 |      0.219 | $350.00        | $76.74          |
| 2024-09-14 |      0.079 | $350.00        | $27.78          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
