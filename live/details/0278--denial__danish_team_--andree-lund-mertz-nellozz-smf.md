### Roster Details<br />
Team Name: Denial (Danish team)<br />
Roster: Andree, lund, mertz, nellozz, smF<br />
Global Rank: [278](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [188]( ../standings_europe.md)<br />
<br />
Final Rank Value:  662.8<br />
<br />
Final Rank Value (662.8) = Starting Rank Value (643.7) + Head To Head Adjustments (19.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.254[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 643.7
- 400 + ( ( 0.122 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 643.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     2901 | 2024-11-23 | Astralis Talent           | L   | 0.537      | -            | -                | -                | -         |    -5.49 | Andree, lund, mertz, nellozz, smF  |
|           16 |     3441 | 2024-11-14 | XI Esport                 | W   | 0.479      | 0.143        | 0.001 (0.000)    | 0.282 (0.019)    | 0 (0.000) |     8.00 | Andree, lund, mertz, nellozz, smF  |
|           15 |     3460 | 2024-11-14 | WOPA Esport               | L   | 0.478      | -            | -                | -                | -         |    -4.12 | Andree, J3nsyy, lund, nellozz, smF |
|           14 |     3596 | 2024-11-11 | Preasy Esport             | W   | 0.459      | 0.143        | 0.012 (0.001)    | 0.701 (0.046)    | 0 (0.000) |     9.26 | Andree, lund, mertz, nellozz, smF  |
|           13 |     3608 | 2024-11-11 | XI Esport                 | L   | 0.459      | -            | -                | -                | -         |   -10.06 | Andree, lund, mertz, nellozz, smF  |
|           12 |     3613 | 2024-11-11 | Copenhagen Wolves Academy | W   | 0.458      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.52 | Andree, lund, mertz, nellozz, smF  |
|           11 |     3986 | 2024-11-04 | XI Esport                 | W   | 0.412      | 0.143        | 0.001 (0.000)    | 0.282 (0.017)    | 0 (0.000) |     6.94 | Andree, lund, mertz, nellozz, smF  |
|           10 |     4416 | 2024-10-28 | Astralis Talent           | W   | 0.366      | 0.143        | 0.002 (0.000)    | 0.724 (0.038)    | 0 (0.000) |     7.32 | Andree, lund, mertz, nellozz, smF  |
|            9 |     4437 | 2024-10-28 | MASONIC                   | L   | 0.365      | -            | -                | -                | -         |    -5.75 | Andree, lund, mertz, nellozz, smF  |
|            8 |     4746 | 2024-10-21 | WOPA Esport               | L   | 0.318      | -            | -                | -                | -         |    -2.51 | Andree, lund, mertz, nellozz, smF  |
|            7 |     5478 | 2024-10-07 | MASONIC                   | W   | 0.225      | 0.143        | 0.001 (0.000)    | 0.164 (0.005)    | 0 (0.000) |     3.66 | Andree, lund, mertz, nellozz, smF  |
|            6 |     5485 | 2024-10-07 | Copenhagen Wolves Academy | W   | 0.225      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.36 | Andree, lund, mertz, nellozz, smF  |
|            5 |     5493 | 2024-10-07 | WOPA Esport               | W   | 0.224      | 0.143        | 0.032 (0.001)    | 0.777 (0.025)    | 0 (0.000) |     5.31 | Andree, lund, mertz, nellozz, smF  |
|            4 |     6457 | 2024-09-23 | Preasy Esport             | W   | 0.132      | 0.143        | 0.012 (0.000)    | 0.701 (0.013)    | 0 (0.000) |     2.96 | Andree, lund, mertz, nellozz, smF  |
|            3 |     6470 | 2024-09-23 | Astralis Talent           | W   | 0.132      | 0.143        | 0.002 (0.000)    | 0.724 (0.014)    | 0 (0.000) |     2.84 | Andree, lund, mertz, nellozz, smF  |
|            2 |     6882 | 2024-09-16 | XI Esport                 | L   | 0.085      | -            | -                | -                | -         |    -1.84 | Andree, lund, mertz, nellozz, smF  |
|            1 |     6892 | 2024-09-16 | XI Esport                 | L   | 0.085      | -            | -                | -                | -         |    -1.20 | Andree, lund, mertz, nellozz, smF  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($376.14)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-23 |      0.538 | $698.53        | $376.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
