### Roster Details<br />
Team Name: HOTU<br />
Roster: kade0, lampada, mizu, Re1GN, youka<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [95]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.9<br />
<br />
Final Rank Value (786.9) = Starting Rank Value (729.3) + Head To Head Adjustments (57.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 729.3
- 400 + ( ( 0.165 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 729.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           81 |       16 | 2025-02-27 | ATOX Esports               | L   | 1.000      | -            | -                | -                | -         |    -4.49 | kade0, lampada, mizu, Re1GN, youka      |
|           80 |       29 | 2025-02-26 | Chinggis Warriors          | L   | 1.000      | -            | -                | -                | -         |   -11.71 | kade0, lampada, mizu, Re1GN, youka      |
|           79 |       47 | 2025-02-25 | Nomads (Mongolian team)    | W   | 1.000      | 0.143        | -                | 0.407 (0.058)    | 0 (0.000) |     8.09 | kade0, lampada, mizu, Re1GN, youka      |
|           78 |       76 | 2025-02-23 | ATOX Esports               | W   | 1.000      | 0.143        | 0.064 (0.009)    | 0.604 (0.086)    | 0 (0.000) |    26.98 | kade0, lampada, mizu, Re1GN, youka      |
|           77 |      354 | 2025-02-16 | Nomads (Mongolian team)    | W   | 1.000      | 0.143        | -                | 0.407 (0.058)    | 0 (0.000) |     8.72 | kade0, lampada, mizu, Re1GN, youka      |
|           76 |      358 | 2025-02-16 | ShamanKings                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.93 | kade0, lampada, mizu, Re1GN, youka      |
|           75 |      365 | 2025-02-16 | Vizora Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.38 | kade0, lampada, mizu, Re1GN, youka      |
|           74 |      375 | 2025-02-16 | Flashback Gaming           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.31 | kade0, lampada, mizu, Re1GN, youka      |
|           73 |      484 | 2025-02-14 | Eruption                   | L   | 1.000      | -            | -                | -                | -         |    -8.63 | kade0, lampada, mizu, Re1GN, youka      |
|           72 |      494 | 2025-02-14 | IHC Esports                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.19 | kade0, lampada, mizu, Re1GN, youka      |
|           71 |     1430 | 2024-12-21 | Avtostopom Po Galaktike    | L   | 0.734      | -            | -                | -                | -         |   -14.66 | kade0, lampada, mizu, Re1GN, youka      |
|           70 |     1435 | 2024-12-21 | ICE SPIRITS                | W   | 0.734      | -            | -                | -                | 0 (0.000) |     3.03 | kade0, lampada, mizu, Re1GN, youka      |
|           69 |     1486 | 2024-12-20 | Nuclear TigeRES            | L   | 0.728      | -            | -                | -                | -         |   -10.19 | kade0, lampada, mizu, Re1GN, youka      |
|           68 |     1490 | 2024-12-20 | Soul's Heart Esport        | W   | 0.727      | -            | -                | -                | 0 (0.000) |     2.91 | kade0, lampada, mizu, Re1GN, youka      |
|           67 |     2499 | 2024-11-30 | K27                        | L   | 0.593      | -            | -                | -                | -         |    -6.44 | kade0, lampada, mizu, Pumpkin66, Re1GN  |
|           66 |     2783 | 2024-11-24 | ARCRED                     | W   | 0.553      | 0.262        | 0.018 (0.003)    | 0.484 (0.070)    | 0 (0.000) |     9.95 | fineshine, kade0, lampada, mizu, Re1GN  |
|           65 |     2790 | 2024-11-24 | NEVERMORE (Ukrainian team) | W   | 0.552      | 0.262        | 0.010 (0.001)    | 0.911 (0.132)    | -         |     9.57 | fineshine, kade0, lampada, mizu, Re1GN  |
|           64 |     2812 | 2024-11-24 | K27                        | L   | 0.551      | -            | -                | -                | -         |    -5.82 | fineshine, kade0, lampada, mizu, Re1GN  |
|           63 |     2837 | 2024-11-23 | CS2NEWS                    | W   | 0.547      | -            | -                | -                | -         |     4.42 | kade0, lampada, mizu, Re1GN, youka      |
|           62 |     2855 | 2024-11-23 | VP.Prodigy                 | W   | 0.547      | -            | -                | -                | -         |     3.41 | kade0, lampada, mizu, Re1GN, youka      |
|           61 |     2944 | 2024-11-22 | GamerLegion Academy        | W   | 0.540      | -            | -                | -                | -         |     5.33 | fineshine, kade0, lampada, mizu, Re1GN  |
|           60 |     3009 | 2024-11-21 | The Suspect                | W   | 0.534      | -            | -                | -                | -         |     8.63 | fineshine, kade0, lampada, mizu, Re1GN  |
|           59 |     3023 | 2024-11-21 | GTZ.ESPORTS                | W   | 0.533      | 0.372        | 0.080 (0.016)    | 0.563 (0.112)    | -         |    15.54 | fineshine, kade0, lampada, mizu, Re1GN  |
|           58 |     3094 | 2024-11-20 | Ex-9INE Academy            | W   | 0.527      | -            | -                | -                | -         |     4.97 | fineshine, kade0, lampada, mizu, Re1GN  |
|           57 |     3245 | 2024-11-17 | VP.Prodigy                 | W   | 0.505      | -            | -                | -                | -         |     3.79 | fineshine, kade0, lampada, mizu, Re1GN  |
|           56 |     3259 | 2024-11-17 | Hyuga                      | L   | 0.505      | -            | -                | -                | -         |   -11.40 | fineshine, kade0, lampada, mizu, Re1GN  |
|           55 |     3273 | 2024-11-17 | Donstu Esports             | W   | 0.504      | -            | -                | -                | -         |     3.99 | fineshine, kade0, lampada, mizu, Re1GN  |
|           54 |     3354 | 2024-11-16 | Chimera Esports            | L   | 0.497      | -            | -                | -                | -         |    -4.37 | fineshine, kade0, lampada, mizu, Re1GN  |
|           53 |     3412 | 2024-11-15 | WOPA Esport                | W   | 0.491      | 0.143        | 0.031 (0.002)    | 0.785 (0.055)    | -         |    10.85 | fineshine, kade0, lampada, mizu, Re1GN  |
|           52 |     3476 | 2024-11-14 | Daystar                    | W   | 0.484      | -            | -                | -                | -         |     6.21 | fineshine, kade0, lampada, mizu, Re1GN  |
|           51 |     3521 | 2024-11-13 | WOPA Esport                | L   | 0.477      | -            | -                | -                | -         |    -4.40 | fineshine, kade0, lampada, mizu, Re1GN  |
|           50 |     3591 | 2024-11-11 | Ex-Soul's Heart Esport     | W   | 0.467      | -            | -                | -                | -         |     6.24 | anttzz, fineshine, lampada, mizu, Re1GN |
|           49 |     3899 | 2024-11-06 | Zero Tenacity              | L   | 0.432      | -            | -                | -                | -         |    -3.71 | anttzz, fineshine, lampada, mizu, Re1GN |
|           48 |     3985 | 2024-11-04 | Soul's Heart Esport        | L   | 0.420      | -            | -                | -                | -         |    -9.21 | anttzz, fineshine, lampada, mizu, Re1GN |
|           47 |     4005 | 2024-11-04 | Johnny Speeds              | L   | 0.419      | -            | -                | -                | -         |    -2.83 | anttzz, fineshine, lampada, mizu, Re1GN |
|           46 |     4070 | 2024-11-03 | VP.Prodigy                 | W   | 0.412      | -            | -                | -                | -         |     2.85 | anttzz, fineshine, lampada, mizu, Re1GN |
|           45 |     4077 | 2024-11-03 | MOLEGAN                    | W   | 0.411      | -            | -                | -                | -         |     2.09 | anttzz, fineshine, lampada, mizu, Re1GN |
|           44 |     4199 | 2024-11-01 | Chimera Esports            | L   | 0.399      | -            | -                | -                | -         |    -3.69 | anttzz, fineshine, lampada, mizu, Re1GN |
|           43 |     4206 | 2024-11-01 | Tricked Esport             | L   | 0.398      | -            | -                | -                | -         |    -3.61 | anttzz, fineshine, lampada, mizu, Re1GN |
|           42 |     4246 | 2024-10-31 | Lausanne-Sport Esports     | L   | 0.393      | -            | -                | -                | -         |    -8.58 | anttzz, fineshine, lampada, mizu, Re1GN |
|           41 |     4384 | 2024-10-29 | SINNERS Esports            | W   | 0.378      | 0.384        | 0.027 (0.004)    | 0.451 (0.066)    | -         |     9.11 | anttzz, fineshine, lampada, mizu, Re1GN |
|           40 |     4436 | 2024-10-28 | TEAM NEXT LEVEL            | L   | 0.373      | -            | -                | -                | -         |    -6.21 | anttzz, fineshine, lampada, mizu, Re1GN |
|           39 |     4470 | 2024-10-27 | 1win                       | L   | 0.366      | -            | -                | -                | -         |    -5.38 | anttzz, fineshine, lampada, mizu, Re1GN |
|           38 |     4479 | 2024-10-27 | 9INE                       | L   | 0.365      | -            | -                | -                | -         |    -4.57 | anttzz, fineshine, lampada, mizu, Re1GN |
|           37 |     4627 | 2024-10-24 | UNiTY esports              | W   | 0.345      | 0.384        | 0.025 (0.003)    | 0.412 (0.055)    | -         |     7.49 | anttzz, fineshine, lampada, mizu, Re1GN |
|           36 |     4655 | 2024-10-23 | Passion UA                 | L   | 0.340      | -            | -                | -                | -         |    -1.48 | anttzz, fineshine, lampada, mizu, Re1GN |
|           35 |     4756 | 2024-10-21 | 9INE                       | L   | 0.324      | -            | -                | -                | -         |    -4.21 | anttzz, fineshine, lampada, mizu, Re1GN |
|           34 |     4770 | 2024-10-20 | K27                        | L   | 0.320      | -            | -                | -                | -         |    -2.48 | anttzz, fineshine, lampada, mizu, Re1GN |
|           33 |     4781 | 2024-10-20 | QUAZAR Academy             | W   | 0.319      | -            | -                | -                | -         |     1.47 | anttzz, fineshine, lampada, mizu, Re1GN |
|           32 |     4949 | 2024-10-17 | TSM                        | W   | 0.298      | 0.384        | 0.009 (0.001)    | -                | -         |     5.30 | anttzz, fineshine, lampada, mizu, Re1GN |
|           31 |     5001 | 2024-10-16 | THE SPELLS                 | L   | 0.292      | -            | -                | -                | -         |    -6.69 | anttzz, fineshine, lampada, mizu, Re1GN |
|           30 |     5079 | 2024-10-15 | ALTERNATE aTTaX            | W   | 0.284      | 0.384        | 0.021 (0.002)    | 0.564 (0.062)    | -         |     6.87 | anttzz, fineshine, lampada, mizu, Re1GN |
|           29 |     5154 | 2024-10-13 | RUSTEC                     | L   | 0.271      | -            | -                | -                | -         |    -4.73 | anttzz, fineshine, lampada, mizu, Re1GN |
|           28 |     5242 | 2024-10-12 | NO BYSTANDERS              | L   | 0.264      | -            | -                | -                | -         |    -6.51 | anttzz, fineshine, lampada, mizu, Re1GN |
|           27 |     5268 | 2024-10-11 | Tricked Esport             | L   | 0.258      | -            | -                | -                | -         |    -2.86 | anttzz, fineshine, lampada, mizu, Re1GN |
|           26 |     5338 | 2024-10-09 | Daystar                    | L   | 0.246      | -            | -                | -                | -         |    -4.73 | anttzz, fineshine, lampada, mizu, Re1GN |
|           25 |     5370 | 2024-10-09 | 500                        | L   | 0.244      | -            | -                | -                | -         |    -1.45 | anttzz, fineshine, lampada, mizu, Re1GN |
|           24 |     5465 | 2024-10-07 | UNiTY esports              | L   | 0.233      | -            | -                | -                | -         |    -2.49 | anttzz, fineshine, lampada, mizu, Re1GN |
|           23 |     5543 | 2024-10-06 | CYBERSHOKE Esports         | L   | 0.224      | -            | -                | -                | -         |    -2.41 | anttzz, fineshine, lampada, mizu, Re1GN |
|           22 |     5776 | 2024-10-02 | FAVBET Team                | L   | 0.199      | -            | -                | -                | -         |    -2.32 | anttzz, fineshine, lampada, mizu, Re1GN |
|           21 |     5800 | 2024-10-02 | Tricked Esport             | W   | 0.197      | 0.384        | 0.033 (0.003)    | -                | -         |     3.96 | anttzz, fineshine, lampada, mizu, Re1GN |
|           20 |     5870 | 2024-10-01 | GUN5 Esports               | L   | 0.191      | -            | -                | -                | -         |    -1.50 | anttzz, fineshine, lampada, mizu, Re1GN |
|           19 |     5881 | 2024-10-01 | ALTERNATE aTTaX            | L   | 0.190      | -            | -                | -                | -         |    -1.57 | anttzz, fineshine, lampada, mizu, Re1GN |
|           18 |     5987 | 2024-09-29 | AMKAL ESPORTS              | W   | 0.177      | -            | -                | -                | -         |     3.19 | anttzz, fineshine, lampada, mizu, Re1GN |
|           17 |     6070 | 2024-09-28 | ENCE Academy               | W   | 0.171      | -            | -                | -                | -         |     3.28 | anttzz, fineshine, lampada, mizu, Re1GN |
|           16 |     6312 | 2024-09-25 | Daystar                    | W   | 0.151      | -            | -                | -                | -         |     1.87 | anttzz, fineshine, lampada, mizu, Re1GN |
|           15 |     6391 | 2024-09-24 | ENCE Academy               | L   | 0.145      | -            | -                | -                | -         |    -1.79 | anttzz, fineshine, lampada, mizu, Re1GN |
|           14 |     6520 | 2024-09-22 | ARCRED                     | W   | 0.132      | -            | -                | -                | -         |     2.24 | anttzz, fineshine, lampada, mizu, Re1GN |
|           13 |     6533 | 2024-09-22 | WW Team                    | L   | 0.131      | -            | -                | -                | -         |    -3.20 | anttzz, fineshine, lampada, mizu, Re1GN |
|           12 |     6633 | 2024-09-20 | AMKAL ESPORTS              | L   | 0.119      | -            | -                | -                | -         |    -1.71 | anttzz, fineshine, lampada, mizu, Re1GN |
|           11 |     6698 | 2024-09-19 | CYBERSHOKE Esports         | L   | 0.112      | -            | -                | -                | -         |    -1.16 | anttzz, fineshine, lampada, mizu, Re1GN |
|           10 |     6713 | 2024-09-19 | GenOne                     | W   | 0.111      | -            | -                | -                | -         |     2.22 | anttzz, fineshine, lampada, mizu, Re1GN |
|            9 |     7085 | 2024-09-13 | FAVBET Team                | L   | 0.072      | -            | -                | -                | -         |    -0.80 | anttzz, fineshine, lampada, mizu, Re1GN |
|            8 |     7101 | 2024-09-13 | Ex-ENTERPRISE esports      | W   | 0.071      | -            | -                | -                | -         |     1.10 | anttzz, fineshine, lampada, mizu, Re1GN |
|            7 |     7187 | 2024-09-11 | Passion UA                 | W   | 0.059      | -            | -                | -                | -         |     1.58 | anttzz, fineshine, lampada, mizu, Re1GN |
|            6 |     7345 | 2024-09-08 | Team Spirit Academy        | L   | 0.039      | -            | -                | -                | -         |    -0.32 | anttzz, fineshine, lampada, mizu, Re1GN |
|            5 |     7497 | 2024-09-06 | FLuffy Gangsters           | L   | 0.026      | -            | -                | -                | -         |    -0.34 | anttzz, fineshine, lampada, mizu, Re1GN |
|            4 |     7516 | 2024-09-06 | FORZE Reload               | W   | 0.026      | -            | -                | -                | -         |     0.54 | anttzz, fineshine, lampada, mizu, Re1GN |
|            3 |     7572 | 2024-09-05 | MOUZ NXT                   | W   | 0.020      | -            | -                | -                | -         |     0.14 | anttzz, fineshine, lampada, mizu, Re1GN |
|            2 |     7604 | 2024-09-05 | RUSH B (Russian team)      | W   | 0.019      | -            | -                | -                | -         |     0.42 | anttzz, fineshine, lampada, mizu, Re1GN |
|            1 |     7729 | 2024-09-03 | Ex-ENTERPRISE esports      | W   | 0.006      | -            | -                | -                | -         |     0.10 | anttzz, fineshine, lampada, mizu, Re1GN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,068.96)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.553 | $1,000.00      | $552.89         |
| 2024-11-03 |      0.413 | $1,021.74      | $422.32         |
| 2024-09-21 |      0.125 | $750.00        | $93.75          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
