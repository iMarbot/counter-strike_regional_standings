### Roster Details<br />
Team Name: MYinsanity<br />
Roster: CagXD, DAVEN, m1kketye, reezk, zed<br />
Global Rank: [314](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [207]( ../standings_europe.md)<br />
<br />
Final Rank Value:  642.0<br />
<br />
Final Rank Value (642.0) = Starting Rank Value (655.1) + Head To Head Adjustments (-13.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 655.1
- 400 + ( ( 0.128 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 655.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     4319 | 2024-10-30 | BIG                     | L   | 0.378      | -            | -                | -                | -         |    -0.10 | CagXD, DAVEN, m1kketye, reezk, zed |
|           19 |     4532 | 2024-10-26 | Reveal (German team)    | L   | 0.351      | -            | -                | -                | -         |    -5.58 | CagXD, DAVEN, m1kketye, reezk, zed |
|           18 |     4605 | 2024-10-25 | Wave Esports            | L   | 0.344      | -            | -                | -                | -         |    -5.71 | CagXD, DAVEN, m1kketye, reezk, zed |
|           17 |     4670 | 2024-10-23 | Permitta Esports        | L   | 0.332      | -            | -                | -                | -         |    -3.40 | CagXD, DAVEN, m1kketye, reezk, zed |
|           16 |     4745 | 2024-10-21 | Regnum4Games            | L   | 0.318      | -            | -                | -                | -         |    -5.53 | CagXD, DAVEN, m1kketye, reezk, zed |
|           15 |     4791 | 2024-10-20 | Reveal (German team)    | W   | 0.311      | 0.143        | 0.001 (0.000)    | 0.187 (0.008)    | 0 (0.000) |     4.75 | CagXD, DAVEN, m1kketye, reezk, zed |
|           14 |     4996 | 2024-10-16 | ESports Cologne         | W   | 0.285      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     2.33 | CagXD, DAVEN, m1kketye, reezk, zed |
|           13 |     5174 | 2024-10-12 | Los kogutos             | L   | 0.262      | -            | -                | -                | -         |    -1.18 | CagXD, DAVEN, m1kketye, reezk, zed |
|           12 |     5204 | 2024-10-12 | Team Solid (Swiss team) | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.012 (0.000)    | 1 (0.258) |     1.71 | CagXD, DAVEN, m1kketye, reezk, zed |
|           11 |     5227 | 2024-10-12 | Addicted Esports        | W   | 0.257      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.257) |     1.57 | CagXD, DAVEN, m1kketye, reezk, zed |
|           10 |     5351 | 2024-10-09 | ALTERNATE aTTaX Evo     | W   | 0.238      | 0.143        | 0.001 (0.000)    | 0.178 (0.006)    | 0 (0.000) |     3.47 | CagXD, DAVEN, m1kketye, reezk, zed |
|            9 |     5491 | 2024-10-07 | SNOGARD Dragons         | L   | 0.224      | -            | -                | -                | -         |    -4.13 | CagXD, DAVEN, m1kketye, reezk, zed |
|            8 |     5851 | 2024-10-01 | Regnum4Games            | W   | 0.185      | 0.143        | 0.002 (0.000)    | 0.112 (0.003)    | 0 (0.000) |     2.72 | CagXD, DAVEN, m1kketye, reezk, zed |
|            7 |     5918 | 2024-09-30 | Wave Esports            | W   | 0.178      | 0.143        | 0.002 (0.000)    | 0.110 (0.003)    | 0 (0.000) |     2.64 | CagXD, DAVEN, m1kketye, reezk, zed |
|            6 |     6296 | 2024-09-25 | Sissi State Punks       | L   | 0.145      | -            | -                | -                | -         |    -2.61 | CagXD, DAVEN, m1kketye, reezk, zed |
|            5 |     6386 | 2024-09-24 | Sissi State Punks       | L   | 0.138      | -            | -                | -                | -         |    -2.52 | CagXD, DAVEN, m1kketye, reezk, zed |
|            4 |     6824 | 2024-09-17 | Wave Esports            | L   | 0.092      | -            | -                | -                | -         |    -1.55 | CagXD, DAVEN, m1kketye, reezk, zed |
|            3 |     7195 | 2024-09-11 | Playing Ducks           | W   | 0.051      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.31 | CagXD, DAVEN, m1kketye, reezk, zed |
|            2 |     7310 | 2024-09-09 | ALTERNATE aTTaX         | L   | 0.038      | -            | -                | -                | -         |    -0.21 | CagXD, DAVEN, m1kketye, reezk, zed |
|            1 |     7656 | 2024-09-04 | XPERION NXT             | L   | 0.005      | -            | -                | -                | -         |    -0.08 | CagXD, DAVEN, m1kketye, reezk, zed |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($723.10)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.678 | $105.05        | $71.25          |
| 2024-10-27 |      0.359 | $539.99        | $193.73         |
| 2024-10-12 |      0.262 | $1,749.84      | $458.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
