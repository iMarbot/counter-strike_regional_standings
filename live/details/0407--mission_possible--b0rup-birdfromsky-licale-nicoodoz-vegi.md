### Roster Details<br />
Team Name: Mission Possible<br />
Roster: b0RUP, birdfromsky, Licale, nicoodoz, Vegi<br />
Global Rank: [407](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [254]( ../standings_europe.md)<br />
<br />
Final Rank Value:  592.4<br />
<br />
Final Rank Value (592.4) = Starting Rank Value (528.8) + Head To Head Adjustments (63.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.064<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 528.8
- 400 + ( ( 0.064 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 528.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      299 | 2025-02-17 | Leo Team               | L   | 1.000      | -            | -                | -                | -         |    -5.77 | b0RUP, birdfromsky, Licale, nicoodoz, Vegi |
|           23 |      341 | 2025-02-16 | Virtual Cottage        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.140 (0.020)    | 0 (0.000) |    13.82 | b0RUP, birdfromsky, Licale, nicoodoz, Vegi |
|           22 |      698 | 2025-02-08 | OG                     | L   | 1.000      | -            | -                | -                | -         |    -3.28 | b0RUP, birdfromsky, Licale, nicoodoz, Vegi |
|           21 |      748 | 2025-02-07 | Bad News Eagles        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.187 (0.027)    | 0 (0.000) |    16.55 | b0RUP, birdfromsky, Licale, nicoodoz, Vegi |
|           20 |     1488 | 2024-12-20 | Permitta Esports       | L   | 0.728      | -            | -                | -                | -         |    -3.86 | aidKiT, b0RUP, birdfromsky, Licale, Vegi   |
|           19 |     1491 | 2024-12-20 | K27                    | W   | 0.727      | 0.143        | 0.008 (0.001)    | 0.776 (0.081)    | 0 (0.000) |    18.97 | aidKiT, b0RUP, birdfromsky, Licale, Vegi   |
|           18 |     1498 | 2024-12-20 | Ex-GODSENT             | W   | 0.727      | 0.143        | 0.000 (0.000)    | 0.142 (0.015)    | 0 (0.000) |    11.50 | aidKiT, b0RUP, birdfromsky, Licale, Vegi   |
|           17 |     1802 | 2024-12-13 | Heimo Esports          | L   | 0.678      | -            | -                | -                | -         |    -5.97 | aidKiT, b0RUP, birdfromsky, Licale, Vegi   |
|           16 |     1964 | 2024-12-09 | ENCE Academy           | L   | 0.651      | -            | -                | -                | -         |    -4.24 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|           15 |     2528 | 2024-11-30 | Metizport X            | L   | 0.592      | -            | -                | -                | -         |    -6.43 | birdfromsky, Licale, m4tthi, SLY, Vegi     |
|           14 |     2647 | 2024-11-28 | Chroma                 | L   | 0.579      | -            | -                | -                | -         |    -6.19 | birdfromsky, Licale, m4tthi, SLY, Vegi     |
|           13 |     3193 | 2024-11-18 | ENTERPRISE Genesis     | L   | 0.514      | -            | -                | -                | -         |    -6.23 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|           12 |     3229 | 2024-11-17 | BRUTE                  | W   | 0.507      | 0.278        | 0.004 (0.001)    | 0.345 (0.049)    | 0 (0.000) |    11.03 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|           11 |     3377 | 2024-11-15 | KUUSAMO.gg             | W   | 0.493      | 0.278        | -                | 0.164 (0.022)    | 0 (0.000) |     6.75 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|           10 |     3450 | 2024-11-14 | Lazer Cats             | L   | 0.486      | -            | -                | -                | -         |    -4.02 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            9 |     3603 | 2024-11-11 | Daystar                | W   | 0.467      | 0.278        | 0.000 (0.000)    | 0.135 (0.017)    | 0 (0.000) |     9.03 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            8 |     3797 | 2024-11-08 | ENTERPRISE Genesis     | L   | 0.446      | -            | -                | -                | -         |    -5.37 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            7 |     3994 | 2024-11-04 | Natus Vincere Youth    | W   | 0.420      | 0.278        | -                | 0.024 (0.003)    | 0 (0.000) |     5.47 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            6 |     5125 | 2024-10-13 | Passion UA             | L   | 0.273      | -            | -                | -                | -         |    -0.55 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            5 |     5189 | 2024-10-12 | Illuminar Gaming       | L   | 0.266      | -            | -                | -                | -         |    -1.15 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            4 |     5194 | 2024-10-12 | Passion UA             | W   | 0.266      | 0.143        | 0.044 (0.002)    | 0.557 (0.021)    | 0 (0.000) |     7.88 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            3 |     5422 | 2024-10-08 | Prime Bulls            | W   | 0.239      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     4.79 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            2 |     5455 | 2024-10-07 | Ex-Soul's Heart Esport | W   | 0.234      | 0.143        | 0.000 (0.000)    | -                | -         |     4.70 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            1 |     5461 | 2024-10-07 | Dark Cloud Esports     | W   | 0.233      | 0.143        | 0.038 (0.001)    | 0.828 (0.028)    | -         |     6.15 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
