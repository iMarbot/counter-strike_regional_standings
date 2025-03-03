### Roster Details<br />
Team Name: GODSENT<br />
Roster: Cham, MaiL09, mogv, Sn0w, viz<br />
Global Rank: [265](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [182]( ../standings_europe.md)<br />
<br />
Final Rank Value:  672.1<br />
<br />
Final Rank Value (672.1) = Starting Rank Value (666.8) + Head To Head Adjustments (5.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.244[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.044[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.8
- 400 + ( ( 0.133 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 666.8


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
|           45 |     1598 | 2024-12-16 | Astralis Talent                           | L   | 0.691      | -            | -                | -                | -         |    -7.82 | Cham, MaiL09, mogv, Sn0w, viz       |
|           44 |     1851 | 2024-12-12 | ADEPTS                                    | W   | 0.664      | 0.333        | -                | 0.287 (0.064)    | 0 (0.000) |     8.94 | Cham, MaiL09, mogv, Sn0w, viz       |
|           43 |     2016 | 2024-12-08 | KONO.ECF                                  | L   | 0.638      | -            | -                | -                | -         |    -6.02 | Cham, MaiL09, mogv, Sn0w, viz       |
|           42 |     2636 | 2024-11-28 | FLuffy Gangsters                          | L   | 0.572      | -            | -                | -                | -         |    -4.93 | Cham, MaiL09, mogv, Sn0w, viz       |
|           41 |     2738 | 2024-11-26 | Preasy Esport                             | L   | 0.558      | -            | -                | -                | -         |    -7.04 | Cham, MaiL09, mogv, Sn0w, viz       |
|           40 |     2796 | 2024-11-24 | Lausanne-Sport Esports                    | W   | 0.545      | 0.372        | -                | 0.124 (0.025)    | 0 (0.000) |     6.09 | MaiL09, mogv, Sn0w, viz, Zyppe      |
|           39 |     2818 | 2024-11-24 | Lilmix                                    | W   | 0.543      | 0.333        | 0.001 (0.000)    | 0.127 (0.023)    | 0 (0.000) |     6.27 | MaiL09, mogv, Sn0w, Svedjehed, viz  |
|           38 |     2973 | 2024-11-22 | Betera Esports                            | L   | 0.531      | -            | -                | -                | -         |    -6.85 | Cham, MaiL09, mogv, Sn0w, viz       |
|           37 |     3034 | 2024-11-21 | PCIFIC Espor                              | L   | 0.525      | -            | -                | -                | -         |    -6.62 | Cham, MaiL09, mogv, Sn0w, viz       |
|           36 |     3100 | 2024-11-20 | MOUZ NXT                                  | L   | 0.519      | -            | -                | -                | -         |   -10.18 | Cham, MaiL09, mogv, Sn0w, viz       |
|           35 |     3121 | 2024-11-20 | RUSTEC                                    | W   | 0.518      | 0.372        | 0.002 (0.000)    | 0.099 (0.019)    | 0 (0.000) |     7.19 | Cham, MaiL09, mogv, Sn0w, viz       |
|           34 |     3381 | 2024-11-15 | Poslednii3ae3d                            | W   | 0.485      | 0.372        | 0.001 (0.000)    | 0.101 (0.018)    | 0 (0.000) |     6.27 | Cham, MaiL09, mogv, Sn0w, viz       |
|           33 |     3452 | 2024-11-14 | Kay Team                                  | W   | 0.478      | -            | -                | -                | 0 (0.000) |     4.05 | Cham, MaiL09, mogv, Sn0w, viz       |
|           32 |     3495 | 2024-11-13 | ADEPTS                                    | W   | 0.472      | 0.372        | -                | 0.287 (0.050)    | 0 (0.000) |     6.25 | Cham, MaiL09, mogv, Sn0w, viz       |
|           31 |     3885 | 2024-11-06 | Soul's Heart Esport                       | W   | 0.425      | -            | -                | -                | 0 (0.000) |     4.51 | Cham, MaiL09, mogv, Sn0w, viz       |
|           30 |     3946 | 2024-11-05 | Kario Mart                                | L   | 0.418      | -            | -                | -                | -         |    -7.47 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           29 |     4065 | 2024-11-03 | Adventurers                               | L   | 0.405      | -            | -                | -                | -         |    -4.11 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           28 |     4259 | 2024-10-31 | Preasy Esport                             | W   | 0.385      | 0.333        | 0.012 (0.002)    | 0.701 (0.090)    | 0 (0.000) |     7.90 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           27 |     4302 | 2024-10-30 | Ex-Soul's Heart Esport                    | W   | 0.379      | 0.372        | 0.000 (0.000)    | -                | 0 (0.000) |     5.25 | Cham, MaiL09, mogv, Sn0w, viz       |
|           26 |     4384 | 2024-10-29 | Natus Vincere Youth                       | W   | 0.371      | -            | -                | -                | -         |     3.11 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           25 |     4440 | 2024-10-28 | GTZ.ESPORTS                               | L   | 0.365      | -            | -                | -                | -         |    -0.58 | Cham, MaiL09, mogv, Sn0w, viz       |
|           24 |     4676 | 2024-10-23 | Los kogutos                               | W   | 0.331      | 0.372        | 0.032 (0.004)    | 0.515 (0.063)    | -         |     8.76 | Cham, MaiL09, mogv, Sn0w, viz       |
|           23 |     4736 | 2024-10-21 | Nuclear TigeRES                           | L   | 0.318      | -            | -                | -                | -         |    -2.84 | Cham, MaiL09, mogv, Sn0w, viz       |
|           22 |     4995 | 2024-10-16 | Copenhagen Wolves (American organization) | L   | 0.285      | -            | -                | -                | -         |    -2.26 | Cham, MaiL09, mogv, Sn0w, viz       |
|           21 |     5076 | 2024-10-15 | Heimo Esports                             | L   | 0.278      | -            | -                | -                | -         |    -3.38 | Cham, MaiL09, mogv, Sn0w, viz       |
|           20 |     5533 | 2024-10-06 | Adventurers                               | L   | 0.217      | -            | -                | -                | -         |    -2.40 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           19 |     5612 | 2024-10-05 | Alliance                                  | L   | 0.210      | -            | -                | -                | -         |    -1.51 | Cham, Sn0w, TiiREX, viz, Wonder     |
|           18 |     5961 | 2024-09-29 | Leo Team                                  | W   | 0.172      | 0.354        | 0.026 (0.002)    | 0.748 (0.045)    | -         |     3.90 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           17 |     6056 | 2024-09-28 | Preasy Esport                             | W   | 0.164      | 0.354        | 0.012 (0.001)    | 0.701 (0.041)    | -         |     3.56 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           16 |     6128 | 2024-09-27 | Lilmix                                    | L   | 0.158      | -            | -                | -                | -         |    -2.56 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           15 |     6139 | 2024-09-27 | Carte Blanche                             | W   | 0.158      | -            | -                | -                | -         |     0.91 | Cham, MaiL09, Sn0w, viz, Wonder     |
|           14 |     6422 | 2024-09-24 | Leo Team                                  | L   | 0.136      | -            | -                | -                | -         |    -1.22 | Cham, Fraaank, MaiL09, simpan, Sn0w |
|           13 |     6495 | 2024-09-23 | Natus Vincere Youth                       | W   | 0.130      | -            | -                | -                | -         |     1.10 | Cham, MaiL09, simpan, Sn0w, Wonder  |
|           12 |     6592 | 2024-09-21 | Partizan Esports                          | L   | 0.117      | -            | -                | -                | -         |    -0.30 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|           11 |     6693 | 2024-09-19 | Lemondogs                                 | L   | 0.105      | -            | -                | -                | -         |    -2.47 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|           10 |     6709 | 2024-09-19 | Leo Team                                  | L   | 0.104      | -            | -                | -                | -         |    -0.94 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            9 |     6762 | 2024-09-18 | BLEKKSPRUTERS                             | W   | 0.098      | -            | -                | -                | -         |     0.56 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            8 |     6827 | 2024-09-17 | Ex-9INE Academy                           | W   | 0.092      | -            | -                | -                | -         |     1.18 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            7 |     6849 | 2024-09-17 | ADEPTS                                    | W   | 0.091      | -            | -                | -                | -         |     1.13 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            6 |     7144 | 2024-09-12 | Lilmix                                    | W   | 0.058      | -            | -                | -                | -         |     0.56 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            5 |     7304 | 2024-09-09 | Showmakerz                                | L   | 0.038      | -            | -                | -                | -         |    -0.70 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            4 |     7482 | 2024-09-07 | TEAM NEXT LEVEL                           | L   | 0.023      | -            | -                | -                | -         |    -0.33 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            3 |     7536 | 2024-09-06 | Viperio                                   | W   | 0.017      | 0.354        | 0.002 (0.000)    | -                | -         |     0.34 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            2 |     7552 | 2024-09-06 | Viperio                                   | L   | 0.015      | -            | -                | -                | -         |    -0.18 | Cham, Fraaank, MaiL09, Sn0w, Wonder |
|            1 |     7623 | 2024-09-05 | Astralis Talent                           | W   | 0.010      | 0.354        | 0.002 (0.000)    | -                | -         |     0.21 | Cham, Fraaank, MaiL09, Sn0w, Wonder |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($263.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-13 |      0.472 | $458.19        | $216.18         |
| 2024-09-27 |      0.158 | $295.92        | $46.82          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
