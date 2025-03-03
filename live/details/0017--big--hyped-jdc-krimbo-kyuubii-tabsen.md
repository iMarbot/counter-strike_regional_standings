### Roster Details<br />
Team Name: BIG<br />
Roster: hyped, JDC, Krimbo, kyuubii, tabseN<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1367.7<br />
<br />
Final Rank Value (1367.7) = Starting Rank Value (1509.1) + Head To Head Adjustments (-141.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.623[<sup>1</sup>](#table2)
- Bounty Collected: 0.498[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.859[<sup>2</sup>](#table1)

The average of these factors is 0.554<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1509.1
- 400 + ( ( 0.554 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1509.1


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
|           52 |      282 | 2025-02-18 | Astralis          | L   | 1.000      | -            | -                | -                | -         |    -4.32 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           51 |      317 | 2025-02-17 | Wildcard          | W   | 1.000      | 1.000        | 0.178 (0.178)    | 0.422 (0.422)    | 1 (1.000) |    14.86 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           50 |      390 | 2025-02-16 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -1.92 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           49 |      442 | 2025-02-15 | FlyQuest          | W   | 1.000      | 1.000        | 0.105 (0.105)    | 0.235 (0.235)    | 1 (1.000) |     7.15 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           48 |      511 | 2025-02-14 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -1.58 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           47 |      574 | 2025-02-11 | HEROIC            | L   | 1.000      | -            | -                | -                | -         |   -24.36 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           46 |      598 | 2025-02-10 | OG                | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | -         |     2.46 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           45 |      609 | 2025-02-10 | BC.Game Esports   | L   | 1.000      | -            | -                | -                | -         |   -26.21 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           44 |      723 | 2025-02-08 | 500               | L   | 1.000      | -            | -                | -                | -         |   -27.50 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           43 |     1041 | 2025-02-02 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -10.16 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           42 |     1072 | 2025-02-01 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -         |    -2.52 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           41 |     1104 | 2025-01-31 | HEROIC            | W   | 0.998      | 1.000        | 0.131 (0.131)    | 0.401 (0.400)    | 1 (0.998) |     5.18 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           40 |     1109 | 2025-01-30 | Imperial Female   | W   | 0.992      | 1.000        | 0.136 (0.135)    | 0.162 (0.161)    | 1 (0.992) |     2.96 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           39 |     1120 | 2025-01-29 | Wildcard          | L   | 0.984      | -            | -                | -                | -         |   -19.34 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           38 |     1159 | 2025-01-19 | G2 Esports        | L   | 0.919      | -            | -                | -                | -         |    -3.05 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           37 |     1195 | 2025-01-15 | SAW               | W   | 0.891      | 0.363        | 0.266 (0.086)    | -                | -         |     8.49 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           36 |     1703 | 2024-12-14 | Permitta Esports  | L   | 0.678      | -            | -                | -                | -         |   -20.74 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           35 |     2155 | 2024-12-06 | PaiN Gaming       | L   | 0.622      | -            | -                | -                | -         |    -7.09 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           34 |     2181 | 2024-12-05 | G2 Esports        | L   | 0.616      | -            | -                | -                | -         |    -2.56 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |     2196 | 2024-12-04 | Team Falcons      | L   | 0.615      | -            | -                | -                | -         |    -1.79 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |     2319 | 2024-12-02 | Complexity        | W   | 0.601      | 1.000        | 0.098 (0.059)    | 0.226 (0.136)    | 1 (0.601) |     2.62 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     2389 | 2024-12-01 | FURIA             | L   | 0.594      | -            | -                | -                | -         |   -10.48 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           30 |     2467 | 2024-11-30 | Virtus.pro        | W   | 0.588      | 1.000        | 0.272 (0.160)    | 0.436 (0.256)    | 1 (0.588) |    12.54 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           29 |     2561 | 2024-11-30 | FlyQuest          | L   | 0.583      | -            | -                | -                | -         |   -16.30 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           28 |     2570 | 2024-11-29 | Passion UA        | W   | 0.582      | 1.000        | 0.044 (0.026)    | 0.545 (0.317)    | 1 (0.582) |     1.21 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           27 |     3011 | 2024-11-21 | Passion UA        | W   | 0.528      | -            | -                | -                | 1 (0.528) |     1.02 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           26 |     3053 | 2024-11-21 | Team Falcons      | W   | 0.524      | 0.143        | 0.939 (0.070)    | -                | 1 (0.524) |    15.07 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           25 |     3074 | 2024-11-20 | Sashi Esport      | W   | 0.522      | -            | -                | -                | 1 (0.522) |     0.75 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           24 |     3644 | 2024-11-11 | GUN5 Esports      | L   | 0.456      | -            | -                | -                | -         |   -13.68 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           23 |     4137 | 2024-11-02 | ALTERNATE aTTaX   | W   | 0.398      | -            | -                | -                | -         |     0.48 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           22 |     4203 | 2024-11-01 | XPERION NXT       | W   | 0.392      | -            | -                | -                | -         |     0.11 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           21 |     4319 | 2024-10-30 | MYinsanity        | W   | 0.378      | -            | -                | -                | -         |     0.10 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           20 |     4380 | 2024-10-29 | SNOGARD Dragons   | W   | 0.372      | -            | -                | -                | -         |     0.08 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           19 |     4442 | 2024-10-28 | XPERION NXT       | W   | 0.365      | -            | -                | -                | -         |     0.10 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           18 |     4452 | 2024-10-28 | ALTERNATE aTTaX   | W   | 0.364      | -            | -                | -                | -         |     0.44 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           17 |     4567 | 2024-10-26 | OG                | L   | 0.349      | -            | -                | -                | -         |   -10.57 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           16 |     4628 | 2024-10-24 | BESTIA            | W   | 0.338      | 0.934        | -                | 0.472 (0.149)    | -         |     0.46 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           15 |     4644 | 2024-10-24 | Aurora Gaming     | W   | 0.336      | 0.934        | -                | 0.514 (0.161)    | -         |     0.22 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           14 |     4752 | 2024-10-21 | ESports Cologne   | W   | 0.318      | -            | -                | -                | -         |     0.03 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           13 |     5014 | 2024-10-16 | Wave Esports      | W   | 0.284      | -            | -                | -                | -         |     0.07 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           12 |     5516 | 2024-10-06 | FlyQuest          | L   | 0.219      | -            | -                | -                | -         |    -6.19 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           11 |     5524 | 2024-10-06 | SAW               | W   | 0.218      | 0.500        | 0.266 (0.029)    | -                | -         |     1.96 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           10 |     5661 | 2024-10-04 | M80               | W   | 0.206      | -            | -                | -                | -         |     0.25 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            9 |     5670 | 2024-10-04 | ODDIK             | W   | 0.205      | -            | -                | -                | -         |     0.14 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            8 |     5927 | 2024-09-30 | Sissi State Punks | W   | 0.178      | -            | -                | -                | -         |     0.04 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            7 |     6309 | 2024-09-25 | ECSTATIC          | L   | 0.144      | -            | -                | -                | -         |    -4.40 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            6 |     6421 | 2024-09-24 | Monte             | L   | 0.136      | -            | -                | -                | -         |    -4.19 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            5 |     6861 | 2024-09-17 | The MongolZ       | L   | 0.090      | -            | -                | -                | -         |    -0.23 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            4 |     7098 | 2024-09-13 | Complexity        | W   | 0.064      | -            | -                | -                | -         |     0.23 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            3 |     7142 | 2024-09-12 | Fnatic            | W   | 0.058      | -            | -                | -                | -         |     0.14 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            2 |     7202 | 2024-09-11 | Rooster           | W   | 0.051      | -            | -                | -                | -         |     0.01 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            1 |     7260 | 2024-09-10 | Imperial Esports  | L   | 0.044      | -            | -                | -                | -         |    -1.32 | JDC, Krimbo, rigoN, syrsoN, tabseN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,850.04)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $31,250.00     | $31,250.00      |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2025-01-19 |      0.919 | $10,000.00     | $9,189.12       |
| 2024-12-15 |      0.683 | $20,000.00     | $13,655.09      |
| 2024-12-14 |      0.678 | $3,676.66      | $2,493.75       |
| 2024-11-12 |      0.464 | $1,000.00      | $464.42         |
| 2024-11-03 |      0.405 | $20,000.00     | $8,094.44       |
| 2024-10-06 |      0.219 | $20,000.00     | $4,381.94       |
| 2024-09-26 |      0.151 | $1,000.00      | $150.79         |
| 2024-09-22 |      0.124 | $17,500.00     | $2,170.49       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
