### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Neityu, podi, sdy, xKacpersky<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  998.3<br />
<br />
Final Rank Value (998.3) = Starting Rank Value (1006.1) + Head To Head Adjustments (-7.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.536[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.116[<sup>2</sup>](#table1)
- LAN Wins: 0.144[<sup>2</sup>](#table1)

The average of these factors is 0.303<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1006.1
- 400 + ( ( 0.303 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1006.1


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
|           25 |      219 | 2025-02-21 | Natus Vincere Junior | L   | 1.000      | -            | -                | -                | -         |   -17.52 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           24 |      419 | 2025-02-15 | Partizan Esports     | L   | 1.000      | -            | -                | -                | -         |   -15.13 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           23 |      467 | 2025-02-14 | Passion UA           | W   | 1.000      | 0.435        | 0.044 (0.019)    | 0.557 (0.242)    | 0 (0.000) |    18.24 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           22 |      531 | 2025-02-12 | Alliance             | W   | 1.000      | 0.435        | 0.015 (0.007)    | 0.573 (0.249)    | 0 (0.000) |     9.91 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           21 |      680 | 2025-02-08 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |   -22.09 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           20 |      693 | 2025-02-08 | AgenciUSB            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.70 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           19 |      745 | 2025-02-07 | Boiets Esports Club  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.93 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           18 |      797 | 2025-02-07 | 9INE                 | L   | 1.000      | -            | -                | -                | -         |   -19.23 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           17 |      903 | 2025-02-05 | 9INE                 | W   | 1.000      | 0.143        | 0.037 (0.005)    | 0.839 (0.120)    | 0 (0.000) |    11.07 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           16 |     1182 | 2025-01-15 | Team Falcons         | L   | 0.899      | -            | -                | -                | -         |    -0.25 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           15 |     1631 | 2024-12-15 | Team Spirit Academy  | L   | 0.692      | -            | -                | -                | -         |   -12.33 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           14 |     1682 | 2024-12-14 | AMKAL ESPORTS        | W   | 0.687      | 0.435        | 0.017 (0.005)    | 0.383 (0.114)    | 0 (0.000) |     5.40 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           13 |     1842 | 2024-12-12 | Endpoint             | W   | 0.672      | 0.435        | 0.009 (0.003)    | 0.385 (0.112)    | -         |     3.38 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           12 |     2793 | 2024-11-24 | Monte                | W   | 0.552      | 0.143        | 0.029 (0.002)    | -                | -         |     5.55 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           11 |     2872 | 2024-11-23 | Zero Tenacity        | W   | 0.546      | 0.143        | -                | 0.692 (0.054)    | -         |     5.44 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           10 |     3619 | 2024-11-11 | 500                  | L   | 0.465      | -            | -                | -                | -         |    -7.47 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            9 |     3728 | 2024-11-09 | Wild Lotus           | W   | 0.452      | 0.143        | -                | 0.444 (0.029)    | -         |     2.90 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            8 |     4797 | 2024-10-20 | Team Falcons         | W   | 0.319      | 0.589        | 0.927 (0.174)    | 0.613 (0.115)    | 1 (0.319) |     9.98 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            7 |     4851 | 2024-10-19 | The MongolZ          | W   | 0.312      | 0.589        | 1.000 (0.184)    | 0.579 (0.106)    | 1 (0.312) |     9.77 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            6 |     4891 | 2024-10-18 | 9z Team              | W   | 0.306      | 0.589        | 0.015 (0.003)    | 0.121 (0.022)    | 1 (0.306) |     2.20 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            5 |     4939 | 2024-10-17 | Team Falcons         | L   | 0.299      | -            | -                | -                | -         |    -0.06 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            4 |     4948 | 2024-10-17 | 9z Team              | W   | 0.298      | 0.589        | 0.015 (0.003)    | -                | 1 (0.298) |     2.14 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            3 |     7077 | 2024-09-13 | ATOX Esports         | L   | 0.073      | -            | -                | -                | -         |    -0.84 | gla1ve, Goofy, Kylar, podi, sdy       |
|            2 |     7138 | 2024-09-12 | RED Canids           | L   | 0.065      | -            | -                | -                | -         |    -1.45 | gla1ve, Goofy, Kylar, podi, sdy       |
|            1 |     7250 | 2024-09-10 | Team Liquid          | L   | 0.052      | -            | -                | -                | -         |    -0.09 | gla1ve, Goofy, Kylar, podi, sdy       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,695.49)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-12-15 |      0.693 | $5,000.00      | $3,464.58       |
| 2024-11-24 |      0.552 | $7,992.37      | $4,413.56       |
| 2024-11-12 |      0.473 | $1,000.00      | $472.62         |
| 2024-10-20 |      0.319 | $100,000.00    | $31,881.94      |
| 2024-09-22 |      0.132 | $3,500.00      | $462.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
