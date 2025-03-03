### Roster Details<br />
Team Name: Ex-RUBY<br />
Roster: forkyz, Kaide, Sowalio, tasman, YumsaN<br />
Global Rank: [441](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [273]( ../standings_europe.md)<br />
<br />
Final Rank Value:  567.6<br />
<br />
Final Rank Value (567.6) = Starting Rank Value (539.2) + Head To Head Adjustments (28.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.070<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 539.2
- 400 + ( ( 0.070 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 539.2


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
|           12 |     2797 | 2024-11-24 | Copenhagen Wolves (American organization) | W   | 0.545      | 0.372        | 0.016 (0.003)    | 1.000 (0.203)    | 0 (0.000) |    14.34 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|           11 |     2804 | 2024-11-24 | THE GENTLEMEN ESPORTS                     | W   | 0.544      | 0.372        | 0.001 (0.000)    | 0.263 (0.053)    | 0 (0.000) |    12.01 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|           10 |     2968 | 2024-11-22 | Anonymo Esports                           | L   | 0.532      | -            | -                | -                | -         |    -8.78 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            9 |     2979 | 2024-11-22 | GenOne                                    | L   | 0.531      | -            | -                | -                | -         |    -2.71 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            8 |     3158 | 2024-11-19 | RUSTEC                                    | L   | 0.512      | -            | -                | -                | -         |    -6.02 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            7 |     3165 | 2024-11-19 | ROUNDS                                    | W   | 0.511      | 0.372        | 0.000 (0.000)    | 0.060 (0.011)    | 0 (0.000) |     7.02 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            6 |     3210 | 2024-11-18 | Lilmix                                    | W   | 0.505      | 0.372        | 0.001 (0.000)    | 0.127 (0.024)    | 0 (0.000) |     9.53 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            5 |     3216 | 2024-11-18 | K27                                       | L   | 0.504      | -            | -                | -                | -         |    -2.04 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            4 |     3624 | 2024-11-11 | Fire Flux Esports                         | L   | 0.458      | -            | -                | -                | -         |    -1.76 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            3 |     3957 | 2024-11-05 | FLuffy Gangsters                          | L   | 0.418      | -            | -                | -                | -         |    -2.68 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            2 |     3963 | 2024-11-05 | BC.Game Esports                           | W   | 0.417      | 0.372        | 0.022 (0.003)    | 0.551 (0.086)    | 0 (0.000) |    11.13 | forkyz, Kaide, Sowalio, tasman, YumsaN |
|            1 |     4517 | 2024-10-26 | Nuclear TigeRES                           | L   | 0.351      | -            | -                | -                | -         |    -1.67 | forkyz, Kaide, Sowalio, tasman, YumsaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
