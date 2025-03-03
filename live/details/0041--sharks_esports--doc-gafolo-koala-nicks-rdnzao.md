### Roster Details<br />
Team Name: Sharks Esports<br />
Roster: doc, gafolo, koala, Nicks, rdnzao<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1008.9<br />
<br />
Final Rank Value (1008.9) = Starting Rank Value (1027.5) + Head To Head Adjustments (-18.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.442[<sup>1</sup>](#table2)
- Bounty Collected: 0.319[<sup>2</sup>](#table1)
- Opponent Network: 0.113[<sup>2</sup>](#table1)
- LAN Wins: 0.380[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1027.5
- 400 + ( ( 0.314 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1027.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |      138 | 2025-02-22 | Imperial Esports         | L   | 1.000      | -            | -                | -                | -         |   -12.84 | doc, gafolo, koala, Nicks, rdnzao |
|           63 |      159 | 2025-02-22 | ODDIK                    | W   | 1.000      | 0.371        | 0.028 (0.011)    | 0.518 (0.192)    | 0 (0.000) |    10.70 | doc, gafolo, koala, Nicks, rdnzao |
|           62 |      208 | 2025-02-21 | Swingers                 | W   | 1.000      | 0.371        | -                | 0.188 (0.069)    | 0 (0.000) |     5.80 | doc, gafolo, koala, Nicks, rdnzao |
|           61 |      238 | 2025-02-20 | Bounty Hunters Esports   | W   | 1.000      | 0.371        | -                | 0.523 (0.194)    | 0 (0.000) |     7.52 | doc, gafolo, koala, Nicks, rdnzao |
|           60 |      539 | 2025-02-12 | Fluxo                    | L   | 1.000      | -            | -                | -                | -         |   -16.32 | doc, gafolo, koala, Nicks, rdnzao |
|           59 |      557 | 2025-02-11 | Imperial Esports         | W   | 1.000      | 0.143        | 0.092 (0.013)    | 0.562 (0.080)    | 0 (0.000) |    18.11 | doc, gafolo, koala, Nicks, rdnzao |
|           58 |      563 | 2025-02-11 | Legacy                   | L   | 1.000      | -            | -                | -                | -         |   -17.56 | doc, gafolo, koala, Nicks, rdnzao |
|           57 |      640 | 2025-02-09 | MIBR                     | L   | 1.000      | -            | -                | -                | -         |    -3.12 | doc, gafolo, koala, Nicks, rdnzao |
|           56 |      701 | 2025-02-08 | BESTIA                   | W   | 1.000      | 0.143        | 0.069 (0.010)    | -                | -         |    14.23 | doc, gafolo, koala, Nicks, rdnzao |
|           55 |     1979 | 2024-12-08 | NRG                      | L   | 0.641      | -            | -                | -                | -         |    -9.52 | doc, gafolo, hoax, koala, rdnzao  |
|           54 |     1980 | 2024-12-08 | BLUEJAYS                 | W   | 0.640      | 0.384        | 0.031 (0.008)    | 0.511 (0.126)    | 1 (0.640) |    13.12 | doc, gafolo, hoax, koala, rdnzao  |
|           53 |     1983 | 2024-12-08 | NRG                      | L   | 0.639      | -            | -                | -                | -         |    -9.67 | doc, gafolo, hoax, koala, rdnzao  |
|           52 |     2059 | 2024-12-07 | Nouns Esports            | W   | 0.634      | 0.384        | -                | 0.327 (0.080)    | 1 (0.634) |     6.68 | doc, gafolo, hoax, koala, rdnzao  |
|           51 |     2071 | 2024-12-07 | Bad News Capybaras       | W   | 0.633      | -            | -                | -                | 1 (0.633) |     2.36 | doc, gafolo, hoax, koala, rdnzao  |
|           50 |     2127 | 2024-12-06 | MIGHT                    | W   | 0.627      | 0.384        | -                | 0.489 (0.118)    | 1 (0.627) |     4.30 | doc, gafolo, hoax, koala, rdnzao  |
|           49 |     2500 | 2024-11-30 | ODDIK                    | L   | 0.586      | -            | -                | -                | -         |   -12.91 | doc, gafolo, hoax, koala, rdnzao  |
|           48 |     2607 | 2024-11-29 | Nitro.GG                 | W   | 0.578      | 0.371        | -                | 0.512 (0.110)    | -         |     2.88 | doc, gafolo, hoax, koala, rdnzao  |
|           47 |     2643 | 2024-11-28 | 20/70                    | W   | 0.572      | -            | -                | -                | -         |     2.27 | doc, gafolo, hoax, koala, rdnzao  |
|           46 |     2940 | 2024-11-22 | Fluxo                    | L   | 0.534      | -            | -                | -                | -         |    -9.50 | doc, gafolo, hoax, koala, rdnzao  |
|           45 |     3703 | 2024-11-09 | Fluxo                    | L   | 0.447      | -            | -                | -                | -         |    -8.29 | doc, gafolo, hoax, koala, rdnzao  |
|           44 |     3728 | 2024-11-09 | Team Solid               | W   | 0.445      | 0.371        | 0.023 (0.004)    | 0.555 (0.091)    | -         |     4.14 | doc, gafolo, hoax, koala, rdnzao  |
|           43 |     3798 | 2024-11-08 | Game Hunters             | W   | 0.439      | -            | -                | -                | -         |     2.07 | doc, gafolo, hoax, koala, rdnzao  |
|           42 |     3826 | 2024-11-07 | MIBR Academy             | W   | 0.433      | 0.371        | -                | 0.464 (0.075)    | -         |     1.89 | doc, gafolo, hoax, koala, rdnzao  |
|           41 |     3922 | 2024-11-05 | Intense Game             | W   | 0.420      | -            | -                | -                | -         |     1.84 | doc, gafolo, hoax, koala, rdnzao  |
|           40 |     3926 | 2024-11-05 | Bounty Hunters Esports   | W   | 0.420      | -            | -                | -                | -         |     2.13 | doc, gafolo, hoax, koala, rdnzao  |
|           39 |     3976 | 2024-11-04 | ODDIK                    | L   | 0.414      | -            | -                | -                | -         |    -9.64 | doc, gafolo, hoax, koala, rdnzao  |
|           38 |     4037 | 2024-11-03 | Team Solid               | L   | 0.407      | -            | -                | -                | -         |    -9.43 | doc, gafolo, hoax, koala, rdnzao  |
|           37 |     4175 | 2024-11-01 | Fluxo                    | W   | 0.394      | 0.143        | 0.056 (0.003)    | -                | -         |     4.70 | doc, gafolo, hoax, koala, rdnzao  |
|           36 |     4230 | 2024-10-31 | América eSports          | W   | 0.387      | -            | -                | -                | -         |     1.07 | doc, gafolo, hoax, koala, rdnzao  |
|           35 |     4326 | 2024-10-30 | AdalYamigos              | W   | 0.378      | -            | -                | -                | -         |     2.29 | doc, gafolo, hoax, koala, rdnzao  |
|           34 |     4356 | 2024-10-29 | Galorys Academy          | W   | 0.373      | -            | -                | -                | -         |     1.25 | doc, gafolo, hoax, koala, rdnzao  |
|           33 |     4409 | 2024-10-28 | UNO MILLE                | L   | 0.366      | -            | -                | -                | -         |    -9.72 | doc, gafolo, hoax, koala, rdnzao  |
|           32 |     4462 | 2024-10-27 | ODDIK                    | W   | 0.359      | -            | -                | -                | 1 (0.359) |     2.78 | doc, gafolo, hoax, koala, rdnzao  |
|           31 |     4510 | 2024-10-26 | Fluxo                    | W   | 0.353      | 0.143        | 0.056 (0.003)    | -                | 1 (0.353) |     4.27 | doc, gafolo, hoax, koala, rdnzao  |
|           30 |     4983 | 2024-10-16 | Imperial Esports         | L   | 0.286      | -            | -                | -                | -         |    -4.96 | doc, gafolo, hoax, koala, rdnzao  |
|           29 |     5050 | 2024-10-15 | Case Esports             | W   | 0.279      | -            | -                | -                | -         |     1.16 | doc, gafolo, hoax, koala, rdnzao  |
|           28 |     5331 | 2024-10-09 | Players (Brazilian team) | W   | 0.240      | -            | -                | -                | -         |     0.22 | doc, gafolo, hoax, koala, rdnzao  |
|           27 |     5339 | 2024-10-09 | Players (Brazilian team) | W   | 0.239      | -            | -                | -                | -         |     0.22 | doc, gafolo, hoax, koala, rdnzao  |
|           26 |     5404 | 2024-10-08 | Case Esports             | W   | 0.233      | -            | -                | -                | -         |     0.98 | doc, gafolo, hoax, koala, rdnzao  |
|           25 |     5415 | 2024-10-08 | Case Esports             | W   | 0.233      | -            | -                | -                | -         |     0.99 | doc, gafolo, hoax, koala, rdnzao  |
|           24 |     5761 | 2024-10-02 | Team Solid               | W   | 0.193      | -            | -                | -                | -         |     1.61 | doc, gafolo, hoax, koala, rdnzao  |
|           23 |     5767 | 2024-10-02 | Team Solid               | L   | 0.193      | -            | -                | -                | -         |    -4.51 | doc, gafolo, hoax, koala, rdnzao  |
|           22 |     5832 | 2024-10-01 | Imperial Esports         | L   | 0.186      | -            | -                | -                | -         |    -3.33 | doc, gafolo, hoax, koala, rdnzao  |
|           21 |     5838 | 2024-10-01 | Imperial Esports         | W   | 0.186      | 0.450        | 0.092 (0.008)    | -                | -         |     2.57 | doc, gafolo, hoax, koala, rdnzao  |
|           20 |     5852 | 2024-10-01 | MIBR                     | W   | 0.185      | 0.450        | 0.142 (0.012)    | -                | -         |     5.32 | doc, gafolo, hoax, koala, rdnzao  |
|           19 |     5855 | 2024-10-01 | MIBR                     | L   | 0.185      | -            | -                | -                | -         |    -0.51 | doc, gafolo, hoax, koala, rdnzao  |
|           18 |     5963 | 2024-09-29 | Myth e-Sports            | W   | 0.172      | -            | -                | -                | -         |     0.46 | doc, gafolo, hoax, koala, rdnzao  |
|           17 |     6006 | 2024-09-28 | Patins da Ferrari        | W   | 0.166      | -            | -                | -                | -         |     0.29 | doc, gafolo, hoax, koala, rdnzao  |
|           16 |     6051 | 2024-09-28 | Nitro.GG                 | W   | 0.164      | -            | -                | -                | -         |     0.66 | doc, gafolo, hoax, koala, rdnzao  |
|           15 |     6190 | 2024-09-26 | BESTIA                   | L   | 0.152      | -            | -                | -                | -         |    -3.12 | doc, gafolo, hoax, koala, rdnzao  |
|           14 |     6221 | 2024-09-26 | Imperial Esports         | L   | 0.151      | -            | -                | -                | -         |    -2.63 | doc, gafolo, hoax, koala, rdnzao  |
|           13 |     6266 | 2024-09-25 | Hype Esports             | L   | 0.146      | -            | -                | -                | -         |    -4.07 | doc, gafolo, hoax, koala, rdnzao  |
|           12 |     6272 | 2024-09-25 | Hype Esports             | W   | 0.146      | -            | -                | -                | -         |     0.54 | doc, gafolo, hoax, koala, rdnzao  |
|           11 |     6307 | 2024-09-25 | MIBR                     | W   | 0.144      | 0.143        | 0.142 (0.003)    | -                | -         |     4.16 | doc, gafolo, hoax, koala, rdnzao  |
|           10 |     6355 | 2024-09-24 | PaiN Gaming              | L   | 0.140      | -            | -                | -                | -         |    -0.12 | doc, gafolo, hoax, koala, rdnzao  |
|            9 |     6361 | 2024-09-24 | PaiN Gaming              | L   | 0.139      | -            | -                | -                | -         |    -0.12 | doc, gafolo, hoax, koala, rdnzao  |
|            8 |     6984 | 2024-09-14 | Nitro.GG                 | W   | 0.072      | -            | -                | -                | -         |     0.28 | doc, gafolo, hoax, koala, rdnzao  |
|            7 |     6995 | 2024-09-14 | Team Solid               | L   | 0.071      | -            | -                | -                | -         |    -1.70 | doc, gafolo, hoax, koala, rdnzao  |
|            6 |     7003 | 2024-09-14 | Yawara E-Sports          | W   | 0.071      | -            | -                | -                | -         |     0.29 | doc, gafolo, hoax, koala, rdnzao  |
|            5 |     7232 | 2024-09-10 | InSanitY Sports          | L   | 0.046      | -            | -                | -                | -         |    -1.29 | doc, gafolo, hoax, koala, rdnzao  |
|            4 |     7236 | 2024-09-10 | InSanitY Sports          | W   | 0.046      | -            | -                | -                | -         |     0.17 | doc, gafolo, hoax, koala, rdnzao  |
|            3 |     7563 | 2024-09-05 | Dusty Roots              | W   | 0.013      | -            | -                | -                | -         |     0.09 | doc, gafolo, hoax, koala, rdnzao  |
|            2 |     7566 | 2024-09-05 | Dusty Roots              | W   | 0.012      | -            | -                | -                | -         |     0.08 | doc, gafolo, hoax, koala, rdnzao  |
|            1 |     7650 | 2024-09-04 | ODDIK                    | L   | 0.006      | -            | -                | -                | -         |    -0.14 | doc, gafolo, hoax, koala, rdnzao  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,053.43)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-12-08 |      0.641 | $7,500.00      | $4,805.73       |
| 2024-11-30 |      0.586 | $1,500.00      | $879.69         |
| 2024-11-24 |      0.546 | $3,878.61      | $2,115.91       |
| 2024-11-09 |      0.447 | $4,000.00      | $1,786.57       |
| 2024-10-27 |      0.359 | $10,512.48     | $3,771.35       |
| 2024-10-20 |      0.312 | $2,000.00      | $623.89         |
| 2024-09-29 |      0.172 | $276.04        | $47.35          |
| 2024-09-14 |      0.073 | $179.69        | $13.04          |
| 2024-09-04 |      0.007 | $1,500.00      | $9.90           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
