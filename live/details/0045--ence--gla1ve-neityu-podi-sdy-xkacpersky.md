### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Neityu, podi, sdy, xKacpersky<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  995.6<br />
<br />
Final Rank Value (995.6) = Starting Rank Value (1003.4) + Head To Head Adjustments (-7.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.536[<sup>1</sup>](#table2)
- Bounty Collected: 0.416[<sup>2</sup>](#table1)
- Opponent Network: 0.114[<sup>2</sup>](#table1)
- LAN Wins: 0.141[<sup>2</sup>](#table1)

The average of these factors is 0.302<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1003.4
- 400 + ( ( 0.302 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1003.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      231 | 2025-02-21 | Natus Vincere Junior | L   | 1.000      | -            | -                | -                | -         |   -17.49 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           24 |      431 | 2025-02-15 | Partizan Esports     | L   | 1.000      | -            | -                | -                | -         |   -15.06 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           23 |      479 | 2025-02-14 | Passion UA           | W   | 1.000      | 0.435        | 0.044 (0.019)    | 0.545 (0.237)    | 0 (0.000) |    18.27 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           22 |      543 | 2025-02-12 | Alliance             | W   | 1.000      | 0.435        | 0.015 (0.007)    | 0.570 (0.248)    | 0 (0.000) |     9.99 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           21 |      692 | 2025-02-08 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |   -22.07 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           20 |      705 | 2025-02-08 | AgenciUSB            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.72 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           19 |      757 | 2025-02-07 | Boiets Esports Club  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.95 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           18 |      809 | 2025-02-07 | 9INE                 | L   | 1.000      | -            | -                | -                | -         |   -19.18 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           17 |      915 | 2025-02-05 | 9INE                 | W   | 1.000      | 0.143        | 0.037 (0.005)    | 0.837 (0.120)    | 0 (0.000) |    11.13 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           16 |     1194 | 2025-01-15 | Team Falcons         | L   | 0.891      | -            | -                | -                | -         |    -0.24 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           15 |     1643 | 2024-12-15 | Team Spirit Academy  | L   | 0.684      | -            | -                | -                | -         |   -12.19 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           14 |     1694 | 2024-12-14 | AMKAL ESPORTS        | W   | 0.678      | 0.435        | 0.017 (0.005)    | 0.379 (0.112)    | 0 (0.000) |     5.36 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           13 |     1854 | 2024-12-12 | Endpoint             | W   | 0.663      | 0.435        | 0.009 (0.003)    | 0.377 (0.109)    | -         |     3.37 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           12 |     2805 | 2024-11-24 | Monte                | W   | 0.544      | 0.143        | 0.029 (0.002)    | -                | -         |     5.47 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           11 |     2884 | 2024-11-23 | Zero Tenacity        | W   | 0.538      | 0.143        | -                | 0.684 (0.053)    | -         |     5.37 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           10 |     3631 | 2024-11-11 | 500                  | L   | 0.457      | -            | -                | -                | -         |    -7.29 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            9 |     3740 | 2024-11-09 | Wild Lotus           | W   | 0.444      | 0.143        | -                | 0.438 (0.028)    | -         |     2.85 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            8 |     4809 | 2024-10-20 | Team Falcons         | W   | 0.311      | 0.589        | 0.939 (0.172)    | 0.609 (0.111)    | 1 (0.311) |     9.72 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            7 |     4863 | 2024-10-19 | The MongolZ          | W   | 0.304      | 0.589        | 1.000 (0.179)    | 0.574 (0.103)    | 1 (0.304) |     9.51 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            6 |     4903 | 2024-10-18 | 9z Team              | W   | 0.298      | 0.589        | 0.015 (0.003)    | 0.119 (0.021)    | 1 (0.298) |     2.12 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            5 |     4951 | 2024-10-17 | Team Falcons         | L   | 0.290      | -            | -                | -                | -         |    -0.06 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            4 |     4960 | 2024-10-17 | 9z Team              | W   | 0.290      | 0.589        | 0.015 (0.003)    | -                | 1 (0.290) |     2.07 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            3 |     7089 | 2024-09-13 | ATOX Esports         | L   | 0.065      | -            | -                | -                | -         |    -0.75 | gla1ve, Goofy, Kylar, podi, sdy       |
|            2 |     7150 | 2024-09-12 | RED Canids           | L   | 0.057      | -            | -                | -                | -         |    -1.27 | gla1ve, Goofy, Kylar, podi, sdy       |
|            1 |     7262 | 2024-09-10 | Team Liquid          | L   | 0.044      | -            | -                | -                | -         |    -0.07 | gla1ve, Goofy, Kylar, podi, sdy       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,732.70)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-12-15 |      0.685 | $5,000.00      | $3,423.61       |
| 2024-11-24 |      0.544 | $7,992.37      | $4,348.07       |
| 2024-11-12 |      0.464 | $1,000.00      | $464.42         |
| 2024-10-20 |      0.311 | $100,000.00    | $31,062.50      |
| 2024-09-22 |      0.124 | $3,500.00      | $434.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
