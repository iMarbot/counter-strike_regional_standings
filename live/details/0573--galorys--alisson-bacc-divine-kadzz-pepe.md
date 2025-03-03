### Roster Details<br />
Team Name: Galorys<br />
Roster: Alisson, bacc, divine, Kadzz, pepe<br />
Global Rank: [573](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [134]( ../standings_americas.md)<br />
<br />
Final Rank Value:  446.9<br />
<br />
Final Rank Value (446.9) = Starting Rank Value (403.5) + Head To Head Adjustments (43.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.002<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 403.5
- 400 + ( ( 0.002 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 403.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |      286 | 2025-02-17 | Bounty Hunters Esports | L   | 1.000      | -            | -                | -                | -         |    -3.94 | Alisson, bacc, divine, Kadzz, pepe |
|            4 |      288 | 2025-02-17 | VELOX Argentina        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.262 (0.037)    | 0 (0.000) |    19.41 | Alisson, bacc, divine, Kadzz, pepe |
|            3 |      294 | 2025-02-17 | W7m esports            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.234 (0.033)    | 0 (0.000) |    19.24 | Alisson, bacc, divine, Kadzz, pepe |
|            2 |      674 | 2025-02-08 | Nitro.GG               | L   | 1.000      | -            | -                | -                | -         |    -6.08 | Alisson, bacc, divine, Kadzz, pepe |
|            1 |      755 | 2025-02-07 | 20/70                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    14.69 | Alisson, bacc, divine, Kadzz, pepe |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
