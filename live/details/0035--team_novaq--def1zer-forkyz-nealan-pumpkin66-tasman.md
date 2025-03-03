### Roster Details<br />
Team Name: Team Novaq<br />
Roster: def1zer, forkyz, neaLaN, Pumpkin66, tasman<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1040.1<br />
<br />
Final Rank Value (1040.1) = Starting Rank Value (1118.1) + Head To Head Adjustments (-78.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.081[<sup>2</sup>](#table1)
- LAN Wins: 0.631[<sup>2</sup>](#table1)

The average of these factors is 0.359<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1118.1
- 400 + ( ( 0.359 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1118.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      114 | 2025-02-23 | Roler Coaster    | L   | 1.000      | -            | -                | -                | -         |   -29.58 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           25 |      147 | 2025-02-22 | Openai chatgpt   | W   | 1.000      | -            | -                | -                | -         |     0.72 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           24 |      245 | 2025-02-20 | POLET            | L   | 1.000      | -            | -                | -                | -         |   -30.14 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           23 |      695 | 2025-02-08 | Little Red Door  | L   | 1.000      | -            | -                | -                | -         |   -29.76 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           22 |      707 | 2025-02-08 | Fnatic           | W   | 1.000      | 0.143        | 0.072 (0.010)    | 0.459 (0.066)    | -         |    14.01 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           21 |      786 | 2025-02-07 | Iberian Soul     | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.551 (0.079)    | -         |     4.83 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           20 |     1652 | 2024-12-15 | AK BARS          | W   | 0.683      | 0.333        | 0.008 (0.002)    | 0.209 (0.048)    | 1 (0.683) |     4.48 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           19 |     1663 | 2024-12-15 | AimAssassins     | W   | 0.682      | 0.333        | 0.004 (0.001)    | 0.238 (0.054)    | 1 (0.682) |     6.13 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           18 |     1729 | 2024-12-14 | Mix52            | W   | 0.676      | 0.333        | 0.002 (0.000)    | 0.063 (0.014)    | 1 (0.676) |     2.81 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           17 |     1741 | 2024-12-13 | DEPO             | W   | 0.675      | 0.333        | 0.006 (0.001)    | 0.291 (0.066)    | 1 (0.675) |     3.29 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           16 |     1801 | 2024-12-13 | AK BARS          | L   | 0.671      | -            | -                | -                | -         |   -17.13 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           15 |     1808 | 2024-12-13 | Mix52            | W   | 0.671      | 0.333        | 0.002 (0.000)    | 0.063 (0.014)    | 1 (0.671) |     2.45 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           14 |     2406 | 2024-12-01 | MYSKILL          | W   | 0.592      | 0.143        | 0.002 (0.000)    | -                | -         |     1.64 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           13 |     2415 | 2024-12-01 | ALLINNERS        | L   | 0.592      | -            | -                | -                | -         |   -16.84 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           12 |     2438 | 2024-12-01 | Mix52            | W   | 0.591      | -            | -                | -                | -         |     2.06 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           11 |     3328 | 2024-11-16 | GTZ.ESPORTS      | L   | 0.492      | -            | -                | -                | -         |    -7.18 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|           10 |     3397 | 2024-11-15 | KONO.ECF         | W   | 0.485      | 0.617        | 0.046 (0.014)    | 0.747 (0.224)    | 1 (0.485) |     3.23 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            9 |     3403 | 2024-11-15 | GnG x Amazigh    | W   | 0.484      | -            | -                | -                | 1 (0.484) |     0.26 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            8 |     3455 | 2024-11-14 | Team Latvia      | W   | 0.478      | 0.617        | -                | 0.045 (0.013)    | 1 (0.478) |     0.74 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            7 |     3464 | 2024-11-14 | Nexus Gaming     | W   | 0.478      | 0.617        | 0.187 (0.055)    | 0.795 (0.234)    | 1 (0.478) |     6.98 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            6 |     6834 | 2024-09-17 | Partizan Esports | L   | 0.092      | -            | -                | -                | -         |    -1.55 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            5 |     6946 | 2024-09-15 | DEPO             | W   | 0.077      | -            | -                | -                | 1 (0.077) |     0.31 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            4 |     7046 | 2024-09-14 | MYSKILL          | W   | 0.070      | -            | -                | -                | -         |     0.17 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            3 |     7065 | 2024-09-13 | LostEverySense   | W   | 0.068      | -            | -                | -                | -         |     0.04 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            2 |     7079 | 2024-09-13 | PodREDBULom      | W   | 0.065      | -            | -                | -                | -         |     0.04 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            1 |     7628 | 2024-09-05 | Team Uzbekistan  | W   | 0.010      | -            | -                | -                | -         |     0.01 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,985.22)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.683 | $5,000.00      | $3,415.97       |
| 2024-11-17 |      0.498 | $12,500.00     | $6,225.69       |
| 2024-09-22 |      0.125 | $175.00        | $21.80          |
| 2024-09-15 |      0.077 | $4,166.59      | $321.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
