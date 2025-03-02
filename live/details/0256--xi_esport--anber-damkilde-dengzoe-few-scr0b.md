### Roster Details<br />
Team Name: XI Esport<br />
Roster: anber, Damkilde, Dengzoe, Few, Scr0b<br />
Global Rank: [256](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [179]( ../standings_europe.md)<br />
<br />
Final Rank Value:  675.5<br />
<br />
Final Rank Value (675.5) = Starting Rank Value (680.7) + Head To Head Adjustments (-5.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.252[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 680.7
- 400 + ( ( 0.141 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 680.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      340 | 2025-02-16 | Mercenaires                | L   | 1.000      | -            | -                | -                | -         |   -22.53 | anber, Damkilde, Dengzoe, Few, Scr0b |
|           30 |     1510 | 2024-12-20 | Dark Cloud Esports         | L   | 0.726      | -            | -                | -                | -         |    -6.55 | anber, Few, Kragh, Scr0b, smF        |
|           29 |     1542 | 2024-12-19 | ALASKA                     | W   | 0.718      | 0.303        | 0.030 (0.007)    | 0.875 (0.190)    | 0 (0.000) |    17.69 | anber, Few, Kragh, Scr0b, smF        |
|           28 |     1595 | 2024-12-16 | Venom (Swedish team)       | W   | 0.698      | 0.303        | 0.000 (0.000)    | 0.063 (0.013)    | 0 (0.000) |     5.92 | anber, Few, Kragh, Scr0b, smF        |
|           27 |     1716 | 2024-12-14 | PLUSH                      | W   | 0.684      | -            | -                | -                | 0 (0.000) |     3.72 | anber, Few, Kragh, Scr0b, smF        |
|           26 |     1977 | 2024-12-08 | BRUTE                      | L   | 0.647      | -            | -                | -                | -         |    -9.07 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           25 |     2324 | 2024-12-02 | WOPA Esport                | L   | 0.607      | -            | -                | -                | -         |    -5.79 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           24 |     2413 | 2024-12-01 | MASONIC                    | L   | 0.600      | -            | -                | -                | -         |   -10.73 | anber, Damkilde, Dengzoe, Few, Scr0b |
|           23 |     2479 | 2024-11-30 | 777 Esports                | W   | 0.594      | 0.333        | 0.002 (0.000)    | 0.239 (0.047)    | 0 (0.000) |     8.38 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           22 |     2615 | 2024-11-28 | NEVERMORE (Ukrainian team) | W   | 0.580      | 0.333        | 0.010 (0.002)    | 0.911 (0.176)    | 0 (0.000) |    11.11 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           21 |     2712 | 2024-11-26 | Ex-UHKA eSports            | W   | 0.567      | 0.333        | -                | 0.271 (0.051)    | 0 (0.000) |     4.88 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           20 |     3429 | 2024-11-14 | Denial (Danish team)       | L   | 0.487      | -            | -                | -                | -         |    -8.13 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           19 |     3447 | 2024-11-14 | Astralis Talent            | L   | 0.486      | -            | -                | -                | -         |    -5.71 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           18 |     3585 | 2024-11-11 | Copenhagen Wolves Academy  | W   | 0.467      | -            | -                | -                | 0 (0.000) |     2.20 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           17 |     3599 | 2024-11-11 | XI Esport                  | W   | 0.467      | 0.143        | -                | 0.127 (0.008)    | 0 (0.000) |     4.09 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           16 |     3606 | 2024-11-11 | Preasy Esport              | W   | 0.466      | 0.143        | 0.012 (0.001)    | 0.710 (0.047)    | 0 (0.000) |     9.32 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           15 |     3974 | 2024-11-04 | Denial (Danish team)       | L   | 0.421      | -            | -                | -                | -         |    -7.08 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           14 |     3991 | 2024-11-04 | MASONIC                    | W   | 0.420      | 0.143        | 0.001 (0.000)    | 0.166 (0.010)    | 0 (0.000) |     6.17 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           13 |     3997 | 2024-11-04 | Astralis Talent            | L   | 0.420      | -            | -                | -                | -         |    -5.55 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           12 |     4418 | 2024-10-28 | WOPA Esport                | L   | 0.374      | -            | -                | -                | -         |    -3.40 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           11 |     5457 | 2024-10-07 | Astralis Talent            | W   | 0.233      | 0.143        | 0.002 (0.000)    | 0.733 (0.024)    | -         |     4.56 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           10 |     5480 | 2024-10-07 | XI Esport                  | W   | 0.233      | -            | -                | -                | -         |     2.06 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            9 |     5852 | 2024-10-01 | Preasy Esport              | L   | 0.192      | -            | -                | -                | -         |    -1.98 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            8 |     6444 | 2024-09-23 | MASONIC                    | L   | 0.140      | -            | -                | -                | -         |    -2.36 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            7 |     6466 | 2024-09-23 | WOPA Esport                | W   | 0.139      | 0.143        | 0.031 (0.001)    | 0.785 (0.016)    | -         |     3.19 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            6 |     6880 | 2024-09-16 | Denial (Danish team)       | W   | 0.093      | 0.143        | 0.001 (0.000)    | -                | -         |     1.32 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            5 |     6889 | 2024-09-16 | Copenhagen Wolves Academy  | W   | 0.092      | -            | -                | -                | -         |     0.50 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            4 |     7173 | 2024-09-11 | Chroma                     | L   | 0.060      | -            | -                | -                | -         |    -0.93 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            3 |     7275 | 2024-09-09 | Flame Sharks               | L   | 0.047      | -            | -                | -                | -         |    -0.80 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            2 |     7568 | 2024-09-05 | Ex-UHKA eSports            | W   | 0.020      | -            | -                | -                | -         |     0.17 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            1 |     7713 | 2024-09-03 | GOOFYBOYZ                  | W   | 0.007      | 0.333        | 0.003 (0.000)    | -                | -         |     0.13 | anber, Dengzoe, Few, Kragh, Scr0b    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($365.42)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-21 |      0.731 | $500.00        | $365.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
