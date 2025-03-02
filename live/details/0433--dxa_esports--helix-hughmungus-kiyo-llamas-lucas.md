### Roster Details<br />
Team Name: DXA Esports<br />
Roster: helix, HUGHMUNGUS, Kiyo, Llamas, lucas<br />
Global Rank: [433](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [71]( ../standings_asia.md)<br />
<br />
Final Rank Value:  571.5<br />
<br />
Final Rank Value (571.5) = Starting Rank Value (597.9) + Head To Head Adjustments (-26.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.229[<sup>1</sup>](#table2)
- Bounty Collected: 0.165[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.099<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 597.9
- 400 + ( ( 0.099 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 597.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |      384 | 2025-02-15 | KZG                              | L   | 1.000      | -            | -                | -                | -         |   -14.99 | helix, HUGHMUNGUS, Kiyo, Llamas, lucas |
|            7 |      447 | 2025-02-14 | SemperFi Esports                 | L   | 1.000      | -            | -                | -                | -         |   -12.01 | helix, HUGHMUNGUS, Kiyo, Llamas, lucas |
|            6 |     5365 | 2024-10-09 | Arcade Esports (Australian team) | W   | 0.244      | 0.333        | 0.000 (0.000)    | 0.011 (0.001)    | 0 (0.000) |     3.72 | helix, Kiyo, lucas, prakM, Roflko      |
|            5 |     5369 | 2024-10-09 | Arcade Esports (Australian team) | L   | 0.244      | -            | -                | -                | -         |    -4.04 | helix, Kiyo, lucas, prakM, Roflko      |
|            4 |     5796 | 2024-10-02 | Only One Word                    | W   | 0.198      | 0.333        | 0.001 (0.000)    | 0.191 (0.013)    | 0 (0.000) |     3.47 | helix, Kiyo, lucas, prakM, Roflko      |
|            3 |     5798 | 2024-10-02 | Only One Word                    | L   | 0.197      | -            | -                | -                | -         |    -2.79 | helix, Kiyo, lucas, prakM, Roflko      |
|            2 |     6316 | 2024-09-25 | MANTRA                           | L   | 0.151      | -            | -                | -                | -         |    -2.29 | helix, Kiyo, lucas, prakM, Roflko      |
|            1 |     6323 | 2024-09-25 | MANTRA                           | W   | 0.151      | 0.333        | 0.000 (0.000)    | 0.175 (0.009)    | 0 (0.000) |     2.49 | helix, Kiyo, lucas, prakM, Roflko      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($142.38)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.316 | $450.00        | $142.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
