### Roster Details<br />
Team Name: ESC Gaming<br />
Roster: AMSALEM, bajmi, maaryy, mASKED, SaMey<br />
Global Rank: [354](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [229]( ../standings_europe.md)<br />
<br />
Final Rank Value:  623.6<br />
<br />
Final Rank Value (623.6) = Starting Rank Value (561.7) + Head To Head Adjustments (61.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.081<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 561.7
- 400 + ( ( 0.081 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 561.7


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
|           15 |       10 | 2025-02-28 | Tricked Esport        | L   | 1.000      | -            | -                | -                | -         |    -6.25 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           14 |       38 | 2025-02-25 | OG                    | L   | 1.000      | -            | -                | -                | -         |    -3.85 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           13 |       67 | 2025-02-24 | Ninjas in Pyjamas     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.606 (0.087)    | 0 (0.000) |    21.88 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           12 |       94 | 2025-02-23 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |    -5.30 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           11 |      137 | 2025-02-22 | Fire Flux Esports     | L   | 1.000      | -            | -                | -                | -         |    -4.74 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|           10 |      203 | 2025-02-21 | Rebels Gaming         | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.301 (0.043)    | 0 (0.000) |    21.35 | AMSALEM, bajmi, maaryy, mASKED, SaMey    |
|            9 |     1377 | 2024-12-23 | WOPA Esport           | L   | 0.745      | -            | -                | -                | -         |    -4.22 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            8 |     1407 | 2024-12-22 | Astralis Talent       | W   | 0.738      | 0.333        | 0.002 (0.001)    | 0.733 (0.180)    | 0 (0.000) |    17.12 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            7 |     1547 | 2024-12-19 | ENCE Academy          | L   | 0.718      | -            | -                | -                | -         |    -5.05 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            6 |     1562 | 2024-12-18 | WOPA Esport           | W   | 0.711      | 0.333        | 0.031 (0.007)    | 0.785 (0.186)    | 0 (0.000) |    18.14 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            5 |     1574 | 2024-12-17 | Viperio               | W   | 0.705      | 0.333        | 0.002 (0.000)    | 0.411 (0.097)    | 0 (0.000) |    16.36 | AMSALEM, maaryy, mASKED, shushan, tomiko |
|            4 |     1636 | 2024-12-15 | SemperFi Esports      | W   | 0.692      | 0.333        | 0.000 (0.000)    | 0.665 (0.153)    | 0 (0.000) |    11.05 | AMSALEM, maaryy, mASKED, shushan, tein   |
|            3 |     1702 | 2024-12-14 | G2 Ares               | L   | 0.686      | -            | -                | -                | -         |    -6.86 | AMSALEM, maaryy, mASKED, tomiko, znxxX   |
|            2 |     1898 | 2024-12-11 | Viperio               | L   | 0.664      | -            | -                | -                | -         |    -5.46 | AMSALEM, maaryy, mASKED, tein, znxxX     |
|            1 |     1917 | 2024-12-10 | ALASKA                | L   | 0.660      | -            | -                | -                | -         |    -2.26 | AMSALEM, maaryy, mASKED, tomiko, znxxX   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
