### Roster Details<br />
Team Name: HAVU<br />
Roster: Alxc, ottob, p3kko, puuha, uli<br />
Global Rank: [218](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [156]( ../standings_europe.md)<br />
<br />
Final Rank Value:  697.1<br />
<br />
Final Rank Value (697.1) = Starting Rank Value (659.3) + Head To Head Adjustments (37.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 659.3
- 400 + ( ( 0.130 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 659.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      180 | 2025-02-21 | ENCE Academy    | L   | 1.000      | -            | -                | -                | -         |   -10.39 | Alxc, ottob, p3kko, puuha, uli |
|           15 |      286 | 2025-02-17 | Heimo Esports   | L   | 1.000      | -            | -                | -                | -         |   -14.43 | Alxc, ottob, p3kko, puuha, uli |
|           14 |      513 | 2025-02-13 | FCottoNd        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.179 (0.026)    | 0 (0.000) |     5.81 | Alxc, ottob, p3kko, puuha, uli |
|           13 |      832 | 2025-02-06 | Smuuttikusilkki | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.224 (0.032)    | 0 (0.000) |     6.84 | Alxc, ottob, p3kko, puuha, uli |
|           12 |      991 | 2025-02-04 | JANO Esports    | L   | 1.000      | -            | -                | -                | -         |   -12.40 | Alxc, ottob, p3kko, puuha, uli |
|           11 |     1037 | 2025-02-02 | JANO Esports    | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.442 (0.063)    | 0 (0.000) |    19.41 | Alxc, ottob, p3kko, puuha, uli |
|           10 |     1063 | 2025-02-01 | ENCE Academy    | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.655 (0.094)    | 0 (0.000) |    20.82 | Alxc, ottob, p3kko, puuha, uli |
|            9 |     1122 | 2025-01-27 | Ex-UHKA eSports | W   | 0.979      | 0.143        | 0.000 (0.000)    | 0.271 (0.038)    | 0 (0.000) |     9.92 | Alxc, ottob, p3kko, puuha, uli |
|            8 |     1135 | 2025-01-25 | SAUCEMEN        | W   | 0.965      | 0.143        | 0.000 (0.000)    | 0.087 (0.012)    | 0 (0.000) |     5.90 | Alxc, ottob, p3kko, puuha, uli |
|            7 |     1169 | 2025-01-17 | Team yaNgile    | W   | 0.914      | 0.143        | 0.000 (0.000)    | 0.043 (0.006)    | 0 (0.000) |     5.78 | Alxc, ottob, p3kko, puuha, uli |
|            6 |     1173 | 2025-01-17 | Torakka         | W   | 0.913      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.45 | Alxc, ottob, p3kko, puuha, uli |
|            5 |     5910 | 2024-09-30 | Cspojat         | L   | 0.186      | -            | -                | -                | -         |    -4.25 | Alxc, jelo, jv, puuha, uli     |
|            4 |     5918 | 2024-09-30 | SIUUUUUU        | W   | 0.185      | 0.143        | 0.000 (0.000)    | 0.011 (0.000)    | 0 (0.000) |     1.14 | Alxc, jelo, jv, puuha, uli     |
|            3 |     6531 | 2024-09-22 | KUUSAMO.gg      | W   | 0.131      | 0.143        | 0.000 (0.000)    | 0.164 (0.003)    | 0 (0.000) |     1.26 | Alxc, jelo, jv, puuha, uli     |
|            2 |     6885 | 2024-09-16 | Cspojat         | L   | 0.093      | -            | -                | -                | -         |    -2.13 | Alxc, jelo, jv, puuha, uli     |
|            1 |     7363 | 2024-09-08 | Smuuttikusilkki | L   | 0.037      | -            | -                | -                | -         |    -0.87 | Alxc, jelo, jv, puuha, uli     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($523.23)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $523.23        | $523.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
