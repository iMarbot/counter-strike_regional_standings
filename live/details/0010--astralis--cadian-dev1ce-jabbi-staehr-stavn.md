### Roster Details<br />
Team Name: Astralis<br />
Roster: cadiaN, dev1ce, jabbi, Staehr, stavn<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1707.3<br />
<br />
Final Rank Value (1707.3) = Starting Rank Value (1852.8) + Head To Head Adjustments (-145.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.823[<sup>1</sup>](#table2)
- Bounty Collected: 0.688[<sup>2</sup>](#table1)
- Opponent Network: 0.399[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.727<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1852.8
- 400 + ( ( 0.727 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1852.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      105 | 2025-02-23 | FaZe Clan       | W   | 1.000      | 1.000        | 0.744 (0.744)    | 0.482 (0.482)    | 1 (1.000) |    22.65 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           40 |      157 | 2025-02-22 | MOUZ            | L   | 1.000      | -            | -                | -                | -         |    -8.51 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           39 |      217 | 2025-02-21 | The MongolZ     | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.579 (0.579)    | 1 (1.000) |    25.05 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           38 |      250 | 2025-02-20 | HEROIC          | L   | 1.000      | -            | -                | -                | -         |   -29.67 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           37 |      270 | 2025-02-18 | BIG             | W   | 1.000      | 1.000        | 0.246 (0.246)    | 0.579 (0.579)    | 1 (1.000) |     4.38 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           36 |      303 | 2025-02-17 | MIBR            | W   | 1.000      | 1.000        | 0.141 (0.141)    | 0.471 (0.471)    | 1 (1.000) |     4.32 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           35 |      366 | 2025-02-16 | Team Falcons    | L   | 1.000      | -            | -                | -                | -         |   -10.94 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           34 |      411 | 2025-02-15 | SAW             | W   | 1.000      | 1.000        | 0.262 (0.262)    | 0.329 (0.329)    | 1 (1.000) |     2.21 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           33 |      483 | 2025-02-14 | PaiN Gaming     | L   | 1.000      | -            | -                | -                | -         |   -21.87 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           32 |      552 | 2025-02-11 | BetBoom Team    | W   | 1.000      | -            | -                | -                | -         |     0.92 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           31 |      560 | 2025-02-11 | Zero Tenacity   | W   | 1.000      | -            | -                | -                | -         |     0.29 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           30 |      587 | 2025-02-10 | BC.Game Esports | L   | 1.000      | -            | -                | -                | -         |   -30.55 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           29 |      596 | 2025-02-10 | OG              | W   | 1.000      | -            | -                | -                | -         |     0.33 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           28 |      630 | 2025-02-09 | PARIVISION      | W   | 1.000      | -            | -                | -                | -         |     0.18 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           27 |      635 | 2025-02-09 | 500             | W   | 1.000      | -            | -                | -                | -         |     0.80 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           26 |      710 | 2025-02-08 | 9INE            | W   | 1.000      | -            | -                | -                | -         |     0.33 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           25 |      996 | 2025-02-04 | GamerLegion     | L   | 1.000      | -            | -                | -                | -         |   -22.11 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           24 |     1024 | 2025-02-03 | FURIA           | W   | 1.000      | 1.000        | 0.094 (0.094)    | 0.384 (0.384)    | 1 (1.000) |     4.66 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           23 |     1040 | 2025-02-02 | Team Spirit     | L   | 1.000      | -            | -                | -                | -         |    -7.02 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           22 |     1089 | 2025-01-31 | PaiN Gaming     | W   | 1.000      | 1.000        | 0.318 (0.318)    | 0.555 (0.555)    | 1 (1.000) |     8.35 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           21 |     1100 | 2025-01-30 | FlyQuest        | W   | 0.999      | 1.000        | 0.105 (0.105)    | 0.239 (0.239)    | 1 (0.999) |     0.96 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           20 |     1111 | 2025-01-29 | MIBR            | L   | 0.992      | -            | -                | -                | -         |   -27.67 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           19 |     1157 | 2025-01-18 | Natus Vincere   | L   | 0.920      | -            | -                | -                | -         |   -18.09 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           18 |     1184 | 2025-01-15 | Wildcard        | W   | 0.898      | -            | -                | -                | -         |     1.95 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           17 |     2816 | 2024-11-23 | Passion UA      | L   | 0.550      | -            | -                | -                | -         |   -17.14 | br0, cadiaN, jabbi, Staehr, stavn    |
|           16 |     2906 | 2024-11-23 | Eternal Fire    | W   | 0.544      | -            | -                | -                | 1 (0.544) |     8.84 | br0, cadiaN, jabbi, Staehr, stavn    |
|           15 |     2992 | 2024-11-22 | B8              | W   | 0.538      | -            | -                | -                | 1 (0.538) |     0.37 | br0, cadiaN, jabbi, Staehr, stavn    |
|           14 |     3049 | 2024-11-21 | Sashi Esport    | L   | 0.532      | -            | -                | -                | -         |   -16.64 | br0, cadiaN, jabbi, Staehr, stavn    |
|           13 |     3064 | 2024-11-20 | 9Pandas         | L   | 0.530      | -            | -                | -                | -         |   -16.51 | br0, cadiaN, jabbi, Staehr, stavn    |
|           12 |     4145 | 2024-11-02 | Team Spirit     | L   | 0.405      | -            | -                | -                | -         |    -4.05 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           11 |     4262 | 2024-10-31 | MOUZ            | W   | 0.391      | 1.000        | 1.000 (0.391)    | 0.473 (0.185)    | -         |     8.53 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           10 |     4334 | 2024-10-29 | Natus Vincere   | W   | 0.383      | 1.000        | 0.555 (0.213)    | 0.478 (0.183)    | -         |     4.14 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            9 |     5347 | 2024-10-09 | Virtus.pro      | L   | 0.245      | -            | -                | -                | -         |    -5.73 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            8 |     5415 | 2024-10-08 | Team Falcons    | L   | 0.240      | -            | -                | -                | -         |    -3.07 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            7 |     5469 | 2024-10-07 | Eternal Fire    | W   | 0.233      | -            | -                | -                | -         |     4.11 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            6 |     6203 | 2024-09-26 | Team Spirit     | L   | 0.159      | -            | -                | -                | -         |    -1.55 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            5 |     6294 | 2024-09-25 | Team Vitality   | L   | 0.152      | -            | -                | -                | -         |    -1.96 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            4 |     7003 | 2024-09-14 | Complexity      | L   | 0.079      | -            | -                | -                | -         |    -2.43 | br0, dev1ce, jabbi, Staehr, stavn    |
|            3 |     7091 | 2024-09-13 | Rooster         | W   | 0.072      | -            | -                | -                | -         |     0.00 | br0, dev1ce, jabbi, Staehr, stavn    |
|            2 |     7189 | 2024-09-11 | Complexity      | L   | 0.059      | -            | -                | -                | -         |    -1.82 | br0, dev1ce, jabbi, Staehr, stavn    |
|            1 |     7256 | 2024-09-10 | Fnatic          | L   | 0.051      | -            | -                | -                | -         |    -1.59 | br0, dev1ce, jabbi, Staehr, stavn    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($204,996.39)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.61) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $150,000.00    | $150,000.00     |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-11-03 |      0.411 | $85,000.00     | $34,920.83      |
| 2024-10-13 |      0.273 | $5,000.00      | $1,363.89       |
| 2024-09-29 |      0.179 | $10,000.00     | $1,786.11       |
| 2024-09-22 |      0.132 | $7,000.00      | $925.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
