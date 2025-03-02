### Roster Details<br />
Team Name: Rhyno Esports<br />
Roster: Ag1l, krazy, rafaxF, snapy, TMKj<br />
Global Rank: [220](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [157]( ../standings_europe.md)<br />
<br />
Final Rank Value:  695.5<br />
<br />
Final Rank Value (695.5) = Starting Rank Value (674.5) + Head To Head Adjustments (21.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.025[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.5
- 400 + ( ( 0.137 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 674.5


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
|           23 |     5532 | 2024-10-06 | Rhyno Esports           | L   | 0.225      | -            | -                | -                | -         |    -2.08 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           22 |     5616 | 2024-10-05 | Iberian Soul            | W   | 0.218      | 0.143        | 0.015 (0.000)    | 0.553 (0.017)    | 1 (0.218) |     4.74 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           21 |     5721 | 2024-10-03 | 3DMAX                   | L   | 0.206      | -            | -                | -                | -         |    -0.04 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           20 |     5856 | 2024-10-01 | CYBERSHOKE Esports      | W   | 0.192      | 0.435        | 0.011 (0.001)    | 1.000 (0.083)    | 0 (0.000) |     4.35 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           19 |     5980 | 2024-09-29 | FAVBET Team             | W   | 0.178      | 0.435        | 0.032 (0.002)    | 0.814 (0.063)    | 0 (0.000) |     3.90 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           18 |     6054 | 2024-09-28 | Rhyno Esports           | W   | 0.172      | 0.143        | 0.013 (0.000)    | 0.447 (0.011)    | 0 (0.000) |     3.92 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           17 |     6063 | 2024-09-28 | Mixzada                 | W   | 0.171      | 0.143        | 0.000 (0.000)    | 0.032 (0.001)    | 0 (0.000) |     2.11 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           16 |     6144 | 2024-09-27 | TALON                   | W   | 0.165      | 0.435        | 0.000 (0.000)    | 0.214 (0.015)    | 0 (0.000) |     1.76 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           15 |     6285 | 2024-09-25 | ALTERNATE aTTaX         | L   | 0.153      | -            | -                | -                | -         |    -0.93 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           14 |     6407 | 2024-09-24 | Monte                   | L   | 0.145      | -            | -                | -                | -         |    -0.94 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           13 |     6505 | 2024-09-22 | RUBY                    | W   | 0.133      | 0.143        | 0.003 (0.000)    | 0.204 (0.004)    | 0 (0.000) |     2.20 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           12 |     6598 | 2024-09-21 | QUAZAR                  | W   | 0.124      | 0.143        | 0.005 (0.000)    | 0.257 (0.005)    | 0 (0.000) |     2.12 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           11 |     6630 | 2024-09-20 | SQUAD (Portuguese team) | W   | 0.119      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     0.98 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|           10 |     6688 | 2024-09-19 | Turritos                | W   | 0.113      | -            | -                | -                | 0 (0.000) |     0.64 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            9 |     6778 | 2024-09-18 | ENCE Academy            | W   | 0.104      | 0.143        | 0.009 (0.000)    | 0.655 (0.010)    | -         |     2.26 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            8 |     6836 | 2024-09-17 | Rhyno Youngsters        | L   | 0.099      | -            | -                | -                | -         |    -1.20 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            7 |     6845 | 2024-09-17 | Team Space              | L   | 0.098      | -            | -                | -                | -         |    -2.27 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            6 |     6886 | 2024-09-16 | EXSAD Gaming            | W   | 0.093      | -            | -                | -                | -         |     0.73 | Ag1l, krazy, rafaxF, snapy, TMKj     |
|            5 |     7312 | 2024-09-09 | QUAZAR                  | L   | 0.045      | -            | -                | -                | -         |    -0.64 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |
|            4 |     7348 | 2024-09-08 | Insilio                 | L   | 0.039      | -            | -                | -                | -         |    -0.59 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |
|            3 |     7539 | 2024-09-06 | Team Space              | W   | 0.024      | 0.435        | -                | 0.023 (0.000)    | -         |     0.20 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |
|            2 |     7677 | 2024-09-04 | Tricked Esport          | L   | 0.011      | -            | -                | -                | -         |    -0.10 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |
|            1 |     7687 | 2024-09-04 | JANO Esports            | L   | 0.010      | -            | -                | -                | -         |    -0.07 | Ag1l, krazy, NOPEEj, P3R3IIRA, snapy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($741.27)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-06 |      0.225 | $3,294.52      | $741.27         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
