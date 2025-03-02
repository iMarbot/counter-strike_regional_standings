### Roster Details<br />
Team Name: Perfect Storm<br />
Roster: BiS, DaciaBlue3, Gaz, SEBASEN, vlady<br />
Global Rank: [266](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [185]( ../standings_europe.md)<br />
<br />
Final Rank Value:  669.6<br />
<br />
Final Rank Value (669.6) = Starting Rank Value (663.0) + Head To Head Adjustments (6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.323[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.0
- 400 + ( ( 0.132 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 663.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     1701 | 2024-12-14 | Nexus Gaming                | L   | 0.686      | -            | -                | -                | -         |    -2.23 | BiS, DaciaBlue3, Gaz, SEBASEN, vlady |
|            7 |     1912 | 2024-12-10 | Wu-Tang Clan                | L   | 0.660      | -            | -                | -                | -         |   -11.41 | BiS, DaciaBlue3, Gaz, SEBASEN, vlady |
|            6 |     1987 | 2024-12-08 | DEVASTATION (Romanian team) | W   | 0.647      | 0.143        | 0.003 (0.000)    | 0.082 (0.008)    | 0 (0.000) |     9.31 | BiS, DaciaBlue3, Gaz, SEBASEN, vlady |
|            5 |     2065 | 2024-12-07 | REDPack Esports             | W   | 0.640      | 0.143        | 0.001 (0.000)    | 0.085 (0.008)    | 0 (0.000) |     8.38 | BiS, DaciaBlue3, Gaz, SEBASEN, vlady |
|            4 |     2396 | 2024-12-01 | Theboyz                     | L   | 0.600      | -            | -                | -                | -         |   -10.33 | BiS, DaciaBlue3, Gaz, SEBASEN, vlady |
|            3 |     2402 | 2024-12-01 | Infinite Gaming             | W   | 0.600      | 0.143        | 0.000 (0.000)    | 0.059 (0.005)    | 0 (0.000) |     5.14 | BiS, DaciaBlue3, Gaz, SEBASEN, vlady |
|            2 |     2431 | 2024-12-01 | JackBoyz                    | W   | 0.599      | 0.143        | 0.008 (0.001)    | 0.056 (0.005)    | 0 (0.000) |     9.12 | BiS, DaciaBlue3, Gaz, SEBASEN, vlady |
|            1 |     2518 | 2024-11-30 | Nexus Gaming                | L   | 0.593      | -            | -                | -                | -         |    -1.35 | BiS, DaciaBlue3, Gaz, SEBASEN, vlady |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,684.85)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.694 | $200.00        | $138.76         |
| 2024-12-15 |      0.693 | $3,676.66      | $2,546.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
