### Roster Details<br />
Team Name: Pikejagarna<br />
Roster: Fabbelit0, GAME, Malmie, Robski, z1egers<br />
Global Rank: [599](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [365]( ../standings_europe.md)<br />
<br />
Final Rank Value:  403.2<br />
<br />
Final Rank Value (403.2) = Starting Rank Value (400.0) + Head To Head Adjustments (3.1)<br />

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


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     4850 | 2024-10-19 | Venom (Swedish team) | L   | 0.312      | -            | -                | -                | -         |    -3.87 | Fabbelit0, GAME, Malmie, Robski, z1egers |
|            5 |     4925 | 2024-10-17 | Lemondogs            | W   | 0.299      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     5.67 | Fabbelit0, GAME, Malmie, Robski, z1egers |
|            4 |     5102 | 2024-10-14 | Alliance             | L   | 0.279      | -            | -                | -                | -         |    -0.55 | Fabbelit0, GAME, Malmie, Robski, z1egers |
|            3 |     6128 | 2024-09-27 | Lilmix               | L   | 0.166      | -            | -                | -                | -         |    -1.02 | AvoY, frigolito, GAME, Malmie, z1egers   |
|            2 |     6914 | 2024-09-15 | KILLBOX              | W   | 0.087      | 0.143        | 0.000 (0.000)    | 0.020 (0.000)    | 0 (0.000) |     1.63 | Fabbelit0, GAME, Malmie, Robski, z1egers |
|            1 |     6981 | 2024-09-14 | Snapphanar           | W   | 0.080      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.25 | Fabbelit0, GAME, Malmie, Robski, z1egers |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
