### Roster Details<br />
Team Name: ShindeN<br />
Roster: abizz, BK1, ivz, nacho, roy<br />
Global Rank: [230](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  688.8<br />
<br />
Final Rank Value (688.8) = Starting Rank Value (721.4) + Head To Head Adjustments (-32.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.031[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.4
- 400 + ( ( 0.161 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 721.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      279 | 2025-02-17 | Yawara E-Sports         | L   | 1.000      | -            | -                | -                | -         |   -16.90 | abizz, BK1, ivz, nacho, roy      |
|           27 |      326 | 2025-02-16 | UNO MILLE               | L   | 1.000      | -            | -                | -                | -         |   -13.23 | abizz, BK1, ivz, nacho, roy      |
|           26 |      479 | 2025-02-14 | Game Hunters            | W   | 1.000      | 0.371        | 0.002 (0.001)    | 0.396 (0.147)    | 0 (0.000) |    14.09 | abizz, BK1, ivz, nacho, roy      |
|           25 |      555 | 2025-02-11 | Atrix Esports           | W   | 1.000      | 0.371        | 0.005 (0.002)    | 0.215 (0.080)    | 0 (0.000) |    14.31 | abizz, BK1, ivz, nacho, roy      |
|           24 |      742 | 2025-02-07 | Imperial Esports        | L   | 1.000      | -            | -                | -                | -         |    -4.58 | abizz, BK1, ivz, nacho, roy      |
|           23 |      934 | 2025-02-04 | Floripa Stars           | L   | 1.000      | -            | -                | -                | -         |   -19.49 | abizz, BK1, ivz, nacho, roy      |
|           22 |     1195 | 2025-01-10 | Legacy                  | L   | 0.868      | -            | -                | -                | -         |    -7.63 | abizz, BK1, ivz, relentless, roy |
|           21 |     1203 | 2025-01-09 | Patins da Ferrari       | W   | 0.861      | -            | -                | -                | 0 (0.000) |     8.00 | abizz, BK1, ivz, relentless, roy |
|           20 |     1549 | 2024-12-18 | Fake do Biru            | W   | 0.714      | 0.384        | -                | 0.292 (0.080)    | 0 (0.000) |     7.43 | abizz, BK1, ivz, relentless, roy |
|           19 |     1582 | 2024-12-16 | 9z Academy              | W   | 0.700      | 0.384        | 0.001 (0.000)    | 0.388 (0.104)    | 0 (0.000) |    10.47 | abizz, BK1, ivz, relentless, roy |
|           18 |     1687 | 2024-12-14 | América eSports         | W   | 0.687      | 0.384        | 0.000 (0.000)    | 0.429 (0.113)    | 0 (0.000) |     8.74 | abizz, BK1, ivz, relentless, roy |
|           17 |     2194 | 2024-12-04 | TROPA DO TACO           | L   | 0.622      | -            | -                | -                | -         |    -7.75 | abizz, BK1, ivz, relentless, roy |
|           16 |     2254 | 2024-12-03 | VELOX Argentina         | W   | 0.614      | 0.262        | 0.000 (0.000)    | 0.266 (0.043)    | 0 (0.000) |     6.80 | abizz, BK1, ivz, relentless, roy |
|           15 |     2472 | 2024-11-30 | AMIGOS (Brazilian team) | L   | 0.594      | -            | -                | -                | -         |   -13.77 | abizz, BK1, ivz, relentless, roy |
|           14 |     2753 | 2024-11-25 | 20/70                   | L   | 0.560      | -            | -                | -                | -         |   -10.36 | abizz, BK1, ivz, relentless, roy |
|           13 |     2941 | 2024-11-22 | VELOX Argentina         | L   | 0.541      | -            | -                | -                | -         |   -11.70 | abizz, BK1, ivz, relentless, roy |
|           12 |     3018 | 2024-11-21 | Nitro.GG                | L   | 0.533      | -            | -                | -                | -         |    -9.81 | abizz, BK1, ivz, relentless, roy |
|           11 |     3179 | 2024-11-18 | LaChampionsLiga         | W   | 0.514      | 0.371        | 0.003 (0.001)    | 0.444 (0.085)    | 0 (0.000) |     6.34 | abizz, BK1, ivz, relentless, roy |
|           10 |     3862 | 2024-11-06 | Hype Esports            | L   | 0.435      | -            | -                | -                | -         |    -7.92 | abizz, BK1, ivz, relentless, roy |
|            9 |     4028 | 2024-11-03 | MIBR Academy            | W   | 0.415      | 0.371        | 0.001 (0.000)    | 0.470 (0.072)    | 0 (0.000) |     5.83 | abizz, BK1, ivz, relentless, roy |
|            8 |     4109 | 2024-11-02 | VELOX Argentina         | W   | 0.407      | 0.371        | -                | 0.266 (0.040)    | -         |     4.36 | abizz, BK1, ivz, relentless, roy |
|            7 |     4234 | 2024-10-31 | TROPA DO TACO           | L   | 0.394      | -            | -                | -                | -         |    -6.54 | abizz, BK1, ivz, relentless, roy |
|            6 |     4427 | 2024-10-28 | 9z Academy              | W   | 0.373      | 0.371        | 0.001 (0.000)    | 0.388 (0.054)    | -         |     5.10 | abizz, BK1, ivz, relentless, roy |
|            5 |     5247 | 2024-10-11 | LaChampionsLiga         | W   | 0.262      | 0.143        | 0.003 (0.000)    | -                | 1 (0.262) |     3.62 | abizz, BK1, ivz, relentless, roy |
|            4 |     6176 | 2024-09-26 | Team Solid              | L   | 0.161      | -            | -                | -                | -         |    -1.80 | abizz, BK1, ivz, relentless, roy |
|            3 |     6496 | 2024-09-22 | LaChampionsLiga         | W   | 0.135      | 0.143        | 0.003 (0.000)    | -                | -         |     1.84 | abizz, BK1, ivz, relentless, roy |
|            2 |     6547 | 2024-09-21 | VELOX Argentina         | W   | 0.128      | -            | -                | -                | -         |     1.34 | abizz, BK1, ivz, relentless, roy |
|            1 |     6552 | 2024-09-21 | InFernales eSports      | W   | 0.127      | -            | -                | -                | -         |     0.57 | abizz, BK1, ivz, relentless, roy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,746.27)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-11 |      0.262 | $6,668.35      | $1,746.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
