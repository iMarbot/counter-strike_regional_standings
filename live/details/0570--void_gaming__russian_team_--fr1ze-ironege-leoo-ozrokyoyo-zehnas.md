### Roster Details<br />
Team Name: VOID GAMING (Russian team)<br />
Roster: Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas<br />
Global Rank: [570](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [349]( ../standings_europe.md)<br />
<br />
Final Rank Value:  453.6<br />
<br />
Final Rank Value (453.6) = Starting Rank Value (475.2) + Head To Head Adjustments (-21.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.149[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.038<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 475.2
- 400 + ( ( 0.038 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 475.2


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
|            7 |     2346 | 2024-12-02 | NewBALLS              | L   | 0.598      | -            | -                | -                | -         |    -4.77 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            6 |     2523 | 2024-11-30 | Fragmatic             | W   | 0.585      | 0.333        | 0.000 (0.000)    | 0.068 (0.013)    | 0 (0.000) |    11.81 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            5 |     2735 | 2024-11-26 | VP.Prodigy            | L   | 0.558      | -            | -                | -                | -         |    -8.15 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            4 |     3759 | 2024-11-09 | RUSH B (Russian team) | L   | 0.443      | -            | -                | -                | -         |    -1.15 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            3 |     4030 | 2024-11-04 | QUAZAR Academy        | L   | 0.410      | -            | -                | -                | -         |    -7.53 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            2 |     4094 | 2024-11-03 | Donstu Esports        | L   | 0.403      | -            | -                | -                | -         |    -5.94 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |
|            1 |     4826 | 2024-10-20 | ПuBo3aBpbI            | L   | 0.309      | -            | -                | -                | -         |    -5.86 | Fr1ze, ironege, Leoo, Ozrokyoyo, zehnas |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
