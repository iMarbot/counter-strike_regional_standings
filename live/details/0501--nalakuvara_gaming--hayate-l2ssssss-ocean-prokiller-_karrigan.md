### Roster Details<br />
Team Name: Nalakuvara Gaming<br />
Roster: Hayate, L2ssssss, ocean, Prokiller, 小karrigan<br />
Global Rank: [501](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [81]( ../standings_asia.md)<br />
<br />
Final Rank Value:  515.3<br />
<br />
Final Rank Value (515.3) = Starting Rank Value (509.5) + Head To Head Adjustments (5.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 509.5
- 400 + ( ( 0.055 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 509.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      335 | 2025-02-16 | LaiShanHui                | L   | 1.000      | -            | -                | -                | -         |   -21.16 | Hayate, L2ssssss, ocean, Prokiller, 小karrigan |
|            5 |     1435 | 2024-12-22 | FengDa Gaming             | L   | 0.729      | -            | -                | -                | -         |    -6.82 | Hayate, L2ssssss, ocean, toxic, Zero          |
|            4 |     1555 | 2024-12-19 | Teamwork (Chinese team)   | L   | 0.710      | -            | -                | -                | -         |    -7.09 | Hayate, L2ssssss, ocean, toxic, Zero          |
|            3 |     1906 | 2024-12-11 | Just Swing (Chinese team) | W   | 0.657      | 0.372        | 0.005 (0.001)    | 0.346 (0.085)    | 0 (0.000) |    16.00 | Hayate, L2ssssss, ocean, toxic, Zero          |
|            2 |     2557 | 2024-11-30 | XNL Gaming                | W   | 0.583      | 0.143        | 0.003 (0.000)    | 0.090 (0.008)    | 0 (0.000) |    12.39 | Hayate, L2ssssss, ocean, toxic, Zero          |
|            1 |     2565 | 2024-11-29 | Win New Star              | W   | 0.582      | 0.143        | 0.002 (0.000)    | 0.083 (0.007)    | 0 (0.000) |    12.46 | Hayate, L2ssssss, ocean, toxic, Zero          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
