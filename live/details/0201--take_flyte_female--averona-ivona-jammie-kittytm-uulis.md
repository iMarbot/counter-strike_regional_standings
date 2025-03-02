### Roster Details<br />
Team Name: Take Flyte Female<br />
Roster: AverOna, Ivona, Jammie, KittyTM, uulis<br />
Global Rank: [201](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [147]( ../standings_europe.md)<br />
<br />
Final Rank Value:  711.6<br />
<br />
Final Rank Value (711.6) = Starting Rank Value (668.2) + Head To Head Adjustments (43.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 668.2
- 400 + ( ( 0.134 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 668.2


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
|           23 |     1698 | 2024-12-14 | Permitta W            | L   | 0.686      | -            | -                | -                | -         |   -13.63 | AverOna, Ivona, Jammie, KittyTM, uulis |
|           22 |     2409 | 2024-12-01 | Nomercy (Female team) | W   | 0.600      | 0.250        | 0.004 (0.001)    | 0.344 (0.052)    | 0 (0.000) |     8.44 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           21 |     2515 | 2024-11-30 | AKA HERO KAJO         | W   | 0.593      | 0.250        | 0.004 (0.001)    | 0.204 (0.030)    | 0 (0.000) |    10.59 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           20 |     2522 | 2024-11-30 | Okfjong               | W   | 0.593      | -            | -                | -                | 0 (0.000) |     2.86 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           19 |     3230 | 2024-11-17 | Also                  | W   | 0.507      | 0.250        | 0.002 (0.000)    | 0.197 (0.025)    | 0 (0.000) |     6.69 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           18 |     3238 | 2024-11-17 | Take Flyte Female     | W   | 0.506      | 0.250        | -                | 0.023 (0.003)    | 0 (0.000) |     2.65 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           17 |     3319 | 2024-11-16 | AKA HERO Althea       | W   | 0.500      | 0.250        | -                | 0.019 (0.002)    | 0 (0.000) |     3.89 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           16 |     4041 | 2024-11-03 | Wwaves                | W   | 0.413      | 0.250        | 0.000 (0.000)    | 0.038 (0.004)    | 0 (0.000) |     3.67 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           15 |     4058 | 2024-11-03 | Elite Klan Violet     | W   | 0.412      | 0.250        | -                | 0.020 (0.002)    | 0 (0.000) |     2.25 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           14 |     4129 | 2024-11-02 | VHS                   | W   | 0.406      | -            | -                | -                | 0 (0.000) |     2.15 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           13 |     4456 | 2024-10-27 | OneDay                | W   | 0.367      | 0.250        | 0.000 (0.000)    | 0.149 (0.014)    | 0 (0.000) |     4.74 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           12 |     4467 | 2024-10-27 | Also                  | W   | 0.366      | 0.250        | 0.002 (0.000)    | 0.197 (0.018)    | -         |     5.15 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           11 |     4518 | 2024-10-26 | SAW Myst              | W   | 0.359      | -            | -                | -                | -         |     2.86 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|           10 |     4879 | 2024-10-18 | ENCE Athena           | W   | 0.306      | 0.328        | 0.001 (0.000)    | -                | -         |     2.96 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            9 |     5767 | 2024-10-02 | Eco Warriors          | L   | 0.200      | -            | -                | -                | -         |    -2.07 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            8 |     6288 | 2024-09-25 | NIP Impact            | L   | 0.153      | -            | -                | -                | -         |    -2.11 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            7 |     6926 | 2024-09-15 | Let Her Cook          | W   | 0.086      | 0.250        | 0.002 (0.000)    | -                | -         |     1.24 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            6 |     6937 | 2024-09-15 | Permitta W            | W   | 0.085      | 0.250        | 0.003 (0.000)    | 0.172 (0.004)    | -         |     1.28 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            5 |     6993 | 2024-09-14 | Insilio Female        | W   | 0.079      | -            | -                | -                | -         |     0.97 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            4 |     7038 | 2024-09-14 | Eco Warriors          | L   | 0.078      | -            | -                | -                | -         |    -0.81 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            3 |     7179 | 2024-09-11 | Let Her Cook          | L   | 0.060      | -            | -                | -                | -         |    -1.02 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            2 |     7430 | 2024-09-07 | Permitta W            | W   | 0.032      | -            | -                | -                | -         |     0.48 | AverOna, Jammie, kr4sy, Rony4ka, uulis |
|            1 |     7656 | 2024-09-04 | Ex-Astralis Women     | W   | 0.013      | 0.328        | 0.010 (0.000)    | -                | -         |     0.25 | AverOna, Jammie, kr4sy, Rony4ka, uulis |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,926.72)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-01 |      0.600 | $750.00        | $450.00         |
| 2024-11-17 |      0.507 | $750.00        | $379.93         |
| 2024-11-03 |      0.413 | $750.00        | $310.00         |
| 2024-10-27 |      0.367 | $750.00        | $275.00         |
| 2024-10-20 |      0.320 | $1,400.00      | $447.42         |
| 2024-09-15 |      0.086 | $750.00        | $64.38          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
