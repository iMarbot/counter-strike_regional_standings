### Roster Details<br />
Team Name: TSM<br />
Roster: acoR, niko, sirah, valde, Zyphon<br />
Global Rank: [158](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
<br />
Final Rank Value:  752.8<br />
<br />
Final Rank Value (752.8) = Starting Rank Value (745.4) + Head To Head Adjustments (7.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.329[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.173<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 745.4
- 400 + ( ( 0.173 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 745.4


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
|           31 |     1860 | 2024-12-12 | 9INE                 | L   | 0.663      | -            | -                | -                | -         |    -6.20 | acoR, niko, sirah, valde, Zyphon  |
|           30 |     1943 | 2024-12-10 | Iberian Soul         | L   | 0.650      | -            | -                | -                | -         |    -6.89 | acoR, niko, sirah, valde, Zyphon  |
|           29 |     2035 | 2024-12-08 | Illuminar Gaming     | W   | 0.636      | 0.371        | 0.007 (0.002)    | 0.581 (0.137)    | 0 (0.000) |    11.93 | acoR, niko, sirah, valde, Zyphon  |
|           28 |     2148 | 2024-12-06 | Natus Vincere Junior | L   | 0.623      | -            | -                | -                | -         |    -4.09 | acoR, niko, sirah, valde, Zyphon  |
|           27 |     2361 | 2024-12-02 | Endpoint             | W   | 0.597      | 0.371        | 0.009 (0.002)    | 0.377 (0.083)    | 0 (0.000) |     9.38 | acoR, niko, sirah, valde, Zyphon  |
|           26 |     2924 | 2024-11-22 | Ninjas in Pyjamas    | L   | 0.535      | -            | -                | -                | -         |    -5.50 | acoR, niko, sirah, valde, Zyphon  |
|           25 |     3010 | 2024-11-21 | PARIVISION           | W   | 0.528      | 0.143        | 0.006 (0.000)    | -                | 1 (0.528) |     7.81 | acoR, niko, sirah, valde, Zyphon  |
|           24 |     3055 | 2024-11-21 | Virtus.pro           | L   | 0.524      | -            | -                | -                | -         |    -0.12 | acoR, niko, sirah, valde, Zyphon  |
|           23 |     3073 | 2024-11-20 | 3DMAX                | L   | 0.522      | -            | -                | -                | -         |    -0.17 | acoR, niko, sirah, valde, Zyphon  |
|           22 |     4534 | 2024-10-26 | Chimera Esports      | L   | 0.350      | -            | -                | -                | -         |    -4.01 | acoR, niko, sirah, valde, Zyphon  |
|           21 |     4961 | 2024-10-17 | HOTU                 | L   | 0.290      | -            | -                | -                | -         |    -5.13 | acoR, niko, sirah, valde, Zyphon  |
|           20 |     5008 | 2024-10-16 | 9Pandas              | L   | 0.285      | -            | -                | -                | -         |    -2.00 | acoR, niko, sirah, valde, Zyphon  |
|           19 |     5069 | 2024-10-15 | 3DMAX                | L   | 0.278      | -            | -                | -                | -         |    -0.09 | acoR, niko, sirah, valde, Zyphon  |
|           18 |     5435 | 2024-10-08 | FAVBET Team          | L   | 0.231      | -            | -                | -                | -         |    -2.91 | acoR, niko, sirah, valde, Zyphon  |
|           17 |     5534 | 2024-10-06 | G2 Ares              | W   | 0.217      | 0.435        | -                | 0.257 (0.024)    | 0 (0.000) |     2.80 | acoR, niko, sirah, valde, Zyphon  |
|           16 |     5641 | 2024-10-05 | Passion UA           | L   | 0.209      | -            | -                | -                | -         |    -1.16 | acoR, niko, sirah, valde, Zyphon  |
|           15 |     5682 | 2024-10-04 | ECSTATIC             | L   | 0.204      | -            | -                | -                | -         |    -2.11 | acoR, niko, sirah, valde, Zyphon  |
|           14 |     5702 | 2024-10-04 | GameAgents           | W   | 0.202      | -            | -                | -                | 0 (0.000) |     2.78 | acoR, niko, sirah, valde, Zyphon  |
|           13 |     5731 | 2024-10-03 | ALTERNATE aTTaX      | L   | 0.198      | -            | -                | -                | -         |    -1.83 | acoR, niko, sirah, valde, Zyphon  |
|           12 |     5750 | 2024-10-03 | Illuminar Gaming     | W   | 0.195      | 0.371        | 0.007 (0.000)    | 0.581 (0.042)    | 0 (0.000) |     4.07 | acoR, niko, sirah, valde, Zyphon  |
|           11 |     5817 | 2024-10-02 | Tricked Esport       | W   | 0.189      | 0.371        | 0.034 (0.002)    | 0.687 (0.048)    | 0 (0.000) |     3.60 | acoR, niko, sirah, valde, Zyphon  |
|           10 |     5888 | 2024-10-01 | GameAgents           | L   | 0.183      | -            | -                | -                | -         |    -3.28 | acoR, niko, sirah, valde, Zyphon  |
|            9 |     5940 | 2024-09-30 | Adventurers          | W   | 0.176      | 0.435        | 0.016 (0.001)    | 0.161 (0.012)    | 0 (0.000) |     2.99 | acoR, niko, sirah, valde, Zyphon  |
|            8 |     5990 | 2024-09-29 | Illuminar Gaming     | W   | 0.170      | 0.371        | 0.007 (0.000)    | 0.581 (0.036)    | 0 (0.000) |     3.51 | acoR, niko, sirah, valde, Zyphon  |
|            7 |     6281 | 2024-09-25 | Astralis Talent      | L   | 0.145      | -            | -                | -                | -         |    -2.15 | acoR, niko, sirah, valde, Zyphon  |
|            6 |     6325 | 2024-09-25 | Tricked Esport       | W   | 0.143      | 0.371        | 0.034 (0.002)    | 0.687 (0.036)    | 0 (0.000) |     2.77 | acoR, niko, sirah, valde, Zyphon  |
|            5 |     6612 | 2024-09-21 | Los kogutos          | W   | 0.115      | 0.371        | 0.032 (0.001)    | 0.515 (0.022)    | -         |     2.94 | acoR, niko, sirah, valde, Zyphon  |
|            4 |     7152 | 2024-09-12 | Sashi Esport         | L   | 0.057      | -            | -                | -                | -         |    -0.42 | acoR, Altekz, niko, sirah, Zyphon |
|            3 |     7264 | 2024-09-10 | ALTERNATE aTTaX      | W   | 0.044      | 0.384        | 0.021 (0.000)    | 0.552 (0.009)    | -         |     1.02 | acoR, Altekz, niko, valde, Zyphon |
|            2 |     7270 | 2024-09-10 | SAW                  | L   | 0.043      | -            | -                | -                | -         |    -0.05 | acoR, Altekz, niko, valde, Zyphon |
|            1 |     7696 | 2024-09-04 | Young Ninjas         | L   | 0.003      | -            | -                | -                | -         |    -0.07 | acoR, Altekz, niko, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,979.17)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.311 | $6,000.00      | $1,864.17       |
| 2024-10-05 |      0.209 | $5,000.00      | $1,043.75       |
| 2024-09-14 |      0.071 | $1,000.00      | $71.25          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
