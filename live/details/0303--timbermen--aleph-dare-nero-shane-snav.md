### Roster Details<br />
Team Name: Timbermen<br />
Roster: aleph, dare, nero, shane, snav<br />
Global Rank: [303](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [60]( ../standings_americas.md)<br />
<br />
Final Rank Value:  647.5<br />
<br />
Final Rank Value (647.5) = Starting Rank Value (654.3) + Head To Head Adjustments (-6.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.279[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.010[<sup>2</sup>](#table1)

The average of these factors is 0.127<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.3
- 400 + ( ( 0.127 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 654.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     5044 | 2024-10-15 | Familia Maquininha  | L   | 0.280      | -            | -                | -                | -         |    -4.00 | aleph, dare, nero, shane, snav   |
|           20 |     5316 | 2024-10-09 | Vagrants            | W   | 0.240      | 0.477        | 0.001 (0.000)    | 0.276 (0.032)    | 0 (0.000) |     3.92 | aleph, dare, nero, shane, snav   |
|           19 |     5323 | 2024-10-09 | Vagrants            | L   | 0.240      | -            | -                | -                | -         |    -3.71 | aleph, dare, nero, shane, snav   |
|           18 |     5387 | 2024-10-08 | FLUFFY AIMERS       | W   | 0.234      | 0.477        | 0.005 (0.001)    | 0.213 (0.024)    | 0 (0.000) |     5.38 | aleph, dare, nero, shane, snav   |
|           17 |     5393 | 2024-10-08 | FLUFFY AIMERS       | L   | 0.233      | -            | -                | -                | -         |    -2.00 | aleph, dare, nero, shane, snav   |
|           16 |     5660 | 2024-10-04 | FLUFFY AIMERS       | L   | 0.206      | -            | -                | -                | -         |    -1.85 | aleph, dare, Fr3nk1e, nero, snav |
|           15 |     5706 | 2024-10-03 | Party Astronauts    | L   | 0.200      | -            | -                | -                | -         |    -2.08 | aleph, dare, nero, shane, snav   |
|           14 |     5712 | 2024-10-03 | Party Astronauts    | W   | 0.200      | 0.477        | 0.008 (0.001)    | 0.382 (0.036)    | 0 (0.000) |     4.28 | aleph, dare, nero, shane, snav   |
|           13 |     5901 | 2024-09-30 | Familia Maquininha  | W   | 0.179      | 0.371        | 0.003 (0.000)    | 0.202 (0.013)    | 0 (0.000) |     3.13 | aleph, dare, nero, shane, snav   |
|           12 |     6175 | 2024-09-26 | M80                 | L   | 0.154      | -            | -                | -                | -         |    -0.86 | aleph, dare, nero, shane, snav   |
|           11 |     6176 | 2024-09-26 | M80                 | L   | 0.153      | -            | -                | -                | -         |    -0.86 | aleph, dare, nero, shane, snav   |
|           10 |     6177 | 2024-09-26 | RazDva              | L   | 0.153      | -            | -                | -                | -         |    -3.48 | aleph, dare, nero, shane, snav   |
|            9 |     6347 | 2024-09-24 | NRG                 | L   | 0.140      | -            | -                | -                | -         |    -0.49 | aleph, dare, nero, shane, snav   |
|            8 |     6351 | 2024-09-24 | NRG                 | L   | 0.140      | -            | -                | -                | -         |    -0.49 | aleph, dare, nero, shane, snav   |
|            7 |     6434 | 2024-09-23 | Familia Maquininha  | L   | 0.134      | -            | -                | -                | -         |    -1.95 | aleph, dare, nero, shane, snav   |
|            6 |     6438 | 2024-09-23 | Familia Maquininha  | L   | 0.133      | -            | -                | -                | -         |    -1.97 | aleph, dare, nero, shane, snav   |
|            5 |     6558 | 2024-09-21 | BLUEJAYS            | L   | 0.120      | -            | -                | -                | -         |    -0.19 | dare, dea, intra, shane, snav    |
|            4 |     7337 | 2024-09-08 | Nouns Esports       | L   | 0.034      | -            | -                | -                | -         |    -0.43 | dare, dea, Peeping, shane, snav  |
|            3 |     7341 | 2024-09-08 | Bad News Capybaras  | W   | 0.033      | 0.333        | 0.000 (0.000)    | 0.113 (0.001)    | 1 (0.033) |     0.53 | dare, dea, Peeping, shane, snav  |
|            2 |     7392 | 2024-09-07 | BHOP Esports        | W   | 0.026      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 1 (0.026) |     0.16 | dare, dea, Peeping, shane, snav  |
|            1 |     7393 | 2024-09-07 | MMM (American team) | W   | 0.026      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.026) |     0.16 | dare, dea, Peeping, shane, snav  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($870.07)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.313 | $2,000.00      | $625.83         |
| 2024-10-05 |      0.214 | $750.00        | $160.21         |
| 2024-09-08 |      0.034 | $2,500.00      | $84.03          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
