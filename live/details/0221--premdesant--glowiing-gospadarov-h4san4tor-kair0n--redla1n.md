### Roster Details<br />
Team Name: Premdesant<br />
Roster: glowiing, Gospadarov, H4SAN4TOR, KaiR0N-, redla1N<br />
Global Rank: [221](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [158]( ../standings_europe.md)<br />
<br />
Final Rank Value:  695.0<br />
<br />
Final Rank Value (695.0) = Starting Rank Value (658.3) + Head To Head Adjustments (36.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.303[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 658.3
- 400 + ( ( 0.129 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 658.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     1627 | 2024-12-15 | QUAZAR                | W   | 0.692      | 0.143        | 0.005 (0.001)    | 0.257 (0.025)    | 0 (0.000) |    12.35 | glowiing, Gospadarov, H4SAN4TOR, KaiR0N-, redla1N |
|            7 |     1694 | 2024-12-14 | VSCL                  | W   | 0.686      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.37 | glowiing, Gospadarov, H4SAN4TOR, KaiR0N-, redla1N |
|            6 |     2798 | 2024-11-24 | RUSH B (Russian team) | L   | 0.552      | -            | -                | -                | -         |    -4.13 | fozil, Gospadarov, H4SAN4TOR, redla1N, Ryujin     |
|            5 |     3327 | 2024-11-16 | Nuclear TigeRES       | W   | 0.499      | 0.143        | 0.004 (0.000)    | 0.586 (0.042)    | 0 (0.000) |    11.01 | fozil, Gospadarov, H4SAN4TOR, redla1N, Ryujin     |
|            4 |     3342 | 2024-11-16 | QUAZAR                | W   | 0.498      | 0.143        | 0.005 (0.000)    | 0.257 (0.018)    | 0 (0.000) |     9.51 | fozil, Gospadarov, H4SAN4TOR, redla1N, Ryujin     |
|            3 |     3350 | 2024-11-16 | FLuffy Gangsters      | L   | 0.497      | -            | -                | -                | -         |    -4.66 | fozil, Gospadarov, H4SAN4TOR, redla1N, Ryujin     |
|            2 |     4535 | 2024-10-26 | Aimhaus               | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     3.02 | fozil, Gospadarov, H4SAN4TOR, redla1N, Ryujin     |
|            1 |     4548 | 2024-10-26 | Donstu Esports        | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.205 (0.010)    | 0 (0.000) |     3.19 | fozil, Gospadarov, H4SAN4TOR, redla1N, Ryujin     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,675.93)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.692 | $2,421.08      | $1,675.93       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
