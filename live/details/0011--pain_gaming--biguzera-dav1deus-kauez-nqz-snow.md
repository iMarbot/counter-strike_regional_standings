### Roster Details<br />
Team Name: PaiN Gaming<br />
Roster: biguzera, dav1deuS, kauez, nqz, snow<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1605.7<br />
<br />
Final Rank Value (1605.7) = Starting Rank Value (1656.6) + Head To Head Adjustments (-51.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.671[<sup>1</sup>](#table2)
- Bounty Collected: 0.636[<sup>2</sup>](#table1)
- Opponent Network: 0.349[<sup>2</sup>](#table1)
- LAN Wins: 0.856[<sup>2</sup>](#table1)

The average of these factors is 0.628<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1656.6
- 400 + ( ( 0.628 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1656.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |      232 | 2025-02-21 | MOUZ             | L   | 1.000      | -            | -                | -                | -         |    -6.18 | biguzera, dav1deuS, kauez, nqz, snow |
|           59 |      299 | 2025-02-17 | Virtus.pro       | W   | 1.000      | 1.000        | 0.272 (0.272)    | 0.436 (0.436)    | 1 (1.000) |    15.90 | biguzera, dav1deuS, kauez, nqz, snow |
|           58 |      362 | 2025-02-16 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -4.20 | biguzera, dav1deuS, kauez, nqz, snow |
|           57 |      421 | 2025-02-15 | Team Falcons     | W   | 1.000      | 1.000        | 0.939 (0.939)    | 0.609 (0.609)    | 1 (1.000) |    24.67 | biguzera, dav1deuS, kauez, nqz, snow |
|           56 |      495 | 2025-02-14 | Astralis         | W   | 1.000      | 1.000        | 0.619 (0.619)    | 0.786 (0.786)    | 1 (1.000) |    21.91 | biguzera, dav1deuS, kauez, nqz, snow |
|           55 |      644 | 2025-02-09 | Imperial Esports | L   | 1.000      | -            | -                | -                | -         |   -29.92 | biguzera, dav1deuS, kauez, nqz, snow |
|           54 |      680 | 2025-02-08 | RED Canids       | W   | 1.000      | -            | -                | -                | -         |     0.52 | biguzera, dav1deuS, kauez, nqz, snow |
|           53 |     1101 | 2025-01-31 | Astralis         | L   | 0.998      | -            | -                | -                | -         |    -8.28 | biguzera, dav1deuS, kauez, nqz, snow |
|           52 |     1113 | 2025-01-30 | GamerLegion      | L   | 0.990      | -            | -                | -                | -         |   -17.27 | biguzera, dav1deuS, kauez, nqz, snow |
|           51 |     1125 | 2025-01-29 | Virtus.pro       | W   | 0.983      | 1.000        | 0.272 (0.268)    | 0.436 (0.428)    | 1 (0.983) |    14.48 | biguzera, dav1deuS, kauez, nqz, snow |
|           50 |     1150 | 2025-01-24 | Natus Vincere    | L   | 0.952      | -            | -                | -                | -         |   -10.05 | biguzera, dav1deuS, kauez, nqz, snow |
|           49 |     1177 | 2025-01-18 | FaZe Clan        | W   | 0.911      | 0.363        | 0.753 (0.249)    | 0.478 (0.158)    | -         |    24.15 | biguzera, dav1deuS, kauez, nqz, snow |
|           48 |     1188 | 2025-01-17 | GamerLegion      | W   | 0.903      | 0.363        | 0.129 (0.042)    | 0.490 (0.160)    | -         |    13.51 | biguzera, dav1deuS, kauez, nqz, snow |
|           47 |     2109 | 2024-12-07 | FURIA            | L   | 0.629      | -            | -                | -                | -         |   -12.96 | biguzera, kauez, lux, nqz, snow      |
|           46 |     2155 | 2024-12-06 | BIG              | W   | 0.622      | 1.000        | 0.248 (0.155)    | 0.572 (0.356)    | 1 (0.622) |     7.09 | biguzera, kauez, lux, nqz, snow      |
|           45 |     2178 | 2024-12-05 | 3DMAX            | L   | 0.617      | -            | -                | -                | -         |    -9.71 | biguzera, kauez, lux, nqz, snow      |
|           44 |     2199 | 2024-12-04 | MOUZ             | L   | 0.615      | -            | -                | -                | -         |    -1.89 | biguzera, kauez, lux, nqz, snow      |
|           43 |     2384 | 2024-12-01 | FlyQuest         | W   | 0.595      | 1.000        | 0.105 (0.063)    | 0.235 (0.140)    | 1 (0.595) |     1.35 | biguzera, kauez, lux, nqz, snow      |
|           42 |     2464 | 2024-11-30 | Cloud9           | W   | 0.588      | -            | -                | -                | 1 (0.588) |     0.47 | biguzera, kauez, lux, nqz, snow      |
|           41 |     2546 | 2024-11-30 | GamerLegion      | L   | 0.583      | -            | -                | -                | -         |    -9.66 | biguzera, kauez, lux, nqz, snow      |
|           40 |     2566 | 2024-11-29 | Imperial Esports | W   | 0.582      | 1.000        | 0.092 (0.053)    | 0.562 (0.327)    | 1 (0.582) |     0.63 | biguzera, kauez, lux, nqz, snow      |
|           39 |     3493 | 2024-11-13 | 9z Team          | W   | 0.475      | -            | -                | -                | 1 (0.475) |     0.17 | biguzera, kauez, lux, nqz, snow      |
|           38 |     3538 | 2024-11-12 | Imperial Esports | W   | 0.468      | -            | -                | -                | 1 (0.468) |     0.49 | biguzera, kauez, lux, nqz, snow      |
|           37 |     3572 | 2024-11-12 | Wildcard         | L   | 0.463      | -            | -                | -                | -         |   -12.02 | biguzera, kauez, lux, nqz, snow      |
|           36 |     3589 | 2024-11-11 | Nouns Esports    | W   | 0.462      | -            | -                | -                | -         |     0.12 | biguzera, kauez, lux, nqz, snow      |
|           35 |     4483 | 2024-10-27 | B8               | L   | 0.357      | -            | -                | -                | -         |   -10.49 | biguzera, kauez, lux, nqz, snow      |
|           34 |     4602 | 2024-10-25 | Legacy           | W   | 0.344      | 0.500        | -                | 0.549 (0.095)    | -         |     0.20 | biguzera, kauez, lux, nqz, snow      |
|           33 |     4615 | 2024-10-25 | Monte            | W   | 0.343      | -            | -                | -                | -         |     0.16 | biguzera, kauez, lux, nqz, snow      |
|           32 |     4773 | 2024-10-20 | MIBR             | W   | 0.312      | 0.450        | 0.142 (0.020)    | -                | -         |     2.46 | biguzera, kauez, lux, nqz, snow      |
|           31 |     4927 | 2024-10-17 | MIBR             | W   | 0.293      | -            | -                | -                | -         |     2.34 | biguzera, kauez, lux, nqz, snow      |
|           30 |     4981 | 2024-10-16 | AdalYamigos      | W   | 0.286      | -            | -                | -                | -         |     0.08 | biguzera, kauez, lux, nqz, snow      |
|           29 |     5327 | 2024-10-09 | AdalYamigos      | L   | 0.240      | -            | -                | -                | -         |    -7.48 | biguzera, kauez, lux, nqz, snow      |
|           28 |     5335 | 2024-10-09 | AdalYamigos      | L   | 0.239      | -            | -                | -                | -         |    -7.48 | biguzera, kauez, lux, nqz, snow      |
|           27 |     5403 | 2024-10-08 | Imperial Esports | L   | 0.233      | -            | -                | -                | -         |    -7.14 | biguzera, kauez, lux, nqz, snow      |
|           26 |     5414 | 2024-10-08 | Imperial Esports | W   | 0.233      | -            | -                | -                | -         |     0.19 | biguzera, kauez, lux, nqz, snow      |
|           25 |     5423 | 2024-10-08 | MIBR             | W   | 0.232      | -            | -                | -                | -         |     1.71 | biguzera, kauez, lux, nqz, snow      |
|           24 |     5426 | 2024-10-08 | MIBR             | W   | 0.232      | -            | -                | -                | -         |     1.73 | biguzera, kauez, lux, nqz, snow      |
|           23 |     5472 | 2024-10-07 | FaZe Clan        | L   | 0.225      | -            | -                | -                | -         |    -1.21 | biguzera, kauez, lux, nqz, snow      |
|           22 |     5500 | 2024-10-07 | MOUZ             | L   | 0.224      | -            | -                | -                | -         |    -0.80 | biguzera, kauez, lux, nqz, snow      |
|           21 |     5676 | 2024-10-04 | BESTIA           | L   | 0.205      | -            | -                | -                | -         |    -6.32 | biguzera, kauez, lux, nqz, snow      |
|           20 |     5760 | 2024-10-02 | Fluxo            | L   | 0.193      | -            | -                | -                | -         |    -5.96 | biguzera, kauez, lux, nqz, snow      |
|           19 |     5766 | 2024-10-02 | Fluxo            | L   | 0.193      | -            | -                | -                | -         |    -5.96 | biguzera, kauez, lux, nqz, snow      |
|           18 |     5772 | 2024-10-02 | RED Canids       | W   | 0.192      | -            | -                | -                | -         |     0.07 | biguzera, kauez, lux, nqz, snow      |
|           17 |     5777 | 2024-10-02 | RED Canids       | L   | 0.192      | -            | -                | -                | -         |    -5.97 | biguzera, kauez, lux, nqz, snow      |
|           16 |     5835 | 2024-10-01 | Hype Esports     | W   | 0.186      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, snow      |
|           15 |     5840 | 2024-10-01 | Hype Esports     | W   | 0.186      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, snow      |
|           14 |     5955 | 2024-09-29 | Fluxo            | W   | 0.173      | -            | -                | -                | -         |     0.09 | biguzera, kauez, lux, nqz, snow      |
|           13 |     5958 | 2024-09-29 | Team Solid       | W   | 0.172      | -            | -                | -                | -         |     0.06 | biguzera, kauez, lux, nqz, snow      |
|           12 |     6008 | 2024-09-28 | RED Canids       | W   | 0.166      | -            | -                | -                | -         |     0.06 | biguzera, kauez, lux, nqz, snow      |
|           11 |     6016 | 2024-09-28 | Team Solid       | L   | 0.165      | -            | -                | -                | -         |    -5.15 | biguzera, kauez, lux, nqz, snow      |
|           10 |     6263 | 2024-09-25 | ODDIK            | W   | 0.146      | -            | -                | -                | -         |     0.04 | biguzera, kauez, lux, nqz, snow      |
|            9 |     6268 | 2024-09-25 | ODDIK            | W   | 0.146      | -            | -                | -                | -         |     0.04 | biguzera, kauez, lux, nqz, snow      |
|            8 |     6355 | 2024-09-24 | Sharks Esports   | W   | 0.140      | -            | -                | -                | -         |     0.12 | biguzera, kauez, lux, nqz, snow      |
|            7 |     6361 | 2024-09-24 | Sharks Esports   | W   | 0.139      | -            | -                | -                | -         |     0.12 | biguzera, kauez, lux, nqz, snow      |
|            6 |     6449 | 2024-09-23 | RED Canids       | W   | 0.132      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, snow      |
|            5 |     6487 | 2024-09-23 | InSanitY Sports  | W   | 0.131      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, nqz, snow      |
|            4 |     6682 | 2024-09-19 | KRÜ Esports      | W   | 0.106      | -            | -                | -                | -         |     0.01 | biguzera, kauez, lux, nqz, snow      |
|            3 |     6685 | 2024-09-19 | KRÜ Esports      | W   | 0.106      | -            | -                | -                | -         |     0.01 | biguzera, kauez, lux, nqz, snow      |
|            2 |     6744 | 2024-09-18 | BESTIA           | W   | 0.099      | -            | -                | -                | -         |     0.05 | biguzera, kauez, lux, nqz, snow      |
|            1 |     6748 | 2024-09-18 | BESTIA           | W   | 0.099      | -            | -                | -                | -         |     0.05 | biguzera, kauez, lux, nqz, snow      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,387.54)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2025-01-26 |      0.964 | $15,000.00     | $14,464.58      |
| 2024-12-15 |      0.683 | $20,000.00     | $13,655.09      |
| 2024-10-27 |      0.358 | $10,000.00     | $3,583.80       |
| 2024-10-20 |      0.312 | $20,000.00     | $6,238.89       |
| 2024-10-13 |      0.265 | $4,000.00      | $1,058.33       |
| 2024-10-05 |      0.211 | $1,832.41      | $386.84         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
