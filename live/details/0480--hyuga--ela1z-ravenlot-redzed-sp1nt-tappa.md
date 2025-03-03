### Roster Details<br />
Team Name: Hyuga<br />
Roster: eLa1z, Ravenlot, redzed, SP1NT, tappa<br />
Global Rank: [480](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [297]( ../standings_europe.md)<br />
<br />
Final Rank Value:  530.2<br />
<br />
Final Rank Value (530.2) = Starting Rank Value (504.8) + Head To Head Adjustments (25.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.197[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.052<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 504.8
- 400 + ( ( 0.052 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 504.8


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
|           10 |      304 | 2025-02-17 | PLUSH                       | L   | 1.000      | -            | -                | -                | -         |   -20.39 | eLa1z, Ravenlot, redzed, SP1NT, tappa      |
|            9 |      354 | 2025-02-16 | TOOMUCHVIDEOGAMES           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.46 | eLa1z, Ravenlot, redzed, SP1NT, tappa      |
|            8 |     2908 | 2024-11-23 | FORZE Reload                | L   | 0.537      | -            | -                | -                | -         |    -2.51 | 2hug, delus1onn, fearfox, Ravenlot, tappa  |
|            7 |     3258 | 2024-11-17 | Donstu Esports              | W   | 0.497      | 0.143        | 0.000 (0.000)    | 0.203 (0.014)    | 0 (0.000) |     6.77 | 2hug, delus1onn, fearfox, Ravenlot, tappa  |
|            6 |     3271 | 2024-11-17 | HOTU                        | W   | 0.497      | 0.143        | 0.003 (0.000)    | 0.768 (0.054)    | 0 (0.000) |    11.27 | 2hug, delus1onn, fearfox, Ravenlot, tappa  |
|            5 |     3286 | 2024-11-17 | VP.Prodigy                  | W   | 0.496      | 0.143        | 0.000 (0.000)    | 0.204 (0.014)    | 0 (0.000) |     6.94 | 2hug, delus1onn, fearfox, Ravenlot, tappa  |
|            4 |     4548 | 2024-10-26 | QUAZAR Academy              | W   | 0.350      | 0.143        | 0.000 (0.000)    | 0.061 (0.003)    | 0 (0.000) |     3.84 | delus1onn, fearfox, Ravenlot, SP1NT, tappa |
|            3 |     4564 | 2024-10-26 | K27                         | W   | 0.349      | 0.143        | 0.008 (0.000)    | 0.769 (0.038)    | 0 (0.000) |     9.95 | delus1onn, fearfox, Ravenlot, SP1NT, tappa |
|            2 |     7654 | 2024-09-04 | Sleepwalkers (Russian team) | L   | 0.005      | -            | -                | -                | -         |    -0.11 | Heyz1ng, HUckLer, Ravenlot, SP1NT, tappa   |
|            1 |     7664 | 2024-09-04 | Nexus Gaming                | W   | 0.005      | 0.221        | 0.187 (0.000)    | 0.795 (0.001)    | 0 (0.000) |     0.15 | Heyz1ng, HUckLer, Ravenlot, SP1NT, tappa   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
