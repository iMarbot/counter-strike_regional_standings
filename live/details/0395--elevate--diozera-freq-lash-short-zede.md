### Roster Details<br />
Team Name: Elevate<br />
Roster: diozera, fREQ, lash, short, zede<br />
Global Rank: [395](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [82]( ../standings_americas.md)<br />
<br />
Final Rank Value:  600.3<br />
<br />
Final Rank Value (600.3) = Starting Rank Value (521.9) + Head To Head Adjustments (78.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 521.9
- 400 + ( ( 0.061 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 521.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |      788 | 2025-02-07 | RED Canids   | L   | 1.000      | -            | -                | -                | -         |    -5.57 | diozera, fREQ, lash, short, zede    |
|            7 |      823 | 2025-02-06 | 9z Team      | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.121 (0.017)    | 0 (0.000) |    23.28 | diozera, fREQ, lash, short, zede    |
|            6 |      840 | 2025-02-06 | Tropa do VSM | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.140 (0.020)    | 0 (0.000) |    11.94 | diozera, fREQ, lash, short, zede    |
|            5 |      899 | 2025-02-05 | RED Canids   | L   | 1.000      | -            | -                | -                | -         |    -5.28 | diozera, fREQ, lash, short, zede    |
|            4 |      930 | 2025-02-04 | Nitro.GG     | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.518 (0.074)    | 0 (0.000) |    19.55 | diozera, fREQ, lash, short, zede    |
|            3 |      935 | 2025-02-04 | Nova holanda | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.090 (0.013)    | 0 (0.000) |    17.89 | diozera, fREQ, lash, short, zede    |
|            2 |     1196 | 2025-01-10 | BESTIA       | L   | 0.867      | -            | -                | -                | -         |    -2.48 | desh, fREQ, Leomonster, short, zede |
|            1 |     1208 | 2025-01-09 | 9z Academy   | W   | 0.859      | 0.384        | 0.001 (0.000)    | 0.388 (0.128)    | 0 (0.000) |    19.09 | desh, fREQ, Leomonster, short, zede |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
