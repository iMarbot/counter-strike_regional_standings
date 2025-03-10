### Roster Details<br />
Team Name: Theboyz<br />
Roster: d1maje, FLVSH, SAVAGE, warbringer, waZz<br />
Global Rank: [294](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [197]( ../standings_europe.md)<br />
<br />
Final Rank Value:  653.1<br />
<br />
Final Rank Value (653.1) = Starting Rank Value (641.4) + Head To Head Adjustments (11.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.194[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 641.4
- 400 + ( ( 0.121 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 641.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     2095 | 2024-12-07 | HyperSpirit     | W   | 0.631      | 0.143        | 0.000 (0.000)    | 0.087 (0.008)    | 0 (0.000) |     6.06 | d1maje, FLVSH, SAVAGE, warbringer, waZz |
|            4 |     2408 | 2024-12-01 | Perfect Storm   | W   | 0.592      | 0.143        | 0.008 (0.001)    | 0.115 (0.010)    | 0 (0.000) |    10.19 | d1maje, FLVSH, SAVAGE, warbringer, waZz |
|            3 |     2426 | 2024-12-01 | JackBoyz        | L   | 0.592      | -            | -                | -                | -         |    -9.16 | d1maje, FLVSH, SAVAGE, warbringer, waZz |
|            2 |     2437 | 2024-12-01 | Infinite Gaming | W   | 0.591      | 0.143        | 0.000 (0.000)    | 0.059 (0.005)    | 0 (0.000) |     5.82 | d1maje, FLVSH, SAVAGE, warbringer, waZz |
|            1 |     2513 | 2024-11-30 | Nexus Gaming    | L   | 0.585      | -            | -                | -                | -         |    -1.19 | d1maje, FLVSH, SAVAGE, warbringer, waZz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,078.27)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.684 | $1,575.71      | $1,078.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
