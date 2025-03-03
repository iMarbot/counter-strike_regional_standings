### Roster Details<br />
Team Name: EC BANGA<br />
Roster: cgk, ChipaaN, nisker, whiskas, Zortexx<br />
Global Rank: [500](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [311]( ../standings_europe.md)<br />
<br />
Final Rank Value:  515.6<br />
<br />
Final Rank Value (515.6) = Starting Rank Value (496.1) + Head To Head Adjustments (19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.186[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.048<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 496.1
- 400 + ( ( 0.048 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 496.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     3317 | 2024-11-16 | Viperio         | W   | 0.492      | 0.284        | 0.002 (0.000)    | 0.404 (0.056)    | 0 (0.000) |    12.04 | cgk, ChipaaN, nisker, whiskas, Zortexx           |
|            5 |     3387 | 2024-11-15 | Diamant Esports | W   | 0.485      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.46 | cgk, ChipaaN, nisker, whiskas, Zortexx           |
|            4 |     7016 | 2024-09-14 | NewBALLS        | L   | 0.071      | -            | -                | -                | -         |    -0.64 | ChipaaN, ComputerGeeK, discplex, nisker, Zortexx |
|            3 |     7024 | 2024-09-14 | TryHearts       | W   | 0.070      | 0.215        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.00 | ChipaaN, ComputerGeeK, discplex, nisker, Zortexx |
|            2 |     7030 | 2024-09-14 | LEON Esports    | W   | 0.070      | 0.215        | 0.010 (0.000)    | 0.271 (0.004)    | 0 (0.000) |     1.82 | ChipaaN, ComputerGeeK, discplex, nisker, Zortexx |
|            1 |     7410 | 2024-09-07 | Chroma          | L   | 0.025      | -            | -                | -                | -         |    -0.20 | ChipaaN, ComputerGeeK, discplex, nisker, Zortexx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
