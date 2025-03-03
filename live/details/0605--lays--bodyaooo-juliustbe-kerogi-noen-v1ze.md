### Roster Details<br />
Team Name: Lays<br />
Roster: bodyaooo, juliustbe, kerogi, noeN, v1ze<br />
Global Rank: [605](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [368]( ../standings_europe.md)<br />
<br />
Final Rank Value:  401.5<br />
<br />
Final Rank Value (401.5) = Starting Rank Value (400.0) + Head To Head Adjustments (1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     7086 | 2024-09-13 | Chroma       | L   | 0.065      | -            | -                | -                | -         |    -0.35 | bodyaooo, juliustbe, kerogi, noeN, v1ze |
|            4 |     7250 | 2024-09-10 | Astra Gaming | W   | 0.045      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.71 | bodyaooo, juliustbe, kerogi, noeN, v1ze |
|            3 |     7296 | 2024-09-09 | The Boys     | W   | 0.038      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.60 | bodyaooo, jeakzz, juliustbe, noeN, v1ze |
|            2 |     7412 | 2024-09-07 | Sampi NEXT   | W   | 0.025      | 0.333        | 0.000 (0.000)    | 0.022 (0.000)    | 0 (0.000) |     0.50 | bodyaooo, jeakzz, juliustbe, noeN, v1ze |
|            1 |     7678 | 2024-09-04 | Lazer Cats   | L   | 0.005      | -            | -                | -                | -         |    -0.02 | bodyaooo, juliustbe, kerogi, noeN, v1ze |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
