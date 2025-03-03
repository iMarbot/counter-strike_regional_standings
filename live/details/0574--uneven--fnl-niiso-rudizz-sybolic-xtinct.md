### Roster Details<br />
Team Name: UNEVEN<br />
Roster: FNL, niiso, Rudizz, Sybolic, Xtinct<br />
Global Rank: [574](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [350]( ../standings_europe.md)<br />
<br />
Final Rank Value:  446.1<br />
<br />
Final Rank Value (446.1) = Starting Rank Value (464.3) + Head To Head Adjustments (-18.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.129[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.032<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 464.3
- 400 + ( ( 0.032 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 464.3


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
|            9 |     3847 | 2024-11-07 | Unorganized Five     | L   | 0.432      | -            | -                | -                | -         |    -4.49 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            8 |     3891 | 2024-11-06 | BIG SELECTA          | L   | 0.425      | -            | -                | -                | -         |    -4.75 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            7 |     4467 | 2024-10-27 | Team Fragster        | L   | 0.358      | -            | -                | -                | -         |    -3.58 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            6 |     4849 | 2024-10-19 | Reveal (German team) | L   | 0.305      | -            | -                | -                | -         |    -2.56 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            5 |     4906 | 2024-10-18 | ALTERNATE aTTaX Evo  | L   | 0.297      | -            | -                | -                | -         |    -2.81 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            4 |     5265 | 2024-10-11 | Entropy Gaming       | L   | 0.251      | -            | -                | -                | -         |    -2.80 | FNL, jaadoosh, niiso, Rudizz, Sybolic |
|            3 |     6136 | 2024-09-27 | Team NinjaParentz    | W   | 0.158      | 0.143        | 0.000 (0.000)    | 0.035 (0.001)    | 0 (0.000) |     3.19 | FNL, jaadoosh, niiso, Rudizz, Sybolic |
|            2 |     7093 | 2024-09-13 | AKA HERO             | L   | 0.065      | -            | -                | -                | -         |    -0.68 | FNL, niiso, Rudizz, Sybolic, Xtinct   |
|            1 |     7522 | 2024-09-06 | RIZON                | W   | 0.018      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.23 | FNL, niiso, Rudizz, Sybolic, Xtinct   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
