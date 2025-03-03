### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: isak, jocab, MisteM, r1nkle, REZ<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  898.5<br />
<br />
Final Rank Value (898.5) = Starting Rank Value (877.8) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.239[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 877.8
- 400 + ( ( 0.239 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 877.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     2811 | 2024-11-24 | Team Spirit      | L   | 0.543      | -            | -                | -                | -         |    -0.05 | isak, jocab, MisteM, r1nkle, REZ   |
|           19 |     2831 | 2024-11-23 | 9Pandas          | W   | 0.541      | 0.143        | 0.085 (0.007)    | 0.477 (0.037)    | 1 (0.541) |    12.16 | isak, jocab, MisteM, r1nkle, REZ   |
|           18 |     2924 | 2024-11-22 | TSM              | W   | 0.535      | 0.143        | 0.009 (0.001)    | 0.127 (0.010)    | 1 (0.535) |     5.50 | isak, jocab, MisteM, r1nkle, REZ   |
|           17 |     3012 | 2024-11-21 | Team Falcons     | L   | 0.528      | -            | -                | -                | -         |    -0.06 | isak, jocab, MisteM, r1nkle, REZ   |
|           16 |     3068 | 2024-11-21 | PARIVISION       | W   | 0.523      | 0.143        | 0.006 (0.000)    | 0.058 (0.004)    | 1 (0.523) |     5.07 | isak, jocab, MisteM, r1nkle, REZ   |
|           15 |     3081 | 2024-11-20 | G2 Esports       | L   | 0.521      | -            | -                | -                | -         |    -0.08 | isak, jocab, MisteM, r1nkle, REZ   |
|           14 |     3564 | 2024-11-12 | BetBoom Team     | L   | 0.464      | -            | -                | -                | -         |    -4.55 | isak, jocab, MisteM, r1nkle, REZ   |
|           13 |     3609 | 2024-11-11 | Zero Tenacity    | W   | 0.459      | 0.384        | 0.028 (0.005)    | 0.684 (0.121)    | 0 (0.000) |     7.38 | isak, jocab, MisteM, r1nkle, REZ   |
|           12 |     3732 | 2024-11-09 | Metizport        | L   | 0.445      | -            | -                | -                | -         |    -3.33 | isak, jocab, MisteM, r1nkle, REZ   |
|           11 |     3808 | 2024-11-08 | Alliance         | W   | 0.438      | 0.143        | 0.015 (0.001)    | 0.570 (0.036)    | 1 (0.438) |     7.35 | isak, jocab, MisteM, r1nkle, REZ   |
|           10 |     4607 | 2024-10-25 | Imperial Esports | L   | 0.344      | -            | -                | -                | -         |    -3.76 | isak, jocab, MisteM, r1nkle, REZ   |
|            9 |     4656 | 2024-10-23 | Team Falcons     | L   | 0.332      | -            | -                | -                | -         |    -0.03 | isak, jocab, MisteM, r1nkle, REZ   |
|            8 |     4692 | 2024-10-23 | Imperial Esports | W   | 0.330      | 0.934        | 0.092 (0.028)    | 0.562 (0.173)    | 0 (0.000) |     6.87 | isak, jocab, MisteM, r1nkle, REZ   |
|            7 |     5009 | 2024-10-16 | JANO Esports     | L   | 0.284      | -            | -                | -                | -         |    -3.85 | isak, jocab, MisteM, r1nkle, REZ   |
|            6 |     5024 | 2024-10-16 | B8               | L   | 0.283      | -            | -                | -                | -         |    -1.78 | isak, jocab, MisteM, r1nkle, REZ   |
|            5 |     5696 | 2024-10-04 | ECSTATIC         | L   | 0.202      | -            | -                | -                | -         |    -3.09 | isak, jocab, MisteM, r1nkle, REZ   |
|            4 |     6287 | 2024-09-25 | ARCRED           | L   | 0.145      | -            | -                | -                | -         |    -3.05 | isak, maxster, MisteM, r1nkle, REZ |
|            3 |     7436 | 2024-09-07 | Team Falcons     | L   | 0.024      | -            | -                | -                | -         |    -0.00 | alex, isak, maxster, r1nkle, REZ   |
|            2 |     7589 | 2024-09-05 | FaZe Clan        | L   | 0.012      | -            | -                | -                | -         |    -0.00 | alex, isak, maxster, r1nkle, REZ   |
|            1 |     7670 | 2024-09-04 | Natus Vincere    | L   | 0.005      | -            | -                | -                | -         |    -0.00 | alex, isak, maxster, r1nkle, REZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,051.69)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-12 |      0.464 | $1,500.00      | $696.63         |
| 2024-11-09 |      0.445 | $11,097.44     | $4,933.74       |
| 2024-10-20 |      0.311 | $5,000.00      | $1,553.13       |
| 2024-09-22 |      0.124 | $7,000.00      | $868.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
