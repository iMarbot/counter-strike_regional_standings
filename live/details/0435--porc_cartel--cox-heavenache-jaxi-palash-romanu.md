### Roster Details<br />
Team Name: PORC CARTEL<br />
Roster: cox, HEAVENACHE, jaxi, Palash, Romanu<br />
Global Rank: [435](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [271]( ../standings_europe.md)<br />
<br />
Final Rank Value:  569.5<br />
<br />
Final Rank Value (569.5) = Starting Rank Value (598.5) + Head To Head Adjustments (-28.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.254[<sup>1</sup>](#table2)
- Bounty Collected: 0.143[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.099<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 598.5
- 400 + ( ( 0.099 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 598.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     2584 | 2024-11-29 | DEVASTATION (Romanian team) | L   | 0.586      | -            | -                | -                | -         |    -7.49 | cox, HEAVENACHE, jaxi, Palash, Romanu |
|            7 |     2588 | 2024-11-29 | REDPack Esports             | L   | 0.586      | -            | -                | -                | -         |    -8.61 | cox, HEAVENACHE, jaxi, Palash, Romanu |
|            6 |     2619 | 2024-11-28 | HyperSpirit                 | L   | 0.580      | -            | -                | -                | -         |   -11.38 | cox, HEAVENACHE, jaxi, Palash, Romanu |
|            5 |     2637 | 2024-11-28 | Aimclub                     | L   | 0.579      | -            | -                | -                | -         |    -4.19 | cox, HEAVENACHE, jaxi, Palash, Romanu |
|            4 |     4799 | 2024-10-20 | Nexus Gaming                | L   | 0.319      | -            | -                | -                | -         |    -0.49 | cox, HEAVENACHE, jaxi, Palash, Romanu |
|            3 |     4830 | 2024-10-19 | Aimclub                     | W   | 0.313      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     3.28 | cox, HEAVENACHE, jaxi, Palash, Romanu |
|            2 |     4844 | 2024-10-19 | Infinite Gaming             | W   | 0.312      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     4.74 | cox, HEAVENACHE, jaxi, Palash, Romanu |
|            1 |     4853 | 2024-10-19 | BLOCKBUSTERS                | L   | 0.312      | -            | -                | -                | -         |    -4.78 | cox, HEAVENACHE, jaxi, Palash, Romanu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($395.36)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.366 | $1,079.97      | $395.36         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
