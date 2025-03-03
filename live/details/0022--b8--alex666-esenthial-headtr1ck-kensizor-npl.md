### Roster Details<br />
Team Name: B8<br />
Roster: alex666, esenthial, headtr1ck, kensizor, npl<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1147.1<br />
<br />
Final Rank Value (1147.1) = Starting Rank Value (1112.7) + Head To Head Adjustments (34.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.526[<sup>1</sup>](#table2)
- Bounty Collected: 0.436[<sup>2</sup>](#table1)
- Opponent Network: 0.272[<sup>2</sup>](#table1)
- LAN Wins: 0.191[<sup>2</sup>](#table1)

The average of these factors is 0.356<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1112.7
- 400 + ( ( 0.356 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1112.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      104 | 2025-02-23 | BC.Game Esports    | W   | 1.000      | 0.435        | 0.078 (0.034)    | 0.945 (0.411)    | 0 (0.000) |    16.34 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           45 |      122 | 2025-02-23 | 9Pandas            | W   | 1.000      | 0.435        | 0.085 (0.037)    | 0.477 (0.207)    | 0 (0.000) |    12.80 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           44 |      170 | 2025-02-22 | CYBERSHOKE Esports | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |     9.10 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           43 |      254 | 2025-02-20 | Monte              | W   | 1.000      | 0.435        | 0.045 (0.019)    | 0.696 (0.302)    | 0 (0.000) |     9.12 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           42 |      436 | 2025-02-15 | 500                | L   | 1.000      | -            | -                | -                | -         |   -15.81 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           41 |      490 | 2025-02-14 | Nemiga Gaming      | W   | 1.000      | 0.435        | 0.176 (0.076)    | 0.345 (0.150)    | 0 (0.000) |    10.54 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           40 |      547 | 2025-02-12 | GUN5 Esports       | W   | 1.000      | 0.435        | 0.103 (0.045)    | 0.505 (0.219)    | -         |    10.46 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           39 |      775 | 2025-02-07 | Benched            | L   | 1.000      | -            | -                | -                | -         |   -30.18 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           38 |      818 | 2025-02-07 | PARIVISION         | L   | 1.000      | -            | -                | -                | -         |   -28.26 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           37 |      845 | 2025-02-06 | Alliance           | W   | 1.000      | 0.435        | -                | 0.570 (0.248)    | -         |     5.64 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           36 |      914 | 2025-02-05 | PARIVISION         | W   | 1.000      | -            | -                | -                | -         |     2.58 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           35 |      929 | 2025-02-05 | Nemiga Gaming      | W   | 1.000      | 0.143        | 0.176 (0.025)    | -                | -         |    10.51 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           34 |      952 | 2025-02-04 | Fire Flux Esports  | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     7.86 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           33 |     1053 | 2025-02-02 | Sashi Esport       | W   | 1.000      | 0.435        | -                | 0.499 (0.217)    | -         |     8.64 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           32 |     1179 | 2025-01-17 | G2 Esports         | L   | 0.906      | -            | -                | -                | -         |    -0.51 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           31 |     1859 | 2024-12-12 | ECSTATIC           | L   | 0.663      | -            | -                | -                | -         |   -16.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     3004 | 2024-11-22 | Astralis           | L   | 0.529      | -            | -                | -                | -         |    -0.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     3063 | 2024-11-21 | Aurora Gaming      | L   | 0.523      | -            | -                | -                | -         |   -14.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     3082 | 2024-11-20 | Team Spirit        | L   | 0.521      | -            | -                | -                | -         |    -0.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     4469 | 2024-10-27 | SAW                | L   | 0.358      | -            | -                | -                | -         |    -3.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     4483 | 2024-10-27 | PaiN Gaming        | W   | 0.357      | 0.500        | 0.323 (0.058)    | 0.549 (0.098)    | 1 (0.357) |    10.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           25 |     4525 | 2024-10-26 | Eternal Fire       | W   | 0.351      | 0.500        | 0.599 (0.105)    | -                | 1 (0.351) |    10.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           24 |     4608 | 2024-10-25 | SAW                | L   | 0.344      | -            | -                | -                | -         |    -2.73 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           23 |     4620 | 2024-10-25 | Eternal Fire       | W   | 0.343      | 0.500        | 0.599 (0.103)    | -                | 1 (0.343) |    10.64 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           22 |     4846 | 2024-10-19 | Team Falcons       | L   | 0.305      | -            | -                | -                | -         |    -0.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           21 |     4911 | 2024-10-18 | JANO Esports       | W   | 0.297      | -            | -                | -                | 1 (0.297) |     2.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           20 |     5021 | 2024-10-16 | The MongolZ        | L   | 0.284      | -            | -                | -                | -         |    -0.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           19 |     5024 | 2024-10-16 | Ninjas in Pyjamas  | W   | 0.283      | -            | -                | -                | 1 (0.283) |     1.78 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           18 |     5579 | 2024-10-05 | GamerLegion        | L   | 0.212      | -            | -                | -                | -         |    -0.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           17 |     5739 | 2024-10-03 | ALTERNATE aTTaX    | W   | 0.197      | -            | -                | -                | -         |     1.53 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           16 |     6032 | 2024-09-28 | 3DMAX              | W   | 0.165      | 0.143        | 0.298 (0.007)    | -                | -         |     4.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           15 |     6127 | 2024-09-27 | SAW                | W   | 0.158      | -            | -                | -                | -         |     3.90 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           14 |     6150 | 2024-09-27 | OG                 | W   | 0.157      | -            | -                | -                | -         |     1.22 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           13 |     6158 | 2024-09-27 | GamerLegion        | L   | 0.156      | -            | -                | -                | -         |    -4.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           12 |     6205 | 2024-09-26 | Fire Flux Esports  | W   | 0.151      | -            | -                | -                | -         |     0.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           11 |     6211 | 2024-09-26 | Illuminar Gaming   | W   | 0.151      | -            | -                | -                | -         |     0.95 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           10 |     6244 | 2024-09-26 | Insilio            | W   | 0.149      | -            | -                | -                | -         |     0.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            9 |     6289 | 2024-09-25 | BC.Game Esports    | W   | 0.145      | -            | -                | -                | -         |     0.81 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            8 |     6918 | 2024-09-16 | Team Sampi         | L   | 0.082      | -            | -                | -                | -         |    -2.20 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            7 |     7165 | 2024-09-12 | AMKAL ESPORTS      | L   | 0.055      | -            | -                | -                | -         |    -1.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            6 |     7358 | 2024-09-08 | GamerLegion        | W   | 0.031      | -            | -                | -                | -         |     0.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            5 |     7367 | 2024-09-08 | Zero Tenacity      | W   | 0.030      | -            | -                | -                | -         |     0.19 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            4 |     7438 | 2024-09-07 | BC.Game Esports    | W   | 0.024      | -            | -                | -                | -         |     0.30 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            3 |     7511 | 2024-09-06 | 9Pandas            | L   | 0.018      | -            | -                | -                | -         |    -0.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            2 |     7590 | 2024-09-05 | SINNERS Esports    | W   | 0.012      | -            | -                | -                | -         |     0.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            1 |     7633 | 2024-09-05 | 9INE               | W   | 0.010      | -            | -                | -                | -         |     0.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,361.81)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $22,000.00     | $22,000.00      |
| 2025-02-15 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-10-27 |      0.358 | $20,000.00     | $7,167.59       |
| 2024-10-20 |      0.311 | $3,500.00      | $1,087.43       |
| 2024-10-20 |      0.311 | $15,000.00     | $4,659.38       |
| 2024-10-06 |      0.218 | $2,000.00      | $436.53         |
| 2024-09-28 |      0.165 | $2,000.00      | $329.49         |
| 2024-09-08 |      0.031 | $22,000.00     | $681.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
