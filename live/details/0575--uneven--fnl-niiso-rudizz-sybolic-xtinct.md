### Roster Details<br />
Team Name: UNEVEN<br />
Roster: FNL, niiso, Rudizz, Sybolic, Xtinct<br />
Global Rank: [575](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [351]( ../standings_europe.md)<br />
<br />
Final Rank Value:  445.8<br />
<br />
Final Rank Value (445.8) = Starting Rank Value (464.4) + Head To Head Adjustments (-18.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.129[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.032<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 464.4
- 400 + ( ( 0.032 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 464.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     3835 | 2024-11-07 | Unorganized Five     | L   | 0.440      | -            | -                | -                | -         |    -4.58 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            8 |     3879 | 2024-11-06 | BIG SELECTA          | L   | 0.433      | -            | -                | -                | -         |    -4.84 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            7 |     4455 | 2024-10-27 | Team Fragster        | L   | 0.367      | -            | -                | -                | -         |    -3.66 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            6 |     4837 | 2024-10-19 | Reveal (German team) | L   | 0.313      | -            | -                | -                | -         |    -2.63 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            5 |     4894 | 2024-10-18 | ALTERNATE aTTaX Evo  | L   | 0.306      | -            | -                | -                | -         |    -2.88 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            4 |     5253 | 2024-10-11 | Entropy Gaming       | L   | 0.259      | -            | -                | -                | -         |    -2.90 | FNL, jaadoosh, niiso, Rudizz, Sybolic |
|            3 |     6124 | 2024-09-27 | Team NinjaParentz    | W   | 0.166      | 0.143        | 0.000 (0.000)    | 0.036 (0.001)    | 0 (0.000) |     3.35 | FNL, jaadoosh, niiso, Rudizz, Sybolic |
|            2 |     7081 | 2024-09-13 | AKA HERO             | L   | 0.073      | -            | -                | -                | -         |    -0.77 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            1 |     7510 | 2024-09-06 | RIZON                | W   | 0.026      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.34 | FNL, niiso, Rudizz, Sybolic, Xtinct   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
