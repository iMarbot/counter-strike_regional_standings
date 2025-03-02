### Roster Details<br />
Team Name: TSM<br />
Roster: acoR, niko, sirah, valde, Zyphon<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
<br />
Final Rank Value:  755.1<br />
<br />
Final Rank Value (755.1) = Starting Rank Value (747.3) + Head To Head Adjustments (7.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.329[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.063[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.3
- 400 + ( ( 0.174 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 747.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     1848 | 2024-12-12 | 9INE                 | L   | 0.671      | -            | -                | -                | -         |    -6.31 | acoR, niko, sirah, valde, Zyphon  |
|           31 |     1931 | 2024-12-10 | Iberian Soul         | L   | 0.658      | -            | -                | -                | -         |    -6.99 | acoR, niko, sirah, valde, Zyphon  |
|           30 |     2023 | 2024-12-08 | Illuminar Gaming     | W   | 0.644      | 0.371        | 0.007 (0.002)    | 0.593 (0.141)    | 0 (0.000) |    12.05 | acoR, niko, sirah, valde, Zyphon  |
|           29 |     2136 | 2024-12-06 | Natus Vincere Junior | L   | 0.632      | -            | -                | -                | -         |    -4.14 | acoR, niko, sirah, valde, Zyphon  |
|           28 |     2349 | 2024-12-02 | Endpoint             | W   | 0.605      | 0.371        | 0.009 (0.002)    | 0.385 (0.086)    | 0 (0.000) |     9.47 | acoR, niko, sirah, valde, Zyphon  |
|           27 |     2912 | 2024-11-22 | Ninjas in Pyjamas    | L   | 0.544      | -            | -                | -                | -         |    -5.55 | acoR, niko, sirah, valde, Zyphon  |
|           26 |     2998 | 2024-11-21 | PARIVISION           | W   | 0.537      | 0.143        | 0.006 (0.000)    | -                | 1 (0.537) |     7.93 | acoR, niko, sirah, valde, Zyphon  |
|           25 |     3043 | 2024-11-21 | Virtus.pro           | L   | 0.532      | -            | -                | -                | -         |    -0.12 | acoR, niko, sirah, valde, Zyphon  |
|           24 |     3061 | 2024-11-20 | 3DMAX                | L   | 0.530      | -            | -                | -                | -         |    -0.17 | acoR, niko, sirah, valde, Zyphon  |
|           23 |     4522 | 2024-10-26 | Chimera Esports      | L   | 0.359      | -            | -                | -                | -         |    -4.11 | acoR, niko, sirah, valde, Zyphon  |
|           22 |     4949 | 2024-10-17 | HOTU                 | L   | 0.298      | -            | -                | -                | -         |    -5.30 | acoR, niko, sirah, valde, Zyphon  |
|           21 |     4996 | 2024-10-16 | 9Pandas              | L   | 0.293      | -            | -                | -                | -         |    -2.06 | acoR, niko, sirah, valde, Zyphon  |
|           20 |     5057 | 2024-10-15 | 3DMAX                | L   | 0.286      | -            | -                | -                | -         |    -0.09 | acoR, niko, sirah, valde, Zyphon  |
|           19 |     5423 | 2024-10-08 | FAVBET Team          | L   | 0.239      | -            | -                | -                | -         |    -3.03 | acoR, niko, sirah, valde, Zyphon  |
|           18 |     5522 | 2024-10-06 | G2 Ares              | W   | 0.226      | 0.435        | -                | 0.261 (0.026)    | 0 (0.000) |     2.89 | acoR, niko, sirah, valde, Zyphon  |
|           17 |     5629 | 2024-10-05 | Passion UA           | L   | 0.217      | -            | -                | -                | -         |    -1.21 | acoR, niko, sirah, valde, Zyphon  |
|           16 |     5670 | 2024-10-04 | ECSTATIC             | L   | 0.212      | -            | -                | -                | -         |    -2.20 | acoR, niko, sirah, valde, Zyphon  |
|           15 |     5690 | 2024-10-04 | GameAgents           | W   | 0.210      | -            | -                | -                | 0 (0.000) |     2.91 | acoR, niko, sirah, valde, Zyphon  |
|           14 |     5719 | 2024-10-03 | ALTERNATE aTTaX      | L   | 0.206      | -            | -                | -                | -         |    -1.91 | acoR, niko, sirah, valde, Zyphon  |
|           13 |     5738 | 2024-10-03 | Illuminar Gaming     | W   | 0.204      | 0.371        | 0.007 (0.001)    | 0.593 (0.045)    | 0 (0.000) |     4.24 | acoR, niko, sirah, valde, Zyphon  |
|           12 |     5805 | 2024-10-02 | Tricked Esport       | W   | 0.197      | 0.371        | 0.033 (0.002)    | 0.696 (0.051)    | 0 (0.000) |     3.75 | acoR, niko, sirah, valde, Zyphon  |
|           11 |     5876 | 2024-10-01 | GameAgents           | L   | 0.191      | -            | -                | -                | -         |    -3.41 | acoR, niko, sirah, valde, Zyphon  |
|           10 |     5928 | 2024-09-30 | Adventurers          | W   | 0.185      | 0.435        | 0.017 (0.001)    | 0.166 (0.013)    | 0 (0.000) |     3.12 | acoR, niko, sirah, valde, Zyphon  |
|            9 |     5978 | 2024-09-29 | Illuminar Gaming     | W   | 0.178      | 0.371        | 0.007 (0.000)    | 0.593 (0.039)    | 0 (0.000) |     3.68 | acoR, niko, sirah, valde, Zyphon  |
|            8 |     6269 | 2024-09-25 | Astralis Talent      | L   | 0.154      | -            | -                | -                | -         |    -2.28 | acoR, niko, sirah, valde, Zyphon  |
|            7 |     6313 | 2024-09-25 | Tricked Esport       | W   | 0.151      | 0.371        | 0.033 (0.002)    | 0.696 (0.039)    | 0 (0.000) |     2.92 | acoR, niko, sirah, valde, Zyphon  |
|            6 |     6600 | 2024-09-21 | Los kogutos          | W   | 0.124      | 0.371        | 0.032 (0.001)    | 0.527 (0.024)    | -         |     3.16 | acoR, niko, sirah, valde, Zyphon  |
|            5 |     7140 | 2024-09-12 | Sashi Esport         | L   | 0.065      | -            | -                | -                | -         |    -0.49 | acoR, Altekz, niko, sirah, Zyphon |
|            4 |     7252 | 2024-09-10 | ALTERNATE aTTaX      | W   | 0.052      | 0.384        | 0.021 (0.000)    | 0.564 (0.011)    | -         |     1.22 | acoR, Altekz, niko, valde, Zyphon |
|            3 |     7258 | 2024-09-10 | SAW                  | L   | 0.051      | -            | -                | -                | -         |    -0.06 | acoR, Altekz, niko, valde, Zyphon |
|            2 |     7684 | 2024-09-04 | Young Ninjas         | L   | 0.011      | -            | -                | -                | -         |    -0.28 | acoR, Altekz, niko, valde, Zyphon |
|            1 |     7743 | 2024-09-03 | B8                   | W   | 0.005      | -            | -                | -                | -         |     0.14 | acoR, Altekz, niko, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,077.50)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.319 | $6,000.00      | $1,913.33       |
| 2024-10-05 |      0.217 | $5,000.00      | $1,084.72       |
| 2024-09-14 |      0.079 | $1,000.00      | $79.44          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
