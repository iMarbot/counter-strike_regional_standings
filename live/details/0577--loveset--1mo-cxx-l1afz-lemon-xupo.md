### Roster Details<br />
Team Name: Loveset<br />
Roster: 1Mo, CXX, L1afz, Lemon, xupo<br />
Global Rank: [577](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [93]( ../standings_asia.md)<br />
<br />
Final Rank Value:  428.6<br />
<br />
Final Rank Value (428.6) = Starting Rank Value (402.7) + Head To Head Adjustments (25.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.001<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 402.7
- 400 + ( ( 0.001 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 402.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      434 | 2025-02-15 | Change The Game | L   | 1.000      | -            | -                | -                | -         |    -5.65 | 1Mo, CXX, L1afz, Lemon, xupo    |
|            5 |      441 | 2025-02-15 | Boring Players  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.344 (0.049)    | 0 (0.000) |    20.08 | 1Mo, CXX, L1afz, Lemon, xupo    |
|            4 |      447 | 2025-02-14 | E9 Esports      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.037 (0.005)    | 0 (0.000) |    19.02 | 1Mo, CXX, L1afz, Lemon, xupo    |
|            3 |      456 | 2025-02-14 | XNL Gaming      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    15.86 | 1Mo, CXX, L1afz, Lemon, xupo    |
|            2 |      878 | 2025-02-05 | LaiShanHui      | L   | 1.000      | -            | -                | -                | -         |   -15.17 | 1Mo, CXX, L1afz, Lemon, xupo    |
|            1 |     1252 | 2024-12-30 | Boring Players  | L   | 0.783      | -            | -                | -                | -         |    -8.30 | 1Mo, Cxx, L1afz, Lem0nCat, xupo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
