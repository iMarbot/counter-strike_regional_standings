### Roster Details<br />
Team Name: INWESKO<br />
Roster: HexoQ, Panar, r1pper3, Sleezy, sm0kkk<br />
Global Rank: [546](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [338]( ../standings_europe.md)<br />
<br />
Final Rank Value:  482.0<br />
<br />
Final Rank Value (482.0) = Starting Rank Value (484.6) + Head To Head Adjustments (-2.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.168[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.042<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 484.6
- 400 + ( ( 0.042 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 484.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3145 | 2024-11-19 | MightyWolves          | W   | 0.520      | 0.143        | 0.000 (0.000)    | 0.040 (0.003)    | 0 (0.000) |     6.57 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            6 |     3226 | 2024-11-17 | CyberMAN              | L   | 0.507      | -            | -                | -                | -         |    -8.32 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            5 |     3929 | 2024-11-05 | HAVENs                | L   | 0.427      | -            | -                | -                | -         |    -8.23 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            4 |     4451 | 2024-10-27 | Hypewrld              | W   | 0.367      | 0.143        | 0.002 (0.000)    | 0.187 (0.010)    | 0 (0.000) |     9.25 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            3 |     4776 | 2024-10-20 | Sunshine!             | W   | 0.319      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.84 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            2 |     5126 | 2024-10-13 | Way2go (Latvian team) | L   | 0.273      | -            | -                | -                | -         |    -2.60 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            1 |     5514 | 2024-10-06 | EC BANGA              | L   | 0.226      | -            | -                | -                | -         |    -3.18 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
