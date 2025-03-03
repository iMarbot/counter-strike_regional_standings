### Roster Details<br />
Team Name: 9z Team<br />
Roster: adamS, HUASOPEEK, Luken, Martinez, max<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [30]( ../standings_americas.md)<br />
<br />
Final Rank Value:  753.0<br />
<br />
Final Rank Value (753.0) = Starting Rank Value (777.3) + Head To Head Adjustments (-24.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.355[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.144[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.3
- 400 + ( ( 0.189 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 777.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      271 | 2025-02-19 | ODDIK         | L   | 1.000      | -            | -                | -                | -         |   -10.33 | adamS, HUASOPEEK, Luken, Martinez, max |
|           22 |      835 | 2025-02-06 | Elevate       | L   | 1.000      | -            | -                | -                | -         |   -23.14 | HUASOPEEK, Luken, Martinez, max, yel   |
|           21 |      883 | 2025-02-05 | RED Canids    | L   | 1.000      | -            | -                | -                | -         |   -12.62 | dgt, HUASOPEEK, Luken, Martinez, max   |
|           20 |      910 | 2025-02-05 | Tropa do VSM  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |     4.96 | dgt, HUASOPEEK, Luken, Martinez, max   |
|           19 |     3425 | 2024-11-15 | FURIA         | L   | 0.483      | -            | -                | -                | -         |    -0.41 | buda, dgt, HUASOPEEK, Martinez, max    |
|           18 |     3493 | 2024-11-13 | PaiN Gaming   | L   | 0.475      | -            | -                | -                | -         |    -0.17 | buda, dgt, HUASOPEEK, Martinez, max    |
|           17 |     3537 | 2024-11-12 | Wildcard      | L   | 0.468      | -            | -                | -                | -         |    -0.69 | buda, dgt, HUASOPEEK, Martinez, max    |
|           16 |     3574 | 2024-11-12 | Legacy        | W   | 0.463      | 0.143        | 0.036 (0.002)    | 0.549 (0.036)    | 1 (0.463) |     9.65 | buda, dgt, HUASOPEEK, Martinez, max    |
|           15 |     3586 | 2024-11-11 | RED Canids    | W   | 0.462      | 0.143        | 0.020 (0.001)    | 0.191 (0.013)    | 1 (0.462) |     8.85 | buda, dgt, HUASOPEEK, Martinez, max    |
|           14 |     4717 | 2024-10-22 | Cloud9        | L   | 0.324      | -            | -                | -                | -         |    -3.63 | buda, dgt, HUASOPEEK, Martinez, max    |
|           13 |     4723 | 2024-10-22 | Fnatic        | L   | 0.323      | -            | -                | -                | -         |    -1.79 | buda, dgt, HUASOPEEK, Martinez, max    |
|           12 |     4903 | 2024-10-18 | ENCE          | L   | 0.298      | -            | -                | -                | -         |    -2.12 | buda, dgt, HUASOPEEK, Martinez, max    |
|           11 |     4941 | 2024-10-17 | Rebels Gaming | W   | 0.291      | 0.589        | 0.009 (0.001)    | 0.298 (0.051)    | 1 (0.291) |     3.99 | buda, dgt, HUASOPEEK, Martinez, max    |
|           10 |     4960 | 2024-10-17 | ENCE          | L   | 0.290      | -            | -                | -                | -         |    -2.07 | buda, dgt, HUASOPEEK, Martinez, max    |
|            9 |     5438 | 2024-10-08 | Virtus.pro    | L   | 0.230      | -            | -                | -                | -         |    -0.05 | buda, dgt, HUASOPEEK, Martinez, max    |
|            8 |     5490 | 2024-10-07 | Team Vitality | L   | 0.224      | -            | -                | -                | -         |    -0.01 | buda, dgt, HUASOPEEK, Martinez, max    |
|            7 |     6033 | 2024-09-28 | SAW           | L   | 0.165      | -            | -                | -                | -         |    -0.22 | buda, dgt, HUASOPEEK, Martinez, max    |
|            6 |     6065 | 2024-09-28 | GameAgents    | W   | 0.164      | 0.143        | 0.003 (0.000)    | 0.111 (0.003)    | 0 (0.000) |     2.01 | buda, dgt, HUASOPEEK, Martinez, max    |
|            5 |     6132 | 2024-09-27 | 3DMAX         | L   | 0.158      | -            | -                | -                | -         |    -0.05 | buda, dgt, HUASOPEEK, Martinez, max    |
|            4 |     6151 | 2024-09-27 | Alliance      | W   | 0.157      | 0.143        | 0.015 (0.000)    | 0.570 (0.013)    | 0 (0.000) |     3.28 | buda, dgt, HUASOPEEK, Martinez, max    |
|            3 |     7467 | 2024-09-07 | The MongolZ   | L   | 0.023      | -            | -                | -                | -         |    -0.00 | buda, dgt, HUASOPEEK, Martinez, max    |
|            2 |     7544 | 2024-09-06 | 3DMAX         | L   | 0.016      | -            | -                | -                | -         |    -0.01 | buda, dgt, HUASOPEEK, Martinez, max    |
|            1 |     7617 | 2024-09-05 | Wildcard      | W   | 0.011      | 0.889        | 0.178 (0.002)    | 0.422 (0.004)    | 1 (0.011) |     0.32 | buda, dgt, HUASOPEEK, Martinez, max    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,032.78)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.311 | $10,000.00     | $3,106.25       |
| 2024-10-13 |      0.265 | $4,000.00      | $1,058.33       |
| 2024-09-22 |      0.124 | $7,000.00      | $868.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
