### Roster Details<br />
Team Name: BBBCBMBS<br />
Roster: ApeX, Arcay, Dirty, HaZ, muffin<br />
Global Rank: [602](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [99]( ../standings_asia.md)<br />
<br />
Final Rank Value:  402.4<br />
<br />
Final Rank Value (402.4) = Starting Rank Value (400.7) + Head To Head Adjustments (1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.7
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      397 | 2025-02-15 | MANTRA               | L   | 1.000      | -            | -                | -                | -         |    -7.84 | ApeX, Arcay, Dirty, HaZ, muffin |
|            5 |      463 | 2025-02-14 | Housebets            | L   | 1.000      | -            | -                | -                | -         |    -8.12 | ApeX, Arcay, Dirty, HaZ, muffin |
|            4 |     1055 | 2025-02-01 | SemperFi Esports     | L   | 1.000      | -            | -                | -                | -         |    -8.13 | ApeX, Arcay, Dirty, HaZ, muffin |
|            3 |     1057 | 2025-02-01 | Justice For Tomorrow | L   | 1.000      | -            | -                | -                | -         |    -6.66 | ApeX, Arcay, Dirty, HaZ, muffin |
|            2 |     1082 | 2025-01-31 | Brojay and Co        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    14.95 | ApeX, Arcay, Dirty, HaZ, muffin |
|            1 |     1088 | 2025-01-31 | PrevailANZ           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    17.54 | ApeX, Arcay, Dirty, HaZ, muffin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
