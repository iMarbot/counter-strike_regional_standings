### Roster Details<br />
Team Name: TYLOO<br />
Roster: Attacker, JamYoung, Jee, Mercury, Moseyuh<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [13]( ../standings_asia.md)<br />
<br />
Final Rank Value:  810.2<br />
<br />
Final Rank Value (810.2) = Starting Rank Value (759.5) + Head To Head Adjustments (50.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.365[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.048[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 759.5
- 400 + ( ( 0.180 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 759.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |      558 | 2025-02-11 | Lynn Vision Gaming      | L   | 1.000      | -            | -                | -                | -         |   -14.49 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           26 |      565 | 2025-02-11 | ATOX Esports            | L   | 1.000      | -            | -                | -                | -         |    -5.41 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           25 |      567 | 2025-02-10 | Rare Atom               | L   | 1.000      | -            | -                | -                | -         |    -9.15 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           24 |      715 | 2025-02-08 | DogEvil                 | W   | 1.000      | 0.143        | 0.024 (0.003)    | 0.896 (0.128)    | 0 (0.000) |    16.74 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           23 |      720 | 2025-02-08 | Harizma                 | W   | 1.000      | 0.143        | -                | 0.433 (0.062)    | 0 (0.000) |    14.16 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           22 |      799 | 2025-02-07 | The QUBE Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.78 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           21 |     2675 | 2024-11-27 | Lynn Vision Gaming      | W   | 0.572      | 0.143        | 0.017 (0.001)    | 0.368 (0.030)    | 0 (0.000) |    10.27 | aumaN, Jee, Mercury, Moseyuh, Starry      |
|           20 |     2683 | 2024-11-26 | Ex-GR Gaming            | W   | 0.570      | 0.143        | 0.011 (0.001)    | -                | 0 (0.000) |     6.89 | aumaN, Jee, Mercury, Moseyuh, Starry      |
|           19 |     2734 | 2024-11-26 | DogEvil                 | L   | 0.565      | -            | -                | -                | -         |    -8.99 | aumaN, Jee, Mercury, Moseyuh, Starry      |
|           18 |     2738 | 2024-11-26 | Teamwork (Chinese team) | W   | 0.564      | 0.143        | 0.031 (0.003)    | 0.137 (0.011)    | 0 (0.000) |     6.34 | aumaN, Jee, Mercury, Moseyuh, Starry      |
|           17 |     4090 | 2024-11-03 | Lynn Vision Gaming      | W   | 0.411      | 0.417        | 0.017 (0.003)    | 0.368 (0.063)    | 1 (0.411) |     7.93 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           16 |     4152 | 2024-11-02 | ATOX Esports            | W   | 0.405      | 0.417        | 0.008 (0.001)    | 0.061 (0.010)    | 0 (0.000) |     5.36 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           15 |     5014 | 2024-10-16 | Unsettled Resentment    | W   | 0.291      | 0.417        | 0.013 (0.002)    | 0.259 (0.032)    | 0 (0.000) |     4.16 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           14 |     5353 | 2024-10-09 | Lynn Vision Gaming      | L   | 0.245      | -            | -                | -                | -         |    -2.99 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           13 |     5359 | 2024-10-09 | Lynn Vision Gaming      | L   | 0.245      | -            | -                | -                | -         |    -3.05 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           12 |     5432 | 2024-10-08 | Ex-GR Gaming            | W   | 0.238      | 0.417        | 0.011 (0.001)    | -                | 0 (0.000) |     2.93 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           11 |     5438 | 2024-10-08 | Ex-GR Gaming            | W   | 0.238      | 0.417        | 0.011 (0.001)    | -                | -         |     2.98 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           10 |     5780 | 2024-10-02 | DEWA United             | W   | 0.198      | 0.417        | -                | 0.161 (0.013)    | -         |     1.31 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            9 |     5785 | 2024-10-02 | DEWA United             | W   | 0.198      | 0.417        | -                | 0.161 (0.013)    | -         |     1.32 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            8 |     5860 | 2024-10-01 | Nomads (Mongolian team) | W   | 0.192      | -            | -                | -                | -         |     2.01 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            7 |     5863 | 2024-10-01 | Nomads (Mongolian team) | W   | 0.191      | -            | -                | -                | -         |     2.04 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            6 |     5925 | 2024-09-30 | -72C                    | W   | 0.185      | -            | -                | -                | -         |     1.21 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            5 |     5926 | 2024-09-30 | -72C                    | W   | 0.185      | -            | -                | -                | -         |     1.23 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            4 |     6300 | 2024-09-25 | The QUBE Esports        | W   | 0.152      | -            | -                | -                | -         |     1.46 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            3 |     6306 | 2024-09-25 | The QUBE Esports        | W   | 0.151      | -            | -                | -                | -         |     1.48 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            2 |     6397 | 2024-09-24 | The Huns Esports        | L   | 0.145      | -            | -                | -                | -         |    -1.19 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            1 |     6405 | 2024-09-24 | The Huns Esports        | W   | 0.145      | 0.417        | 0.025 (0.001)    | 0.557 (0.034)    | -         |     3.40 | JamYoung, Jee, Mercury, Moseyuh, Starry   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,161.81)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.411 | $15,000.00     | $6,161.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
