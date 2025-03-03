### Roster Details<br />
Team Name: CyberMAN<br />
Roster: ASTR, Dabok, H1kari, meowpop, vladick<br />
Global Rank: [559](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [343]( ../standings_europe.md)<br />
<br />
Final Rank Value:  471.9<br />
<br />
Final Rank Value (471.9) = Starting Rank Value (480.6) + Head To Head Adjustments (-8.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.160[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.040<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 480.6
- 400 + ( ( 0.040 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 480.6


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
|            8 |     2733 | 2024-11-26 | HAVENs                | L   | 0.558      | -            | -                | -                | -         |   -10.45 | ASTR, Dabok, H1kari, meowpop, vladick |
|            7 |     2788 | 2024-11-24 | EC BANGA              | W   | 0.545      | 0.143        | 0.001 (0.000)    | 0.096 (0.007)    | 0 (0.000) |     9.59 | ASTR, Dabok, H1kari, meowpop, vladick |
|            6 |     3238 | 2024-11-17 | INWESKO               | W   | 0.498      | 0.143        | 0.000 (0.000)    | 0.055 (0.004)    | 0 (0.000) |     8.18 | ASTR, Dabok, H1kari, meowpop, vladick |
|            5 |     3938 | 2024-11-05 | MightyWolves          | L   | 0.419      | -            | -                | -                | -         |    -7.82 | ASTR, Dabok, H1kari, meowpop, vladick |
|            4 |     4707 | 2024-10-22 | Way2go (Latvian team) | L   | 0.325      | -            | -                | -                | -         |    -2.95 | ASTR, Dabok, H1kari, meowpop, vladick |
|            3 |     4778 | 2024-10-20 | HAVENs                | L   | 0.312      | -            | -                | -                | -         |    -6.05 | ASTR, Dabok, H1kari, meowpop, vladick |
|            2 |     5424 | 2024-10-08 | Hypewrld              | L   | 0.232      | -            | -                | -                | -         |    -1.45 | ASTR, Dabok, H1kari, meowpop, vladick |
|            1 |     5853 | 2024-10-01 | Sunshine!             | W   | 0.185      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.26 | ASTR, Dabok, H1kari, meowpop, vladick |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
