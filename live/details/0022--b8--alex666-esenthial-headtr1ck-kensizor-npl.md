### Roster Details<br />
Team Name: B8<br />
Roster: alex666, esenthial, headtr1ck, kensizor, npl<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1149.0<br />
<br />
Final Rank Value (1149.0) = Starting Rank Value (1114.5) + Head To Head Adjustments (34.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.525[<sup>1</sup>](#table2)
- Bounty Collected: 0.436[<sup>2</sup>](#table1)
- Opponent Network: 0.274[<sup>2</sup>](#table1)
- LAN Wins: 0.195[<sup>2</sup>](#table1)

The average of these factors is 0.358<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1114.5
- 400 + ( ( 0.358 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1114.5


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
|           47 |       89 | 2025-02-23 | BC.Game Esports    | W   | 1.000      | 0.435        | 0.077 (0.034)    | 0.945 (0.411)    | 0 (0.000) |    16.29 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           46 |      107 | 2025-02-23 | 9Pandas            | W   | 1.000      | 0.435        | 0.085 (0.037)    | 0.485 (0.211)    | 0 (0.000) |    12.82 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           45 |      158 | 2025-02-22 | CYBERSHOKE Esports | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |     9.08 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           44 |      242 | 2025-02-20 | Monte              | W   | 1.000      | 0.435        | 0.045 (0.019)    | 0.704 (0.306)    | 0 (0.000) |     9.13 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           43 |      424 | 2025-02-15 | 500                | L   | 1.000      | -            | -                | -                | -         |   -15.86 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           42 |      478 | 2025-02-14 | Nemiga Gaming      | W   | 1.000      | 0.435        | 0.177 (0.077)    | 0.351 (0.153)    | 0 (0.000) |    10.59 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           41 |      535 | 2025-02-12 | GUN5 Esports       | W   | 1.000      | 0.435        | 0.102 (0.044)    | 0.515 (0.224)    | -         |    10.48 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           40 |      763 | 2025-02-07 | Benched            | L   | 1.000      | -            | -                | -                | -         |   -30.19 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           39 |      806 | 2025-02-07 | PARIVISION         | L   | 1.000      | -            | -                | -                | -         |   -28.29 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           38 |      833 | 2025-02-06 | Alliance           | W   | 1.000      | 0.435        | -                | 0.573 (0.249)    | -         |     5.61 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           37 |      902 | 2025-02-05 | PARIVISION         | W   | 1.000      | -            | -                | -                | -         |     2.56 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           36 |      917 | 2025-02-05 | Nemiga Gaming      | W   | 1.000      | 0.143        | 0.177 (0.025)    | -                | -         |    10.57 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           35 |      940 | 2025-02-04 | Fire Flux Esports  | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     7.86 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           34 |     1041 | 2025-02-02 | Sashi Esport       | W   | 1.000      | 0.435        | -                | 0.503 (0.218)    | -         |     8.62 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           33 |     1167 | 2025-01-17 | G2 Esports         | L   | 0.914      | -            | -                | -                | -         |    -0.51 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           32 |     1847 | 2024-12-12 | ECSTATIC           | L   | 0.671      | -            | -                | -                | -         |   -16.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2992 | 2024-11-22 | Astralis           | L   | 0.538      | -            | -                | -                | -         |    -0.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     3051 | 2024-11-21 | Aurora Gaming      | L   | 0.531      | -            | -                | -                | -         |   -14.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     3070 | 2024-11-20 | Team Spirit        | L   | 0.529      | -            | -                | -                | -         |    -0.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     4457 | 2024-10-27 | SAW                | L   | 0.367      | -            | -                | -                | -         |    -3.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     4471 | 2024-10-27 | PaiN Gaming        | W   | 0.366      | 0.500        | 0.318 (0.058)    | 0.555 (0.102)    | 1 (0.366) |    10.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     4513 | 2024-10-26 | Eternal Fire       | W   | 0.359      | 0.500        | 0.591 (0.106)    | -                | 1 (0.359) |    11.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           25 |     4596 | 2024-10-25 | SAW                | L   | 0.352      | -            | -                | -                | -         |    -2.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           24 |     4608 | 2024-10-25 | Eternal Fire       | W   | 0.351      | 0.500        | 0.591 (0.104)    | -                | 1 (0.351) |    10.89 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           23 |     4834 | 2024-10-19 | Team Falcons       | L   | 0.313      | -            | -                | -                | -         |    -0.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           22 |     4899 | 2024-10-18 | JANO Esports       | W   | 0.305      | -            | -                | -                | 1 (0.305) |     2.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           21 |     5009 | 2024-10-16 | The MongolZ        | L   | 0.292      | -            | -                | -                | -         |    -0.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           20 |     5012 | 2024-10-16 | Ninjas in Pyjamas  | W   | 0.292      | -            | -                | -                | 1 (0.292) |     1.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           19 |     5567 | 2024-10-05 | GamerLegion        | L   | 0.220      | -            | -                | -                | -         |    -0.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           18 |     5727 | 2024-10-03 | ALTERNATE aTTaX    | W   | 0.205      | -            | -                | -                | -         |     1.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           17 |     6020 | 2024-09-28 | 3DMAX              | W   | 0.173      | 0.143        | 0.295 (0.007)    | -                | -         |     5.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           16 |     6115 | 2024-09-27 | SAW                | W   | 0.166      | -            | -                | -                | -         |     4.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           15 |     6138 | 2024-09-27 | OG                 | W   | 0.165      | -            | -                | -                | -         |     1.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           14 |     6146 | 2024-09-27 | GamerLegion        | L   | 0.165      | -            | -                | -                | -         |    -4.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           13 |     6193 | 2024-09-26 | Fire Flux Esports  | W   | 0.159      | -            | -                | -                | -         |     0.96 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           12 |     6199 | 2024-09-26 | Illuminar Gaming   | W   | 0.159      | -            | -                | -                | -         |     1.01 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           11 |     6232 | 2024-09-26 | Insilio            | W   | 0.157      | -            | -                | -                | -         |     0.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           10 |     6277 | 2024-09-25 | BC.Game Esports    | W   | 0.153      | -            | -                | -                | -         |     0.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            9 |     6906 | 2024-09-16 | Team Sampi         | L   | 0.090      | -            | -                | -                | -         |    -2.41 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            8 |     7153 | 2024-09-12 | AMKAL ESPORTS      | L   | 0.064      | -            | -                | -                | -         |    -1.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            7 |     7346 | 2024-09-08 | GamerLegion        | W   | 0.039      | -            | -                | -                | -         |     0.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            6 |     7355 | 2024-09-08 | Zero Tenacity      | W   | 0.038      | -            | -                | -                | -         |     0.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            5 |     7426 | 2024-09-07 | BC.Game Esports    | W   | 0.032      | -            | -                | -                | -         |     0.40 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            4 |     7499 | 2024-09-06 | 9Pandas            | L   | 0.026      | -            | -                | -                | -         |    -0.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            3 |     7578 | 2024-09-05 | SINNERS Esports    | W   | 0.020      | -            | -                | -                | -         |     0.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            2 |     7621 | 2024-09-05 | 9INE               | W   | 0.018      | -            | -                | -                | -         |     0.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            1 |     7743 | 2024-09-03 | TSM                | L   | 0.005      | -            | -                | -                | -         |    -0.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,890.35)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $22,000.00     | $22,000.00      |
| 2025-02-15 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-10-27 |      0.367 | $20,000.00     | $7,331.48       |
| 2024-10-20 |      0.319 | $3,500.00      | $1,116.11       |
| 2024-10-20 |      0.319 | $15,000.00     | $4,782.29       |
| 2024-10-06 |      0.226 | $2,000.00      | $452.92         |
| 2024-09-28 |      0.173 | $2,000.00      | $345.88         |
| 2024-09-08 |      0.039 | $22,000.00     | $861.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
