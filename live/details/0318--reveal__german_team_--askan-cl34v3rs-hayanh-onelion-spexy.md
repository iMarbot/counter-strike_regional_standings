### Roster Details<br />
Team Name: Reveal (German team)<br />
Roster: Askan, Cl34v3rs, hayanh, OneLion, Spexy<br />
Global Rank: [318](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [212]( ../standings_europe.md)<br />
<br />
Final Rank Value:  639.9<br />
<br />
Final Rank Value (639.9) = Starting Rank Value (631.2) + Head To Head Adjustments (8.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.253[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 631.2
- 400 + ( ( 0.116 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 631.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     2325 | 2024-12-02 | Team Genesium       | L   | 0.607      | -            | -                | -                | -         |    -8.52 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           26 |     2480 | 2024-11-30 | 52squad             | W   | 0.594      | -            | -                | -                | 0 (0.000) |     3.71 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           25 |     2622 | 2024-11-28 | Dragon Esports Club | L   | 0.580      | -            | -                | -                | -         |    -8.04 | Askan, Cl34v3rs, OneLion, Spexy, Yoshireax |
|           24 |     3232 | 2024-11-17 | Endpoint            | L   | 0.506      | -            | -                | -                | -         |    -5.26 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           23 |     3588 | 2024-11-11 | Permitta Esports    | W   | 0.467      | 0.143        | 0.013 (0.001)    | 0.494 (0.033)    | 0 (0.000) |    10.22 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           22 |     3654 | 2024-11-10 | ALTERNATE aTTaX Evo | W   | 0.460      | 0.143        | 0.001 (0.000)    | 0.184 (0.012)    | 0 (0.000) |     7.04 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           21 |     3707 | 2024-11-09 | AKA HERO            | W   | 0.453      | 0.143        | 0.000 (0.000)    | 0.062 (0.004)    | 0 (0.000) |     6.18 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           20 |     4037 | 2024-11-03 | Team Fragster       | L   | 0.413      | -            | -                | -                | -         |    -7.24 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           19 |     4464 | 2024-10-27 | Wave Esports        | L   | 0.366      | -            | -                | -                | -         |    -5.97 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           18 |     4520 | 2024-10-26 | MYinsanity          | W   | 0.359      | 0.143        | 0.002 (0.000)    | 0.086 (0.004)    | 0 (0.000) |     5.71 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           17 |     4577 | 2024-10-25 | Regnum4Games        | L   | 0.353      | -            | -                | -                | -         |    -5.91 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           16 |     4589 | 2024-10-25 | Entropy Gaming      | W   | 0.353      | 0.143        | 0.000 (0.000)    | 0.051 (0.003)    | 0 (0.000) |     4.45 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           15 |     4779 | 2024-10-20 | MYinsanity          | L   | 0.319      | -            | -                | -                | -         |    -4.87 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           14 |     4795 | 2024-10-20 | SNOGARD Dragons     | W   | 0.319      | 0.143        | 0.000 (0.000)    | 0.039 (0.002)    | 0 (0.000) |     4.37 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           13 |     4837 | 2024-10-19 | UNEVEN              | W   | 0.313      | -            | -                | -                | 0 (0.000) |     2.63 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           12 |     4992 | 2024-10-16 | ALTERNATE aTTaX Evo | W   | 0.293      | 0.143        | 0.001 (0.000)    | 0.184 (0.008)    | 0 (0.000) |     4.42 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           11 |     5254 | 2024-10-11 | ALTERNATE aTTaX Evo | W   | 0.259      | 0.143        | 0.001 (0.000)    | 0.184 (0.007)    | 0 (0.000) |     3.94 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|           10 |     5409 | 2024-10-08 | Playing Ducks       | W   | 0.240      | -            | -                | -                | -         |     1.60 | Askan, Cl34v3rs, frozeN, hayanh, Spexy     |
|            9 |     5516 | 2024-10-06 | Team NinjaParentz   | W   | 0.226      | 0.143        | -                | 0.036 (0.001)    | -         |     2.92 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|            8 |     5771 | 2024-10-02 | Sissi State Punks   | L   | 0.199      | -            | -                | -                | -         |    -3.40 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|            7 |     6125 | 2024-09-27 | Unorganized Five    | W   | 0.166      | 0.143        | 0.000 (0.000)    | 0.067 (0.002)    | -         |     2.20 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|            6 |     6629 | 2024-09-20 | AKA HERO            | L   | 0.119      | -            | -                | -                | -         |    -2.12 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|            5 |     7082 | 2024-09-13 | RIZON               | W   | 0.073      | -            | -                | -                | -         |     0.49 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|            4 |     7234 | 2024-09-10 | Regnum4Games        | W   | 0.053      | 0.143        | 0.002 (0.000)    | -                | -         |     0.84 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|            3 |     7394 | 2024-09-07 | TOOMUCHVIDEOGAMES   | L   | 0.033      | -            | -                | -                | -         |    -0.74 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|            2 |     7511 | 2024-09-06 | BIG SELECTA         | W   | 0.026      | -            | -                | -                | -         |     0.34 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |
|            1 |     7649 | 2024-09-04 | The Chosen Few      | L   | 0.013      | -            | -                | -                | -         |    -0.29 | Askan, Cl34v3rs, hayanh, OneLion, Spexy    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($370.79)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.460 | $375.29        | $172.63         |
| 2024-10-27 |      0.367 | $539.99        | $198.16         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
