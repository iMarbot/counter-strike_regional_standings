### Roster Details<br />
Team Name: Elite Klan Violet<br />
Roster: Emma, kim, Madam, Moraltis, Tess<br />
Global Rank: [626](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [383]( ../standings_europe.md)<br />
<br />
Final Rank Value:  373.0<br />
<br />
Final Rank Value (373.0) = Starting Rank Value (400.0) + Head To Head Adjustments (-27.0)<br />

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


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |      884 | 2025-02-05 | AKA HERO KAJO            | L   | 1.000      | -            | -                | -                | -         |    -4.13 | Emma, kim, Madam, Moraltis, Tess     |
|            7 |     1290 | 2024-12-28 | Also                     | L   | 0.780      | -            | -                | -                | -         |    -4.70 | Emma, kim, Madam, Moraltis, Tess     |
|            6 |     2078 | 2024-12-07 | 95 Vikings Female        | L   | 0.640      | -            | -                | -                | -         |    -9.66 | Emma, kim, Madam, Moraltis, Tess     |
|            5 |     2521 | 2024-11-30 | AKA HERO KAJO            | L   | 0.593      | -            | -                | -                | -         |    -2.13 | Emma, Jodiee, kim, Madam, Moraltis   |
|            4 |     3311 | 2024-11-16 | Also                     | L   | 0.500      | -            | -                | -                | -         |    -3.32 | Lowlita, Madam, Moraltis, oona, Tess |
|            3 |     5592 | 2024-10-05 | SoulEaters (Female team) | L   | 0.219      | -            | -                | -                | -         |    -3.45 | Lowlita, Madam, Moraltis, oona, Tess |
|            2 |     7429 | 2024-09-07 | NIP Impact               | L   | 0.032      | -            | -                | -                | -         |    -0.15 | Lowlita, Madam, Moraltis, oona, Tess |
|            1 |     7461 | 2024-09-07 | Needachance              | W   | 0.031      | 0.294        | 0.000 (0.000)    | 0.032 (0.000)    | 0 (0.000) |     0.49 | Lowlita, Madam, Moraltis, oona, Tess |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
