### Roster Details<br />
Team Name: Take Flyte Female<br />
Roster: AverOna, Ivona, Jammie, KittyTM, uulis<br />
Global Rank: [203](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [145]( ../standings_europe.md)<br />
<br />
Final Rank Value:  710.6<br />
<br />
Final Rank Value (710.6) = Starting Rank Value (668.0) + Head To Head Adjustments (42.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 668.0
- 400 + ( ( 0.134 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 668.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     1710 | 2024-12-14 | Permitta W            | L   | 0.678      | -            | -                | -                | -         |   -13.43 | AverOna, Ivona, Jammie, KittyTM, uulis |
|           22 |     2419 | 2024-12-01 | Nomercy (Female team) | W   | 0.592      | 0.250        | 0.004 (0.001)    | 0.341 (0.051)    | 0 (0.000) |     8.35 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           21 |     2527 | 2024-11-30 | AKA HERO KAJO         | W   | 0.585      | 0.250        | 0.004 (0.001)    | 0.203 (0.030)    | 0 (0.000) |    10.43 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           20 |     2534 | 2024-11-30 | Okfjong               | W   | 0.585      | -            | -                | -                | 0 (0.000) |     2.83 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           19 |     3242 | 2024-11-17 | Also                  | W   | 0.498      | 0.250        | 0.002 (0.000)    | 0.195 (0.024)    | 0 (0.000) |     6.61 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           18 |     3253 | 2024-11-17 | Take Flyte Female     | W   | 0.498      | 0.250        | -                | 0.023 (0.003)    | 0 (0.000) |     2.62 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           17 |     3331 | 2024-11-16 | AKA HERO Althea       | W   | 0.491      | 0.250        | -                | 0.019 (0.002)    | 0 (0.000) |     3.84 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           16 |     4053 | 2024-11-03 | Wwaves                | W   | 0.405      | 0.250        | 0.000 (0.000)    | 0.038 (0.004)    | 0 (0.000) |     3.61 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           15 |     4070 | 2024-11-03 | Elite Klan Violet     | W   | 0.404      | 0.250        | -                | 0.020 (0.002)    | 0 (0.000) |     2.21 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           14 |     4141 | 2024-11-02 | VHS                   | W   | 0.398      | -            | -                | -                | 0 (0.000) |     2.12 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           13 |     4468 | 2024-10-27 | OneDay                | W   | 0.358      | 0.250        | 0.000 (0.000)    | 0.148 (0.013)    | 0 (0.000) |     4.64 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           12 |     4479 | 2024-10-27 | Also                  | W   | 0.358      | 0.250        | 0.002 (0.000)    | 0.195 (0.017)    | -         |     5.05 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           11 |     4530 | 2024-10-26 | SAW Myst              | W   | 0.351      | -            | -                | -                | -         |     2.78 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           10 |     4891 | 2024-10-18 | ENCE Athena           | W   | 0.298      | 0.328        | 0.001 (0.000)    | -                | -         |     2.89 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            9 |     5779 | 2024-10-02 | Eco Warriors          | L   | 0.191      | -            | -                | -                | -         |    -1.98 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            8 |     6300 | 2024-09-25 | NIP Impact            | L   | 0.145      | -            | -                | -                | -         |    -1.99 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            7 |     6938 | 2024-09-15 | Let Her Cook          | W   | 0.078      | 0.250        | 0.002 (0.000)    | -                | -         |     1.12 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            6 |     6949 | 2024-09-15 | Permitta W            | W   | 0.077      | 0.250        | 0.003 (0.000)    | 0.169 (0.003)    | -         |     1.16 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            5 |     7005 | 2024-09-14 | Insilio Female        | W   | 0.071      | -            | -                | -                | -         |     0.86 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            4 |     7050 | 2024-09-14 | Eco Warriors          | L   | 0.070      | -            | -                | -                | -         |    -0.73 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            3 |     7191 | 2024-09-11 | Let Her Cook          | L   | 0.051      | -            | -                | -                | -         |    -0.88 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            2 |     7442 | 2024-09-07 | Permitta W            | W   | 0.024      | 0.294        | 0.003 (0.000)    | -                | -         |     0.36 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            1 |     7668 | 2024-09-04 | Ex-Astralis Women     | W   | 0.005      | -            | -                | -                | -         |     0.09 | AverOna, Jammie, kr4sy, Rony4ka, uulis |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,884.52)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-01 |      0.592 | $750.00        | $443.85         |
| 2024-11-17 |      0.498 | $750.00        | $373.78         |
| 2024-11-03 |      0.405 | $750.00        | $303.85         |
| 2024-10-27 |      0.358 | $750.00        | $268.85         |
| 2024-10-20 |      0.311 | $1,400.00      | $435.94         |
| 2024-09-15 |      0.078 | $750.00        | $58.23          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
