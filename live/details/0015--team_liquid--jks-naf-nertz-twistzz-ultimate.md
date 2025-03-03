### Roster Details<br />
Team Name: Team Liquid<br />
Roster: jks, NAF, NertZ, Twistzz, ultimate<br />
Global Rank: [15](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1524.9<br />
<br />
Final Rank Value (1524.9) = Starting Rank Value (1518.8) + Head To Head Adjustments (6.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.578[<sup>1</sup>](#table2)
- Bounty Collected: 0.573[<sup>2</sup>](#table1)
- Opponent Network: 0.255[<sup>2</sup>](#table1)
- LAN Wins: 0.830[<sup>2</sup>](#table1)

The average of these factors is 0.559<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1518.8
- 400 + ( ( 0.559 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1518.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |     1007 | 2025-02-04 | Team Spirit   | L   | 1.000      | -            | -                | -                | -         |    -2.41 | jks, NAF, NertZ, Twistzz, ultimate    |
|           32 |     1039 | 2025-02-03 | MOUZ          | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.470 (0.470)    | 1 (1.000) |    28.15 | jks, NAF, NertZ, Twistzz, ultimate    |
|           31 |     1051 | 2025-02-02 | The MongolZ   | L   | 1.000      | -            | -                | -                | -         |    -2.35 | jks, NAF, NertZ, Twistzz, ultimate    |
|           30 |     1102 | 2025-01-31 | Wildcard      | W   | 0.998      | 1.000        | 0.178 (0.178)    | 0.422 (0.421)    | 1 (0.998) |     9.49 | jks, NAF, NertZ, Twistzz, ultimate    |
|           29 |     1106 | 2025-01-31 | Complexity    | W   | 0.997      | 1.000        | 0.098 (0.098)    | 0.226 (0.225)    | 1 (0.997) |     3.96 | jks, NAF, NertZ, Twistzz, ultimate    |
|           28 |     1116 | 2025-01-29 | HEROIC        | L   | 0.985      | -            | -                | -                | -         |   -27.47 | jks, NAF, NertZ, Twistzz, ultimate    |
|           27 |     1178 | 2025-01-18 | HEROIC        | L   | 0.910      | -            | -                | -                | -         |   -26.17 | jks, NAF, NertZ, Twistzz, ultimate    |
|           26 |     1198 | 2025-01-14 | 9Pandas       | W   | 0.885      | 0.363        | 0.085 (0.027)    | 0.477 (0.153)    | -         |     1.69 | jks, NAF, NertZ, Twistzz, ultimate    |
|           25 |     1858 | 2024-12-12 | Team Spirit   | L   | 0.663      | -            | -                | -                | -         |    -1.93 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           24 |     2115 | 2024-12-06 | MIBR          | W   | 0.628      | 1.000        | 0.142 (0.089)    | 0.465 (0.292)    | 1 (0.628) |     6.90 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           23 |     2160 | 2024-12-05 | FURIA         | W   | 0.621      | 1.000        | 0.094 (0.059)    | 0.379 (0.235)    | 1 (0.621) |     7.99 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           22 |     2192 | 2024-12-05 | GamerLegion   | W   | 0.616      | 1.000        | 0.129 (0.079)    | 0.490 (0.302)    | 1 (0.616) |    11.07 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           21 |     2202 | 2024-12-04 | Natus Vincere | L   | 0.614      | -            | -                | -                | -         |    -4.88 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           20 |     2462 | 2024-11-30 | FlyQuest      | W   | 0.588      | 1.000        | 0.105 (0.062)    | 0.235 (0.138)    | 1 (0.588) |     1.86 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           19 |     2552 | 2024-11-30 | Wildcard      | W   | 0.583      | 1.000        | 0.178 (0.104)    | 0.422 (0.246)    | 1 (0.583) |     4.92 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           18 |     2573 | 2024-11-29 | Cloud9        | W   | 0.581      | -            | -                | -                | 1 (0.581) |     0.63 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           17 |     3484 | 2024-11-14 | FURIA         | W   | 0.476      | -            | -                | -                | 1 (0.476) |     6.07 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           16 |     3539 | 2024-11-12 | BESTIA        | W   | 0.468      | -            | -                | -                | -         |     0.62 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           15 |     3560 | 2024-11-12 | KRÜ Esports   | W   | 0.464      | -            | -                | -                | -         |     0.15 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           14 |     3592 | 2024-11-11 | Wildcard      | L   | 0.461      | -            | -                | -                | -         |   -10.99 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           13 |     4271 | 2024-10-31 | Team Vitality | L   | 0.383      | -            | -                | -                | -         |    -1.25 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           12 |     4341 | 2024-10-30 | G2 Esports    | L   | 0.376      | -            | -                | -                | -         |    -2.13 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           11 |     5422 | 2024-10-08 | FaZe Clan     | L   | 0.232      | -            | -                | -                | -         |    -0.74 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           10 |     5462 | 2024-10-07 | Natus Vincere | L   | 0.226      | -            | -                | -                | -         |    -1.87 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            9 |     5498 | 2024-10-07 | Complexity    | W   | 0.224      | -            | -                | -                | -         |     0.79 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            8 |     6134 | 2024-09-27 | FaZe Clan     | L   | 0.158      | -            | -                | -                | -         |    -0.49 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            7 |     6193 | 2024-09-26 | Team Vitality | L   | 0.152      | -            | -                | -                | -         |    -0.48 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            6 |     6303 | 2024-09-25 | Team Spirit   | W   | 0.145      | 0.729        | 1.000 (0.105)    | 0.658 (0.069)    | -         |     4.26 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            5 |     6638 | 2024-09-20 | G2 Esports    | L   | 0.111      | -            | -                | -                | -         |    -0.64 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            4 |     6766 | 2024-09-18 | Complexity    | W   | 0.098      | -            | -                | -                | -         |     0.35 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            3 |     6936 | 2024-09-15 | Team Vitality | L   | 0.078      | -            | -                | -                | -         |    -0.24 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            2 |     7157 | 2024-09-12 | Virtus.pro    | W   | 0.056      | -            | -                | -                | -         |     1.22 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            1 |     7262 | 2024-09-10 | ENCE          | W   | 0.044      | -            | -                | -                | -         |     0.07 | jks, NAF, Twistzz, ultimate, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61,463.68)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-12-15 |      0.683 | $45,000.00     | $30,723.96      |
| 2024-11-03 |      0.403 | $15,000.00     | $6,039.58       |
| 2024-10-13 |      0.265 | $5,000.00      | $1,322.92       |
| 2024-09-29 |      0.170 | $20,000.00     | $3,408.33       |
| 2024-09-22 |      0.124 | $32,000.00     | $3,968.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
