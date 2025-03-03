### Roster Details<br />
Team Name: Mission Possible<br />
Roster: b0RUP, birdfromsky, Licale, nicoodoz, Vegi<br />
Global Rank: [411](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [254]( ../standings_europe.md)<br />
<br />
Final Rank Value:  591.2<br />
<br />
Final Rank Value (591.2) = Starting Rank Value (528.4) + Head To Head Adjustments (62.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.064<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 528.4
- 400 + ( ( 0.064 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 528.4


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
|           24 |      311 | 2025-02-17 | Leo Team               | L   | 1.000      | -            | -                | -                | -         |    -5.79 | b0RUP, birdfromsky, Licale, nicoodoz, Vegi |
|           23 |      353 | 2025-02-16 | Virtual Cottage        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |    13.88 | b0RUP, birdfromsky, Licale, nicoodoz, Vegi |
|           22 |      710 | 2025-02-08 | OG                     | L   | 1.000      | -            | -                | -                | -         |    -3.27 | b0RUP, birdfromsky, Licale, nicoodoz, Vegi |
|           21 |      760 | 2025-02-07 | Bad News Eagles        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.188 (0.027)    | 0 (0.000) |    16.61 | b0RUP, birdfromsky, Licale, nicoodoz, Vegi |
|           20 |     1500 | 2024-12-20 | Permitta Esports       | L   | 0.719      | -            | -                | -                | -         |    -3.83 | aidKiT, b0RUP, birdfromsky, Licale, Vegi   |
|           19 |     1503 | 2024-12-20 | K27                    | W   | 0.719      | 0.143        | 0.008 (0.001)    | 0.769 (0.079)    | 0 (0.000) |    18.79 | aidKiT, b0RUP, birdfromsky, Licale, Vegi   |
|           18 |     1510 | 2024-12-20 | Ex-GODSENT             | W   | 0.719      | 0.143        | 0.000 (0.000)    | 0.141 (0.015)    | 0 (0.000) |    11.40 | aidKiT, b0RUP, birdfromsky, Licale, Vegi   |
|           17 |     1814 | 2024-12-13 | Heimo Esports          | L   | 0.670      | -            | -                | -                | -         |    -5.95 | aidKiT, b0RUP, birdfromsky, Licale, Vegi   |
|           16 |     1976 | 2024-12-09 | ENCE Academy           | L   | 0.643      | -            | -                | -                | -         |    -4.16 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|           15 |     2540 | 2024-11-30 | Metizport X            | L   | 0.584      | -            | -                | -                | -         |    -6.33 | birdfromsky, Licale, m4tthi, SLY, Vegi     |
|           14 |     2659 | 2024-11-28 | Chroma                 | L   | 0.570      | -            | -                | -                | -         |    -6.07 | birdfromsky, Licale, m4tthi, SLY, Vegi     |
|           13 |     3205 | 2024-11-18 | ENTERPRISE Genesis     | L   | 0.505      | -            | -                | -                | -         |    -6.11 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|           12 |     3241 | 2024-11-17 | BRUTE                  | W   | 0.498      | 0.278        | 0.004 (0.001)    | 0.341 (0.047)    | 0 (0.000) |    10.88 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|           11 |     3389 | 2024-11-15 | KUUSAMO.gg             | W   | 0.485      | 0.278        | -                | 0.162 (0.022)    | 0 (0.000) |     6.67 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|           10 |     3462 | 2024-11-14 | Lazer Cats             | L   | 0.478      | -            | -                | -                | -         |    -3.96 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            9 |     3615 | 2024-11-11 | Daystar                | W   | 0.458      | 0.278        | 0.000 (0.000)    | 0.131 (0.017)    | 0 (0.000) |     8.86 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            8 |     3809 | 2024-11-08 | ENTERPRISE Genesis     | L   | 0.438      | -            | -                | -                | -         |    -5.25 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            7 |     4006 | 2024-11-04 | Natus Vincere Youth    | W   | 0.412      | 0.278        | -                | 0.024 (0.003)    | 0 (0.000) |     5.38 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            6 |     5137 | 2024-10-13 | Passion UA             | L   | 0.265      | -            | -                | -                | -         |    -0.53 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            5 |     5201 | 2024-10-12 | Illuminar Gaming       | L   | 0.258      | -            | -                | -                | -         |    -1.12 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            4 |     5206 | 2024-10-12 | Passion UA             | W   | 0.258      | 0.143        | 0.044 (0.002)    | 0.545 (0.020)    | 0 (0.000) |     7.63 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            3 |     5434 | 2024-10-08 | Prime Bulls            | W   | 0.231      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     4.63 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            2 |     5467 | 2024-10-07 | Ex-Soul's Heart Esport | W   | 0.225      | 0.143        | 0.000 (0.000)    | -                | -         |     4.53 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |
|            1 |     5473 | 2024-10-07 | Dark Cloud Esports     | W   | 0.225      | 0.143        | 0.039 (0.001)    | 0.819 (0.026)    | -         |     5.94 | b0RUP, birdfromsky, Licale, m4tthi, Vegi   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
