### Roster Details<br />
Team Name: Hyuga<br />
Roster: eLa1z, Ravenlot, redzed, SP1NT, tappa<br />
Global Rank: [480](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [298]( ../standings_europe.md)<br />
<br />
Final Rank Value:  533.5<br />
<br />
Final Rank Value (533.5) = Starting Rank Value (507.9) + Head To Head Adjustments (25.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 507.9
- 400 + ( ( 0.054 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 507.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      292 | 2025-02-17 | PLUSH                       | L   | 1.000      | -            | -                | -                | -         |   -20.52 | eLa1z, Ravenlot, redzed, SP1NT, tappa      |
|            9 |      342 | 2025-02-16 | TOOMUCHVIDEOGAMES           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.33 | eLa1z, Ravenlot, redzed, SP1NT, tappa      |
|            8 |     2896 | 2024-11-23 | FORZE Reload                | L   | 0.545      | -            | -                | -                | -         |    -2.58 | 2hug, delus1onn, fearfox, Ravenlot, tappa  |
|            7 |     3246 | 2024-11-17 | Donstu Esports              | W   | 0.505      | 0.143        | 0.000 (0.000)    | 0.205 (0.015)    | 0 (0.000) |     6.81 | 2hug, delus1onn, fearfox, Ravenlot, tappa  |
|            6 |     3259 | 2024-11-17 | HOTU                        | W   | 0.505      | 0.143        | 0.003 (0.000)    | 0.777 (0.056)    | 0 (0.000) |    11.40 | 2hug, delus1onn, fearfox, Ravenlot, tappa  |
|            5 |     3274 | 2024-11-17 | VP.Prodigy                  | W   | 0.504      | 0.143        | 0.000 (0.000)    | 0.206 (0.015)    | 0 (0.000) |     6.98 | 2hug, delus1onn, fearfox, Ravenlot, tappa  |
|            4 |     4536 | 2024-10-26 | QUAZAR Academy              | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.062 (0.003)    | 0 (0.000) |     3.88 | delus1onn, fearfox, Ravenlot, SP1NT, tappa |
|            3 |     4552 | 2024-10-26 | K27                         | W   | 0.358      | 0.143        | 0.008 (0.000)    | 0.776 (0.040)    | 0 (0.000) |    10.16 | delus1onn, fearfox, Ravenlot, SP1NT, tappa |
|            2 |     7642 | 2024-09-04 | Sleepwalkers (Russian team) | L   | 0.013      | -            | -                | -                | -         |    -0.28 | Heyz1ng, HUckLer, Ravenlot, SP1NT, tappa   |
|            1 |     7652 | 2024-09-04 | Nexus Gaming                | W   | 0.013      | 0.221        | 0.186 (0.001)    | 0.808 (0.002)    | 0 (0.000) |     0.40 | Heyz1ng, HUckLer, Ravenlot, SP1NT, tappa   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
