### Roster Details<br />
Team Name: BC.Game Esports<br />
Roster: CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  868.7<br />
<br />
Final Rank Value (868.7) = Starting Rank Value (837.2) + Head To Head Adjustments (31.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.345[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.219<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 837.2
- 400 + ( ( 0.219 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 837.2


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
|           55 |     1544 | 2024-12-19 | AMKAL ESPORTS      | L   | 0.718      | -            | -                | -                | -         |   -12.14 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           54 |     1589 | 2024-12-16 | G2 Ares            | W   | 0.699      | -            | -                | -                | 0 (0.000) |     5.50 | CacaNito, GuardiaN, jkaem, Lekr0, sense       |
|           53 |     1803 | 2024-12-13 | Nexus Gaming       | W   | 0.678      | 0.333        | 0.186 (0.042)    | 0.808 (0.183)    | 0 (0.000) |    16.15 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           52 |     1884 | 2024-12-11 | Betera Esports     | L   | 0.665      | -            | -                | -                | -         |   -13.65 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           51 |     1961 | 2024-12-09 | K27                | L   | 0.651      | -            | -                | -                | -         |   -10.66 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           50 |     2177 | 2024-12-05 | GenOne             | W   | 0.624      | 0.333        | -                | 0.848 (0.176)    | 0 (0.000) |     9.97 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           49 |     2224 | 2024-12-04 | Illuminar Gaming   | W   | 0.619      | 0.333        | -                | 0.593 (0.122)    | 0 (0.000) |     8.72 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           48 |     2233 | 2024-12-04 | GenOne             | L   | 0.618      | -            | -                | -                | -         |    -9.29 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           47 |     2288 | 2024-12-03 | GenOne             | L   | 0.611      | -            | -                | -                | -         |    -9.92 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           46 |     2345 | 2024-12-02 | FLuffy Gangsters   | L   | 0.605      | -            | -                | -                | -         |   -10.22 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           45 |     2353 | 2024-12-02 | FORZE Reload       | L   | 0.605      | -            | -                | -                | -         |   -10.16 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           44 |     2430 | 2024-12-01 | KONO.ECF           | W   | 0.599      | 0.372        | 0.045 (0.010)    | 0.757 (0.169)    | 0 (0.000) |     7.90 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           43 |     2439 | 2024-12-01 | Illuminar Gaming   | W   | 0.598      | -            | -                | -                | 0 (0.000) |     8.00 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           42 |     2546 | 2024-11-30 | GUN5 Esports       | L   | 0.591      | -            | -                | -                | -         |    -8.02 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           41 |     2587 | 2024-11-29 | Dark Cloud Esports | W   | 0.586      | 0.333        | 0.038 (0.008)    | 0.828 (0.162)    | 0 (0.000) |     8.43 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           40 |     2598 | 2024-11-29 | KONO.ECF           | W   | 0.585      | 0.333        | 0.045 (0.009)    | 0.757 (0.148)    | 0 (0.000) |     8.56 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           39 |     2602 | 2024-11-29 | Tricked Esport     | W   | 0.584      | 0.333        | 0.033 (0.007)    | 0.696 (0.135)    | 0 (0.000) |    10.01 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           38 |     2629 | 2024-11-28 | 500                | L   | 0.580      | -            | -                | -                | -         |    -5.59 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           37 |     2646 | 2024-11-28 | JANO Esports       | W   | 0.579      | -            | -                | -                | 0 (0.000) |     9.45 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           36 |     2670 | 2024-11-27 | Viperio            | W   | 0.573      | -            | -                | -                | -         |     6.12 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           35 |     2678 | 2024-11-27 | Chimera Esports    | W   | 0.572      | -            | -                | -                | -         |     9.79 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           34 |     2731 | 2024-11-26 | Viperio            | L   | 0.566      | -            | -                | -                | -         |   -12.15 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           33 |     2737 | 2024-11-26 | ALASKA             | W   | 0.564      | 0.333        | 0.030 (0.006)    | 0.875 (0.165)    | -         |    11.30 | CacaNito, GuardiaN, Lekr0, M1key, pr1metapz   |
|           32 |     2763 | 2024-11-25 | Leo Team           | W   | 0.557      | 0.333        | -                | 0.758 (0.141)    | -         |    10.42 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           31 |     2794 | 2024-11-24 | G2 Ares            | W   | 0.552      | -            | -                | -                | -         |     5.37 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           30 |     2902 | 2024-11-23 | GenOne             | W   | 0.545      | 0.333        | -                | 0.848 (0.154)    | -         |     9.03 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           29 |     2968 | 2024-11-22 | UNiTY esports      | L   | 0.539      | -            | -                | -                | -         |    -8.26 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           28 |     2985 | 2024-11-22 | Lilmix             | W   | 0.538      | -            | -                | -                | -         |     3.47 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           27 |     3053 | 2024-11-21 | FORZE Reload       | L   | 0.531      | -            | -                | -                | -         |    -8.17 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           26 |     3212 | 2024-11-18 | Astralis Talent    | L   | 0.511      | -            | -                | -                | -         |    -9.56 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           25 |     3403 | 2024-11-15 | FLuffy Gangsters   | L   | 0.492      | -            | -                | -                | -         |    -8.94 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           24 |     3411 | 2024-11-15 | Preasy Esport      | W   | 0.491      | -            | -                | -                | -         |     5.46 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           23 |     3446 | 2024-11-14 | TEAM NEXT LEVEL    | W   | 0.486      | 0.372        | 0.039 (0.007)    | -                | -         |     7.22 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           22 |     3455 | 2024-11-14 | Passion UA         | W   | 0.486      | 0.372        | 0.044 (0.008)    | -                | -         |    10.84 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           21 |     3553 | 2024-11-12 | WW Team            | W   | 0.472      | -            | -                | -                | -         |     2.06 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           20 |     3615 | 2024-11-11 | Chimera Esports    | L   | 0.466      | -            | -                | -                | -         |    -7.06 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           19 |     3618 | 2024-11-11 | QUAZAR             | W   | 0.465      | -            | -                | -                | -         |     5.22 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           18 |     3844 | 2024-11-07 | Nuclear TigeRES    | L   | 0.439      | -            | -                | -                | -         |    -6.98 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           17 |     3944 | 2024-11-05 | Poslednii3ae3d     | W   | 0.426      | -            | -                | -                | -         |     2.97 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           16 |     3951 | 2024-11-05 | Ex-RUBY            | L   | 0.426      | -            | -                | -                | -         |   -11.36 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           15 |     4321 | 2024-10-30 | RUSTEC             | W   | 0.386      | -            | -                | -                | -         |     2.02 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           14 |     4375 | 2024-10-29 | Leo Team           | W   | 0.379      | -            | -                | -                | -         |     5.77 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           13 |     4382 | 2024-10-29 | GTZ.ESPORTS        | W   | 0.379      | 0.372        | 0.080 (0.011)    | -                | -         |    10.52 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           12 |     4385 | 2024-10-29 | RUSTEC             | L   | 0.378      | -            | -                | -                | -         |    -8.45 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           11 |     4703 | 2024-10-22 | Nexus Gaming       | L   | 0.333      | -            | -                | -                | -         |    -1.77 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|           10 |     4788 | 2024-10-20 | K27                | L   | 0.319      | -            | -                | -                | -         |    -4.07 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            9 |     4862 | 2024-10-19 | Nexus Gaming       | W   | 0.311      | 0.333        | 0.186 (0.019)    | -                | -         |     8.23 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            8 |     4892 | 2024-10-18 | Kay Team           | W   | 0.306      | -            | -                | -                | -         |     1.40 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            7 |     5011 | 2024-10-16 | FLuffy Gangsters   | L   | 0.292      | -            | -                | -                | -         |    -5.08 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            6 |     5026 | 2024-10-16 | TEAM NEXT LEVEL    | L   | 0.290      | -            | -                | -                | -         |    -4.52 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz  |
|            5 |     5075 | 2024-10-15 | K27                | W   | 0.285      | -            | -                | -                | -         |     5.46 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            4 |     5093 | 2024-10-14 | Viperio            | W   | 0.280      | -            | -                | -                | -         |     3.52 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            3 |     6277 | 2024-09-25 | B8                 | L   | 0.153      | -            | -                | -                | -         |    -0.86 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz  |
|            2 |     7349 | 2024-09-08 | K27                | L   | 0.039      | -            | -                | -                | -         |    -0.45 | anarkez, CacaNito, GuardiaN, Lekr0, pr1metapz |
|            1 |     7751 | 2024-09-03 | RUBY               | L   | 0.004      | -            | -                | -                | -         |    -0.10 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,250.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-05 |      0.624 | $6,000.00      | $3,745.00       |
| 2024-11-29 |      0.584 | $6,000.00      | $3,505.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
