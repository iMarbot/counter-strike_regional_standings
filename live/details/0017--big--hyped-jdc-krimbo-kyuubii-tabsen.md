### Roster Details<br />
Team Name: BIG<br />
Roster: hyped, JDC, Krimbo, kyuubii, tabseN<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1367.9<br />
<br />
Final Rank Value (1367.9) = Starting Rank Value (1510.7) + Head To Head Adjustments (-142.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.621[<sup>1</sup>](#table2)
- Bounty Collected: 0.497[<sup>2</sup>](#table1)
- Opponent Network: 0.243[<sup>2</sup>](#table1)
- LAN Wins: 0.863[<sup>2</sup>](#table1)

The average of these factors is 0.556<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1510.7
- 400 + ( ( 0.556 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1510.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           52 |      270 | 2025-02-18 | Astralis          | L   | 1.000      | -            | -                | -                | -         |    -4.38 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           51 |      305 | 2025-02-17 | Wildcard          | W   | 1.000      | 1.000        | 0.176 (0.176)    | 0.428 (0.428)    | 1 (1.000) |    14.77 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           50 |      378 | 2025-02-16 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -1.94 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           49 |      430 | 2025-02-15 | FlyQuest          | W   | 1.000      | 1.000        | 0.105 (0.105)    | 0.239 (0.239)    | 1 (1.000) |     7.27 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           48 |      499 | 2025-02-14 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -1.59 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           47 |      562 | 2025-02-11 | HEROIC            | L   | 1.000      | -            | -                | -                | -         |   -24.25 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           46 |      586 | 2025-02-10 | OG                | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | -         |     2.47 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           45 |      597 | 2025-02-10 | BC.Game Esports   | L   | 1.000      | -            | -                | -                | -         |   -26.20 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           44 |      711 | 2025-02-08 | 500               | L   | 1.000      | -            | -                | -                | -         |   -27.49 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           43 |     1029 | 2025-02-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -10.14 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           42 |     1060 | 2025-02-01 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -         |    -2.55 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           41 |     1092 | 2025-01-31 | HEROIC            | W   | 1.000      | 1.000        | 0.131 (0.131)    | 0.404 (0.404)    | 1 (1.000) |     5.29 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           40 |     1097 | 2025-01-30 | Imperial Female   | W   | 1.000      | 1.000        | 0.134 (0.134)    | 0.165 (0.165)    | 1 (1.000) |     3.01 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           39 |     1108 | 2025-01-29 | Wildcard          | L   | 0.992      | -            | -                | -                | -         |   -19.60 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           38 |     1147 | 2025-01-19 | G2 Esports        | L   | 0.927      | -            | -                | -                | -         |    -3.02 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           37 |     1183 | 2025-01-15 | SAW               | W   | 0.899      | 0.363        | 0.262 (0.086)    | -                | -         |     8.56 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           36 |     1691 | 2024-12-14 | Permitta Esports  | L   | 0.686      | -            | -                | -                | -         |   -20.99 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           35 |     2143 | 2024-12-06 | PaiN Gaming       | L   | 0.631      | -            | -                | -                | -         |    -7.26 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           34 |     2169 | 2024-12-05 | G2 Esports        | L   | 0.625      | -            | -                | -                | -         |    -2.54 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |     2184 | 2024-12-04 | Team Falcons      | L   | 0.623      | -            | -                | -                | -         |    -1.85 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |     2307 | 2024-12-02 | Complexity        | W   | 0.609      | 1.000        | 0.097 (0.059)    | 0.229 (0.139)    | 1 (0.609) |     2.67 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     2377 | 2024-12-01 | FURIA             | L   | 0.603      | -            | -                | -                | -         |   -10.55 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           30 |     2455 | 2024-11-30 | Virtus.pro        | W   | 0.596      | 1.000        | 0.268 (0.160)    | 0.439 (0.261)    | 1 (0.596) |    12.67 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           29 |     2549 | 2024-11-30 | FlyQuest          | L   | 0.591      | -            | -                | -                | -         |   -16.48 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           28 |     2558 | 2024-11-29 | Passion UA        | W   | 0.590      | 1.000        | 0.044 (0.026)    | 0.557 (0.329)    | 1 (0.590) |     1.23 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           27 |     2999 | 2024-11-21 | Passion UA        | W   | 0.537      | -            | -                | -                | 1 (0.537) |     1.04 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           26 |     3041 | 2024-11-21 | Team Falcons      | W   | 0.532      | 0.143        | 0.927 (0.070)    | -                | 1 (0.532) |    15.28 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           25 |     3062 | 2024-11-20 | Sashi Esport      | W   | 0.530      | -            | -                | -                | 1 (0.530) |     0.77 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           24 |     3632 | 2024-11-11 | GUN5 Esports      | L   | 0.464      | -            | -                | -                | -         |   -13.92 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           23 |     4125 | 2024-11-02 | ALTERNATE aTTaX   | W   | 0.406      | -            | -                | -                | -         |     0.50 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           22 |     4191 | 2024-11-01 | XPERION NXT       | W   | 0.400      | -            | -                | -                | -         |     0.11 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           21 |     4307 | 2024-10-30 | MYinsanity        | W   | 0.386      | -            | -                | -                | -         |     0.11 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           20 |     4368 | 2024-10-29 | SNOGARD Dragons   | W   | 0.380      | -            | -                | -                | -         |     0.08 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           19 |     4430 | 2024-10-28 | XPERION NXT       | W   | 0.373      | -            | -                | -                | -         |     0.10 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           18 |     4440 | 2024-10-28 | ALTERNATE aTTaX   | W   | 0.372      | -            | -                | -                | -         |     0.45 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           17 |     4555 | 2024-10-26 | OG                | L   | 0.357      | -            | -                | -                | -         |   -10.82 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           16 |     4616 | 2024-10-24 | BESTIA            | W   | 0.347      | 0.934        | -                | 0.478 (0.155)    | -         |     0.48 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           15 |     4632 | 2024-10-24 | Aurora Gaming     | W   | 0.344      | 0.934        | -                | 0.516 (0.166)    | -         |     0.23 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           14 |     4740 | 2024-10-21 | ESports Cologne   | W   | 0.326      | -            | -                | -                | -         |     0.03 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           13 |     5002 | 2024-10-16 | Wave Esports      | W   | 0.292      | -            | -                | -                | -         |     0.07 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           12 |     5504 | 2024-10-06 | FlyQuest          | L   | 0.227      | -            | -                | -                | -         |    -6.41 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           11 |     5512 | 2024-10-06 | SAW               | W   | 0.226      | 0.500        | 0.262 (0.030)    | -                | -         |     2.03 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           10 |     5649 | 2024-10-04 | M80               | W   | 0.214      | -            | -                | -                | -         |     0.26 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            9 |     5658 | 2024-10-04 | ODDIK             | W   | 0.213      | -            | -                | -                | -         |     0.14 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            8 |     5915 | 2024-09-30 | Sissi State Punks | W   | 0.186      | -            | -                | -                | -         |     0.04 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            7 |     6297 | 2024-09-25 | ECSTATIC          | L   | 0.152      | -            | -                | -                | -         |    -4.64 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            6 |     6409 | 2024-09-24 | Monte             | L   | 0.145      | -            | -                | -                | -         |    -4.45 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            5 |     6849 | 2024-09-17 | The MongolZ       | L   | 0.098      | -            | -                | -                | -         |    -0.25 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            4 |     7086 | 2024-09-13 | Complexity        | W   | 0.072      | -            | -                | -                | -         |     0.27 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            3 |     7130 | 2024-09-12 | Fnatic            | W   | 0.066      | -            | -                | -                | -         |     0.16 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            2 |     7190 | 2024-09-11 | Rooster           | W   | 0.059      | -            | -                | -                | -         |     0.02 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            1 |     7248 | 2024-09-10 | Imperial Esports  | L   | 0.052      | -            | -                | -                | -         |    -1.56 | JDC, Krimbo, rigoN, syrsoN, tabseN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($82,613.58)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $31,250.00     | $31,250.00      |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2025-01-19 |      0.927 | $10,000.00     | $9,271.06       |
| 2024-12-15 |      0.691 | $20,000.00     | $13,818.98      |
| 2024-12-14 |      0.686 | $3,676.66      | $2,523.88       |
| 2024-11-12 |      0.473 | $1,000.00      | $472.62         |
| 2024-11-03 |      0.413 | $20,000.00     | $8,258.33       |
| 2024-10-06 |      0.227 | $20,000.00     | $4,545.83       |
| 2024-09-26 |      0.159 | $1,000.00      | $158.98         |
| 2024-09-22 |      0.132 | $17,500.00     | $2,313.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
