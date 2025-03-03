### Roster Details<br />
Team Name: HAVU<br />
Roster: Alxc, ottob, p3kko, puuha, uli<br />
Global Rank: [222](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [156]( ../standings_europe.md)<br />
<br />
Final Rank Value:  697.3<br />
<br />
Final Rank Value (697.3) = Starting Rank Value (659.9) + Head To Head Adjustments (37.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 659.9
- 400 + ( ( 0.130 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 659.9


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
|           16 |      192 | 2025-02-21 | ENCE Academy    | L   | 1.000      | -            | -                | -                | -         |   -10.45 | Alxc, ottob, p3kko, puuha, uli |
|           15 |      298 | 2025-02-17 | Heimo Esports   | L   | 1.000      | -            | -                | -                | -         |   -14.58 | Alxc, ottob, p3kko, puuha, uli |
|           14 |      525 | 2025-02-13 | FCottoNd        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.179 (0.026)    | 0 (0.000) |     5.79 | Alxc, ottob, p3kko, puuha, uli |
|           13 |      844 | 2025-02-06 | Smuuttikusilkki | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.223 (0.032)    | 0 (0.000) |     6.80 | Alxc, ottob, p3kko, puuha, uli |
|           12 |     1003 | 2025-02-04 | JANO Esports    | L   | 1.000      | -            | -                | -                | -         |   -12.43 | Alxc, ottob, p3kko, puuha, uli |
|           11 |     1049 | 2025-02-02 | JANO Esports    | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.440 (0.063)    | 0 (0.000) |    19.37 | Alxc, ottob, p3kko, puuha, uli |
|           10 |     1075 | 2025-02-01 | ENCE Academy    | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.649 (0.093)    | 0 (0.000) |    20.74 | Alxc, ottob, p3kko, puuha, uli |
|            9 |     1134 | 2025-01-27 | Ex-UHKA eSports | W   | 0.971      | 0.143        | 0.000 (0.000)    | 0.268 (0.037)    | 0 (0.000) |     9.78 | Alxc, ottob, p3kko, puuha, uli |
|            8 |     1147 | 2025-01-25 | SAUCEMEN        | W   | 0.956      | 0.143        | 0.000 (0.000)    | 0.086 (0.012)    | 0 (0.000) |     5.83 | Alxc, ottob, p3kko, puuha, uli |
|            7 |     1181 | 2025-01-17 | Team yaNgile    | W   | 0.905      | 0.143        | 0.000 (0.000)    | 0.042 (0.005)    | 0 (0.000) |     5.70 | Alxc, ottob, p3kko, puuha, uli |
|            6 |     1185 | 2025-01-17 | Torakka         | W   | 0.905      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.38 | Alxc, ottob, p3kko, puuha, uli |
|            5 |     5922 | 2024-09-30 | Cspojat         | L   | 0.178      | -            | -                | -                | -         |    -4.07 | Alxc, jelo, jv, puuha, uli     |
|            4 |     5930 | 2024-09-30 | SIUUUUUU        | W   | 0.177      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     1.08 | Alxc, jelo, jv, puuha, uli     |
|            3 |     6543 | 2024-09-22 | KUUSAMO.gg      | W   | 0.122      | 0.143        | 0.000 (0.000)    | 0.162 (0.003)    | 0 (0.000) |     1.17 | Alxc, jelo, jv, puuha, uli     |
|            2 |     6897 | 2024-09-16 | Cspojat         | L   | 0.085      | -            | -                | -                | -         |    -1.95 | Alxc, jelo, jv, puuha, uli     |
|            1 |     7375 | 2024-09-08 | Smuuttikusilkki | L   | 0.029      | -            | -                | -                | -         |    -0.68 | Alxc, jelo, jv, puuha, uli     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($523.23)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $523.23        | $523.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
