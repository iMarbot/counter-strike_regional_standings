### Roster Details<br />
Team Name: AMIGOS (Brazilian team)<br />
Roster: aNgelo, brokeN, CloN7, doiz, hug1<br />
Global Rank: [527](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [120]( ../standings_americas.md)<br />
<br />
Final Rank Value:  490.4<br />
<br />
Final Rank Value (490.4) = Starting Rank Value (485.7) + Head To Head Adjustments (4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.170[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.043<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 485.7
- 400 + ( ( 0.043 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 485.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     4432 | 2024-10-28 | Bad News Chickens         | W   | 0.365      | 0.143        | 0.002 (0.000)    | 0.234 (0.012)    | 0 (0.000) |     8.67 | aNgelo, brokeN, CloN7, doiz, hug1 |
|            8 |     4699 | 2024-10-22 | VELOX Argentina           | L   | 0.325      | -            | -                | -                | -         |    -4.62 | aNgelo, brokeN, CloN7, doiz, hug1 |
|            7 |     5837 | 2024-10-01 | Floripa Stars             | L   | 0.186      | -            | -                | -                | -         |    -1.66 | aNgelo, brokeN, CloN7, doiz, hta  |
|            6 |     6631 | 2024-09-20 | Sharks Youngsters         | W   | 0.112      | 0.143        | 0.000 (0.000)    | 0.095 (0.002)    | 0 (0.000) |     2.21 | aNgelo, brokeN, doiz, hta, nz1    |
|            5 |     6811 | 2024-09-17 | Bad News Chickens         | L   | 0.093      | -            | -                | -                | -         |    -0.74 | aNgelo, brokeN, doiz, hta, nz1    |
|            4 |     7285 | 2024-09-09 | Nova holanda              | W   | 0.038      | 0.143        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.46 | aNgelo, brokeN, doiz, hta, nz1    |
|            3 |     7342 | 2024-09-08 | Só os do JOB              | W   | 0.033      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.39 | aNgelo, brokeN, doiz, hta, nz1    |
|            2 |     7398 | 2024-09-07 | América eSports           | W   | 0.026      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.31 | aNgelo, brokeN, doiz, hta, nz1    |
|            1 |     7400 | 2024-09-07 | SamuraiS (Brazilian team) | L   | 0.025      | -            | -                | -                | -         |    -0.38 | aNgelo, brokeN, doiz, hta, nz1    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
