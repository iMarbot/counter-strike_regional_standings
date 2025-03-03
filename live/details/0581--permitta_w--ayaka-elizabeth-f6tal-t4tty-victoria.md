### Roster Details<br />
Team Name: Permitta W<br />
Roster: ayaka, Elizabeth, f6tal, t4tty, victoria<br />
Global Rank: [581](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [354]( ../standings_europe.md)<br />
<br />
Final Rank Value:  424.3<br />
<br />
Final Rank Value (424.3) = Starting Rank Value (401.0) + Head To Head Adjustments (23.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.001<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 401.0
- 400 + ( ( 0.001 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 401.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      848 | 2025-02-06 | VAMOS                   | L   | 1.000      | -            | -                | -                | -         |   -16.11 | ayaka, Elizabeth, f6tal, t4tty, victoria  |
|            5 |      901 | 2025-02-05 | Artemis (Female team)   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    18.80 | ayaka, Elizabeth, f6tal, t4tty, victoria  |
|            4 |     1045 | 2025-02-02 | Prototype Blaze         | L   | 1.000      | -            | -                | -                | -         |    -2.41 | ayaka, Elizabeth, f6tal, t4tty, victoria  |
|            3 |     1063 | 2025-02-01 | Akuma (Female team)     | L   | 1.000      | -            | -                | -                | -         |   -11.49 | ayaka, Elizabeth, f6tal, oxycet, victoria |
|            2 |     1068 | 2025-02-01 | SAW Myst                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.094 (0.013)    | 0 (0.000) |    19.46 | ayaka, Elizabeth, f6tal, oxycet, victoria |
|            1 |     1098 | 2025-01-31 | Outsiders (Female team) | W   | 0.999      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    15.03 | ayaka, Elizabeth, f6tal, oxycet, victoria |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
