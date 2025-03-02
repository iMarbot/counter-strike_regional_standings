### Roster Details<br />
Team Name: DogEvil<br />
Roster: B1NGO, BZA, lan, Roninbaby, TiGeR<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  888.1<br />
<br />
Final Rank Value (888.1) = Starting Rank Value (777.8) + Head To Head Adjustments (110.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.380[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.8
- 400 + ( ( 0.189 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 777.8


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
|           34 |       17 | 2025-02-27 | Shika                    | W   | 1.000      | 0.143        | -                | 0.374 (0.053)    | 0 (0.000) |     6.11 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           33 |       19 | 2025-02-26 | Change The Game          | W   | 1.000      | 0.143        | 0.061 (0.009)    | -                | 0 (0.000) |     8.97 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           32 |       30 | 2025-02-25 | Unsettled Resentment     | W   | 1.000      | 0.143        | 0.013 (0.002)    | -                | 0 (0.000) |    10.33 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           31 |       43 | 2025-02-25 | Rare Atom                | L   | 1.000      | -            | -                | -                | -         |   -10.40 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           30 |       70 | 2025-02-23 | FengDa Gaming            | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.553 (0.079)    | 0 (0.000) |     8.92 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           29 |      304 | 2025-02-17 | Boring Players           | W   | 1.000      | 0.143        | -                | 0.344 (0.049)    | 0 (0.000) |     4.83 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           28 |      309 | 2025-02-17 | LaiShanHui               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.53 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           27 |      313 | 2025-02-16 | Steel Helmet             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.38 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           26 |      324 | 2025-02-16 | NEVERMIND (Chinese team) | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.33 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           25 |      604 | 2025-02-09 | Rare Atom                | L   | 1.000      | -            | -                | -                | -         |   -10.25 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           24 |      607 | 2025-02-09 | JiJieHao                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.05 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           23 |      649 | 2025-02-08 | Housebets                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.34 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           22 |      715 | 2025-02-08 | TYLOO                    | L   | 1.000      | -            | -                | -                | -         |   -16.74 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           21 |      719 | 2025-02-08 | THE (Russian team)       | W   | 1.000      | 0.143        | -                | 0.360 (0.051)    | -         |     9.94 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           20 |      725 | 2025-02-07 | Rare Atom                | L   | 1.000      | -            | -                | -                | -         |   -10.97 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           19 |      795 | 2025-02-07 | JiJieHao                 | W   | 1.000      | -            | -                | -                | -         |     7.92 | B1NGO, BZA, lan, Roninbaby, TiGeR  |
|           18 |      845 | 2025-02-06 | Believe.                 | W   | 1.000      | -            | -                | -                | -         |     4.72 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           17 |      851 | 2025-02-06 | FengDa Gaming            | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.553 (0.079)    | -         |    11.61 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           16 |      857 | 2025-02-06 | 14 blades                | W   | 1.000      | -            | -                | -                | -         |     2.69 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           15 |      863 | 2025-02-05 | XNL Gaming               | W   | 1.000      | -            | -                | -                | -         |     2.52 | B1NGO, BZA, heartZ, lan, Roninbaby |
|           14 |     1232 | 2024-12-30 | Unsettled Resentment     | L   | 0.797      | -            | -                | -                | -         |   -16.08 | B1NGO, BZA, Cate, lan, Roninbaby   |
|           13 |     1241 | 2024-12-30 | Rare Atom                | L   | 0.791      | -            | -                | -                | -         |    -8.12 | B1NGO, BZA, Cate, lan, Roninbaby   |
|           12 |     1245 | 2024-12-29 | ATOX Esports             | W   | 0.790      | 0.396        | 0.064 (0.020)    | 0.604 (0.189)    | -         |    20.38 | B1NGO, BZA, Cate, lan, Roninbaby   |
|           11 |     1263 | 2024-12-29 | Unsettled Resentment     | W   | 0.784      | 0.396        | 0.013 (0.004)    | 0.259 (0.081)    | -         |     9.23 | B1NGO, BZA, Cate, lan, Roninbaby   |
|           10 |     1307 | 2024-12-28 | Bromo                    | W   | 0.778      | 0.396        | 0.016 (0.005)    | 0.141 (0.044)    | -         |     8.90 | B1NGO, BZA, Cate, lan, Roninbaby   |
|            9 |     1338 | 2024-12-27 | Lynn Vision Gaming       | L   | 0.771      | -            | -                | -                | -         |   -11.48 | B1NGO, BZA, Cate, lan, Roninbaby   |
|            8 |     2141 | 2024-12-06 | ATOX Esports             | L   | 0.631      | -            | -                | -                | -         |    -3.66 | BZA, Cate, lan, Roninbaby, twy     |
|            7 |     2179 | 2024-12-05 | Harizma                  | W   | 0.624      | 0.333        | -                | 0.433 (0.090)    | -         |     8.33 | BZA, Cate, lan, Roninbaby, twy     |
|            6 |     2185 | 2024-12-04 | Ex-GR Gaming             | W   | 0.623      | 0.333        | 0.011 (0.002)    | -                | -         |     6.58 | BZA, Cate, lan, Roninbaby, twy     |
|            5 |     2295 | 2024-12-02 | Flashback Gaming         | W   | 0.611      | -            | -                | -                | -         |     9.64 | BZA, Cate, lan, Roninbaby, twy     |
|            4 |     2298 | 2024-12-02 | DEWA United              | W   | 0.610      | -            | -                | -                | -         |     4.48 | BZA, Cate, lan, Roninbaby, twy     |
|            3 |     2303 | 2024-12-02 | Harizma                  | W   | 0.610      | 0.143        | -                | 0.433 (0.038)    | -         |     7.69 | BZA, Cate, lan, Roninbaby, twy     |
|            2 |     2734 | 2024-11-26 | TYLOO                    | W   | 0.565      | 0.143        | 0.018 (0.001)    | -                | -         |     8.99 | BZA, Cate, lan, Roninbaby, twy     |
|            1 |     2735 | 2024-11-26 | Lynn Vision Gaming       | W   | 0.564      | 0.143        | 0.017 (0.001)    | -                | -         |    10.63 | BZA, Cate, lan, Roninbaby, twy     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,913.89)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.791 | $10,000.00     | $7,913.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
