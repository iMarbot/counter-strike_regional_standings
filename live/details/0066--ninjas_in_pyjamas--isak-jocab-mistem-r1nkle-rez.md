### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: isak, jocab, MisteM, r1nkle, REZ<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  902.6<br />
<br />
Final Rank Value (902.6) = Starting Rank Value (882.0) + Head To Head Adjustments (20.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.242[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 882.0
- 400 + ( ( 0.241 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 882.0


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
|           21 |     2799 | 2024-11-24 | Team Spirit      | L   | 0.552      | -            | -                | -                | -         |    -0.05 | isak, jocab, MisteM, r1nkle, REZ   |
|           20 |     2819 | 2024-11-23 | 9Pandas          | W   | 0.549      | 0.143        | 0.085 (0.007)    | 0.485 (0.038)    | 1 (0.549) |    12.32 | isak, jocab, MisteM, r1nkle, REZ   |
|           19 |     2912 | 2024-11-22 | TSM              | W   | 0.544      | 0.143        | 0.009 (0.001)    | 0.130 (0.010)    | 1 (0.544) |     5.55 | isak, jocab, MisteM, r1nkle, REZ   |
|           18 |     3000 | 2024-11-21 | Team Falcons     | L   | 0.536      | -            | -                | -                | -         |    -0.06 | isak, jocab, MisteM, r1nkle, REZ   |
|           17 |     3056 | 2024-11-21 | PARIVISION       | W   | 0.531      | 0.143        | 0.006 (0.000)    | 0.060 (0.005)    | 1 (0.531) |     5.11 | isak, jocab, MisteM, r1nkle, REZ   |
|           16 |     3069 | 2024-11-20 | G2 Esports       | L   | 0.530      | -            | -                | -                | -         |    -0.08 | isak, jocab, MisteM, r1nkle, REZ   |
|           15 |     3552 | 2024-11-12 | BetBoom Team     | L   | 0.472      | -            | -                | -                | -         |    -4.67 | isak, jocab, MisteM, r1nkle, REZ   |
|           14 |     3597 | 2024-11-11 | Zero Tenacity    | W   | 0.467      | 0.384        | 0.028 (0.005)    | 0.692 (0.124)    | 0 (0.000) |     7.49 | isak, jocab, MisteM, r1nkle, REZ   |
|           13 |     3720 | 2024-11-09 | Metizport        | L   | 0.453      | -            | -                | -                | -         |    -3.40 | isak, jocab, MisteM, r1nkle, REZ   |
|           12 |     3796 | 2024-11-08 | Alliance         | W   | 0.446      | 0.143        | 0.015 (0.001)    | 0.573 (0.037)    | 1 (0.446) |     7.42 | isak, jocab, MisteM, r1nkle, REZ   |
|           11 |     4595 | 2024-10-25 | Imperial Esports | L   | 0.352      | -            | -                | -                | -         |    -3.86 | isak, jocab, MisteM, r1nkle, REZ   |
|           10 |     4644 | 2024-10-23 | Team Falcons     | L   | 0.340      | -            | -                | -                | -         |    -0.03 | isak, jocab, MisteM, r1nkle, REZ   |
|            9 |     4680 | 2024-10-23 | Imperial Esports | W   | 0.338      | 0.934        | 0.091 (0.029)    | 0.564 (0.178)    | 0 (0.000) |     7.04 | isak, jocab, MisteM, r1nkle, REZ   |
|            8 |     4997 | 2024-10-16 | JANO Esports     | L   | 0.293      | -            | -                | -                | -         |    -4.01 | isak, jocab, MisteM, r1nkle, REZ   |
|            7 |     5012 | 2024-10-16 | B8               | L   | 0.292      | -            | -                | -                | -         |    -1.85 | isak, jocab, MisteM, r1nkle, REZ   |
|            6 |     5684 | 2024-10-04 | ECSTATIC         | L   | 0.211      | -            | -                | -                | -         |    -3.24 | isak, jocab, MisteM, r1nkle, REZ   |
|            5 |     6275 | 2024-09-25 | ARCRED           | L   | 0.154      | -            | -                | -                | -         |    -3.25 | isak, maxster, MisteM, r1nkle, REZ |
|            4 |     7424 | 2024-09-07 | Team Falcons     | L   | 0.032      | -            | -                | -                | -         |    -0.00 | alex, isak, maxster, r1nkle, REZ   |
|            3 |     7577 | 2024-09-05 | FaZe Clan        | L   | 0.020      | -            | -                | -                | -         |    -0.00 | alex, isak, maxster, r1nkle, REZ   |
|            2 |     7658 | 2024-09-04 | Natus Vincere    | L   | 0.013      | -            | -                | -                | -         |    -0.00 | alex, isak, maxster, r1nkle, REZ   |
|            1 |     7738 | 2024-09-03 | Team Falcons     | W   | 0.005      | 0.889        | 0.927 (0.005)    | 0.613 (0.003)    | 1 (0.005) |     0.17 | alex, isak, maxster, r1nkle, REZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,253.25)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-12 |      0.473 | $1,500.00      | $708.92         |
| 2024-11-09 |      0.453 | $11,097.44     | $5,024.67       |
| 2024-10-20 |      0.319 | $5,000.00      | $1,594.10       |
| 2024-09-22 |      0.132 | $7,000.00      | $925.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
