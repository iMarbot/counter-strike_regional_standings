### Roster Details<br />
Team Name: EC BANGA<br />
Roster: cgk, ChipaaN, nisker, whiskas, Zortexx<br />
Global Rank: [499](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [311]( ../standings_europe.md)<br />
<br />
Final Rank Value:  516.5<br />
<br />
Final Rank Value (516.5) = Starting Rank Value (496.6) + Head To Head Adjustments (19.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.187[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.048<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 496.6
- 400 + ( ( 0.048 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 496.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3305 | 2024-11-16 | Viperio         | W   | 0.500      | 0.284        | 0.002 (0.000)    | 0.411 (0.058)    | 0 (0.000) |    12.26 | cgk, ChipaaN, nisker, whiskas, Zortexx           |
|            6 |     3375 | 2024-11-15 | Diamant Esports | W   | 0.493      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.54 | cgk, ChipaaN, nisker, whiskas, Zortexx           |
|            5 |     7004 | 2024-09-14 | NewBALLS        | L   | 0.079      | -            | -                | -                | -         |    -0.71 | ChipaaN, ComputerGeeK, discplex, nisker, Zortexx |
|            4 |     7012 | 2024-09-14 | TryHearts       | W   | 0.078      | 0.215        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     1.12 | ChipaaN, ComputerGeeK, discplex, nisker, Zortexx |
|            3 |     7018 | 2024-09-14 | LEON Esports    | W   | 0.078      | 0.215        | 0.010 (0.000)    | 0.275 (0.005)    | 0 (0.000) |     2.04 | ChipaaN, ComputerGeeK, discplex, nisker, Zortexx |
|            2 |     7398 | 2024-09-07 | Chroma          | L   | 0.033      | -            | -                | -                | -         |    -0.27 | ChipaaN, ComputerGeeK, discplex, nisker, Zortexx |
|            1 |     7723 | 2024-09-03 | Rejected by all | L   | 0.006      | -            | -                | -                | -         |    -0.11 | ChipaaN, ComputerGeeK, discplex, nisker, Zortexx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
