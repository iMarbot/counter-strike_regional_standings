### Roster Details<br />
Team Name: Timbermen<br />
Roster: dare, dea, nosraC, shane, snav<br />
Global Rank: [142](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [27]( ../standings_americas.md)<br />
<br />
Final Rank Value:  770.1<br />
<br />
Final Rank Value (770.1) = Starting Rank Value (728.6) + Head To Head Adjustments (41.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.338[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 728.6
- 400 + ( ( 0.164 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 728.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     1602 | 2024-12-15 | NRG                 | W   | 0.695      | 0.303        | 0.049 (0.010)    | 0.444 (0.094)    | 0 (0.000) |    17.84 | dare, dea, nosraC, shane, snav  |
|           24 |     1606 | 2024-12-15 | Nouns Esports       | W   | 0.695      | 0.303        | 0.007 (0.001)    | 0.328 (0.069)    | 0 (0.000) |    14.55 | dare, dea, nosraC, shane, snav  |
|           23 |     1653 | 2024-12-14 | BOSS                | W   | 0.689      | 0.303        | 0.014 (0.003)    | 0.327 (0.068)    | 0 (0.000) |    15.77 | dare, dea, nosraC, shane, snav  |
|           22 |     2771 | 2024-11-24 | NRG                 | L   | 0.554      | -            | -                | -                | -         |    -3.05 | dare, dea, nosraC, shane, snav  |
|           21 |     2822 | 2024-11-23 | Party Astronauts    | W   | 0.548      | 0.303        | 0.008 (0.001)    | 0.385 (0.064)    | 0 (0.000) |    10.54 | dare, dea, nosraC, shane, snav  |
|           20 |     5032 | 2024-10-15 | Familia Maquininha  | L   | 0.288      | -            | -                | -                | -         |    -4.88 | aleph, dare, nero, shane, snav  |
|           19 |     5304 | 2024-10-09 | Vagrants            | W   | 0.249      | 0.477        | 0.001 (0.000)    | 0.278 (0.033)    | 0 (0.000) |     3.31 | aleph, dare, nero, shane, snav  |
|           18 |     5311 | 2024-10-09 | Vagrants            | L   | 0.248      | -            | -                | -                | -         |    -4.60 | aleph, dare, nero, shane, snav  |
|           17 |     5375 | 2024-10-08 | FLUFFY AIMERS       | W   | 0.242      | 0.477        | 0.005 (0.001)    | 0.228 (0.026)    | 0 (0.000) |     4.87 | aleph, dare, nero, shane, snav  |
|           16 |     5381 | 2024-10-08 | FLUFFY AIMERS       | L   | 0.242      | -            | -                | -                | -         |    -2.79 | aleph, dare, nero, shane, snav  |
|           15 |     5694 | 2024-10-03 | Party Astronauts    | L   | 0.209      | -            | -                | -                | -         |    -2.77 | aleph, dare, nero, shane, snav  |
|           14 |     5700 | 2024-10-03 | Party Astronauts    | W   | 0.208      | 0.477        | 0.008 (0.001)    | 0.385 (0.038)    | 0 (0.000) |     3.85 | aleph, dare, nero, shane, snav  |
|           13 |     5889 | 2024-09-30 | Familia Maquininha  | W   | 0.188      | 0.371        | 0.003 (0.000)    | 0.205 (0.014)    | -         |     2.75 | aleph, dare, nero, shane, snav  |
|           12 |     6163 | 2024-09-26 | M80                 | L   | 0.162      | -            | -                | -                | -         |    -1.22 | aleph, dare, nero, shane, snav  |
|           11 |     6164 | 2024-09-26 | M80                 | L   | 0.162      | -            | -                | -                | -         |    -1.23 | aleph, dare, nero, shane, snav  |
|           10 |     6165 | 2024-09-26 | RazDva              | L   | 0.161      | -            | -                | -                | -         |    -4.00 | aleph, dare, nero, shane, snav  |
|            9 |     6335 | 2024-09-24 | NRG                 | L   | 0.149      | -            | -                | -                | -         |    -0.74 | aleph, dare, nero, shane, snav  |
|            8 |     6339 | 2024-09-24 | NRG                 | L   | 0.148      | -            | -                | -                | -         |    -0.74 | aleph, dare, nero, shane, snav  |
|            7 |     6422 | 2024-09-23 | Familia Maquininha  | L   | 0.142      | -            | -                | -                | -         |    -2.48 | aleph, dare, nero, shane, snav  |
|            6 |     6426 | 2024-09-23 | Familia Maquininha  | L   | 0.142      | -            | -                | -                | -         |    -2.50 | aleph, dare, nero, shane, snav  |
|            5 |     6546 | 2024-09-21 | BOSS                | L   | 0.128      | -            | -                | -                | -         |    -1.08 | dare, dea, intra, shane, snav   |
|            4 |     7325 | 2024-09-08 | Nouns Esports       | L   | 0.042      | -            | -                | -                | -         |    -0.67 | dare, dea, Peeping, shane, snav |
|            3 |     7329 | 2024-09-08 | Bad News Capybaras  | W   | 0.041      | 0.333        | 0.001 (0.000)    | 0.115 (0.002)    | 1 (0.041) |     0.53 | dare, dea, Peeping, shane, snav |
|            2 |     7380 | 2024-09-07 | BHOP Esports        | W   | 0.035      | 0.333        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.035) |     0.15 | dare, dea, Peeping, shane, snav |
|            1 |     7381 | 2024-09-07 | MMM (American team) | W   | 0.034      | -            | -                | -                | 1 (0.034) |     0.15 | dare, dea, Peeping, shane, snav |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,694.76)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.695 | $4,000.00      | $2,781.67       |
| 2024-10-20 |      0.321 | $2,000.00      | $642.22         |
| 2024-10-05 |      0.222 | $750.00        | $166.35         |
| 2024-09-08 |      0.042 | $2,500.00      | $104.51         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
