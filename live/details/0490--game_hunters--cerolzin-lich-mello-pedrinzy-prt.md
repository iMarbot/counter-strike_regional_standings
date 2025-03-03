### Roster Details<br />
Team Name: Game Hunters<br />
Roster: cerolzin, Lich, mello, pedrinzy, prt<br />
Global Rank: [490](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [110]( ../standings_americas.md)<br />
<br />
Final Rank Value:  524.5<br />
<br />
Final Rank Value (524.5) = Starting Rank Value (500.1) + Head To Head Adjustments (24.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.184[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 500.1
- 400 + ( ( 0.050 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 500.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     2655 | 2024-11-28 | Dusty Roots     | L   | 0.571      | -            | -                | -                | -         |    -3.84 | cerolzin, Lich, mello, pedrinzy, prt |
|            4 |     2755 | 2024-11-25 | Floripa Stars   | W   | 0.553      | 0.371        | 0.001 (0.000)    | 0.296 (0.061)    | 0 (0.000) |    11.91 | cerolzin, Lich, mello, pedrinzy, prt |
|            3 |     2839 | 2024-11-23 | TROPA DO TACO   | L   | 0.539      | -            | -                | -                | -         |    -3.39 | cerolzin, Lich, mello, pedrinzy, prt |
|            2 |     3049 | 2024-11-21 | 20/70           | W   | 0.524      | 0.371        | 0.001 (0.000)    | 0.286 (0.056)    | 0 (0.000) |    11.45 | cerolzin, Lich, mello, pedrinzy, prt |
|            1 |     3218 | 2024-11-18 | VELOX Argentina | W   | 0.504      | 0.371        | 0.000 (0.000)    | 0.262 (0.049)    | 0 (0.000) |     8.30 | cerolzin, Lich, mello, pedrinzy, prt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
