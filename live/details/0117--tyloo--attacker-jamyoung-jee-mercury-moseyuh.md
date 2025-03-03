### Roster Details<br />
Team Name: TYLOO<br />
Roster: Attacker, JamYoung, Jee, Mercury, Moseyuh<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [13]( ../standings_asia.md)<br />
<br />
Final Rank Value:  808.6<br />
<br />
Final Rank Value (808.6) = Starting Rank Value (758.9) + Head To Head Adjustments (49.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.365[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.9
- 400 + ( ( 0.179 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 758.9


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
|           27 |      570 | 2025-02-11 | Lynn Vision Gaming      | L   | 1.000      | -            | -                | -                | -         |   -14.46 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           26 |      577 | 2025-02-11 | ATOX Esports            | L   | 1.000      | -            | -                | -                | -         |    -5.45 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           25 |      579 | 2025-02-10 | Rare Atom               | L   | 1.000      | -            | -                | -                | -         |    -9.13 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           24 |      727 | 2025-02-08 | DogEvil                 | W   | 1.000      | 0.143        | 0.024 (0.003)    | 0.895 (0.128)    | 0 (0.000) |    16.79 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           23 |      732 | 2025-02-08 | Harizma                 | W   | 1.000      | 0.143        | -                | 0.428 (0.061)    | 0 (0.000) |    14.15 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           22 |      811 | 2025-02-07 | The QUBE Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.80 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           21 |     2687 | 2024-11-27 | Lynn Vision Gaming      | W   | 0.564      | 0.143        | 0.017 (0.001)    | 0.365 (0.029)    | 0 (0.000) |    10.13 | aumaN, Jee, Mercury, Moseyuh, Starry      |
|           20 |     2695 | 2024-11-26 | Ex-GR Gaming            | W   | 0.562      | 0.143        | 0.012 (0.001)    | -                | 0 (0.000) |     6.82 | aumaN, Jee, Mercury, Moseyuh, Starry      |
|           19 |     2746 | 2024-11-26 | DogEvil                 | L   | 0.557      | -            | -                | -                | -         |    -8.82 | aumaN, Jee, Mercury, Moseyuh, Starry      |
|           18 |     2750 | 2024-11-26 | Teamwork (Chinese team) | W   | 0.556      | 0.143        | 0.032 (0.003)    | 0.136 (0.011)    | 0 (0.000) |     6.30 | aumaN, Jee, Mercury, Moseyuh, Starry      |
|           17 |     4102 | 2024-11-03 | Lynn Vision Gaming      | W   | 0.403      | 0.417        | 0.017 (0.003)    | 0.365 (0.061)    | 1 (0.403) |     7.77 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           16 |     4164 | 2024-11-02 | ATOX Esports            | W   | 0.396      | 0.417        | 0.008 (0.001)    | 0.059 (0.010)    | 0 (0.000) |     5.25 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           15 |     5026 | 2024-10-16 | Unsettled Resentment    | W   | 0.283      | 0.417        | 0.014 (0.002)    | 0.258 (0.030)    | 0 (0.000) |     4.05 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           14 |     5365 | 2024-10-09 | Lynn Vision Gaming      | L   | 0.237      | -            | -                | -                | -         |    -2.89 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           13 |     5371 | 2024-10-09 | Lynn Vision Gaming      | L   | 0.237      | -            | -                | -                | -         |    -2.94 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           12 |     5444 | 2024-10-08 | Ex-GR Gaming            | W   | 0.230      | 0.417        | 0.012 (0.001)    | -                | 0 (0.000) |     2.84 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           11 |     5450 | 2024-10-08 | Ex-GR Gaming            | W   | 0.230      | 0.417        | 0.012 (0.001)    | -                | -         |     2.89 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           10 |     5792 | 2024-10-02 | DEWA United             | W   | 0.190      | 0.417        | -                | 0.158 (0.013)    | -         |     1.26 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            9 |     5797 | 2024-10-02 | DEWA United             | W   | 0.190      | 0.417        | -                | 0.158 (0.013)    | -         |     1.27 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            8 |     5872 | 2024-10-01 | Nomads (Mongolian team) | W   | 0.183      | -            | -                | -                | -         |     1.93 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            7 |     5875 | 2024-10-01 | Nomads (Mongolian team) | W   | 0.183      | -            | -                | -                | -         |     1.95 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            6 |     5937 | 2024-09-30 | -72C                    | W   | 0.177      | -            | -                | -                | -         |     1.17 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            5 |     5938 | 2024-09-30 | -72C                    | W   | 0.177      | -            | -                | -                | -         |     1.18 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            4 |     6312 | 2024-09-25 | The QUBE Esports        | W   | 0.143      | -            | -                | -                | -         |     1.39 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            3 |     6318 | 2024-09-25 | The QUBE Esports        | W   | 0.143      | -            | -                | -                | -         |     1.40 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            2 |     6409 | 2024-09-24 | The Huns Esports        | L   | 0.137      | -            | -                | -                | -         |    -1.13 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            1 |     6417 | 2024-09-24 | The Huns Esports        | W   | 0.137      | 0.417        | 0.025 (0.001)    | 0.553 (0.031)    | -         |     3.20 | JamYoung, Jee, Mercury, Moseyuh, Starry   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,038.89)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.403 | $15,000.00     | $6,038.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
