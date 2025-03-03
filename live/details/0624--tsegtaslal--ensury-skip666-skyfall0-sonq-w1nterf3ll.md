### Roster Details<br />
Team Name: Tsegtaslal<br />
Roster: Ensury, skip666, Skyfall0, sonq, w1nterf3ll<br />
Global Rank: [624](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [102]( ../standings_asia.md)<br />
<br />
Final Rank Value:  383.2<br />
<br />
Final Rank Value (383.2) = Starting Rank Value (400.9) + Head To Head Adjustments (-17.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.9
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |      379 | 2025-02-16 | Taimyr                  | L   | 1.000      | -            | -                | -                | -         |   -14.97 | Ensury, skip666, Skyfall0, sonq, w1nterf3ll   |
|            7 |      498 | 2025-02-14 | Eruption                | L   | 1.000      | -            | -                | -                | -         |    -1.77 | Ensury, gwemn, skip666, Skyfall0, w1nterf3ll  |
|            6 |      871 | 2025-02-06 | Eruption                | L   | 1.000      | -            | -                | -                | -         |    -1.82 | Breakk, Ensury, gwemn, Skyfall0, w1nterf3ll   |
|            5 |      936 | 2025-02-05 | Vizora Esports          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.122 (0.017)    | 0 (0.000) |    19.13 | Breakk, Ensury, gwemn, Skyfall0, w1nterf3ll   |
|            4 |     2308 | 2024-12-02 | Harizma                 | L   | 0.602      | -            | -                | -                | -         |    -2.49 | Ensury, Guns, ise, Skyfall0, w1nterf3ll       |
|            3 |     3292 | 2024-11-17 | Northwest               | L   | 0.496      | -            | -                | -                | -         |    -7.69 | baitinhard, Ensury, ise, Skyfall0, w1nterf3ll |
|            2 |     3367 | 2024-11-16 | Nomads (Mongolian team) | L   | 0.489      | -            | -                | -                | -         |    -4.95 | baitinhard, Ensury, ise, Skyfall0, w1nterf3ll |
|            1 |     3377 | 2024-11-15 | CatEvil                 | L   | 0.489      | -            | -                | -                | -         |    -3.10 | baitinhard, Ensury, ise, Skyfall0, w1nterf3ll |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
