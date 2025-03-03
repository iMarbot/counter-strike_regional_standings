### Roster Details<br />
Team Name: PCIFIC Espor<br />
Roster: EMSTAR, eNs, jresy, lugseN, scolleN<br />
Global Rank: [179](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [129]( ../standings_europe.md)<br />
<br />
Final Rank Value:  726.2<br />
<br />
Final Rank Value (726.2) = Starting Rank Value (773.0) + Head To Head Adjustments (-46.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.298[<sup>1</sup>](#table2)
- Bounty Collected: 0.288[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.186<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 773.0
- 400 + ( ( 0.186 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 773.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      350 | 2025-02-16 | Hesta                       | L   | 1.000      | -            | -                | -                | -         |   -12.74 | EMSTAR, eNs, jresy, lugseN, scolleN  |
|           28 |     1371 | 2024-12-24 | Des1ngnadted                | W   | 0.745      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.49 | EMSTAR, eNs, jresy, lugseN, scolleN  |
|           27 |     1991 | 2024-12-08 | VOLT (European team)        | L   | 0.639      | -            | -                | -                | -         |   -11.11 | EMSTAR, eNs, jresy, lugseN, scolleN  |
|           26 |     1995 | 2024-12-08 | LEON Esports                | W   | 0.639      | 0.143        | 0.010 (0.001)    | 0.271 (0.025)    | 0 (0.000) |    11.17 | EMSTAR, eNs, jresy, lugseN, scolleN  |
|           25 |     2881 | 2024-11-23 | DUSTY                       | L   | 0.538      | -            | -                | -                | -         |   -10.19 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           24 |     2890 | 2024-11-23 | Endpoint                    | L   | 0.538      | -            | -                | -                | -         |    -8.84 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           23 |     2905 | 2024-11-23 | Kubix Esports               | W   | 0.537      | 0.372        | 0.045 (0.009)    | 0.487 (0.097)    | 0 (0.000) |    12.75 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           22 |     2965 | 2024-11-22 | Impulse GW                  | L   | 0.532      | -            | -                | -                | -         |    -8.85 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           21 |     2987 | 2024-11-22 | ALTERNATE aTTaX             | L   | 0.531      | -            | -                | -                | -         |    -4.63 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           20 |     3020 | 2024-11-21 | Soul's Heart Esport         | L   | 0.525      | -            | -                | -                | -         |   -12.38 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           19 |     3034 | 2024-11-21 | GODSENT                     | W   | 0.525      | 0.372        | 0.001 (0.000)    | 0.269 (0.052)    | 0 (0.000) |     6.62 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           18 |     3409 | 2024-11-15 | Team Norway                 | L   | 0.484      | -            | -                | -                | -         |   -10.51 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           17 |     3422 | 2024-11-15 | Los kogutos                 | L   | 0.483      | -            | -                | -                | -         |    -5.13 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           16 |     3432 | 2024-11-14 | Mindfreak (Australian team) | W   | 0.479      | 0.617        | 0.002 (0.001)    | 0.091 (0.027)    | 1 (0.479) |     6.29 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           15 |     3516 | 2024-11-13 | Metizport                   | W   | 0.471      | 0.617        | 0.074 (0.022)    | 0.507 (0.147)    | 1 (0.471) |    12.78 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           14 |     3521 | 2024-11-13 | Homyno                      | L   | 0.470      | -            | -                | -                | -         |    -8.54 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           13 |     3805 | 2024-11-08 | Betera Esports              | L   | 0.438      | -            | -                | -                | -         |    -7.59 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           12 |     3883 | 2024-11-06 | Los kogutos                 | L   | 0.425      | -            | -                | -                | -         |    -4.50 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           11 |     3994 | 2024-11-04 | Lazer Cats                  | W   | 0.412      | 0.372        | 0.005 (0.001)    | 0.378 (0.058)    | 0 (0.000) |     5.80 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           10 |     4303 | 2024-10-30 | The Suspect                 | W   | 0.379      | 0.372        | 0.003 (0.000)    | 0.216 (0.030)    | 0 (0.000) |     5.16 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            9 |     4446 | 2024-10-28 | Permitta Esports            | L   | 0.365      | -            | -                | -                | -         |    -5.41 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            8 |     4674 | 2024-10-23 | THE SPELLS                  | W   | 0.331      | 0.372        | 0.000 (0.000)    | 0.144 (0.018)    | 0 (0.000) |     2.41 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            7 |     4738 | 2024-10-21 | ROUNDS                      | W   | 0.318      | -            | -                | -                | 0 (0.000) |     2.09 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            6 |     4993 | 2024-10-16 | GenOne                      | L   | 0.285      | -            | -                | -                | -         |    -3.74 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            5 |     5108 | 2024-10-14 | XP Academy                  | W   | 0.272      | 0.372        | -                | 0.200 (0.020)    | -         |     2.03 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            4 |     5345 | 2024-10-09 | Lilmix                      | W   | 0.238      | 0.372        | 0.001 (0.000)    | 0.127 (0.011)    | -         |     2.56 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            3 |     5476 | 2024-10-07 | Illuminar Gaming            | L   | 0.225      | -            | -                | -                | -         |    -2.59 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            2 |     6322 | 2024-09-25 | ROYALS                      | L   | 0.143      | -            | -                | -                | -         |    -2.79 | Cizzx, Ckanic, eNs, jresy, lugseN    |
|            1 |     6486 | 2024-09-23 | Lazer Cats                  | L   | 0.131      | -            | -                | -                | -         |    -2.36 | Cizzx, Ckanic, eNs, jresy, lugseN    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,448.38)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-27 |      0.764 | $709.45        | $542.23         |
| 2024-11-24 |      0.544 | $1,250.00      | $680.38         |
| 2024-11-10 |      0.452 | $500.00        | $225.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
