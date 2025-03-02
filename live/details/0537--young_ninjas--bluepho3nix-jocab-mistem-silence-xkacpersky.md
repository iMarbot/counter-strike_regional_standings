### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Global Rank: [537](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [334]( ../standings_europe.md)<br />
<br />
Final Rank Value:  485.1<br />
<br />
Final Rank Value (485.1) = Starting Rank Value (484.6) + Head To Head Adjustments (0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.169[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.042<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 484.6
- 400 + ( ( 0.042 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 484.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     7342 | 2024-09-08 | FAVBET Team         | L   | 0.039      | -            | -                | -                | -         |    -0.15 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|            7 |     7366 | 2024-09-08 | CYBERSHOKE Esports  | L   | 0.037      | -            | -                | -                | -         |    -0.13 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|            6 |     7468 | 2024-09-07 | GUN5 Esports        | L   | 0.031      | -            | -                | -                | -         |    -0.07 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|            5 |     7537 | 2024-09-06 | Zero Tenacity       | L   | 0.024      | -            | -                | -                | -         |    -0.08 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|            4 |     7668 | 2024-09-04 | G2 Ares             | W   | 0.013      | 0.354        | 0.001 (0.000)    | 0.261 (0.001)    | 0 (0.000) |     0.30 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|            3 |     7673 | 2024-09-04 | Alliance            | W   | 0.012      | 0.435        | 0.015 (0.000)    | 0.573 (0.003)    | 0 (0.000) |     0.35 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|            2 |     7684 | 2024-09-04 | TSM                 | W   | 0.011      | 0.384        | 0.009 (0.000)    | 0.130 (0.001)    | 0 (0.000) |     0.28 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|            1 |     7737 | 2024-09-03 | Team Spirit Academy | L   | 0.006      | -            | -                | -                | -         |    -0.01 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
