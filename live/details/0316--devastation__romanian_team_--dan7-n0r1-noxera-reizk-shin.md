### Roster Details<br />
Team Name: DEVASTATION (Romanian team)<br />
Roster: dan7, N0R1, NoXera, reizk, shin<br />
Global Rank: [316](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [208]( ../standings_europe.md)<br />
<br />
Final Rank Value:  640.2<br />
<br />
Final Rank Value (640.2) = Starting Rank Value (632.6) + Head To Head Adjustments (7.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.176[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.6
- 400 + ( ( 0.116 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 632.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1999 | 2024-12-08 | Perfect Storm   | L   | 0.638      | -            | -                | -                | -         |    -9.19 | dan7, N0R1, NoXera, reizk, shin |
|            4 |     2589 | 2024-11-29 | HyperSpirit     | W   | 0.579      | 0.143        | 0.000 (0.000)    | 0.087 (0.007)    | 0 (0.000) |     5.77 | dan7, N0R1, NoXera, reizk, shin |
|            3 |     2592 | 2024-11-29 | Aimclub         | L   | 0.578      | -            | -                | -                | -         |    -4.87 | dan7, N0R1, NoXera, reizk, shin |
|            2 |     2596 | 2024-11-29 | PORC CARTEL     | W   | 0.578      | 0.143        | 0.001 (0.000)    | 0.029 (0.002)    | 0 (0.000) |     7.39 | dan7, N0R1, NoXera, reizk, shin |
|            1 |     2644 | 2024-11-28 | REDPack Esports | W   | 0.572      | 0.143        | 0.001 (0.000)    | 0.084 (0.007)    | 0 (0.000) |     8.51 | dan7, N0R1, NoXera, reizk, shin |

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
