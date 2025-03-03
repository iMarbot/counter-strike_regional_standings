### Roster Details<br />
Team Name: ESC Gaming<br />
Roster: AMSALEM, bajmi, maaryy, mASKED, SaMey<br />
Global Rank: [356](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [227]( ../standings_europe.md)<br />
<br />
Final Rank Value:  622.4<br />
<br />
Final Rank Value (622.4) = Starting Rank Value (561.2) + Head To Head Adjustments (61.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.081<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 561.2
- 400 + ( ( 0.081 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 561.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |       25 | 2025-02-28 | Tricked Esport        | L   | 1.000      | -            | -                | -                | -         |    -6.26 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           14 |       53 | 2025-02-25 | OG                    | L   | 1.000      | -            | -                | -                | -         |    -3.85 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           13 |       82 | 2025-02-24 | Ninjas in Pyjamas     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.607 (0.087)    | 0 (0.000) |    21.89 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           12 |      109 | 2025-02-23 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |    -5.31 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           11 |      152 | 2025-02-22 | Fire Flux Esports     | L   | 1.000      | -            | -                | -                | -         |    -4.75 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           10 |      215 | 2025-02-21 | Rebels Gaming         | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.298 (0.043)    | 0 (0.000) |    21.33 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|            9 |     1389 | 2024-12-23 | WOPA Esport           | L   | 0.737      | -            | -                | -                | -         |    -4.20 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            8 |     1419 | 2024-12-22 | Astralis Talent       | W   | 0.730      | 0.333        | 0.002 (0.001)    | 0.724 (0.176)    | 0 (0.000) |    16.89 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            7 |     1559 | 2024-12-19 | ENCE Academy          | L   | 0.709      | -            | -                | -                | -         |    -5.00 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            6 |     1574 | 2024-12-18 | WOPA Esport           | W   | 0.703      | 0.333        | 0.032 (0.007)    | 0.777 (0.182)    | 0 (0.000) |    17.93 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            5 |     1586 | 2024-12-17 | Viperio               | W   | 0.697      | 0.333        | 0.002 (0.000)    | 0.404 (0.094)    | 0 (0.000) |    16.13 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            4 |     1648 | 2024-12-15 | SemperFi Esports      | W   | 0.683      | 0.333        | 0.000 (0.000)    | 0.666 (0.152)    | 0 (0.000) |    10.92 | AMSALEM, maaryy, mASKED, shushan, tein   |
|            3 |     1714 | 2024-12-14 | G2 Ares               | L   | 0.678      | -            | -                | -                | -         |    -6.80 | AMSALEM, maaryy, mASKED, tomiko, znxxX   |
|            2 |     1910 | 2024-12-11 | Viperio               | L   | 0.656      | -            | -                | -                | -         |    -5.44 | AMSALEM, maaryy, mASKED, tein, znxxX     |
|            1 |     1929 | 2024-12-10 | ALASKA                | L   | 0.652      | -            | -                | -                | -         |    -2.19 | AMSALEM, maaryy, mASKED, tomiko, znxxX   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
