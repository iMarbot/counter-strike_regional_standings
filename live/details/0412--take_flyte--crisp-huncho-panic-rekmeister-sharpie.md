### Roster Details<br />
Team Name: Take Flyte<br />
Roster: Crisp, huncho, Panic, REKMEISTER, Sharpie<br />
Global Rank: [412](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [93]( ../standings_americas.md)<br />
<br />
Final Rank Value:  590.3<br />
<br />
Final Rank Value (590.3) = Starting Rank Value (551.7) + Head To Head Adjustments (38.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.076<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 551.7
- 400 + ( ( 0.076 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 551.7


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
|           11 |        4 | 2025-03-01 | Getting Info           | L   | 1.000      | -            | -                | -                | -         |    -4.81 | Crisp, huncho, Panic, REKMEISTER, Sharpie |
|           10 |        7 | 2025-03-01 | Graveyard Shift        | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (1.000) |     7.91 | Crisp, huncho, Panic, REKMEISTER, Sharpie |
|            9 |       89 | 2025-02-23 | Rolling Stone          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.094 (0.013)    | 0 (0.000) |    13.10 | Crisp, huncho, Panic, REKMEISTER, Sharpie |
|            8 |       92 | 2025-02-23 | MIGHT                  | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.489 (0.070)    | 0 (0.000) |    22.13 | Crisp, huncho, Panic, REKMEISTER, Sharpie |
|            7 |      127 | 2025-02-22 | Vireo.pro              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.20 | Crisp, huncho, Panic, REKMEISTER, Sharpie |
|            6 |     2085 | 2024-12-07 | Fisher College         | L   | 0.632      | -            | -                | -                | -         |    -4.23 | Crisp, huncho, Jpp, Orb1t, Sharpie        |
|            5 |     2126 | 2024-12-06 | Party Astronauts       | L   | 0.627      | -            | -                | -                | -         |    -3.98 | Crisp, huncho, Jpp, Orb1t, Sharpie        |
|            4 |     7281 | 2024-09-09 | Orbital vsat online    | L   | 0.040      | -            | -                | -                | -         |    -0.89 | Crisp, huncho, Jpp, Panic, Sharpie        |
|            3 |     7384 | 2024-09-07 | LOSTHILLS              | W   | 0.027      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.25 | Crisp, huncho, Jpp, Panic, Sharpie        |
|            2 |     7555 | 2024-09-05 | MIGHT                  | L   | 0.014      | -            | -                | -                | -         |    -0.09 | Crisp, huncho, Jpp, Panic, Sharpie        |
|            1 |     7707 | 2024-09-03 | WICKED (American team) | W   | 0.000      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.00 | Crisp, huncho, Jpp, Panic, Sharpie        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
