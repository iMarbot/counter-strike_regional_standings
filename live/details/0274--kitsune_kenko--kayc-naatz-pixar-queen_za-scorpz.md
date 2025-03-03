### Roster Details<br />
Team Name: Kitsune Kenko<br />
Roster: KayC, nAAtz, Pixar, Queen_za, scorpz<br />
Global Rank: [274](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [37]( ../standings_asia.md)<br />
<br />
Final Rank Value:  666.8<br />
<br />
Final Rank Value (666.8) = Starting Rank Value (643.3) + Head To Head Adjustments (23.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 643.3
- 400 + ( ( 0.122 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 643.3


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
|           12 |     1309 | 2024-12-28 | Boo Bees               | W   | 0.771      | 0.233        | 0.001 (0.000)    | 0.052 (0.009)    | 0 (0.000) |    11.26 | KayC, nAAtz, Pixar, Queen_za, scorpz |
|           11 |     1709 | 2024-12-14 | Boo Bees               | L   | 0.678      | -            | -                | -                | -         |   -11.98 | Cjay, KayC, Pixar, Queen_za, S1R3N   |
|           10 |     2099 | 2024-12-07 | Boo Bees               | W   | 0.631      | 0.233        | 0.001 (0.000)    | 0.052 (0.008)    | 0 (0.000) |     9.49 | KayC, mu, nAAtz, Pixar, scorpz       |
|            9 |     2539 | 2024-11-30 | Boo Bees               | L   | 0.584      | -            | -                | -                | -         |    -9.82 | KayC, mu, nAAtz, Pixar, scorpz       |
|            8 |     3329 | 2024-11-16 | INVICTTA               | W   | 0.491      | 0.233        | 0.000 (0.000)    | 0.023 (0.003)    | 0 (0.000) |     4.55 | KayC, mu, nAAtz, Pixar, scorpz       |
|            7 |     3338 | 2024-11-16 | Aperture Gaming Female | W   | 0.491      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.90 | KayC, mu, nAAtz, Pixar, scorpz       |
|            6 |     4139 | 2024-11-02 | Team queenza           | W   | 0.398      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.74 | KayC, nAAtz, Pixar, Queen_za, scorpz |
|            5 |     4518 | 2024-10-26 | Boo Bees               | W   | 0.351      | 0.233        | 0.001 (0.000)    | 0.048 (0.004)    | 0 (0.000) |     5.02 | Cjay, mu, nAAtz, Pixar, scorpz       |
|            4 |     4529 | 2024-10-26 | INVICTTA               | W   | 0.351      | 0.233        | 0.000 (0.000)    | 0.023 (0.002)    | 0 (0.000) |     3.43 | Cjay, mu, nAAtz, Pixar, scorpz       |
|            3 |     5597 | 2024-10-05 | Boo Bees               | W   | 0.211      | 0.233        | 0.001 (0.000)    | 0.048 (0.002)    | 0 (0.000) |     3.10 | Graceyy, KayC, mu, nAAtz, scorpz     |
|            2 |     7002 | 2024-09-14 | Boo Bees               | W   | 0.071      | 0.233        | 0.001 (0.000)    | 0.052 (0.001)    | 0 (0.000) |     1.14 | KayC, mu, nAAtz, Pixar, scorpz       |
|            1 |     7017 | 2024-09-14 | INVICTTA               | W   | 0.070      | 0.233        | 0.000 (0.000)    | 0.023 (0.000)    | 0 (0.000) |     0.71 | KayC, mu, nAAtz, Pixar, scorpz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,212.99)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.771 | $350.00        | $269.82         |
| 2024-12-14 |      0.678 | $150.00        | $101.68         |
| 2024-12-07 |      0.631 | $350.00        | $220.84         |
| 2024-11-30 |      0.584 | $150.00        | $87.60          |
| 2024-11-16 |      0.491 | $350.00        | $171.99         |
| 2024-11-02 |      0.398 | $350.00        | $139.34         |
| 2024-10-26 |      0.351 | $350.00        | $122.94         |
| 2024-10-05 |      0.211 | $350.00        | $73.87          |
| 2024-09-14 |      0.071 | $350.00        | $24.91          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
