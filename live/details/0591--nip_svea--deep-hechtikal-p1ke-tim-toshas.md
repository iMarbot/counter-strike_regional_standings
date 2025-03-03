### Roster Details<br />
Team Name: NIP Svea<br />
Roster: DeeP, hechtikal, p1ke, TIM, toshas<br />
Global Rank: [591](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [359]( ../standings_europe.md)<br />
<br />
Final Rank Value:  409.6<br />
<br />
Final Rank Value (409.6) = Starting Rank Value (400.3) + Head To Head Adjustments (9.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.3
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     2497 | 2024-11-30 | Rhyno Esports        | L   | 0.586      | -            | -                | -                | -         |    -1.25 | DeeP, hechtikal, p1ke, TIM, toshas   |
|            8 |     2730 | 2024-11-26 | Dragon Esports Club  | L   | 0.559      | -            | -                | -                | -         |    -3.09 | DeeP, hechtikal, p1ke, TIM, toshas   |
|            7 |     3499 | 2024-11-13 | Venom (Swedish team) | W   | 0.472      | 0.143        | 0.000 (0.000)    | 0.062 (0.004)    | 0 (0.000) |     9.31 | DeeP, hechtikal, otto, p1ke, toshas  |
|            6 |     4197 | 2024-11-01 | Showmakerz           | L   | 0.392      | -            | -                | -                | -         |    -3.08 | DeeP, hechtikal, otto, p1ke, toshas  |
|            5 |     5078 | 2024-10-15 | KILLBOX              | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     5.15 | DeeP, hechtikal, p1ke, toshas, Zitte |
|            4 |     5268 | 2024-10-11 | Northern Lights      | W   | 0.251      | 0.143        | 0.000 (0.000)    | 0.037 (0.001)    | 0 (0.000) |     3.96 | DeeP, hechtikal, p1ke, toshas, Zitte |
|            3 |     5613 | 2024-10-05 | EYEBALLERS           | L   | 0.210      | -            | -                | -                | -         |    -0.63 | DeeP, hechtikal, p1ke, TIM, toshas   |
|            2 |     6772 | 2024-09-18 | Privateshow          | L   | 0.098      | -            | -                | -                | -         |    -1.04 | DeeP, hechtikal, otto, p1ke, toshas  |
|            1 |     7599 | 2024-09-05 | Kario Mart           | L   | 0.011      | -            | -                | -                | -         |    -0.08 | DeeP, hechtikal, otto, p1ke, toshas  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
