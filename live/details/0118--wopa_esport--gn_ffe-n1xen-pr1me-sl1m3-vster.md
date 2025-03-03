### Roster Details<br />
Team Name: WOPA Esport<br />
Roster: Gnøffe, n1Xen, PR1mE, sL1m3, Vster<br />
Global Rank: [118](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  802.3<br />
<br />
Final Rank Value (802.3) = Starting Rank Value (856.5) + Head To Head Adjustments (-54.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.400[<sup>1</sup>](#table2)
- Bounty Collected: 0.294[<sup>2</sup>](#table1)
- Opponent Network: 0.156[<sup>2</sup>](#table1)
- LAN Wins: 0.063[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 856.5
- 400 + ( ( 0.228 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 856.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           68 |      340 | 2025-02-16 | GenOne                    | L   | 1.000      | -            | -                | -                | -         |   -14.12 | Gnøffe, n1Xen, PR1mE, sL1m3, Vster |
|           67 |     1230 | 2025-01-06 | BadGuys                   | L   | 0.830      | -            | -                | -                | -         |   -18.71 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           66 |     1234 | 2025-01-05 | Wu-Tang Clan              | W   | 0.823      | -            | -                | -                | 0 (0.000) |     7.26 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           65 |     1271 | 2024-12-29 | CS2NEWS                   | L   | 0.777      | -            | -                | -                | -         |   -20.70 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           64 |     1314 | 2024-12-28 | EYEBALLERS                | L   | 0.770      | -            | -                | -                | -         |   -15.00 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           63 |     1366 | 2024-12-25 | KONO.ECF                  | L   | 0.750      | -            | -                | -                | -         |   -10.05 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           62 |     1374 | 2024-12-24 | ENCE Academy              | W   | 0.743      | 0.333        | 0.009 (0.002)    | 0.649 (0.161)    | 0 (0.000) |     9.63 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           61 |     1378 | 2024-12-24 | ALASKA                    | L   | 0.743      | -            | -                | -                | -         |   -10.13 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           60 |     1389 | 2024-12-23 | ESC Gaming                | W   | 0.737      | -            | -                | -                | 0 (0.000) |     4.20 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           59 |     1391 | 2024-12-23 | Heimo Esports             | W   | 0.736      | 0.333        | 0.004 (0.001)    | 0.651 (0.160)    | 0 (0.000) |     7.55 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           58 |     1410 | 2024-12-22 | ADEPTS                    | W   | 0.731      | -            | -                | -                | 0 (0.000) |     4.95 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           57 |     1432 | 2024-12-22 | Astralis Talent           | W   | 0.729      | 0.333        | -                | 0.724 (0.176)    | 0 (0.000) |     9.42 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           56 |     1468 | 2024-12-21 | ALASKA                    | W   | 0.724      | 0.333        | 0.031 (0.007)    | 0.867 (0.209)    | 0 (0.000) |    13.86 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           55 |     1495 | 2024-12-21 | KONO.ECF                  | W   | 0.723      | 0.333        | 0.046 (0.011)    | 0.747 (0.180)    | 0 (0.000) |    13.07 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           54 |     1529 | 2024-12-20 | Heimo Esports             | L   | 0.717      | -            | -                | -                | -         |   -14.22 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           53 |     1569 | 2024-12-18 | Viperio                   | W   | 0.703      | 0.333        | -                | 0.404 (0.095)    | 0 (0.000) |     8.11 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           52 |     1574 | 2024-12-18 | ESC Gaming                | L   | 0.703      | -            | -                | -                | -         |   -17.93 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           51 |     1603 | 2024-12-16 | Lilmix                    | W   | 0.690      | -            | -                | -                | -         |     3.99 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           50 |     1778 | 2024-12-13 | LEON Esports              | L   | 0.672      | -            | -                | -                | -         |   -13.02 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           49 |     1837 | 2024-12-12 | AMKAL ESPORTS             | W   | 0.666      | 0.333        | -                | 0.674 (0.149)    | -         |    10.11 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           48 |     1861 | 2024-12-12 | GenOne                    | W   | 0.663      | 0.333        | 0.012 (0.003)    | 0.837 (0.185)    | -         |    11.31 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           47 |     1884 | 2024-12-11 | XPERION NXT               | W   | 0.659      | -            | -                | -                | -         |     6.08 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           46 |     1894 | 2024-12-11 | BRUTE                     | W   | 0.658      | -            | -                | -                | -         |     7.45 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           45 |     2026 | 2024-12-08 | Lilmix                    | W   | 0.637      | -            | -                | -                | -         |     4.30 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           44 |     2096 | 2024-12-07 | Lilmix                    | L   | 0.631      | -            | -                | -                | -         |   -15.96 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           43 |     2220 | 2024-12-04 | LEON Esports              | L   | 0.612      | -            | -                | -                | -         |   -11.22 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           42 |     2336 | 2024-12-02 | XI Esport                 | W   | 0.599      | -            | -                | -                | -         |     5.73 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           41 |     2418 | 2024-12-01 | Dragon Esports Club       | W   | 0.592      | 0.333        | 0.007 (0.001)    | -                | -         |     5.97 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           40 |     2588 | 2024-11-29 | Betclic Apogee Esports    | L   | 0.579      | -            | -                | -                | -         |    -7.86 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           39 |     2628 | 2024-11-28 | Team Genesium             | W   | 0.572      | -            | -                | -                | -         |     5.40 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           38 |     2693 | 2024-11-27 | Dark Cloud Esports        | L   | 0.563      | -            | -                | -                | -         |    -8.60 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           37 |     2729 | 2024-11-26 | Insilio                   | W   | 0.559      | 0.354        | -                | 0.500 (0.099)    | -         |     4.40 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           36 |     2740 | 2024-11-26 | 9INE                      | W   | 0.558      | 0.354        | 0.011 (0.002)    | -                | -         |     7.28 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           35 |     2741 | 2024-11-26 | Betclic Apogee Esports    | L   | 0.558      | -            | -                | -                | -         |    -7.75 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           34 |     2767 | 2024-11-25 | Natus Vincere Junior      | L   | 0.551      | -            | -                | -                | -         |    -4.92 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           33 |     2857 | 2024-11-23 | Astralis Talent           | W   | 0.538      | -            | -                | -                | 1 (0.538) |     7.61 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           32 |     3140 | 2024-11-20 | Dark Cloud Esports        | W   | 0.517      | 0.333        | 0.039 (0.007)    | 0.819 (0.141)    | -         |     8.44 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           31 |     3365 | 2024-11-16 | G2 Ares                   | L   | 0.489      | -            | -                | -                | -         |   -10.50 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           30 |     3424 | 2024-11-15 | HOTU                      | L   | 0.483      | -            | -                | -                | -         |   -10.66 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           29 |     3440 | 2024-11-14 | Astralis Talent           | W   | 0.479      | -            | -                | -                | -         |     6.32 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           28 |     3460 | 2024-11-14 | Denial (Danish team)      | W   | 0.478      | -            | -                | -                | -         |     4.12 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           27 |     3463 | 2024-11-14 | G2 Ares                   | L   | 0.478      | -            | -                | -                | -         |   -10.63 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           26 |     3533 | 2024-11-13 | HOTU                      | W   | 0.469      | -            | -                | -                | -         |     4.34 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           25 |     3575 | 2024-11-12 | GenOne                    | L   | 0.463      | -            | -                | -                | -         |    -7.52 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           24 |     3612 | 2024-11-11 | Astralis Talent           | L   | 0.458      | -            | -                | -                | -         |    -9.03 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           23 |     3619 | 2024-11-11 | MASONIC                   | W   | 0.458      | -            | -                | -                | -         |     3.36 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           22 |     3944 | 2024-11-05 | Preasy Esport             | W   | 0.418      | -            | -                | -                | -         |     5.32 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           21 |     4008 | 2024-11-04 | XI Esport                 | W   | 0.412      | -            | -                | -                | -         |     1.88 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           20 |     4415 | 2024-10-28 | Copenhagen Wolves Academy | W   | 0.366      | -            | -                | -                | -         |     0.81 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           19 |     4430 | 2024-10-28 | XI Esport                 | W   | 0.365      | -            | -                | -                | -         |     3.33 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           18 |     4643 | 2024-10-24 | Leo Team                  | L   | 0.336      | -            | -                | -                | -         |    -5.58 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           17 |     4687 | 2024-10-23 | Natus Vincere Junior      | L   | 0.330      | -            | -                | -                | -         |    -3.52 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           16 |     4746 | 2024-10-21 | Denial (Danish team)      | W   | 0.318      | -            | -                | -                | -         |     2.51 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           15 |     4824 | 2024-10-20 | ALASKA                    | W   | 0.309      | 0.333        | 0.031 (0.003)    | -                | -         |     7.99 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           14 |     4861 | 2024-10-19 | Ex-9INE Academy           | W   | 0.304      | -            | -                | -                | -         |     1.87 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           13 |     5031 | 2024-10-16 | Chimera Esports           | L   | 0.283      | -            | -                | -                | -         |    -4.58 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           12 |     5035 | 2024-10-16 | UNiTY esports             | W   | 0.282      | 0.333        | 0.025 (0.002)    | -                | -         |     4.54 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           11 |     5129 | 2024-10-14 | Lilmix                    | W   | 0.269      | -            | -                | -                | -         |     2.12 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|           10 |     5456 | 2024-10-08 | Chimera Esports           | L   | 0.229      | -            | -                | -                | -         |    -3.63 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            9 |     5479 | 2024-10-07 | Copenhagen Wolves Academy | W   | 0.225      | -            | -                | -                | -         |     0.53 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            8 |     5484 | 2024-10-07 | Preasy Esport             | W   | 0.225      | -            | -                | -                | -         |     3.12 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            7 |     5493 | 2024-10-07 | Denial (Danish team)      | L   | 0.224      | -            | -                | -                | -         |    -5.31 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            6 |     5910 | 2024-09-30 | MASONIC                   | L   | 0.178      | -            | -                | -                | -         |    -4.16 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            5 |     5924 | 2024-09-30 | Astralis Talent           | L   | 0.178      | -            | -                | -                | -         |    -3.43 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            4 |     6326 | 2024-09-25 | ADEPTS                    | W   | 0.143      | -            | -                | -                | -         |     0.85 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            3 |     6478 | 2024-09-23 | XI Esport                 | L   | 0.131      | -            | -                | -                | -         |    -3.00 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            2 |     6482 | 2024-09-23 | XI Esport                 | W   | 0.131      | -            | -                | -                | -         |     0.51 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |
|            1 |     6492 | 2024-09-23 | Dark Cloud Esports        | L   | 0.130      | -            | -                | -                | -         |    -2.16 | Gnøffe, Leakz, PR1mE, sL1m3, Vster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,393.96)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-25 |      0.750 | $3,000.00      | $2,250.21       |
| 2024-12-24 |      0.743 | $3,000.00      | $2,227.92       |
| 2024-12-15 |      0.684 | $1,500.00      | $1,026.04       |
| 2024-11-23 |      0.538 | $9,080.87      | $4,889.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
