### Roster Details<br />
Team Name: Ex-RUBY<br />
Roster: forkyz, Kaide, Sowalio, tasman, YumsaN<br />
Global Rank: [436](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [272]( ../standings_europe.md)<br />
<br />
Final Rank Value:  568.5<br />
<br />
Final Rank Value (568.5) = Starting Rank Value (539.6) + Head To Head Adjustments (28.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.070<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 539.6
- 400 + ( ( 0.070 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 539.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     2785 | 2024-11-24 | Copenhagen Wolves (American organization) | W   | 0.553      | 0.372        | 0.016 (0.003)    | 1.000 (0.206)    | 0 (0.000) |    14.55 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|           11 |     2792 | 2024-11-24 | THE GENTLEMEN ESPORTS                     | W   | 0.552      | 0.372        | 0.001 (0.000)    | 0.269 (0.055)    | 0 (0.000) |    12.21 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|           10 |     2956 | 2024-11-22 | Anonymo Esports                           | L   | 0.540      | -            | -                | -                | -         |    -8.90 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            9 |     2967 | 2024-11-22 | GenOne                                    | L   | 0.539      | -            | -                | -                | -         |    -2.74 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            8 |     3146 | 2024-11-19 | RUSTEC                                    | L   | 0.520      | -            | -                | -                | -         |    -6.14 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            7 |     3153 | 2024-11-19 | ROUNDS                                    | W   | 0.520      | 0.372        | 0.000 (0.000)    | 0.061 (0.012)    | 0 (0.000) |     7.15 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            6 |     3198 | 2024-11-18 | Lilmix                                    | W   | 0.513      | 0.372        | 0.001 (0.000)    | 0.130 (0.025)    | 0 (0.000) |     9.67 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            5 |     3204 | 2024-11-18 | K27                                       | L   | 0.512      | -            | -                | -                | -         |    -2.09 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            4 |     3612 | 2024-11-11 | Fire Flux Esports                         | L   | 0.466      | -            | -                | -                | -         |    -1.78 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            3 |     3945 | 2024-11-05 | FLuffy Gangsters                          | L   | 0.426      | -            | -                | -                | -         |    -2.72 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            2 |     3951 | 2024-11-05 | BC.Game Esports                           | W   | 0.426      | 0.372        | 0.022 (0.003)    | 0.559 (0.089)    | 0 (0.000) |    11.36 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            1 |     4505 | 2024-10-26 | Nuclear TigeRES                           | L   | 0.359      | -            | -                | -                | -         |    -1.71 | forkyz, Kaide, Sowalio, tasman, YumsaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
