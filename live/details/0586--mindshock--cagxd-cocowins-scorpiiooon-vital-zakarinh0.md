### Roster Details<br />
Team Name: Mindshock<br />
Roster: CagXD, COCOWINS, ScorpiioooN, ViTaL, zakarinh0<br />
Global Rank: [586](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [96]( ../standings_asia.md)<br />
<br />
Final Rank Value:  414.3<br />
<br />
Final Rank Value (414.3) = Starting Rank Value (400.4) + Head To Head Adjustments (13.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.4
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |       42 | 2025-02-26 | Al-Ittihad    | L   | 1.000      | -            | -                | -                | -         |    -5.54 | CagXD, COCOWINS, ScorpiioooN, ViTaL, zakarinh0 |
|            6 |       59 | 2025-02-25 | TheShtrongolZ | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    14.62 | CagXD, COCOWINS, ScorpiioooN, ViTaL, zakarinh0 |
|            5 |       76 | 2025-02-24 | Al-Ittihad    | L   | 1.000      | -            | -                | -                | -         |    -5.03 | CagXD, COCOWINS, ScorpiioooN, ViTaL, zakarinh0 |
|            4 |     2640 | 2024-11-28 | JiJieHao      | L   | 0.572      | -            | -                | -                | -         |    -3.81 | 7kick, CagXD, NAKO, ViTaL, zakarinh0           |
|            3 |     2654 | 2024-11-28 | Al-Ittihad    | W   | 0.571      | 0.143        | 0.000 (0.000)    | 0.050 (0.004)    | 0 (0.000) |     8.96 | 7kick, CagXD, NAKO, ViTaL, zakarinh0           |
|            2 |     3022 | 2024-11-21 | JiJieHao      | L   | 0.525      | -            | -                | -                | -         |    -3.48 | 7kick, CagXD, NAKO, ViTaL, zakarinh0           |
|            1 |     3040 | 2024-11-21 | Al-Ittihad    | W   | 0.525      | 0.143        | 0.000 (0.000)    | 0.050 (0.004)    | 0 (0.000) |     8.16 | 7kick, CagXD, NAKO, ViTaL, zakarinh0           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
