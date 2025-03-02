### Roster Details<br />
Team Name: Lore Gaming<br />
Roster: hyza, JoJo, ondyey, seNsite, SlooKy<br />
Global Rank: [596](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [362]( ../standings_europe.md)<br />
<br />
Final Rank Value:  404.8<br />
<br />
Final Rank Value (404.8) = Starting Rank Value (400.0) + Head To Head Adjustments (4.8)<br />

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


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     5756 | 2024-10-02 | Legacy                  | L   | 0.201      | -            | -                | -                | -         |    -0.38 | hyza, JoJo, ondyey, seNsite, SlooKy |
|            5 |     6337 | 2024-09-24 | InControl               | W   | 0.148      | 0.371        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     2.33 | hyza, JoJo, ondyey, seNsite, SlooKy |
|            4 |     6500 | 2024-09-22 | Penance (American Team) | W   | 0.133      | 0.371        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     2.10 | hyza, JoJo, ondyey, seNsite, SlooKy |
|            3 |     6727 | 2024-09-18 | What's for Dinner       | W   | 0.108      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.70 | hyza, JoJo, ondyey, seNsite, SlooKy |
|            2 |     6960 | 2024-09-14 | Final Form              | L   | 0.082      | -            | -                | -                | -         |    -0.60 | hyza, JoJo, ondyey, seNsite, SlooKy |
|            1 |     7110 | 2024-09-12 | Homyno                  | L   | 0.068      | -            | -                | -                | -         |    -0.32 | hyza, JoJo, ondyey, seNsite, SlooKy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
