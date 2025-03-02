### Roster Details<br />
Team Name: M1X<br />
Roster: 2high, gxx-, Krabeni, makazze, SENER1<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  780.7<br />
<br />
Final Rank Value (780.7) = Starting Rank Value (771.4) + Head To Head Adjustments (9.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.323[<sup>1</sup>](#table2)
- Bounty Collected: 0.207[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.212[<sup>2</sup>](#table1)

The average of these factors is 0.186<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 771.4
- 400 + ( ( 0.186 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 771.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1385 | 2024-12-22 | Kubix Esports | L   | 0.740      | -            | -                | -                | -         |    -8.13 | 2high, gxx-, Krabeni, makazze, SENER1  |
|            4 |     1391 | 2024-12-22 | HAWKTUAH      | W   | 0.740      | 0.143        | 0.002 (0.000)    | 0.034 (0.004)    | 1 (0.740) |     8.01 | 2high, gxx-, Krabeni, makazze, SENER1  |
|            3 |     1437 | 2024-12-21 | MANA eSports  | W   | 0.733      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.733) |     4.48 | 2high, gxx-, Krabeni, makazze, SENER1  |
|            2 |     6011 | 2024-09-28 | Kubix Esports | W   | 0.173      | 0.143        | 0.045 (0.001)    | 0.496 (0.012)    | 1 (0.173) |     3.90 | Caleyy, gxx-, Krabeni, makazze, SENER1 |
|            1 |     6066 | 2024-09-28 | 2shkupiflow   | W   | 0.171      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.171) |     1.01 | Caleyy, gxx-, Krabeni, makazze, SENER1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,703.52)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.740 | $2,607.56      | $1,930.44       |
| 2024-09-28 |      0.173 | $4,467.26      | $773.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
