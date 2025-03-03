### Roster Details<br />
Team Name: XI Esport<br />
Roster: anber, Damkilde, Dengzoe, Few, Scr0b<br />
Global Rank: [259](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [179]( ../standings_europe.md)<br />
<br />
Final Rank Value:  674.9<br />
<br />
Final Rank Value (674.9) = Starting Rank Value (680.4) + Head To Head Adjustments (-5.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.253[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.057[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 680.4
- 400 + ( ( 0.140 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 680.4


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
|           30 |      352 | 2025-02-16 | Mercenaires                | L   | 1.000      | -            | -                | -                | -         |   -22.50 | anber, Damkilde, Dengzoe, Few, Scr0b |
|           29 |     1522 | 2024-12-20 | Dark Cloud Esports         | L   | 0.717      | -            | -                | -                | -         |    -6.51 | anber, Few, Kragh, Scr0b, smF        |
|           28 |     1554 | 2024-12-19 | ALASKA                     | W   | 0.710      | 0.303        | 0.031 (0.007)    | 0.867 (0.186)    | 0 (0.000) |    17.56 | anber, Few, Kragh, Scr0b, smF        |
|           27 |     1607 | 2024-12-16 | Venom (Swedish team)       | W   | 0.690      | 0.303        | 0.000 (0.000)    | 0.062 (0.013)    | 0 (0.000) |     5.87 | anber, Few, Kragh, Scr0b, smF        |
|           26 |     1728 | 2024-12-14 | PLUSH                      | W   | 0.676      | 0.303        | 0.000 (0.000)    | -                | 0 (0.000) |     3.69 | anber, Few, Kragh, Scr0b, smF        |
|           25 |     1989 | 2024-12-08 | BRUTE                      | L   | 0.639      | -            | -                | -                | -         |    -8.95 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           24 |     2336 | 2024-12-02 | WOPA Esport                | L   | 0.599      | -            | -                | -                | -         |    -5.73 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           23 |     2425 | 2024-12-01 | MASONIC                    | L   | 0.592      | -            | -                | -                | -         |   -10.56 | anber, Damkilde, Dengzoe, Few, Scr0b |
|           22 |     2491 | 2024-11-30 | 777 Esports                | W   | 0.586      | 0.333        | 0.002 (0.000)    | 0.235 (0.046)    | 0 (0.000) |     8.23 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           21 |     2627 | 2024-11-28 | NEVERMORE (Ukrainian team) | W   | 0.572      | 0.333        | 0.010 (0.002)    | 0.904 (0.172)    | 0 (0.000) |    10.96 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           20 |     2724 | 2024-11-26 | Ex-UHKA eSports            | W   | 0.559      | 0.333        | -                | 0.268 (0.050)    | 0 (0.000) |     4.81 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           19 |     3441 | 2024-11-14 | Denial (Danish team)       | L   | 0.479      | -            | -                | -                | -         |    -8.00 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           18 |     3459 | 2024-11-14 | Astralis Talent            | L   | 0.478      | -            | -                | -                | -         |    -5.64 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           17 |     3597 | 2024-11-11 | Copenhagen Wolves Academy  | W   | 0.459      | -            | -                | -                | 0 (0.000) |     2.17 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           16 |     3611 | 2024-11-11 | XI Esport                  | W   | 0.458      | 0.143        | -                | 0.124 (0.008)    | 0 (0.000) |     4.01 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           15 |     3618 | 2024-11-11 | Preasy Esport              | W   | 0.458      | 0.143        | 0.012 (0.001)    | 0.701 (0.046)    | 0 (0.000) |     9.15 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           14 |     3986 | 2024-11-04 | Denial (Danish team)       | L   | 0.412      | -            | -                | -                | -         |    -6.94 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           13 |     4003 | 2024-11-04 | MASONIC                    | W   | 0.412      | 0.143        | 0.001 (0.000)    | 0.164 (0.010)    | 0 (0.000) |     6.06 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           12 |     4009 | 2024-11-04 | Astralis Talent            | L   | 0.412      | -            | -                | -                | -         |    -5.44 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           11 |     4430 | 2024-10-28 | WOPA Esport                | L   | 0.365      | -            | -                | -                | -         |    -3.33 | anber, Dengzoe, Few, Kragh, Scr0b    |
|           10 |     5469 | 2024-10-07 | Astralis Talent            | W   | 0.225      | 0.143        | 0.002 (0.000)    | 0.724 (0.023)    | -         |     4.39 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            9 |     5492 | 2024-10-07 | XI Esport                  | W   | 0.224      | -            | -                | -                | -         |     1.98 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            8 |     5864 | 2024-10-01 | Preasy Esport              | L   | 0.184      | -            | -                | -                | -         |    -1.90 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            7 |     6456 | 2024-09-23 | MASONIC                    | L   | 0.132      | -            | -                | -                | -         |    -2.22 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            6 |     6478 | 2024-09-23 | WOPA Esport                | W   | 0.131      | 0.143        | 0.032 (0.001)    | 0.777 (0.015)    | -         |     3.00 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            5 |     6892 | 2024-09-16 | Denial (Danish team)       | W   | 0.085      | 0.143        | 0.001 (0.000)    | -                | -         |     1.20 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            4 |     6901 | 2024-09-16 | Copenhagen Wolves Academy  | W   | 0.084      | -            | -                | -                | -         |     0.46 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            3 |     7185 | 2024-09-11 | Chroma                     | L   | 0.052      | -            | -                | -                | -         |    -0.80 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            2 |     7287 | 2024-09-09 | Flame Sharks               | L   | 0.038      | -            | -                | -                | -         |    -0.66 | anber, Dengzoe, Few, Kragh, Scr0b    |
|            1 |     7580 | 2024-09-05 | Ex-UHKA eSports            | W   | 0.012      | -            | -                | -                | -         |     0.10 | anber, Dengzoe, Few, Kragh, Scr0b    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($361.32)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-21 |      0.723 | $500.00        | $361.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
