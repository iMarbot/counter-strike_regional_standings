### Roster Details<br />
Team Name: INWESKO<br />
Roster: HexoQ, Panar, r1pper3, Sleezy, sm0kkk<br />
Global Rank: [544](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [335]( ../standings_europe.md)<br />
<br />
Final Rank Value:  482.0<br />
<br />
Final Rank Value (482.0) = Starting Rank Value (484.6) + Head To Head Adjustments (-2.6)<br />

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
- 400 + ( ( 0.042 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 484.6


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
|            7 |     3157 | 2024-11-19 | MightyWolves          | W   | 0.512      | 0.143        | 0.000 (0.000)    | 0.039 (0.003)    | 0 (0.000) |     6.46 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            6 |     3238 | 2024-11-17 | CyberMAN              | L   | 0.498      | -            | -                | -                | -         |    -8.18 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            5 |     3941 | 2024-11-05 | HAVENs                | L   | 0.418      | -            | -                | -                | -         |    -8.08 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            4 |     4463 | 2024-10-27 | Hypewrld              | W   | 0.358      | 0.143        | 0.002 (0.000)    | 0.185 (0.009)    | 0 (0.000) |     9.04 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            3 |     4788 | 2024-10-20 | Sunshine!             | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.74 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            2 |     5138 | 2024-10-13 | Way2go (Latvian team) | L   | 0.265      | -            | -                | -                | -         |    -2.52 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |
|            1 |     5526 | 2024-10-06 | EC BANGA              | L   | 0.218      | -            | -                | -                | -         |    -3.06 | HexoQ, Panar, r1pper3, Sleezy, sm0kkk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
