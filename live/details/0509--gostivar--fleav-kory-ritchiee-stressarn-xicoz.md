### Roster Details<br />
Team Name: GOSTIVAR<br />
Roster: fleav, kory, ritchiEE, stressarN, xicoz<br />
Global Rank: [509](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [314]( ../standings_europe.md)<br />
<br />
Final Rank Value:  504.3<br />
<br />
Final Rank Value (504.3) = Starting Rank Value (494.8) + Head To Head Adjustments (9.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.047<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 494.8
- 400 + ( ( 0.047 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 494.8


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
|            7 |     4414 | 2024-10-28 | Haspers Team           | L   | 0.366      | -            | -                | -                | -         |    -2.73 | fleav, kory, ritchiEE, stressarN, xicoz |
|            6 |     5420 | 2024-10-08 | Haspers Team           | W   | 0.232      | 0.143        | 0.013 (0.000)    | 0.171 (0.006)    | 0 (0.000) |     5.57 | fleav, kory, ritchiEE, stressarN, xicoz |
|            5 |     5959 | 2024-09-29 | ENTERPRISE Genesis     | W   | 0.172      | 0.143        | 0.001 (0.000)    | 0.175 (0.004)    | 0 (0.000) |     3.76 | fleav, kory, ritchiEE, stressarN, xicoz |
|            4 |     6379 | 2024-09-24 | Error404               | W   | 0.138      | 0.143        | 0.000 (0.000)    | 0.014 (0.000)    | 0 (0.000) |     1.61 | fleav, kory, ritchiEE, stressarN, xicoz |
|            3 |     6396 | 2024-09-24 | Dynamo Eclot           | L   | 0.138      | -            | -                | -                | -         |    -0.16 | fleav, kory, ritchiEE, stressarN, xicoz |
|            2 |     7239 | 2024-09-10 | Sampi NEXT             | W   | 0.046      | 0.143        | 0.000 (0.000)    | 0.022 (0.000)    | 0 (0.000) |     0.72 | fleav, Q-Q, ritchiEE, stressarN, xicoz  |
|            1 |     7242 | 2024-09-10 | MADNESS (Kosovar team) | W   | 0.045      | 0.143        | 0.003 (0.000)    | 0.018 (0.000)    | 0 (0.000) |     0.80 | fleav, Q-Q, ritchiEE, stressarN, xicoz  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
