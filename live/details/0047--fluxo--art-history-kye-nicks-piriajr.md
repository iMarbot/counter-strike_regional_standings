### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, history, kye, nicks, piriajr<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [13]( ../standings_americas.md)<br />
<br />
Final Rank Value:  984.6<br />
<br />
Final Rank Value (984.6) = Starting Rank Value (927.7) + Head To Head Adjustments (56.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.444[<sup>1</sup>](#table2)
- Bounty Collected: 0.346[<sup>2</sup>](#table1)
- Opponent Network: 0.106[<sup>2</sup>](#table1)
- LAN Wins: 0.159[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 927.7
- 400 + ( ( 0.264 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 927.7


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
|           56 |      140 | 2025-02-22 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |   -12.34 | arT, history, kye, nicks, piriajr |
|           55 |      191 | 2025-02-21 | Team Solid             | W   | 1.000      | 0.371        | 0.023 (0.009)    | 0.555 (0.206)    | 0 (0.000) |    11.38 | arT, history, kye, nicks, piriajr |
|           54 |      535 | 2025-02-12 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -15.61 | arT, history, kye, nicks, piriajr |
|           53 |      539 | 2025-02-12 | Sharks Esports         | W   | 1.000      | 0.143        | 0.055 (0.008)    | 0.622 (0.089)    | 0 (0.000) |    16.32 | arT, history, kye, nicks, piriajr |
|           52 |      556 | 2025-02-11 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -16.30 | arT, history, kye, nicks, piriajr |
|           51 |      562 | 2025-02-11 | Imperial Esports       | W   | 1.000      | 0.143        | 0.092 (0.013)    | 0.562 (0.080)    | 0 (0.000) |    19.49 | arT, history, kye, nicks, piriajr |
|           50 |      718 | 2025-02-08 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |   -14.58 | arT, history, kye, nicks, piriajr |
|           49 |     1191 | 2025-01-16 | Eternal Fire           | L   | 0.897      | -            | -                | -                | -         |    -0.27 | arT, history, kye, nicks, piriajr |
|           48 |     2474 | 2024-11-30 | ODDIK                  | W   | 0.586      | 0.371        | 0.028 (0.006)    | 0.518 (0.113)    | 0 (0.000) |     5.97 | arT, kye, nicks, piriajr, zevy    |
|           47 |     2526 | 2024-11-30 | Team Solid             | W   | 0.585      | 0.371        | -                | 0.555 (0.120)    | 0 (0.000) |     6.33 | arT, kye, nicks, piriajr, zevy    |
|           46 |     2586 | 2024-11-29 | TROPA DO TACO          | W   | 0.579      | 0.371        | -                | 0.377 (0.081)    | 0 (0.000) |     4.37 | arT, kye, nicks, piriajr, zevy    |
|           45 |     2664 | 2024-11-27 | Yawara E-Sports        | W   | 0.567      | 0.371        | -                | 0.448 (0.094)    | 0 (0.000) |     3.26 | arT, kye, nicks, piriajr, zevy    |
|           44 |     2785 | 2024-11-24 | Team Solid             | W   | 0.546      | -            | -                | -                | 1 (0.546) |     6.09 | arT, kye, nicks, piriajr, zevy    |
|           43 |     2940 | 2024-11-22 | Sharks Esports         | W   | 0.534      | -            | -                | -                | 1 (0.534) |     9.50 | arT, kye, nicks, piriajr, zevy    |
|           42 |     3703 | 2024-11-09 | Sharks Esports         | W   | 0.447      | 0.371        | 0.055 (0.009)    | 0.622 (0.103)    | -         |     8.29 | arT, kye, nicks, piriajr, zevy    |
|           41 |     3710 | 2024-11-09 | ODDIK                  | W   | 0.446      | 0.371        | -                | 0.518 (0.085)    | -         |     5.15 | arT, kye, nicks, piriajr, zevy    |
|           40 |     3785 | 2024-11-08 | TROPA DO TACO          | W   | 0.440      | -            | -                | -                | -         |     3.26 | arT, kye, nicks, piriajr, zevy    |
|           39 |     3906 | 2024-11-06 | 9z Academy             | W   | 0.424      | -            | -                | -                | -         |     2.61 | arT, kye, nicks, piriajr, zevy    |
|           38 |     3930 | 2024-11-05 | Bounty Hunters Esports | W   | 0.419      | -            | -                | -                | -         |     2.95 | arT, kye, nicks, piriajr, zevy    |
|           37 |     3977 | 2024-11-04 | Galorys Academy        | W   | 0.413      | -            | -                | -                | -         |     1.85 | arT, kye, nicks, piriajr, zevy    |
|           36 |     4042 | 2024-11-03 | América eSports        | W   | 0.406      | -            | -                | -                | -         |     1.70 | arT, kye, nicks, piriajr, zevy    |
|           35 |     4113 | 2024-11-02 | AdalYamigos            | W   | 0.400      | -            | -                | -                | -         |     3.26 | arT, kye, nicks, piriajr, zevy    |
|           34 |     4175 | 2024-11-01 | Sharks Esports         | L   | 0.394      | -            | -                | -                | -         |    -4.70 | arT, kye, nicks, piriajr, zevy    |
|           33 |     4237 | 2024-10-31 | UNO MILLE              | W   | 0.387      | -            | -                | -                | -         |     3.07 | arT, kye, nicks, piriajr, zevy    |
|           32 |     4308 | 2024-10-30 | Intense Game           | W   | 0.379      | -            | -                | -                | -         |     2.31 | arT, kye, nicks, piriajr, zevy    |
|           31 |     4347 | 2024-10-29 | ODDIK                  | W   | 0.374      | -            | -                | -                | -         |     4.25 | arT, kye, nicks, piriajr, zevy    |
|           30 |     4400 | 2024-10-28 | Team Solid             | L   | 0.367      | -            | -                | -                | -         |    -7.41 | arT, kye, nicks, piriajr, zevy    |
|           29 |     4510 | 2024-10-26 | Sharks Esports         | L   | 0.353      | -            | -                | -                | -         |    -4.27 | arT, kye, nicks, piriajr, zevy    |
|           28 |     4917 | 2024-10-18 | Nemiga Gaming          | L   | 0.296      | -            | -                | -                | -         |    -3.67 | arT, kye, nicks, piriajr, zevy    |
|           27 |     4957 | 2024-10-17 | HEROIC                 | L   | 0.290      | -            | -                | -                | -         |    -2.84 | arT, kye, nicks, piriajr, zevy    |
|           26 |     5038 | 2024-10-16 | Aurora Gaming          | W   | 0.282      | 0.624        | -                | 0.514 (0.090)    | 1 (0.282) |     2.92 | arT, kye, nicks, piriajr, zevy    |
|           25 |     5400 | 2024-10-08 | AdalYamigos            | L   | 0.233      | -            | -                | -                | -         |    -5.53 | arT, kye, nicks, piriajr, zevy    |
|           24 |     5411 | 2024-10-08 | AdalYamigos            | L   | 0.233      | -            | -                | -                | -         |    -5.61 | arT, kye, nicks, piriajr, zevy    |
|           23 |     5657 | 2024-10-04 | MIBR                   | W   | 0.206      | 0.450        | 0.142 (0.013)    | -                | -         |     6.09 | arT, kye, nicks, piriajr, zevy    |
|           22 |     5659 | 2024-10-04 | MIBR                   | L   | 0.206      | -            | -                | -                | -         |    -0.41 | arT, kye, nicks, piriajr, zevy    |
|           21 |     5760 | 2024-10-02 | PaiN Gaming            | W   | 0.193      | 0.450        | 0.323 (0.028)    | -                | -         |     5.96 | arT, kye, nicks, piriajr, zevy    |
|           20 |     5766 | 2024-10-02 | PaiN Gaming            | W   | 0.193      | 0.450        | 0.323 (0.028)    | -                | -         |     5.96 | arT, kye, nicks, piriajr, zevy    |
|           19 |     5897 | 2024-09-30 | Imperial Esports       | W   | 0.180      | 0.450        | 0.092 (0.007)    | -                | -         |     3.24 | arT, kye, nicks, piriajr, zevy    |
|           18 |     5900 | 2024-09-30 | Imperial Esports       | W   | 0.179      | 0.450        | 0.092 (0.007)    | -                | -         |     3.29 | arT, kye, nicks, piriajr, zevy    |
|           17 |     5955 | 2024-09-29 | PaiN Gaming            | L   | 0.173      | -            | -                | -                | -         |    -0.09 | arT, kye, nicks, piriajr, zevy    |
|           16 |     6007 | 2024-09-28 | Team Solid             | W   | 0.166      | -            | -                | -                | -         |     1.99 | arT, kye, nicks, piriajr, zevy    |
|           15 |     6015 | 2024-09-28 | RED Canids             | W   | 0.165      | -            | -                | -                | -         |     2.04 | arT, kye, nicks, piriajr, zevy    |
|           14 |     6099 | 2024-09-27 | Dusty Roots            | W   | 0.160      | -            | -                | -                | -         |     1.63 | arT, kye, nicks, piriajr, zevy    |
|           13 |     6104 | 2024-09-27 | Hype Esports           | W   | 0.159      | -            | -                | -                | -         |     1.00 | arT, kye, nicks, piriajr, zevy    |
|           12 |     6115 | 2024-09-27 | Floripa Stars          | W   | 0.159      | -            | -                | -                | -         |     0.91 | arT, kye, nicks, piriajr, zevy    |
|           11 |     6264 | 2024-09-25 | RED Canids             | W   | 0.146      | -            | -                | -                | -         |     1.85 | arT, kye, nicks, piriajr, zevy    |
|           10 |     6270 | 2024-09-25 | RED Canids             | W   | 0.146      | -            | -                | -                | -         |     1.87 | arT, kye, nicks, piriajr, zevy    |
|            9 |     6357 | 2024-09-24 | KRÜ Esports            | L   | 0.140      | -            | -                | -                | -         |    -3.43 | arT, kye, nicks, piriajr, zevy    |
|            8 |     6363 | 2024-09-24 | KRÜ Esports            | L   | 0.139      | -            | -                | -                | -         |    -3.45 | arT, kye, nicks, piriajr, zevy    |
|            7 |     6383 | 2024-09-24 | RED Canids             | L   | 0.138      | -            | -                | -                | -         |    -3.42 | arT, kye, nicks, piriajr, zevy    |
|            6 |     6402 | 2024-09-24 | InSanitY Sports        | W   | 0.137      | -            | -                | -                | -         |     0.81 | arT, kye, nicks, piriajr, zevy    |
|            5 |     6442 | 2024-09-23 | ODDIK                  | W   | 0.133      | -            | -                | -                | -         |     1.49 | arT, kye, nicks, piriajr, zevy    |
|            4 |     6444 | 2024-09-23 | ODDIK                  | W   | 0.133      | -            | -                | -                | -         |     1.50 | arT, kye, nicks, piriajr, zevy    |
|            3 |     6476 | 2024-09-23 | RED Canids             | L   | 0.131      | -            | -                | -                | -         |    -3.26 | arT, kye, nicks, piriajr, zevy    |
|            2 |     7646 | 2024-09-04 | ODDIK                  | W   | 0.007      | -            | -                | -                | -         |     0.07 | arT, kye, Lucaozy, nicks, zevy    |
|            1 |     7672 | 2024-09-04 | BESTIA                 | W   | 0.005      | -            | -                | -                | -         |     0.07 | arT, kye, Lucaozy, nicks, zevy    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,353.74)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-11-30 |      0.586 | $10,000.00     | $5,864.58       |
| 2024-11-24 |      0.546 | $10,342.97     | $5,642.43       |
| 2024-11-09 |      0.447 | $10,000.00     | $4,466.44       |
| 2024-10-27 |      0.359 | $1,226.46      | $439.99         |
| 2024-10-20 |      0.312 | $1,200.00      | $374.33         |
| 2024-09-04 |      0.007 | $10,000.00     | $65.97          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
