### Roster Details<br />
Team Name: Godne<br />
Roster: Ekuz, IPA, pat_u, SPE7S, Tmirts<br />
Global Rank: [617](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [376]( ../standings_europe.md)<br />
<br />
Final Rank Value:  393.0<br />
<br />
Final Rank Value (393.0) = Starting Rank Value (400.1) + Head To Head Adjustments (-7.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.1
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     2789 | 2024-11-24 | ANimaleGG                 | L   | 0.545      | -            | -                | -                | -         |    -6.61 | Ekuz, IPA, pat_u, SPE7S, Tmirts |
|            7 |     3239 | 2024-11-17 | W2TE                      | W   | 0.498      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     7.63 | Ekuz, IPA, pat_u, SPE7S, Tmirts |
|            6 |     3677 | 2024-11-10 | FullShock (Estonian team) | W   | 0.451      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     7.19 | Ekuz, IPA, pat_u, SPE7S, Tmirts |
|            5 |     4047 | 2024-11-03 | GENESIS (Estonian team)   | L   | 0.405      | -            | -                | -                | -         |    -4.51 | Ekuz, IPA, pat_u, SPE7S, Tmirts |
|            4 |     4470 | 2024-10-27 | ANimaleGG                 | L   | 0.358      | -            | -                | -                | -         |    -4.33 | Ekuz, IPA, pat_u, SPE7S, Tmirts |
|            3 |     4779 | 2024-10-20 | Truck Drivers             | L   | 0.312      | -            | -                | -                | -         |    -1.52 | Ekuz, IPA, pat_u, SPE7S, Tmirts |
|            2 |     5145 | 2024-10-13 | SHOO7ERS                  | L   | 0.264      | -            | -                | -                | -         |    -1.57 | Ekuz, IPA, pat_u, SPE7S, Tmirts |
|            1 |     5535 | 2024-10-06 | M1Z                       | L   | 0.217      | -            | -                | -                | -         |    -3.41 | Ekuz, IPA, pat_u, SPE7S, Tmirts |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
