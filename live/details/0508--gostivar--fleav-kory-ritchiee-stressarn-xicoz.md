### Roster Details<br />
Team Name: GOSTIVAR<br />
Roster: fleav, kory, ritchiEE, stressarN, xicoz<br />
Global Rank: [508](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [315]( ../standings_europe.md)<br />
<br />
Final Rank Value:  505.2<br />
<br />
Final Rank Value (505.2) = Starting Rank Value (495.0) + Head To Head Adjustments (10.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.189[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.048<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 495.0
- 400 + ( ( 0.048 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 495.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     4402 | 2024-10-28 | Haspers Team           | L   | 0.374      | -            | -                | -                | -         |    -2.80 | fleav, kory, ritchiEE, stressarN, xicoz |
|            6 |     5408 | 2024-10-08 | Haspers Team           | W   | 0.240      | 0.143        | 0.013 (0.000)    | 0.174 (0.006)    | 0 (0.000) |     5.77 | fleav, kory, ritchiEE, stressarN, xicoz |
|            5 |     5947 | 2024-09-29 | ENTERPRISE Genesis     | W   | 0.180      | 0.143        | 0.001 (0.000)    | 0.178 (0.005)    | 0 (0.000) |     3.93 | fleav, kory, ritchiEE, stressarN, xicoz |
|            4 |     6367 | 2024-09-24 | Error404               | W   | 0.146      | 0.143        | 0.000 (0.000)    | 0.015 (0.000)    | 0 (0.000) |     1.70 | fleav, kory, ritchiEE, stressarN, xicoz |
|            3 |     6384 | 2024-09-24 | Dynamo Eclot           | L   | 0.146      | -            | -                | -                | -         |    -0.17 | fleav, kory, ritchiEE, stressarN, xicoz |
|            2 |     7227 | 2024-09-10 | Sampi NEXT             | W   | 0.054      | 0.143        | 0.000 (0.000)    | 0.024 (0.000)    | 0 (0.000) |     0.85 | fleav, Q-Q, ritchiEE, stressarN, xicoz  |
|            1 |     7230 | 2024-09-10 | MADNESS (Kosovar team) | W   | 0.053      | 0.143        | 0.003 (0.000)    | 0.019 (0.000)    | 0 (0.000) |     0.95 | fleav, Q-Q, ritchiEE, stressarN, xicoz  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
