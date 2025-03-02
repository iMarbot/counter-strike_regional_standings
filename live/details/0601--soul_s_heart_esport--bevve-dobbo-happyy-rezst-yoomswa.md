### Roster Details<br />
Team Name: Soul's Heart Esport<br />
Roster: bevve, dobbo, Happyy, Rezst, yoomswa<br />
Global Rank: [601](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [367]( ../standings_europe.md)<br />
<br />
Final Rank Value:  402.8<br />
<br />
Final Rank Value (402.8) = Starting Rank Value (400.8) + Head To Head Adjustments (2.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.8
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |      750 | 2025-02-07 | SINNERS Esports      | L   | 1.000      | -            | -                | -                | -         |    -1.74 | bevve, dobbo, Happyy, Rezst, yoomswa  |
|            4 |     1363 | 2024-12-24 | Dragon Esports Club  | L   | 0.751      | -            | -                | -                | -         |    -4.04 | bevve, DEPRESHN, Rezst, sSen, yoomswa |
|            3 |     1371 | 2024-12-23 | Venom (Swedish team) | W   | 0.747      | 0.333        | 0.000 (0.000)    | 0.063 (0.016)    | 0 (0.000) |    14.31 | bevve, DEPRESHN, dobbo, Rezst, sSen   |
|            2 |     1386 | 2024-12-22 | Dragon Esports Club  | L   | 0.740      | -            | -                | -                | -         |    -3.56 | bevve, DEPRESHN, Rezst, sSen, yoomswa |
|            1 |     1490 | 2024-12-20 | HOTU                 | L   | 0.727      | -            | -                | -                | -         |    -2.91 | bevve, Diviiii, Rezst, sSen, yoomswa  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
