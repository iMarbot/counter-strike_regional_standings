### Roster Details<br />
Team Name: 9Pandas<br />
Roster: d1Ledez, KaiR0N-, Krad, r3salt, shalfey<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1050.3<br />
<br />
Final Rank Value (1050.3) = Starting Rank Value (978.0) + Head To Head Adjustments (72.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.483[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.175[<sup>2</sup>](#table1)
- LAN Wins: 0.124[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 978.0
- 400 + ( ( 0.289 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 978.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |      122 | 2025-02-23 | B8                                        | L   | 1.000      | -            | -                | -                | -         |   -12.80 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           49 |      182 | 2025-02-22 | Dynamo Eclot                              | W   | 1.000      | 0.435        | 0.128 (0.056)    | 0.692 (0.301)    | 0 (0.000) |    14.65 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           48 |      263 | 2025-02-20 | Sashi Esport                              | W   | 1.000      | 0.435        | 0.013 (0.006)    | 0.499 (0.217)    | 0 (0.000) |    11.25 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           47 |      518 | 2025-02-13 | 500                                       | L   | 1.000      | -            | -                | -                | -         |   -13.58 | d1Ledez, Krad, mo0N, r3salt, shalfey            |
|           46 |     1198 | 2025-01-14 | Team Liquid                               | L   | 0.885      | -            | -                | -                | -         |    -1.69 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           45 |     1202 | 2025-01-12 | Wildcard                                  | L   | 0.871      | -            | -                | -                | -         |    -4.55 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           44 |     1206 | 2025-01-11 | EYEBALLERS                                | W   | 0.864      | 0.417        | 0.019 (0.007)    | 0.350 (0.126)    | 0 (0.000) |     6.23 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           43 |     1213 | 2025-01-10 | GenOne                                    | W   | 0.857      | 0.417        | -                | 0.837 (0.299)    | 0 (0.000) |     6.53 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           42 |     2831 | 2024-11-23 | Ninjas in Pyjamas                         | L   | 0.541      | -            | -                | -                | -         |   -12.16 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           41 |     2933 | 2024-11-22 | Aurora Gaming                             | W   | 0.535      | -            | -                | -                | 1 (0.535) |     3.79 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           40 |     3014 | 2024-11-21 | Virtus.pro                                | L   | 0.528      | -            | -                | -                | -         |    -0.64 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           39 |     3064 | 2024-11-21 | G2 Esports                                | L   | 0.523      | -            | -                | -                | -         |    -0.22 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           38 |     3076 | 2024-11-20 | Astralis                                  | W   | 0.522      | 0.143        | 0.619 (0.046)    | -                | 1 (0.522) |    16.26 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           37 |     3643 | 2024-11-11 | Dynamo Eclot                              | W   | 0.456      | 0.371        | 0.128 (0.022)    | -                | 0 (0.000) |     7.98 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           36 |     3665 | 2024-11-10 | Dynamo Eclot                              | W   | 0.452      | 0.384        | 0.128 (0.022)    | 0.692 (0.120)    | 0 (0.000) |     8.23 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           35 |     3687 | 2024-11-10 | 500                                       | L   | 0.450      | -            | -                | -                | -         |    -7.34 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           34 |     3736 | 2024-11-09 | Tricked Esport                            | W   | 0.444      | 0.384        | 0.034 (0.006)    | 0.687 (0.117)    | 0 (0.000) |     4.12 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           33 |     3749 | 2024-11-09 | Natus Vincere Junior                      | W   | 0.444      | 0.371        | 0.091 (0.015)    | 0.865 (0.142)    | 0 (0.000) |     6.68 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           32 |     3818 | 2024-11-08 | Fire Flux Esports                         | W   | 0.437      | 0.384        | -                | 1.000 (0.168)    | -         |     4.77 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           31 |     3855 | 2024-11-07 | Aurora Gaming                             | L   | 0.431      | -            | -                | -                | -         |   -10.31 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           30 |     3864 | 2024-11-07 | Dynamo Eclot                              | W   | 0.430      | 0.371        | 0.128 (0.020)    | -                | -         |     7.70 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           29 |     3947 | 2024-11-05 | Insilio                                   | W   | 0.418      | -            | -                | -                | -         |     1.40 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           28 |     3967 | 2024-11-05 | Los kogutos                               | W   | 0.417      | -            | -                | -                | -         |     4.57 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           27 |     4084 | 2024-11-03 | Tricked Esport                            | W   | 0.403      | -            | -                | -                | -         |     3.92 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           26 |     4151 | 2024-11-02 | Endpoint                                  | W   | 0.398      | -            | -                | -                | -         |     2.84 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           25 |     4219 | 2024-11-01 | Natus Vincere Junior                      | W   | 0.390      | 0.371        | 0.091 (0.013)    | 0.865 (0.125)    | -         |     6.10 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           24 |     4276 | 2024-10-31 | 9INE                                      | W   | 0.383      | -            | -                | -                | -         |     3.08 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           23 |     4337 | 2024-10-30 | Johnny Speeds                             | W   | 0.377      | -            | -                | -                | -         |     4.78 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           22 |     4454 | 2024-10-28 | ALASKA                                    | W   | 0.363      | -            | -                | -                | -         |     7.50 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           21 |     4612 | 2024-10-25 | Fire Flux Esports                         | W   | 0.344      | 0.384        | -                | 1.000 (0.132)    | -         |     4.07 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           20 |     4821 | 2024-10-20 | Dynamo Eclot                              | L   | 0.310      | -            | -                | -                | -         |    -3.87 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           19 |     4939 | 2024-10-17 | SAW                                       | L   | 0.291      | -            | -                | -                | -         |    -1.16 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           18 |     5008 | 2024-10-16 | TSM                                       | W   | 0.285      | -            | -                | -                | -         |     2.00 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           17 |     5071 | 2024-10-15 | Zero Tenacity                             | W   | 0.278      | -            | -                | -                | -         |     3.05 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           16 |     5217 | 2024-10-12 | NewBALLS                                  | W   | 0.257      | -            | -                | -                | -         |     1.19 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           15 |     5538 | 2024-10-06 | GamerLegion                               | L   | 0.217      | -            | -                | -                | -         |    -0.22 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           14 |     5601 | 2024-10-05 | ECSTATIC                                  | W   | 0.211      | -            | -                | -                | -         |     2.55 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           13 |     5679 | 2024-10-04 | AMKAL ESPORTS                             | W   | 0.204      | -            | -                | -                | -         |     1.64 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           12 |     6546 | 2024-09-22 | Nemiga Gaming                             | L   | 0.122      | -            | -                | -                | -         |    -1.71 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           11 |     6589 | 2024-09-21 | Nexus Gaming                              | L   | 0.118      | -            | -                | -                | -         |    -0.90 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           10 |     6602 | 2024-09-21 | Devils.one                                | W   | 0.117      | -            | -                | -                | -         |     0.53 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            9 |     6636 | 2024-09-20 | Wild Lotus                                | W   | 0.112      | -            | -                | -                | -         |     0.76 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            8 |     6702 | 2024-09-19 | Copenhagen Wolves (American organization) | L   | 0.105      | -            | -                | -                | -         |    -3.04 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            7 |     6718 | 2024-09-19 | Nemiga Gaming                             | L   | 0.103      | -            | -                | -                | -         |    -1.46 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            6 |     6843 | 2024-09-17 | The Suspect                               | W   | 0.091      | -            | -                | -                | -         |     0.57 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            5 |     6906 | 2024-09-16 | Los kogutos                               | L   | 0.084      | -            | -                | -                | -         |    -1.21 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            4 |     6941 | 2024-09-15 | K27                                       | W   | 0.077      | -            | -                | -                | -         |     1.07 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            3 |     6953 | 2024-09-15 | Johnny Speeds                             | L   | 0.077      | -            | -                | -                | -         |    -1.50 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            2 |     6965 | 2024-09-15 | Underrated                                | W   | 0.076      | -            | -                | -                | -         |     0.41 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            1 |     7511 | 2024-09-06 | B8                                        | W   | 0.018      | -            | -                | -                | -         |     0.39 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,110.76)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $5,000.00      | $5,000.00       |
| 2025-01-12 |      0.871 | $10,000.00     | $8,706.94       |
| 2024-11-12 |      0.464 | $500.00        | $232.21         |
| 2024-11-11 |      0.456 | $11,000.00     | $5,015.69       |
| 2024-11-10 |      0.452 | $12,500.00     | $5,647.57       |
| 2024-11-09 |      0.444 | $15.18         | $6.74           |
| 2024-10-20 |      0.311 | $6,000.00      | $1,864.17       |
| 2024-10-06 |      0.218 | $5,000.00      | $1,091.32       |
| 2024-09-24 |      0.137 | $4,000.00      | $546.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
