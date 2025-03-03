### Roster Details<br />
Team Name: DogEvil<br />
Roster: B1NGO, BZA, lan, Roninbaby, TiGeR<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  887.6<br />
<br />
Final Rank Value (887.6) = Starting Rank Value (778.2) + Head To Head Adjustments (109.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.381[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.2
- 400 + ( ( 0.189 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 778.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       32 | 2025-02-27 | Shika                    | W   | 1.000      | 0.143        | -                | 0.375 (0.054)    | 0 (0.000) |     6.12 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           33 |       34 | 2025-02-26 | Change The Game          | W   | 1.000      | 0.143        | 0.061 (0.009)    | -                | 0 (0.000) |     9.02 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           32 |       45 | 2025-02-25 | Unsettled Resentment     | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.258 (0.037)    | 0 (0.000) |    10.35 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           31 |       58 | 2025-02-25 | Rare Atom                | L   | 1.000      | -            | -                | -                | -         |   -10.42 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           30 |       85 | 2025-02-23 | FengDa Gaming            | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.550 (0.079)    | 0 (0.000) |     8.93 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           29 |      316 | 2025-02-17 | Boring Players           | W   | 1.000      | 0.143        | -                | 0.344 (0.049)    | 0 (0.000) |     4.84 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           28 |      321 | 2025-02-17 | LaiShanHui               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.54 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           27 |      325 | 2025-02-16 | Steel Helmet             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.40 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           26 |      336 | 2025-02-16 | NEVERMIND (Chinese team) | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.33 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           25 |      616 | 2025-02-09 | Rare Atom                | L   | 1.000      | -            | -                | -                | -         |   -10.26 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           24 |      619 | 2025-02-09 | JiJieHao                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.05 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           23 |      661 | 2025-02-08 | Housebets                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.36 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           22 |      727 | 2025-02-08 | TYLOO                    | L   | 1.000      | -            | -                | -                | -         |   -16.79 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           21 |      731 | 2025-02-08 | THE (Russian team)       | W   | 1.000      | 0.143        | -                | 0.357 (0.051)    | -         |     9.95 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           20 |      737 | 2025-02-07 | Rare Atom                | L   | 1.000      | -            | -                | -                | -         |   -10.99 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           19 |      807 | 2025-02-07 | JiJieHao                 | W   | 1.000      | -            | -                | -                | -         |     7.91 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           18 |      857 | 2025-02-06 | Believe.                 | W   | 1.000      | -            | -                | -                | -         |     4.74 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           17 |      863 | 2025-02-06 | FengDa Gaming            | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.550 (0.079)    | -         |    11.63 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           16 |      869 | 2025-02-06 | 14 blades                | W   | 1.000      | -            | -                | -                | -         |     2.70 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           15 |      875 | 2025-02-05 | XNL Gaming               | W   | 1.000      | -            | -                | -                | -         |     2.53 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           14 |     1244 | 2024-12-30 | Unsettled Resentment     | L   | 0.789      | -            | -                | -                | -         |   -15.90 | B1NGO, BZA, Cate, lan, Roninbaby   |
|           13 |     1253 | 2024-12-30 | Rare Atom                | L   | 0.783      | -            | -                | -                | -         |    -8.04 | B1NGO, BZA, Cate, lan, Roninbaby   |
|           12 |     1257 | 2024-12-29 | ATOX Esports             | W   | 0.782      | 0.396        | 0.064 (0.020)    | 0.601 (0.186)    | -         |    20.12 | B1NGO, BZA, Cate, lan, Roninbaby   |
|           11 |     1275 | 2024-12-29 | Unsettled Resentment     | W   | 0.776      | 0.396        | 0.014 (0.004)    | 0.258 (0.079)    | -         |     9.14 | B1NGO, BZA, Cate, lan, Roninbaby   |
|           10 |     1319 | 2024-12-28 | Bromo                    | W   | 0.770      | 0.396        | 0.016 (0.005)    | 0.140 (0.043)    | -         |     8.83 | B1NGO, BZA, Cate, lan, Roninbaby   |
|            9 |     1350 | 2024-12-27 | Lynn Vision Gaming       | L   | 0.762      | -            | -                | -                | -         |   -11.38 | B1NGO, BZA, Cate, lan, Roninbaby   |
|            8 |     2153 | 2024-12-06 | ATOX Esports             | L   | 0.622      | -            | -                | -                | -         |    -3.66 | BZA, Cate, lan, Roninbaby, twy     |
|            7 |     2191 | 2024-12-05 | Harizma                  | W   | 0.616      | 0.333        | -                | 0.428 (0.088)    | -         |     8.19 | BZA, Cate, lan, Roninbaby, twy     |
|            6 |     2197 | 2024-12-04 | Ex-GR Gaming             | W   | 0.615      | 0.333        | 0.012 (0.002)    | -                | -         |     6.49 | BZA, Cate, lan, Roninbaby, twy     |
|            5 |     2307 | 2024-12-02 | Flashback Gaming         | W   | 0.602      | -            | -                | -                | -         |     9.52 | BZA, Cate, lan, Roninbaby, twy     |
|            4 |     2310 | 2024-12-02 | DEWA United              | W   | 0.602      | -            | -                | -                | -         |     4.39 | BZA, Cate, lan, Roninbaby, twy     |
|            3 |     2315 | 2024-12-02 | Harizma                  | W   | 0.602      | -            | -                | -                | -         |     7.56 | BZA, Cate, lan, Roninbaby, twy     |
|            2 |     2746 | 2024-11-26 | TYLOO                    | W   | 0.557      | 0.143        | 0.018 (0.001)    | -                | -         |     8.82 | BZA, Cate, lan, Roninbaby, twy     |
|            1 |     2747 | 2024-11-26 | Lynn Vision Gaming       | W   | 0.556      | 0.143        | 0.017 (0.001)    | -                | -         |    10.44 | BZA, Cate, lan, Roninbaby, twy     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,831.94)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.783 | $10,000.00     | $7,831.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
