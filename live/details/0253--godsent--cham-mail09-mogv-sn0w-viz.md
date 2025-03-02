### Roster Details<br />
Team Name: GODSENT<br />
Roster: Cham, MaiL09, mogv, Sn0w, viz<br />
Global Rank: [253](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [177]( ../standings_europe.md)<br />
<br />
Final Rank Value:  676.0<br />
<br />
Final Rank Value (676.0) = Starting Rank Value (667.7) + Head To Head Adjustments (8.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.244[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 667.7
- 400 + ( ( 0.134 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 667.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |     1586 | 2024-12-16 | Astralis Talent                           | L   | 0.699      | -            | -                | -                | -         |    -7.94 | Cham, MaiL09, mogv, Sn0w, viz       |
|           44 |     1839 | 2024-12-12 | ADEPTS                                    | W   | 0.672      | 0.333        | -                | 0.292 (0.065)    | 0 (0.000) |    10.49 | Cham, MaiL09, mogv, Sn0w, viz       |
|           43 |     2004 | 2024-12-08 | KONO.ECF                                  | L   | 0.646      | -            | -                | -                | -         |    -6.13 | Cham, MaiL09, mogv, Sn0w, viz       |
|           42 |     2624 | 2024-11-28 | FLuffy Gangsters                          | L   | 0.580      | -            | -                | -                | -         |    -5.01 | Cham, MaiL09, mogv, Sn0w, viz       |
|           41 |     2726 | 2024-11-26 | Preasy Esport                             | L   | 0.566      | -            | -                | -                | -         |    -7.17 | Cham, MaiL09, mogv, Sn0w, viz       |
|           40 |     2784 | 2024-11-24 | Lausanne-Sport Esports                    | W   | 0.553      | 0.372        | -                | 0.126 (0.026)    | 0 (0.000) |     6.14 | MaiL09, mogv, Sn0w, viz, Zyppe      |
|           39 |     2806 | 2024-11-24 | Lilmix                                    | W   | 0.551      | 0.333        | 0.001 (0.000)    | 0.130 (0.024)    | 0 (0.000) |     6.31 | MaiL09, mogv, Sn0w, Svedjehed, viz  |
|           38 |     2961 | 2024-11-22 | Betera Esports                            | L   | 0.540      | -            | -                | -                | -         |    -6.99 | Cham, MaiL09, mogv, Sn0w, viz       |
|           37 |     3022 | 2024-11-21 | PCIFIC Espor                              | L   | 0.533      | -            | -                | -                | -         |    -6.77 | Cham, MaiL09, mogv, Sn0w, viz       |
|           36 |     3088 | 2024-11-20 | MOUZ NXT                                  | L   | 0.527      | -            | -                | -                | -         |   -10.36 | Cham, MaiL09, mogv, Sn0w, viz       |
|           35 |     3109 | 2024-11-20 | RUSTEC                                    | W   | 0.526      | 0.372        | 0.002 (0.000)    | 0.100 (0.020)    | 0 (0.000) |     7.23 | Cham, MaiL09, mogv, Sn0w, viz       |
|           34 |     3369 | 2024-11-15 | Poslednii3ae3d                            | W   | 0.494      | 0.372        | 0.001 (0.000)    | 0.103 (0.019)    | 0 (0.000) |     6.31 | Cham, MaiL09, mogv, Sn0w, viz       |
|           33 |     3440 | 2024-11-14 | Kay Team                                  | W   | 0.486      | -            | -                | -                | 0 (0.000) |     4.08 | Cham, MaiL09, mogv, Sn0w, viz       |
|           32 |     3483 | 2024-11-13 | ADEPTS                                    | W   | 0.480      | 0.372        | -                | 0.292 (0.052)    | 0 (0.000) |     7.79 | Cham, MaiL09, mogv, Sn0w, viz       |
|           31 |     3873 | 2024-11-06 | Soul's Heart Esport                       | W   | 0.434      | -            | -                | -                | 0 (0.000) |     4.58 | Cham, MaiL09, mogv, Sn0w, viz       |
|           30 |     3934 | 2024-11-05 | Kario Mart                                | L   | 0.427      | -            | -                | -                | -         |    -7.65 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           29 |     4053 | 2024-11-03 | Adventurers                               | L   | 0.413      | -            | -                | -                | -         |    -4.17 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           28 |     4247 | 2024-10-31 | Preasy Esport                             | W   | 0.393      | 0.333        | 0.012 (0.002)    | 0.710 (0.093)    | 0 (0.000) |     8.06 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           27 |     4290 | 2024-10-30 | Ex-Soul's Heart Esport                    | W   | 0.387      | 0.372        | 0.000 (0.000)    | -                | 0 (0.000) |     5.36 | Cham, MaiL09, mogv, Sn0w, viz       |
|           26 |     4372 | 2024-10-29 | Natus Vincere Youth                       | W   | 0.379      | -            | -                | -                | -         |     3.16 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           25 |     4428 | 2024-10-28 | GTZ.ESPORTS                               | L   | 0.373      | -            | -                | -                | -         |    -0.59 | Cham, MaiL09, mogv, Sn0w, viz       |
|           24 |     4664 | 2024-10-23 | Los kogutos                               | W   | 0.339      | 0.372        | 0.032 (0.004)    | 0.527 (0.067)    | -         |     8.98 | Cham, MaiL09, mogv, Sn0w, viz       |
|           23 |     4724 | 2024-10-21 | Nuclear TigeRES                           | L   | 0.326      | -            | -                | -                | -         |    -2.93 | Cham, MaiL09, mogv, Sn0w, viz       |
|           22 |     4983 | 2024-10-16 | Copenhagen Wolves (American organization) | L   | 0.293      | -            | -                | -                | -         |    -2.33 | Cham, MaiL09, mogv, Sn0w, viz       |
|           21 |     5064 | 2024-10-15 | Heimo Esports                             | L   | 0.286      | -            | -                | -                | -         |    -3.48 | Cham, MaiL09, mogv, Sn0w, viz       |
|           20 |     5521 | 2024-10-06 | Adventurers                               | L   | 0.226      | -            | -                | -                | -         |    -2.48 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           19 |     5597 | 2024-10-05 | Alliance                                  | L   | 0.219      | -            | -                | -                | -         |    -1.57 | Cham, Sn0w, TiiREX, viz, Wonder     |
|           18 |     5949 | 2024-09-29 | Leo Team                                  | W   | 0.180      | 0.354        | 0.026 (0.002)    | 0.758 (0.048)    | -         |     4.09 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           17 |     6044 | 2024-09-28 | Preasy Esport                             | W   | 0.172      | 0.354        | 0.012 (0.001)    | 0.710 (0.043)    | -         |     3.74 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           16 |     6116 | 2024-09-27 | Lilmix                                    | L   | 0.166      | -            | -                | -                | -         |    -2.70 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           15 |     6127 | 2024-09-27 | Carte Blanche                             | W   | 0.166      | -            | -                | -                | -         |     0.96 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           14 |     6410 | 2024-09-24 | Leo Team                                  | L   | 0.145      | -            | -                | -                | -         |    -1.29 | Cham, Fraaank, MaiL09, simpan, Sn0w |
|           13 |     6483 | 2024-09-23 | Natus Vincere Youth                       | W   | 0.138      | -            | -                | -                | -         |     1.17 | Cham, MaiL09, simpan, Sn0w, Wonder  |
|           12 |     6580 | 2024-09-21 | Partizan Esports                          | L   | 0.126      | -            | -                | -                | -         |    -0.32 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|           11 |     6681 | 2024-09-19 | Lemondogs                                 | L   | 0.113      | -            | -                | -                | -         |    -2.66 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|           10 |     6697 | 2024-09-19 | Leo Team                                  | L   | 0.112      | -            | -                | -                | -         |    -1.01 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            9 |     6750 | 2024-09-18 | BLEKKSPRUTERS                             | W   | 0.106      | -            | -                | -                | -         |     0.60 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            8 |     6815 | 2024-09-17 | Ex-9INE Academy                           | W   | 0.100      | -            | -                | -                | -         |     1.29 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            7 |     6837 | 2024-09-17 | ADEPTS                                    | W   | 0.099      | -            | -                | -                | -         |     1.60 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            6 |     7132 | 2024-09-12 | Lilmix                                    | W   | 0.066      | -            | -                | -                | -         |     0.63 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            5 |     7292 | 2024-09-09 | Showmakerz                                | L   | 0.046      | -            | -                | -                | -         |    -0.86 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            4 |     7470 | 2024-09-07 | TEAM NEXT LEVEL                           | L   | 0.031      | -            | -                | -                | -         |    -0.45 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            3 |     7524 | 2024-09-06 | Viperio                                   | W   | 0.025      | 0.354        | 0.002 (0.000)    | -                | -         |     0.50 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            2 |     7540 | 2024-09-06 | Viperio                                   | L   | 0.024      | -            | -                | -                | -         |    -0.28 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            1 |     7611 | 2024-09-05 | Astralis Talent                           | W   | 0.019      | 0.354        | 0.002 (0.000)    | -                | -         |     0.38 | Cham, Fraaank, MaiL09, Sn0w, Wonder |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($269.17)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-13 |      0.480 | $458.19        | $219.93         |
| 2024-09-27 |      0.166 | $295.92        | $49.24          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
