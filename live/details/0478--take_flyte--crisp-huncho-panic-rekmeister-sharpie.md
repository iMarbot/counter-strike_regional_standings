### Roster Details<br />
Team Name: Take Flyte<br />
Roster: Crisp, huncho, Panic, REKMEISTER, Sharpie<br />
Global Rank: [478](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [105]( ../standings_americas.md)<br />
<br />
Final Rank Value:  534.8<br />
<br />
Final Rank Value (534.8) = Starting Rank Value (492.9) + Head To Head Adjustments (41.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.046<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 492.9
- 400 + ( ( 0.046 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 492.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |       74 | 2025-02-23 | Rolling Stone          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.093 (0.013)    | 0 (0.000) |    15.40 | Crisp, huncho, Panic, REKMEISTER, Sharpie |
|            8 |       77 | 2025-02-23 | MIGHT                  | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.444 (0.063)    | 0 (0.000) |    22.24 | Crisp, huncho, Panic, REKMEISTER, Sharpie |
|            7 |      112 | 2025-02-22 | Vireo.pro              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    11.31 | Crisp, huncho, Panic, REKMEISTER, Sharpie |
|            6 |     2073 | 2024-12-07 | Fisher College         | L   | 0.640      | -            | -                | -                | -         |    -3.31 | Crisp, huncho, Jpp, Orb1t, Sharpie        |
|            5 |     2114 | 2024-12-06 | Party Astronauts       | L   | 0.635      | -            | -                | -                | -         |    -3.15 | Crisp, huncho, Jpp, Orb1t, Sharpie        |
|            4 |     7269 | 2024-09-09 | Orbital vsat online    | L   | 0.048      | -            | -                | -                | -         |    -0.96 | Crisp, huncho, Jpp, Panic, Sharpie        |
|            3 |     7372 | 2024-09-07 | LOSTHILLS              | W   | 0.035      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.41 | Crisp, huncho, Jpp, Panic, Sharpie        |
|            2 |     7543 | 2024-09-05 | MIGHT                  | L   | 0.022      | -            | -                | -                | -         |    -0.14 | Crisp, huncho, Jpp, Panic, Sharpie        |
|            1 |     7695 | 2024-09-03 | WICKED (American team) | W   | 0.008      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.10 | Crisp, huncho, Jpp, Panic, Sharpie        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
