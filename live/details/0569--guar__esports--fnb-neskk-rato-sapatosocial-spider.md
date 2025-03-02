### Roster Details<br />
Team Name: Guará eSports<br />
Roster: fnb, neskk, rato, sapatosocial, spider<br />
Global Rank: [569](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [133]( ../standings_americas.md)<br />
<br />
Final Rank Value:  459.6<br />
<br />
Final Rank Value (459.6) = Starting Rank Value (476.3) + Head To Head Adjustments (-16.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.152[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.038<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 476.3
- 400 + ( ( 0.038 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 476.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      330 | 2025-02-16 | Seleção do BT   | L   | 1.000      | -            | -                | -                | -         |   -18.80 | fnb, neskk, rato, sapatosocial, spider    |
|            5 |     2195 | 2024-12-04 | Yawara E-Sports | L   | 0.621      | -            | -                | -                | -         |    -4.45 | fnb, liporace, maNiny, rato, sapatosocial |
|            4 |     2248 | 2024-12-03 | X7 Team         | W   | 0.615      | 0.262        | 0.000 (0.000)    | 0.055 (0.009)    | 0 (0.000) |    13.21 | fnb, liporace, maNiny, rato, sapatosocial |
|            3 |     2851 | 2024-11-23 | INTERDIT        | L   | 0.547      | -            | -                | -                | -         |    -5.53 | fnb, liporace, maNiny, rato, sapatosocial |
|            2 |     6985 | 2024-09-14 | Nitro.GG        | L   | 0.080      | -            | -                | -                | -         |    -0.61 | fnb, liporace, maNiny, rato, sapatosocial |
|            1 |     7162 | 2024-09-11 | Floripa Stars   | L   | 0.061      | -            | -                | -                | -         |    -0.52 | fnb, liporace, maNiny, rato, sapatosocial |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
