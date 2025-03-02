### Roster Details<br />
Team Name: VOID GAMING (Russian team)<br />
Roster: Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas<br />
Global Rank: [573](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [350]( ../standings_europe.md)<br />
<br />
Final Rank Value:  453.3<br />
<br />
Final Rank Value (453.3) = Starting Rank Value (475.3) + Head To Head Adjustments (-22.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.149[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.038<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 475.3
- 400 + ( ( 0.038 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 475.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     2334 | 2024-12-02 | NewBALLS              | L   | 0.607      | -            | -                | -                | -         |    -4.82 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            6 |     2511 | 2024-11-30 | Fragmatic             | W   | 0.593      | 0.333        | 0.000 (0.000)    | 0.069 (0.014)    | 0 (0.000) |    12.00 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            5 |     2723 | 2024-11-26 | VP.Prodigy            | L   | 0.567      | -            | -                | -                | -         |    -8.25 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            4 |     3747 | 2024-11-09 | RUSH B (Russian team) | L   | 0.451      | -            | -                | -                | -         |    -1.17 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            3 |     4018 | 2024-11-04 | QUAZAR Academy        | L   | 0.418      | -            | -                | -                | -         |    -7.67 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            2 |     4082 | 2024-11-03 | Donstu Esports        | L   | 0.411      | -            | -                | -                | -         |    -6.05 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            1 |     4814 | 2024-10-20 | ПuBo3aBpbI            | L   | 0.318      | -            | -                | -                | -         |    -6.02 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
