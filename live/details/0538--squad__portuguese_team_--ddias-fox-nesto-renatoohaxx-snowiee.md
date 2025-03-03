### Roster Details<br />
Team Name: SQUAD (Portuguese team)<br />
Roster: DDias, fox, nesto, renatoohaxx, snowiee<br />
Global Rank: [538](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [333]( ../standings_europe.md)<br />
<br />
Final Rank Value:  484.7<br />
<br />
Final Rank Value (484.7) = Starting Rank Value (481.5) + Head To Head Adjustments (3.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.163[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.041<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 481.5
- 400 + ( ( 0.041 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 481.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     6642 | 2024-09-20 | Rhyno Esports    | L   | 0.111      | -            | -                | -                | -         |    -0.91 | DDias, fox, nesto, renatoohaxx, snowiee  |
|            5 |     6708 | 2024-09-19 | GOOFYBOYZ        | W   | 0.104      | 0.143        | 0.003 (0.000)    | 0.179 (0.003)    | 0 (0.000) |     2.71 | DDias, fox, nesto, renatoohaxx, snowiee  |
|            4 |     6825 | 2024-09-17 | Rhyno Esports    | L   | 0.092      | -            | -                | -                | -         |    -0.33 | DDias, fox, nesto, renatoohaxx, snowiee  |
|            3 |     6883 | 2024-09-16 | TGD Pro          | W   | 0.085      | 0.143        | 0.000 (0.000)    | 0.046 (0.001)    | 0 (0.000) |     1.04 | DDias, fox, nesto, renatoohaxx, snowiee  |
|            2 |     7356 | 2024-09-08 | Impulse GW       | W   | 0.031      | 0.143        | 0.006 (0.000)    | 0.169 (0.001)    | 0 (0.000) |     0.79 | DDias, Ekyy, nesto, snowiee, TMKj        |
|            1 |     7429 | 2024-09-07 | Rhyno Youngsters | L   | 0.024      | -            | -                | -                | -         |    -0.14 | DDias, nesto, renatoohaxx, snowiee, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
