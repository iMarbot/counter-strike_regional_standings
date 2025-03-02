### Roster Details<br />
Team Name: INDINDA<br />
Roster: abiraju, casE, melanta, swiftsteel, znxxX<br />
Global Rank: [491](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [305]( ../standings_europe.md)<br />
<br />
Final Rank Value:  524.0<br />
<br />
Final Rank Value (524.0) = Starting Rank Value (500.9) + Head To Head Adjustments (23.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 500.9
- 400 + ( ( 0.050 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 500.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     3247 | 2024-11-17 | RUSH B (Russian team) | L   | 0.505      | -            | -                | -                | -         |    -1.88 | abiraju, casE, melanta, swiftsteel, znxxX |
|            4 |     3260 | 2024-11-17 | XP Academy            | L   | 0.505      | -            | -                | -                | -         |    -6.47 | abiraju, casE, melanta, swiftsteel, znxxX |
|            3 |     3276 | 2024-11-17 | LEON Esports          | W   | 0.504      | 0.143        | 0.010 (0.001)    | 0.275 (0.020)    | 0 (0.000) |    12.42 | abiraju, casE, melanta, swiftsteel, znxxX |
|            2 |     3736 | 2024-11-09 | Poslednii3ae3d        | W   | 0.452      | 0.143        | 0.001 (0.000)    | 0.103 (0.007)    | 0 (0.000) |     8.83 | abiraju, casE, melanta, swiftsteel, znxxX |
|            1 |     3745 | 2024-11-09 | RUSTEC                | W   | 0.451      | 0.143        | 0.002 (0.000)    | 0.100 (0.006)    | 0 (0.000) |    10.20 | abiraju, casE, melanta, swiftsteel, znxxX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
