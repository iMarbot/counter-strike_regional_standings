### Roster Details<br />
Team Name: Nouns Esports<br />
Roster: CLASIA, Cryptic, junior, Peeping, RUSH<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  889.2<br />
<br />
Final Rank Value (889.2) = Starting Rank Value (840.1) + Head To Head Adjustments (49.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.067[<sup>2</sup>](#table1)
- LAN Wins: 0.222[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 840.1
- 400 + ( ( 0.220 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 840.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      519 | 2025-02-13 | M80              | L   | 1.000      | -            | -                | -                | -         |   -11.29 | CLASIA, Cryptic, junior, Peeping, RUSH  |
|           17 |      534 | 2025-02-12 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -9.40 | CLASIA, Cryptic, junior, Peeping, RUSH  |
|           16 |      537 | 2025-02-12 | BLUEJAYS         | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.511 (0.073)    | 0 (0.000) |    22.66 | CLASIA, Cryptic, junior, Peeping, RUSH  |
|           15 |      555 | 2025-02-11 | Marsborne        | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.234 (0.033)    | 0 (0.000) |    16.36 | CLASIA, Cryptic, junior, Peeping, RUSH  |
|           14 |      559 | 2025-02-11 | BLUEJAYS         | L   | 1.000      | -            | -                | -                | -         |    -7.21 | CLASIA, Cryptic, junior, Peeping, RUSH  |
|           13 |      662 | 2025-02-08 | Marsborne        | L   | 1.000      | -            | -                | -                | -         |   -13.97 | CLASIA, Cryptic, junior, Peeping, RUSH  |
|           12 |      665 | 2025-02-08 | Vagrants         | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.276 (0.039)    | 0 (0.000) |     8.13 | CLASIA, Cryptic, junior, Peeping, RUSH  |
|           11 |      747 | 2025-02-07 | MIGHT            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.489 (0.070)    | 0 (0.000) |    10.42 | CLASIA, Cryptic, junior, Peeping, RUSH  |
|           10 |     1618 | 2024-12-15 | Getting Info     | L   | 0.687      | -            | -                | -                | -         |   -11.04 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |
|            9 |     1671 | 2024-12-14 | Vagrants         | W   | 0.680      | 0.303        | 0.001 (0.000)    | 0.276 (0.057)    | 0 (0.000) |     5.22 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |
|            8 |     1984 | 2024-12-08 | BLUEJAYS         | L   | 0.639      | -            | -                | -                | -         |    -4.30 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |
|            7 |     2005 | 2024-12-08 | Undone           | W   | 0.638      | 0.384        | 0.002 (0.001)    | 0.282 (0.069)    | 1 (0.638) |     7.29 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |
|            6 |     2059 | 2024-12-07 | Sharks Esports   | L   | 0.634      | -            | -                | -                | -         |    -6.68 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |
|            5 |     2072 | 2024-12-07 | Party Astronauts | W   | 0.633      | 0.384        | 0.008 (0.002)    | 0.382 (0.093)    | 1 (0.633) |     7.71 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |
|            4 |     2124 | 2024-12-06 | Fisher College   | W   | 0.627      | 0.384        | 0.008 (0.002)    | 0.324 (0.078)    | 1 (0.627) |     7.52 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |
|            3 |     2777 | 2024-11-24 | NRG              | W   | 0.547      | 0.303        | 0.049 (0.008)    | 0.446 (0.074)    | 0 (0.000) |    12.00 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |
|            2 |     2780 | 2024-11-24 | BLUEJAYS         | W   | 0.546      | 0.303        | 0.031 (0.005)    | 0.511 (0.085)    | 0 (0.000) |    14.35 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |
|            1 |     2838 | 2024-11-23 | Akimbo Esports   | W   | 0.539      | -            | -                | -                | -         |     1.33 | cJ-dA-K1nG, junior, nicx, Peeping, RUSH |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,187.87)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.547 | $4,000.00      | $2,187.87       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
