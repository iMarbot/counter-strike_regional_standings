### Roster Details<br />
Team Name: Sharks Esports<br />
Roster: doc, gafolo, koala, Nicks, rdnzao<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1003.1<br />
<br />
Final Rank Value (1003.1) = Starting Rank Value (1025.3) + Head To Head Adjustments (-22.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.442[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.109[<sup>2</sup>](#table1)
- LAN Wins: 0.384[<sup>2</sup>](#table1)

The average of these factors is 0.313<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1025.3
- 400 + ( ( 0.313 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1025.3


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
|           65 |      123 | 2025-02-22 | Imperial Esports         | L   | 1.000      | -            | -                | -                | -         |   -12.49 | doc, gafolo, koala, Nicks, rdnzao |
|           64 |      144 | 2025-02-22 | ODDIK                    | W   | 1.000      | 0.371        | 0.028 (0.010)    | 0.521 (0.193)    | 0 (0.000) |    11.02 | doc, gafolo, koala, Nicks, rdnzao |
|           63 |      196 | 2025-02-21 | Swingers                 | W   | 1.000      | 0.371        | -                | 0.187 (0.069)    | 0 (0.000) |     5.97 | doc, gafolo, koala, Nicks, rdnzao |
|           62 |      226 | 2025-02-20 | Bounty Hunters Esports   | W   | 1.000      | 0.371        | -                | 0.524 (0.194)    | 0 (0.000) |     7.79 | doc, gafolo, koala, Nicks, rdnzao |
|           61 |      527 | 2025-02-12 | Fluxo                    | L   | 1.000      | -            | -                | -                | -         |   -15.89 | doc, gafolo, koala, Nicks, rdnzao |
|           60 |      545 | 2025-02-11 | Imperial Esports         | W   | 1.000      | 0.143        | 0.091 (0.013)    | 0.564 (0.081)    | 0 (0.000) |    18.57 | doc, gafolo, koala, Nicks, rdnzao |
|           59 |      551 | 2025-02-11 | Legacy                   | L   | 1.000      | -            | -                | -                | -         |   -17.22 | doc, gafolo, koala, Nicks, rdnzao |
|           58 |      628 | 2025-02-09 | MIBR                     | L   | 1.000      | -            | -                | -                | -         |    -2.96 | doc, gafolo, koala, Nicks, rdnzao |
|           57 |      689 | 2025-02-08 | BESTIA                   | W   | 1.000      | 0.143        | 0.069 (0.010)    | -                | -         |    14.55 | doc, gafolo, koala, Nicks, rdnzao |
|           56 |     1967 | 2024-12-08 | NRG                      | L   | 0.649      | -            | -                | -                | -         |    -9.74 | doc, gafolo, hoax, koala, rdnzao  |
|           55 |     1968 | 2024-12-08 | BOSS                     | W   | 0.648      | 0.384        | 0.014 (0.004)    | 0.327 (0.082)    | 1 (0.648) |     7.81 | doc, gafolo, hoax, koala, rdnzao  |
|           54 |     1971 | 2024-12-08 | NRG                      | L   | 0.647      | -            | -                | -                | -         |   -10.06 | doc, gafolo, hoax, koala, rdnzao  |
|           53 |     2047 | 2024-12-07 | Nouns Esports            | W   | 0.642      | 0.384        | -                | 0.328 (0.081)    | 1 (0.642) |     6.57 | doc, gafolo, hoax, koala, rdnzao  |
|           52 |     2059 | 2024-12-07 | Bad News Capybaras       | W   | 0.641      | -            | -                | -                | 1 (0.641) |     2.35 | doc, gafolo, hoax, koala, rdnzao  |
|           51 |     2115 | 2024-12-06 | MIGHT                    | W   | 0.635      | 0.384        | -                | 0.444 (0.108)    | 1 (0.635) |     3.45 | doc, gafolo, hoax, koala, rdnzao  |
|           50 |     2488 | 2024-11-30 | ODDIK                    | L   | 0.594      | -            | -                | -                | -         |   -13.00 | doc, gafolo, hoax, koala, rdnzao  |
|           49 |     2595 | 2024-11-29 | Nitro.GG                 | W   | 0.586      | 0.371        | -                | 0.518 (0.112)    | -         |     2.97 | doc, gafolo, hoax, koala, rdnzao  |
|           48 |     2631 | 2024-11-28 | 20/70                    | W   | 0.580      | -            | -                | -                | -         |     2.34 | doc, gafolo, hoax, koala, rdnzao  |
|           47 |     2928 | 2024-11-22 | Fluxo                    | L   | 0.542      | -            | -                | -                | -         |    -9.54 | doc, gafolo, hoax, koala, rdnzao  |
|           46 |     3691 | 2024-11-09 | Fluxo                    | L   | 0.455      | -            | -                | -                | -         |    -8.35 | doc, gafolo, hoax, koala, rdnzao  |
|           45 |     3716 | 2024-11-09 | Team Solid               | W   | 0.453      | 0.371        | 0.023 (0.004)    | 0.561 (0.094)    | -         |     4.28 | doc, gafolo, hoax, koala, rdnzao  |
|           44 |     3786 | 2024-11-08 | Game Hunters             | W   | 0.447      | -            | -                | -                | -         |     2.14 | doc, gafolo, hoax, koala, rdnzao  |
|           43 |     3814 | 2024-11-07 | MIBR Academy             | W   | 0.442      | 0.371        | -                | 0.470 (0.077)    | -         |     1.95 | doc, gafolo, hoax, koala, rdnzao  |
|           42 |     3910 | 2024-11-05 | Intense Game             | W   | 0.428      | -            | -                | -                | -         |     1.90 | doc, gafolo, hoax, koala, rdnzao  |
|           41 |     3914 | 2024-11-05 | Bounty Hunters Esports   | W   | 0.428      | -            | -                | -                | -         |     2.19 | doc, gafolo, hoax, koala, rdnzao  |
|           40 |     3964 | 2024-11-04 | ODDIK                    | L   | 0.422      | -            | -                | -                | -         |    -9.79 | doc, gafolo, hoax, koala, rdnzao  |
|           39 |     4025 | 2024-11-03 | Team Solid               | L   | 0.415      | -            | -                | -                | -         |    -9.56 | doc, gafolo, hoax, koala, rdnzao  |
|           38 |     4163 | 2024-11-01 | Fluxo                    | W   | 0.402      | 0.143        | 0.056 (0.003)    | -                | -         |     4.88 | doc, gafolo, hoax, koala, rdnzao  |
|           37 |     4218 | 2024-10-31 | América eSports          | W   | 0.395      | -            | -                | -                | -         |     1.10 | doc, gafolo, hoax, koala, rdnzao  |
|           36 |     4314 | 2024-10-30 | AdalYamigos              | W   | 0.386      | -            | -                | -                | -         |     2.38 | doc, gafolo, hoax, koala, rdnzao  |
|           35 |     4344 | 2024-10-29 | Galorys Academy          | W   | 0.381      | -            | -                | -                | -         |     1.29 | doc, gafolo, hoax, koala, rdnzao  |
|           34 |     4397 | 2024-10-28 | UNO MILLE                | L   | 0.374      | -            | -                | -                | -         |    -9.92 | doc, gafolo, hoax, koala, rdnzao  |
|           33 |     4450 | 2024-10-27 | ODDIK                    | W   | 0.367      | -            | -                | -                | 1 (0.367) |     2.88 | doc, gafolo, hoax, koala, rdnzao  |
|           32 |     4498 | 2024-10-26 | Fluxo                    | W   | 0.361      | 0.143        | 0.056 (0.003)    | -                | 1 (0.361) |     4.45 | doc, gafolo, hoax, koala, rdnzao  |
|           31 |     4971 | 2024-10-16 | Imperial Esports         | L   | 0.294      | -            | -                | -                | -         |    -5.02 | doc, gafolo, hoax, koala, rdnzao  |
|           30 |     5038 | 2024-10-15 | Case Esports             | W   | 0.287      | -            | -                | -                | -         |     1.21 | doc, gafolo, hoax, koala, rdnzao  |
|           29 |     5319 | 2024-10-09 | Players (Brazilian team) | W   | 0.248      | -            | -                | -                | -         |     0.23 | doc, gafolo, hoax, koala, rdnzao  |
|           28 |     5327 | 2024-10-09 | Players (Brazilian team) | W   | 0.247      | -            | -                | -                | -         |     0.23 | doc, gafolo, hoax, koala, rdnzao  |
|           27 |     5392 | 2024-10-08 | Case Esports             | W   | 0.241      | -            | -                | -                | -         |     1.03 | doc, gafolo, hoax, koala, rdnzao  |
|           26 |     5403 | 2024-10-08 | Case Esports             | W   | 0.241      | -            | -                | -                | -         |     1.04 | doc, gafolo, hoax, koala, rdnzao  |
|           25 |     5749 | 2024-10-02 | Team Solid               | W   | 0.201      | -            | -                | -                | -         |     1.71 | doc, gafolo, hoax, koala, rdnzao  |
|           24 |     5755 | 2024-10-02 | Team Solid               | L   | 0.201      | -            | -                | -                | -         |    -4.68 | doc, gafolo, hoax, koala, rdnzao  |
|           23 |     5820 | 2024-10-01 | Imperial Esports         | L   | 0.194      | -            | -                | -                | -         |    -3.43 | doc, gafolo, hoax, koala, rdnzao  |
|           22 |     5826 | 2024-10-01 | Imperial Esports         | W   | 0.194      | 0.450        | 0.091 (0.008)    | -                | -         |     2.73 | doc, gafolo, hoax, koala, rdnzao  |
|           21 |     5840 | 2024-10-01 | MIBR                     | W   | 0.193      | 0.450        | 0.141 (0.012)    | -                | -         |     5.57 | doc, gafolo, hoax, koala, rdnzao  |
|           20 |     5843 | 2024-10-01 | MIBR                     | L   | 0.193      | -            | -                | -                | -         |    -0.52 | doc, gafolo, hoax, koala, rdnzao  |
|           19 |     5951 | 2024-09-29 | Myth e-Sports            | W   | 0.180      | -            | -                | -                | -         |     0.49 | doc, gafolo, hoax, koala, rdnzao  |
|           18 |     5994 | 2024-09-28 | Patins da Ferrari        | W   | 0.175      | -            | -                | -                | -         |     0.31 | doc, gafolo, hoax, koala, rdnzao  |
|           17 |     6039 | 2024-09-28 | Nitro.GG                 | W   | 0.172      | -            | -                | -                | -         |     0.70 | doc, gafolo, hoax, koala, rdnzao  |
|           16 |     6178 | 2024-09-26 | BESTIA                   | L   | 0.161      | -            | -                | -                | -         |    -3.25 | doc, gafolo, hoax, koala, rdnzao  |
|           15 |     6209 | 2024-09-26 | Imperial Esports         | L   | 0.159      | -            | -                | -                | -         |    -2.73 | doc, gafolo, hoax, koala, rdnzao  |
|           14 |     6254 | 2024-09-25 | Hype Esports             | L   | 0.154      | -            | -                | -                | -         |    -4.29 | doc, gafolo, hoax, koala, rdnzao  |
|           13 |     6260 | 2024-09-25 | Hype Esports             | W   | 0.154      | -            | -                | -                | -         |     0.58 | doc, gafolo, hoax, koala, rdnzao  |
|           12 |     6295 | 2024-09-25 | MIBR                     | W   | 0.152      | 0.143        | 0.141 (0.003)    | -                | -         |     4.41 | doc, gafolo, hoax, koala, rdnzao  |
|           11 |     6343 | 2024-09-24 | PaiN Gaming              | L   | 0.148      | -            | -                | -                | -         |    -0.13 | doc, gafolo, hoax, koala, rdnzao  |
|           10 |     6349 | 2024-09-24 | PaiN Gaming              | L   | 0.147      | -            | -                | -                | -         |    -0.13 | doc, gafolo, hoax, koala, rdnzao  |
|            9 |     6972 | 2024-09-14 | Nitro.GG                 | W   | 0.080      | -            | -                | -                | -         |     0.32 | doc, gafolo, hoax, koala, rdnzao  |
|            8 |     6983 | 2024-09-14 | Team Solid               | L   | 0.080      | -            | -                | -                | -         |    -1.89 | doc, gafolo, hoax, koala, rdnzao  |
|            7 |     6991 | 2024-09-14 | Yawara E-Sports          | W   | 0.079      | -            | -                | -                | -         |     0.32 | doc, gafolo, hoax, koala, rdnzao  |
|            6 |     7220 | 2024-09-10 | InSanitY Sports          | L   | 0.054      | -            | -                | -                | -         |    -1.52 | doc, gafolo, hoax, koala, rdnzao  |
|            5 |     7224 | 2024-09-10 | InSanitY Sports          | W   | 0.054      | -            | -                | -                | -         |     0.20 | doc, gafolo, hoax, koala, rdnzao  |
|            4 |     7551 | 2024-09-05 | Dusty Roots              | W   | 0.021      | -            | -                | -                | -         |     0.14 | doc, gafolo, hoax, koala, rdnzao  |
|            3 |     7554 | 2024-09-05 | Dusty Roots              | W   | 0.021      | -            | -                | -                | -         |     0.14 | doc, gafolo, hoax, koala, rdnzao  |
|            2 |     7638 | 2024-09-04 | ODDIK                    | L   | 0.014      | -            | -                | -                | -         |    -0.33 | doc, gafolo, hoax, koala, rdnzao  |
|            1 |     7740 | 2024-09-03 | InSanitY Sports          | W   | 0.005      | -            | -                | -                | -         |     0.02 | doc, gafolo, hoax, koala, rdnzao  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,310.30)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-12-08 |      0.649 | $7,500.00      | $4,867.19       |
| 2024-11-30 |      0.595 | $1,500.00      | $891.98         |
| 2024-11-24 |      0.554 | $3,878.61      | $2,147.69       |
| 2024-11-09 |      0.455 | $4,000.00      | $1,819.35       |
| 2024-10-27 |      0.367 | $10,512.48     | $3,857.49       |
| 2024-10-20 |      0.320 | $2,000.00      | $640.28         |
| 2024-09-29 |      0.180 | $276.04        | $49.61          |
| 2024-09-14 |      0.081 | $179.69        | $14.51          |
| 2024-09-04 |      0.015 | $1,500.00      | $22.19          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
