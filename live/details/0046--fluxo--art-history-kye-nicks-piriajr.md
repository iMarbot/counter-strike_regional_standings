### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, history, kye, nicks, piriajr<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [12]( ../standings_americas.md)<br />
<br />
Final Rank Value:  986.9<br />
<br />
Final Rank Value (986.9) = Starting Rank Value (929.6) + Head To Head Adjustments (57.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.443[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.162[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 929.6
- 400 + ( ( 0.265 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 929.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |      125 | 2025-02-22 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |   -12.32 | arT, history, kye, nicks, piriajr |
|           56 |      179 | 2025-02-21 | Team Solid             | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.561 (0.208)    | 0 (0.000) |    11.36 | arT, history, kye, nicks, piriajr |
|           55 |      523 | 2025-02-12 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -15.72 | arT, history, kye, nicks, piriajr |
|           54 |      527 | 2025-02-12 | Sharks Esports         | W   | 1.000      | 0.143        | 0.054 (0.008)    | 0.629 (0.090)    | 0 (0.000) |    15.89 | arT, history, kye, nicks, piriajr |
|           53 |      544 | 2025-02-11 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -16.44 | arT, history, kye, nicks, piriajr |
|           52 |      550 | 2025-02-11 | Imperial Esports       | W   | 1.000      | 0.143        | 0.091 (0.013)    | 0.564 (0.081)    | 0 (0.000) |    19.50 | arT, history, kye, nicks, piriajr |
|           51 |      706 | 2025-02-08 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |   -14.57 | arT, history, kye, nicks, piriajr |
|           50 |     1179 | 2025-01-16 | Eternal Fire           | L   | 0.905      | -            | -                | -                | -         |    -0.28 | arT, history, kye, nicks, piriajr |
|           49 |     2462 | 2024-11-30 | ODDIK                  | W   | 0.595      | 0.371        | 0.028 (0.006)    | 0.521 (0.115)    | 0 (0.000) |     6.04 | arT, kye, nicks, piriajr, zevy    |
|           48 |     2514 | 2024-11-30 | Team Solid             | W   | 0.593      | 0.371        | -                | 0.561 (0.123)    | 0 (0.000) |     6.41 | arT, kye, nicks, piriajr, zevy    |
|           47 |     2574 | 2024-11-29 | TROPA DO TACO          | W   | 0.587      | 0.371        | -                | 0.381 (0.083)    | 0 (0.000) |     4.41 | arT, kye, nicks, piriajr, zevy    |
|           46 |     2652 | 2024-11-27 | Yawara E-Sports        | W   | 0.575      | 0.371        | -                | 0.454 (0.097)    | 0 (0.000) |     3.29 | arT, kye, nicks, piriajr, zevy    |
|           45 |     2773 | 2024-11-24 | Team Solid             | W   | 0.554      | -            | -                | -                | 1 (0.554) |     6.17 | arT, kye, nicks, piriajr, zevy    |
|           44 |     2928 | 2024-11-22 | Sharks Esports         | W   | 0.542      | -            | -                | -                | 1 (0.542) |     9.54 | arT, kye, nicks, piriajr, zevy    |
|           43 |     3691 | 2024-11-09 | Sharks Esports         | W   | 0.455      | 0.371        | 0.054 (0.009)    | 0.629 (0.106)    | -         |     8.35 | arT, kye, nicks, piriajr, zevy    |
|           42 |     3698 | 2024-11-09 | ODDIK                  | W   | 0.454      | 0.371        | -                | 0.521 (0.088)    | -         |     5.22 | arT, kye, nicks, piriajr, zevy    |
|           41 |     3773 | 2024-11-08 | TROPA DO TACO          | W   | 0.448      | -            | -                | -                | -         |     3.30 | arT, kye, nicks, piriajr, zevy    |
|           40 |     3894 | 2024-11-06 | 9z Academy             | W   | 0.432      | -            | -                | -                | -         |     2.65 | arT, kye, nicks, piriajr, zevy    |
|           39 |     3918 | 2024-11-05 | Bounty Hunters Esports | W   | 0.427      | -            | -                | -                | -         |     2.98 | arT, kye, nicks, piriajr, zevy    |
|           38 |     3965 | 2024-11-04 | Galorys Academy        | W   | 0.422      | -            | -                | -                | -         |     1.86 | arT, kye, nicks, piriajr, zevy    |
|           37 |     4030 | 2024-11-03 | América eSports        | W   | 0.414      | -            | -                | -                | -         |     1.71 | arT, kye, nicks, piriajr, zevy    |
|           36 |     4101 | 2024-11-02 | AdalYamigos            | W   | 0.408      | -            | -                | -                | -         |     3.31 | arT, kye, nicks, piriajr, zevy    |
|           35 |     4163 | 2024-11-01 | Sharks Esports         | L   | 0.402      | -            | -                | -                | -         |    -4.88 | arT, kye, nicks, piriajr, zevy    |
|           34 |     4225 | 2024-10-31 | UNO MILLE              | W   | 0.395      | -            | -                | -                | -         |     3.12 | arT, kye, nicks, piriajr, zevy    |
|           33 |     4296 | 2024-10-30 | Intense Game           | W   | 0.387      | -            | -                | -                | -         |     2.33 | arT, kye, nicks, piriajr, zevy    |
|           32 |     4335 | 2024-10-29 | ODDIK                  | W   | 0.382      | -            | -                | -                | -         |     4.32 | arT, kye, nicks, piriajr, zevy    |
|           31 |     4388 | 2024-10-28 | Team Solid             | L   | 0.375      | -            | -                | -                | -         |    -7.58 | arT, kye, nicks, piriajr, zevy    |
|           30 |     4498 | 2024-10-26 | Sharks Esports         | L   | 0.361      | -            | -                | -                | -         |    -4.45 | arT, kye, nicks, piriajr, zevy    |
|           29 |     4905 | 2024-10-18 | Nemiga Gaming          | L   | 0.304      | -            | -                | -                | -         |    -3.77 | arT, kye, nicks, piriajr, zevy    |
|           28 |     4945 | 2024-10-17 | HEROIC                 | L   | 0.298      | -            | -                | -                | -         |    -2.91 | arT, kye, nicks, piriajr, zevy    |
|           27 |     5027 | 2024-10-16 | Aurora Gaming          | W   | 0.290      | 0.624        | -                | 0.516 (0.093)    | 1 (0.290) |     2.99 | arT, kye, nicks, piriajr, zevy    |
|           26 |     5388 | 2024-10-08 | AdalYamigos            | L   | 0.241      | -            | -                | -                | -         |    -5.74 | arT, kye, nicks, piriajr, zevy    |
|           25 |     5399 | 2024-10-08 | AdalYamigos            | L   | 0.241      | -            | -                | -                | -         |    -5.82 | arT, kye, nicks, piriajr, zevy    |
|           24 |     5645 | 2024-10-04 | MIBR                   | W   | 0.214      | 0.450        | 0.141 (0.014)    | -                | -         |     6.33 | arT, kye, nicks, piriajr, zevy    |
|           23 |     5647 | 2024-10-04 | MIBR                   | L   | 0.214      | -            | -                | -                | -         |    -0.42 | arT, kye, nicks, piriajr, zevy    |
|           22 |     5748 | 2024-10-02 | PaiN Gaming            | W   | 0.201      | 0.450        | 0.318 (0.029)    | -                | -         |     6.21 | arT, kye, nicks, piriajr, zevy    |
|           21 |     5754 | 2024-10-02 | PaiN Gaming            | W   | 0.201      | 0.450        | 0.318 (0.029)    | -                | -         |     6.21 | arT, kye, nicks, piriajr, zevy    |
|           20 |     5885 | 2024-09-30 | Imperial Esports       | W   | 0.188      | 0.450        | 0.091 (0.008)    | -                | -         |     3.40 | arT, kye, nicks, piriajr, zevy    |
|           19 |     5888 | 2024-09-30 | Imperial Esports       | W   | 0.188      | 0.450        | 0.091 (0.008)    | -                | -         |     3.45 | arT, kye, nicks, piriajr, zevy    |
|           18 |     5943 | 2024-09-29 | PaiN Gaming            | L   | 0.181      | -            | -                | -                | -         |    -0.10 | arT, kye, nicks, piriajr, zevy    |
|           17 |     5995 | 2024-09-28 | Team Solid             | W   | 0.175      | -            | -                | -                | -         |     2.09 | arT, kye, nicks, piriajr, zevy    |
|           16 |     6003 | 2024-09-28 | RED Canids             | W   | 0.173      | -            | -                | -                | -         |     2.16 | arT, kye, nicks, piriajr, zevy    |
|           15 |     6087 | 2024-09-27 | Dusty Roots            | W   | 0.168      | -            | -                | -                | -         |     1.71 | arT, kye, nicks, piriajr, zevy    |
|           14 |     6092 | 2024-09-27 | Hype Esports           | W   | 0.168      | -            | -                | -                | -         |     1.05 | arT, kye, nicks, piriajr, zevy    |
|           13 |     6103 | 2024-09-27 | Floripa Stars          | W   | 0.167      | -            | -                | -                | -         |     0.95 | arT, kye, nicks, piriajr, zevy    |
|           12 |     6252 | 2024-09-25 | RED Canids             | W   | 0.154      | -            | -                | -                | -         |     1.97 | arT, kye, nicks, piriajr, zevy    |
|           11 |     6258 | 2024-09-25 | RED Canids             | W   | 0.154      | -            | -                | -                | -         |     2.00 | arT, kye, nicks, piriajr, zevy    |
|           10 |     6345 | 2024-09-24 | KRÜ Esports            | L   | 0.148      | -            | -                | -                | -         |    -3.63 | arT, kye, nicks, piriajr, zevy    |
|            9 |     6351 | 2024-09-24 | KRÜ Esports            | L   | 0.147      | -            | -                | -                | -         |    -3.65 | arT, kye, nicks, piriajr, zevy    |
|            8 |     6371 | 2024-09-24 | RED Canids             | L   | 0.146      | -            | -                | -                | -         |    -3.62 | arT, kye, nicks, piriajr, zevy    |
|            7 |     6390 | 2024-09-24 | InSanitY Sports        | W   | 0.146      | -            | -                | -                | -         |     0.86 | arT, kye, nicks, piriajr, zevy    |
|            6 |     6430 | 2024-09-23 | ODDIK                  | W   | 0.141      | -            | -                | -                | -         |     1.57 | arT, kye, nicks, piriajr, zevy    |
|            5 |     6432 | 2024-09-23 | ODDIK                  | W   | 0.141      | -            | -                | -                | -         |     1.59 | arT, kye, nicks, piriajr, zevy    |
|            4 |     6464 | 2024-09-23 | RED Canids             | L   | 0.140      | -            | -                | -                | -         |    -3.47 | arT, kye, nicks, piriajr, zevy    |
|            3 |     7634 | 2024-09-04 | ODDIK                  | W   | 0.015      | -            | -                | -                | -         |     0.17 | arT, kye, Lucaozy, nicks, zevy    |
|            2 |     7660 | 2024-09-04 | BESTIA                 | W   | 0.013      | -            | -                | -                | -         |     0.20 | arT, kye, Lucaozy, nicks, zevy    |
|            1 |     7704 | 2024-09-03 | Galorys                | W   | 0.007      | -            | -                | -                | -         |     0.02 | arT, kye, Lucaozy, nicks, zevy    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,704.21)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-11-30 |      0.595 | $10,000.00     | $5,946.53       |
| 2024-11-24 |      0.554 | $10,342.97     | $5,727.18       |
| 2024-11-09 |      0.455 | $10,000.00     | $4,548.38       |
| 2024-10-27 |      0.367 | $1,226.46      | $450.04         |
| 2024-10-20 |      0.320 | $1,200.00      | $384.17         |
| 2024-09-04 |      0.015 | $10,000.00     | $147.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
