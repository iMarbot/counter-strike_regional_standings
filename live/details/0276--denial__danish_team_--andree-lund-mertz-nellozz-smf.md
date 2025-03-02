### Roster Details<br />
Team Name: Denial (Danish team)<br />
Roster: Andree, lund, mertz, nellozz, smF<br />
Global Rank: [276](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [189]( ../standings_europe.md)<br />
<br />
Final Rank Value:  663.6<br />
<br />
Final Rank Value (663.6) = Starting Rank Value (643.9) + Head To Head Adjustments (19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.253[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 643.9
- 400 + ( ( 0.122 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 643.9


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
|           17 |     2889 | 2024-11-23 | Astralis Talent           | L   | 0.545      | -            | -                | -                | -         |    -5.55 | Andree, lund, mertz, nellozz, smF  |
|           16 |     3429 | 2024-11-14 | XI Esport                 | W   | 0.487      | 0.143        | 0.001 (0.000)    | 0.287 (0.020)    | 0 (0.000) |     8.13 | Andree, lund, mertz, nellozz, smF  |
|           15 |     3448 | 2024-11-14 | WOPA Esport               | L   | 0.486      | -            | -                | -                | -         |    -4.18 | Andree, J3nsyy, lund, nellozz, smF |
|           14 |     3584 | 2024-11-11 | Preasy Esport             | W   | 0.467      | 0.143        | 0.012 (0.001)    | 0.710 (0.047)    | 0 (0.000) |     9.42 | Andree, lund, mertz, nellozz, smF  |
|           13 |     3596 | 2024-11-11 | XI Esport                 | L   | 0.467      | -            | -                | -                | -         |   -10.23 | Andree, lund, mertz, nellozz, smF  |
|           12 |     3601 | 2024-11-11 | Copenhagen Wolves Academy | W   | 0.467      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.55 | Andree, lund, mertz, nellozz, smF  |
|           11 |     3974 | 2024-11-04 | XI Esport                 | W   | 0.421      | 0.143        | 0.001 (0.000)    | 0.287 (0.017)    | 0 (0.000) |     7.08 | Andree, lund, mertz, nellozz, smF  |
|           10 |     4404 | 2024-10-28 | Astralis Talent           | W   | 0.374      | 0.143        | 0.002 (0.000)    | 0.733 (0.039)    | 0 (0.000) |     7.48 | Andree, lund, mertz, nellozz, smF  |
|            9 |     4425 | 2024-10-28 | MASONIC                   | L   | 0.373      | -            | -                | -                | -         |    -5.89 | Andree, lund, mertz, nellozz, smF  |
|            8 |     4734 | 2024-10-21 | WOPA Esport               | L   | 0.326      | -            | -                | -                | -         |    -2.57 | Andree, lund, mertz, nellozz, smF  |
|            7 |     5466 | 2024-10-07 | MASONIC                   | W   | 0.233      | 0.143        | 0.001 (0.000)    | 0.166 (0.006)    | 0 (0.000) |     3.79 | Andree, lund, mertz, nellozz, smF  |
|            6 |     5473 | 2024-10-07 | Copenhagen Wolves Academy | W   | 0.233      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.40 | Andree, lund, mertz, nellozz, smF  |
|            5 |     5481 | 2024-10-07 | WOPA Esport               | W   | 0.233      | 0.143        | 0.031 (0.001)    | 0.785 (0.026)    | 0 (0.000) |     5.51 | Andree, lund, mertz, nellozz, smF  |
|            4 |     6445 | 2024-09-23 | Preasy Esport             | W   | 0.140      | 0.143        | 0.012 (0.000)    | 0.710 (0.014)    | 0 (0.000) |     3.15 | Andree, lund, mertz, nellozz, smF  |
|            3 |     6458 | 2024-09-23 | Astralis Talent           | W   | 0.140      | 0.143        | 0.002 (0.000)    | 0.733 (0.015)    | 0 (0.000) |     3.02 | Andree, lund, mertz, nellozz, smF  |
|            2 |     6870 | 2024-09-16 | XI Esport                 | L   | 0.093      | -            | -                | -                | -         |    -2.02 | Andree, lund, mertz, nellozz, smF  |
|            1 |     6880 | 2024-09-16 | XI Esport                 | L   | 0.093      | -            | -                | -                | -         |    -1.32 | Andree, lund, mertz, nellozz, smF  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($381.86)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-23 |      0.547 | $698.53        | $381.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
