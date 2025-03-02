### Roster Details<br />
Team Name: CONTINENTAL (Russian team)<br />
Roster: fEITAN, HANETi, haponia, mokaen2, tras<br />
Global Rank: [597](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [363]( ../standings_europe.md)<br />
<br />
Final Rank Value:  404.5<br />
<br />
Final Rank Value (404.5) = Starting Rank Value (400.0) + Head To Head Adjustments (4.5)<br />

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
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |      364 | 2025-02-16 | Taimyr                  | L   | 1.000      | -            | -                | -                | -         |   -15.24 | fEITAN, HANETi, haponia, mokaen2, tras |
|            4 |      376 | 2025-02-16 | Klopz team              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    14.88 | fEITAN, HANETi, haponia, mokaen2, tras |
|            3 |      487 | 2025-02-14 | Nomads (Mongolian team) | L   | 1.000      | -            | -                | -                | -         |    -9.55 | dato, fEITAN, HANETi, haponia, mokaen2 |
|            2 |      491 | 2025-02-14 | D13                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    15.12 | dato, fEITAN, HANETi, haponia, mokaen2 |
|            1 |     7197 | 2024-09-11 | THE (Russian team)      | L   | 0.058      | -            | -                | -                | -         |    -0.72 | aicea, Fyzy, HANETi, haponia, tras     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
