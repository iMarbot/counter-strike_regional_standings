### Roster Details<br />
Team Name: Rhyno Esports<br />
Roster: Ag1l, krazy, rafaxF, snapy, TMKj<br />
Global Rank: [228](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [159]( ../standings_europe.md)<br />
<br />
Final Rank Value:  693.4<br />
<br />
Final Rank Value (693.4) = Starting Rank Value (673.1) + Head To Head Adjustments (20.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.025[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 673.1
- 400 + ( ( 0.137 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 673.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     5544 | 2024-10-06 | Rhyno Esports           | L   | 0.217      | -            | -                | -                | -         |    -2.01 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           22 |     5628 | 2024-10-05 | Iberian Soul            | W   | 0.209      | 0.143        | 0.015 (0.000)    | 0.551 (0.016)    | 1 (0.209) |     4.57 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           21 |     5733 | 2024-10-03 | 3DMAX                   | L   | 0.198      | -            | -                | -                | -         |    -0.04 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           20 |     5868 | 2024-10-01 | CYBERSHOKE Esports      | W   | 0.184      | 0.435        | 0.011 (0.001)    | 1.000 (0.080)    | 0 (0.000) |     4.17 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           19 |     5992 | 2024-09-29 | FAVBET Team             | W   | 0.169      | 0.435        | 0.031 (0.002)    | 0.801 (0.059)    | 0 (0.000) |     3.72 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           18 |     6066 | 2024-09-28 | Rhyno Esports           | W   | 0.164      | 0.143        | 0.013 (0.000)    | 0.441 (0.010)    | 0 (0.000) |     3.73 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           17 |     6075 | 2024-09-28 | Mixzada                 | W   | 0.163      | 0.143        | 0.000 (0.000)    | 0.031 (0.001)    | 0 (0.000) |     2.02 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           16 |     6156 | 2024-09-27 | TALON                   | W   | 0.157      | 0.435        | 0.000 (0.000)    | 0.212 (0.014)    | 0 (0.000) |     1.67 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           15 |     6297 | 2024-09-25 | ALTERNATE aTTaX         | L   | 0.145      | -            | -                | -                | -         |    -0.88 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           14 |     6419 | 2024-09-24 | Monte                   | L   | 0.137      | -            | -                | -                | -         |    -0.89 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           13 |     6517 | 2024-09-22 | RUBY                    | W   | 0.125      | 0.143        | 0.003 (0.000)    | 0.201 (0.004)    | 0 (0.000) |     2.06 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           12 |     6610 | 2024-09-21 | QUAZAR                  | W   | 0.116      | 0.143        | 0.005 (0.000)    | 0.251 (0.004)    | 0 (0.000) |     1.98 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           11 |     6642 | 2024-09-20 | SQUAD (Portuguese team) | W   | 0.111      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.91 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           10 |     6700 | 2024-09-19 | Turritos                | W   | 0.105      | -            | -                | -                | 0 (0.000) |     0.60 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            9 |     6790 | 2024-09-18 | ENCE Academy            | W   | 0.096      | 0.143        | 0.009 (0.000)    | 0.649 (0.009)    | -         |     2.08 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            8 |     6848 | 2024-09-17 | Rhyno Youngsters        | L   | 0.091      | -            | -                | -                | -         |    -1.10 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            7 |     6857 | 2024-09-17 | Team Space              | L   | 0.090      | -            | -                | -                | -         |    -2.08 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            6 |     6898 | 2024-09-16 | EXSAD Gaming            | W   | 0.085      | -            | -                | -                | -         |     0.67 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            5 |     7324 | 2024-09-09 | QUAZAR                  | L   | 0.036      | -            | -                | -                | -         |    -0.52 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |
|            4 |     7360 | 2024-09-08 | Insilio                 | L   | 0.031      | -            | -                | -                | -         |    -0.47 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |
|            3 |     7551 | 2024-09-06 | Team Space              | W   | 0.015      | -            | -                | -                | -         |     0.13 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |
|            2 |     7689 | 2024-09-04 | Tricked Esport          | L   | 0.003      | -            | -                | -                | -         |    -0.03 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |
|            1 |     7699 | 2024-09-04 | JANO Esports            | L   | 0.002      | -            | -                | -                | -         |    -0.01 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($714.27)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-06 |      0.217 | $3,294.52      | $714.27         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
