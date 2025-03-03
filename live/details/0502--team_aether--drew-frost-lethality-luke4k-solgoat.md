### Roster Details<br />
Team Name: Team Aether<br />
Roster: Drew, Frost, Lethality, LUKE4k, SolGoat<br />
Global Rank: [502](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [112]( ../standings_americas.md)<br />
<br />
Final Rank Value:  515.0<br />
<br />
Final Rank Value (515.0) = Starting Rank Value (503.4) + Head To Head Adjustments (11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.052<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 503.4
- 400 + ( ( 0.052 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 503.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     5186 | 2024-10-12 | FLUFFY AIMERS              | L   | 0.259      | -            | -                | -                | -         |    -1.35 | Drew, Frost, Lethality, LUKE4k, SolGoat |
|           10 |     5188 | 2024-10-12 | Supernova Comets           | W   | 0.259      | 0.262        | 0.011 (0.001)    | 0.263 (0.018)    | 0 (0.000) |     6.35 | Drew, Frost, Lethality, LUKE4k, SolGoat |
|            9 |     5753 | 2024-10-02 | Nouns Esports              | L   | 0.193      | -            | -                | -                | -         |    -1.35 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            8 |     6102 | 2024-09-27 | Party Astronauts           | L   | 0.159      | -            | -                | -                | -         |    -0.93 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            7 |     6183 | 2024-09-26 | Blahaj                     | W   | 0.153      | 0.143        | 0.000 (0.000)    | 0.144 (0.003)    | 0 (0.000) |     2.45 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            6 |     6371 | 2024-09-24 | Homyno                     | W   | 0.139      | 0.371        | 0.008 (0.000)    | 0.189 (0.010)    | 0 (0.000) |     3.30 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            5 |     6556 | 2024-09-21 | Dangerous (Ukrainian team) | W   | 0.120      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.34 | AtomiK, Frost, Izik, LUKE4k, SolGoat    |
|            4 |     6613 | 2024-09-20 | Kinship                    | L   | 0.114      | -            | -                | -                | -         |    -1.93 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            3 |     6615 | 2024-09-20 | LAG Gaming                 | W   | 0.114      | 0.143        | 0.004 (0.000)    | 0.120 (0.002)    | 0 (0.000) |     2.96 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            2 |     6621 | 2024-09-20 | Mach 5                     | W   | 0.113      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.28 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            1 |     7170 | 2024-09-11 | Akimbo Esports             | L   | 0.053      | -            | -                | -                | -         |    -0.52 | AtomiK, Frost, LUKE4k, RiFT, SolGoat    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
