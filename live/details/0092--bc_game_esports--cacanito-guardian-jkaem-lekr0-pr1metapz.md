### Roster Details<br />
Team Name: BC.Game Esports<br />
Roster: CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  867.1<br />
<br />
Final Rank Value (867.1) = Starting Rank Value (835.7) + Head To Head Adjustments (31.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.344[<sup>2</sup>](#table1)
- Opponent Network: 0.151[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 835.7
- 400 + ( ( 0.218 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 835.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |     1556 | 2024-12-19 | AMKAL ESPORTS      | L   | 0.710      | -            | -                | -                | -         |   -12.02 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           53 |     1601 | 2024-12-16 | G2 Ares            | W   | 0.691      | -            | -                | -                | 0 (0.000) |     5.45 | CacaNito, GuardiaN, jkaem, Lekr0, sense       |
|           52 |     1815 | 2024-12-13 | Nexus Gaming       | W   | 0.670      | 0.333        | 0.187 (0.042)    | 0.795 (0.177)    | 0 (0.000) |    15.99 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           51 |     1896 | 2024-12-11 | Betera Esports     | L   | 0.657      | -            | -                | -                | -         |   -13.48 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           50 |     1973 | 2024-12-09 | K27                | L   | 0.643      | -            | -                | -                | -         |   -10.45 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           49 |     2189 | 2024-12-05 | GenOne             | W   | 0.616      | 0.333        | -                | 0.837 (0.172)    | 0 (0.000) |     9.83 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           48 |     2236 | 2024-12-04 | Illuminar Gaming   | W   | 0.610      | 0.333        | -                | 0.581 (0.118)    | 0 (0.000) |     8.61 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           47 |     2245 | 2024-12-04 | GenOne             | L   | 0.609      | -            | -                | -                | -         |    -9.18 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           46 |     2300 | 2024-12-03 | GenOne             | L   | 0.603      | -            | -                | -                | -         |    -9.79 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           45 |     2357 | 2024-12-02 | FLuffy Gangsters   | L   | 0.597      | -            | -                | -                | -         |   -10.13 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           44 |     2365 | 2024-12-02 | FORZE Reload       | L   | 0.596      | -            | -                | -                | -         |   -10.01 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           43 |     2442 | 2024-12-01 | KONO.ECF           | W   | 0.591      | 0.372        | 0.046 (0.010)    | 0.747 (0.164)    | 0 (0.000) |     7.82 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           42 |     2451 | 2024-12-01 | Illuminar Gaming   | W   | 0.590      | -            | -                | -                | 0 (0.000) |     7.90 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           41 |     2558 | 2024-11-30 | GUN5 Esports       | L   | 0.583      | -            | -                | -                | -         |    -7.90 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           40 |     2599 | 2024-11-29 | Dark Cloud Esports | W   | 0.578      | 0.333        | 0.039 (0.007)    | 0.819 (0.158)    | 0 (0.000) |     8.34 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           39 |     2610 | 2024-11-29 | KONO.ECF           | W   | 0.577      | 0.333        | 0.046 (0.009)    | 0.747 (0.144)    | 0 (0.000) |     8.46 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           38 |     2614 | 2024-11-29 | Tricked Esport     | W   | 0.576      | 0.333        | 0.034 (0.006)    | 0.687 (0.132)    | 0 (0.000) |     9.85 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           37 |     2641 | 2024-11-28 | 500                | L   | 0.572      | -            | -                | -                | -         |    -5.49 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           36 |     2658 | 2024-11-28 | JANO Esports       | W   | 0.571      | -            | -                | -                | 0 (0.000) |     9.35 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           35 |     2682 | 2024-11-27 | Viperio            | W   | 0.565      | -            | -                | -                | -         |     6.02 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           34 |     2690 | 2024-11-27 | Chimera Esports    | W   | 0.563      | -            | -                | -                | -         |     9.63 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           33 |     2743 | 2024-11-26 | Viperio            | L   | 0.557      | -            | -                | -                | -         |   -11.99 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           32 |     2749 | 2024-11-26 | ALASKA             | W   | 0.556      | 0.333        | 0.031 (0.006)    | 0.867 (0.161)    | -         |    11.24 | CacaNito, GuardiaN, Lekr0, M1key, pr1metapz   |
|           31 |     2775 | 2024-11-25 | Leo Team           | W   | 0.549      | 0.333        | -                | 0.748 (0.137)    | -         |    10.24 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           30 |     2806 | 2024-11-24 | G2 Ares            | W   | 0.544      | -            | -                | -                | -         |     5.29 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           29 |     2914 | 2024-11-23 | GenOne             | W   | 0.537      | 0.333        | -                | 0.837 (0.150)    | -         |     8.88 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           28 |     2980 | 2024-11-22 | UNiTY esports      | L   | 0.531      | -            | -                | -                | -         |    -8.17 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           27 |     2997 | 2024-11-22 | Lilmix             | W   | 0.530      | -            | -                | -                | -         |     3.42 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           26 |     3065 | 2024-11-21 | FORZE Reload       | L   | 0.523      | -            | -                | -                | -         |    -8.04 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           25 |     3224 | 2024-11-18 | Astralis Talent    | L   | 0.503      | -            | -                | -                | -         |    -9.41 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           24 |     3415 | 2024-11-15 | FLuffy Gangsters   | L   | 0.483      | -            | -                | -                | -         |    -8.80 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           23 |     3423 | 2024-11-15 | Preasy Esport      | W   | 0.483      | -            | -                | -                | -         |     5.39 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           22 |     3458 | 2024-11-14 | TEAM NEXT LEVEL    | W   | 0.478      | 0.372        | 0.040 (0.007)    | -                | -         |     7.11 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           21 |     3467 | 2024-11-14 | Passion UA         | W   | 0.477      | 0.372        | 0.044 (0.008)    | -                | -         |    10.66 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           20 |     3565 | 2024-11-12 | WW Team            | W   | 0.463      | -            | -                | -                | -         |     2.02 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           19 |     3627 | 2024-11-11 | Chimera Esports    | L   | 0.458      | -            | -                | -                | -         |    -6.96 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           18 |     3630 | 2024-11-11 | QUAZAR             | W   | 0.457      | -            | -                | -                | -         |     5.13 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           17 |     3856 | 2024-11-07 | Nuclear TigeRES    | L   | 0.431      | -            | -                | -                | -         |    -6.82 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           16 |     3956 | 2024-11-05 | Poslednii3ae3d     | W   | 0.418      | -            | -                | -                | -         |     2.93 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           15 |     3963 | 2024-11-05 | Ex-RUBY            | L   | 0.417      | -            | -                | -                | -         |   -11.13 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           14 |     4333 | 2024-10-30 | RUSTEC             | W   | 0.377      | -            | -                | -                | -         |     1.98 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           13 |     4387 | 2024-10-29 | Leo Team           | W   | 0.371      | -            | -                | -                | -         |     5.64 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           12 |     4394 | 2024-10-29 | GTZ.ESPORTS        | W   | 0.370      | 0.372        | 0.080 (0.011)    | -                | -         |    10.29 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           11 |     4397 | 2024-10-29 | RUSTEC             | L   | 0.370      | -            | -                | -                | -         |    -8.25 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           10 |     4715 | 2024-10-22 | Nexus Gaming       | L   | 0.324      | -            | -                | -                | -         |    -1.72 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            9 |     4800 | 2024-10-20 | K27                | L   | 0.311      | -            | -                | -                | -         |    -3.94 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            8 |     4874 | 2024-10-19 | Nexus Gaming       | W   | 0.302      | 0.333        | 0.187 (0.019)    | -                | -         |     8.02 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            7 |     4904 | 2024-10-18 | Kay Team           | W   | 0.297      | -            | -                | -                | -         |     1.36 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            6 |     5023 | 2024-10-16 | FLuffy Gangsters   | L   | 0.283      | -            | -                | -                | -         |    -4.95 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            5 |     5037 | 2024-10-16 | TEAM NEXT LEVEL    | L   | 0.282      | -            | -                | -                | -         |    -4.39 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz  |
|            4 |     5087 | 2024-10-15 | K27                | W   | 0.277      | -            | -                | -                | -         |     5.33 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            3 |     5105 | 2024-10-14 | Viperio            | W   | 0.272      | -            | -                | -                | -         |     3.40 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            2 |     6289 | 2024-09-25 | B8                 | L   | 0.145      | -            | -                | -                | -         |    -0.81 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz  |
|            1 |     7361 | 2024-09-08 | K27                | L   | 0.031      | -            | -                | -                | -         |    -0.35 | anarkez, CacaNito, GuardiaN, Lekr0, pr1metapz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,151.67)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-05 |      0.616 | $6,000.00      | $3,695.83       |
| 2024-11-29 |      0.576 | $6,000.00      | $3,455.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
