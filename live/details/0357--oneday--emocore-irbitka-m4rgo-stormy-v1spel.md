### Roster Details<br />
Team Name: OneDay<br />
Roster: emocore, IRBITka, M4rgo, Stormy, v1spel<br />
Global Rank: [357](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [228]( ../standings_europe.md)<br />
<br />
Final Rank Value:  622.3<br />
<br />
Final Rank Value (622.3) = Starting Rank Value (605.2) + Head To Head Adjustments (17.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.229[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.103<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 605.2
- 400 + ( ( 0.103 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 605.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      847 | 2025-02-06 | SAW Myst                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.094 (0.013)    | 0 (0.000) |    11.05 | emocore, IRBITka, M4rgo, Stormy, v1spel     |
|           10 |      899 | 2025-02-05 | Take Flyte Female        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.39 | emocore, IRBITka, M4rgo, Stormy, v1spel     |
|            9 |     1096 | 2025-01-31 | Prototype Blaze          | L   | 0.999      | -            | -                | -                | -         |    -5.65 | emocore, IRBITka, M4rgo, Stormy, v1spel     |
|            8 |     4468 | 2024-10-27 | Take Flyte Female        | L   | 0.358      | -            | -                | -                | -         |    -4.64 | ayaka, IRBITka, M4rgo, tenweri, v1spel      |
|            7 |     4478 | 2024-10-27 | Permitta W               | W   | 0.358      | 0.250        | 0.003 (0.000)    | 0.169 (0.015)    | 0 (0.000) |     6.20 | ayaka, IRBITka, M4rgo, tenweri, v1spel      |
|            6 |     4521 | 2024-10-26 | VHS                      | W   | 0.351      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.65 | ayaka, IRBITka, M4rgo, tenweri, v1spel      |
|            5 |     5545 | 2024-10-06 | HSG                      | L   | 0.217      | -            | -                | -                | -         |    -3.09 | IRBITka, M4rgo, tenweri, turboxgirl, v1spel |
|            4 |     5600 | 2024-10-05 | SoulEaters (Female team) | W   | 0.211      | 0.250        | 0.000 (0.000)    | 0.010 (0.001)    | 0 (0.000) |     1.61 | IRBITka, M4rgo, tenweri, turboxgirl, v1spel |
|            3 |     5607 | 2024-10-05 | M33 Female               | W   | 0.211      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.59 | IRBITka, M4rgo, tenweri, turboxgirl, v1spel |
|            2 |     7443 | 2024-09-07 | Eco Warriors             | L   | 0.024      | -            | -                | -                | -         |    -0.19 | IRBITka, M4rgo, tenweri, turboxgirl, v1spel |
|            1 |     7475 | 2024-09-07 | SINS                     | W   | 0.023      | 0.294        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.17 | IRBITka, M4rgo, tenweri, turboxgirl, v1spel |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($143.82)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.358 | $250.00        | $89.62          |
| 2024-10-06 |      0.217 | $250.00        | $54.20          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
