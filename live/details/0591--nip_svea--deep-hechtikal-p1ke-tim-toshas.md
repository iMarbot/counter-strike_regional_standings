### Roster Details<br />
Team Name: NIP Svea<br />
Roster: DeeP, hechtikal, p1ke, TIM, toshas<br />
Global Rank: [591](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [360]( ../standings_europe.md)<br />
<br />
Final Rank Value:  409.7<br />
<br />
Final Rank Value (409.7) = Starting Rank Value (400.3) + Head To Head Adjustments (9.4)<br />

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
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.3


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
|            9 |     2485 | 2024-11-30 | Rhyno Esports        | L   | 0.594      | -            | -                | -                | -         |    -1.25 | DeeP, hechtikal, p1ke, TIM, toshas   |
|            8 |     2718 | 2024-11-26 | Dragon Esports Club  | L   | 0.567      | -            | -                | -                | -         |    -3.14 | DeeP, hechtikal, p1ke, TIM, toshas   |
|            7 |     3487 | 2024-11-13 | Venom (Swedish team) | W   | 0.480      | 0.143        | 0.000 (0.000)    | 0.063 (0.004)    | 0 (0.000) |     9.46 | DeeP, hechtikal, otto, p1ke, toshas  |
|            6 |     4185 | 2024-11-01 | Showmakerz           | L   | 0.400      | -            | -                | -                | -         |    -3.14 | DeeP, hechtikal, otto, p1ke, toshas  |
|            5 |     5066 | 2024-10-15 | KILLBOX              | W   | 0.286      | 0.143        | 0.000 (0.000)    | 0.020 (0.001)    | 0 (0.000) |     5.30 | DeeP, hechtikal, p1ke, toshas, Zitte |
|            4 |     5256 | 2024-10-11 | Northern Lights      | W   | 0.259      | 0.143        | 0.000 (0.000)    | 0.038 (0.001)    | 0 (0.000) |     4.09 | DeeP, hechtikal, p1ke, toshas, Zitte |
|            3 |     5598 | 2024-10-05 | EYEBALLERS           | L   | 0.219      | -            | -                | -                | -         |    -0.65 | DeeP, hechtikal, p1ke, TIM, toshas   |
|            2 |     6760 | 2024-09-18 | Privateshow          | L   | 0.106      | -            | -                | -                | -         |    -1.13 | DeeP, hechtikal, otto, p1ke, toshas  |
|            1 |     7587 | 2024-09-05 | Kario Mart           | L   | 0.019      | -            | -                | -                | -         |    -0.14 | DeeP, hechtikal, otto, p1ke, toshas  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
