### Roster Details<br />
Team Name: Guará eSports<br />
Roster: fnb, neskk, rato, sapatosocial, spider<br />
Global Rank: [567](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [132]( ../standings_americas.md)<br />
<br />
Final Rank Value:  459.7<br />
<br />
Final Rank Value (459.7) = Starting Rank Value (476.3) + Head To Head Adjustments (-16.6)<br />

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
- 400 + ( ( 0.038 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 476.3


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
|            6 |      342 | 2025-02-16 | Seleção do BT   | L   | 1.000      | -            | -                | -                | -         |   -18.80 | fnb, neskk, rato, sapatosocial, spider    |
|            5 |     2207 | 2024-12-04 | Yawara E-Sports | L   | 0.613      | -            | -                | -                | -         |    -4.42 | fnb, liporace, maNiny, rato, sapatosocial |
|            4 |     2260 | 2024-12-03 | X7 Team         | W   | 0.607      | 0.262        | 0.000 (0.000)    | 0.054 (0.009)    | 0 (0.000) |    13.04 | fnb, liporace, maNiny, rato, sapatosocial |
|            3 |     2863 | 2024-11-23 | INTERDIT        | L   | 0.538      | -            | -                | -                | -         |    -5.46 | fnb, liporace, maNiny, rato, sapatosocial |
|            2 |     6997 | 2024-09-14 | Nitro.GG        | L   | 0.071      | -            | -                | -                | -         |    -0.55 | fnb, liporace, maNiny, rato, sapatosocial |
|            1 |     7174 | 2024-09-11 | Floripa Stars   | L   | 0.053      | -            | -                | -                | -         |    -0.45 | fnb, liporace, maNiny, rato, sapatosocial |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
