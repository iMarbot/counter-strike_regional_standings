### Roster Details<br />
Team Name: M1X<br />
Roster: 2high, gxx-, Krabeni, makazze, SENER1<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  779.1<br />
<br />
Final Rank Value (779.1) = Starting Rank Value (770.0) + Head To Head Adjustments (9.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.323[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.209[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 770.0
- 400 + ( ( 0.185 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 770.0


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
|            5 |     1397 | 2024-12-22 | Kubix Esports | L   | 0.732      | -            | -                | -                | -         |    -8.05 | 2high, gxx-, Krabeni, makazze, SENER1  |
|            4 |     1403 | 2024-12-22 | HAWKTUAH      | W   | 0.731      | 0.143        | 0.002 (0.000)    | 0.034 (0.004)    | 1 (0.731) |     7.97 | 2high, gxx-, Krabeni, makazze, SENER1  |
|            3 |     1449 | 2024-12-21 | MANA eSports  | W   | 0.725      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.725) |     4.47 | 2high, gxx-, Krabeni, makazze, SENER1  |
|            2 |     6023 | 2024-09-28 | Kubix Esports | W   | 0.165      | 0.143        | 0.045 (0.001)    | 0.487 (0.011)    | 1 (0.165) |     3.71 | Caleyy, gxx-, Krabeni, makazze, SENER1 |
|            1 |     6078 | 2024-09-28 | 2shkupiflow   | W   | 0.163      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.163) |     0.97 | Caleyy, gxx-, Krabeni, makazze, SENER1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,645.55)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.732 | $2,607.56      | $1,909.07       |
| 2024-09-28 |      0.165 | $4,467.26      | $736.48         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
