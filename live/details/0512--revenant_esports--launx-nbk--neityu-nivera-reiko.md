### Roster Details<br />
Team Name: Revenant Esports<br />
Roster: lauNX, NBK-, Neityu, Nivera, reiko<br />
Global Rank: [512](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [318]( ../standings_europe.md)<br />
<br />
Final Rank Value:  502.5<br />
<br />
Final Rank Value (502.5) = Starting Rank Value (502.0) + Head To Head Adjustments (0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.202[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 502.0
- 400 + ( ( 0.051 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 502.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     6527 | 2024-09-22 | Team Space         | L   | 0.131      | -            | -                | -                | -         |    -2.09 | lauNX, NBK-, Nivera, reiko, tiziaN |
|           10 |     6583 | 2024-09-21 | GUN5 Esports       | L   | 0.125      | -            | -                | -                | -         |    -0.33 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            9 |     7000 | 2024-09-14 | SINNERS Esports    | W   | 0.079      | 0.384        | 0.027 (0.001)    | 0.451 (0.014)    | 0 (0.000) |     2.26 | lauNX, NBK-, Neityu, Nivera, reiko |
|            8 |     7247 | 2024-09-10 | Insilio            | L   | 0.052      | -            | -                | -                | -         |    -0.43 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            7 |     7299 | 2024-09-09 | EYEBALLERS         | L   | 0.046      | -            | -                | -                | -         |    -0.22 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            6 |     7459 | 2024-09-07 | AMKAL ESPORTS      | W   | 0.031      | 0.384        | 0.002 (0.000)    | 0.681 (0.008)    | 0 (0.000) |     0.79 | 0SAMAS, lauNX, NBK-, Nivera, reiko |
|            5 |     7513 | 2024-09-06 | JANO Esports       | W   | 0.026      | 0.435        | 0.022 (0.000)    | 0.442 (0.005)    | 0 (0.000) |     0.75 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            4 |     7590 | 2024-09-05 | Preasy Esport      | L   | 0.019      | -            | -                | -                | -         |    -0.09 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            3 |     7629 | 2024-09-05 | Tricked Esport     | L   | 0.017      | -            | -                | -                | -         |    -0.07 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            2 |     7732 | 2024-09-03 | G2 Ares            | L   | 0.006      | -            | -                | -                | -         |    -0.05 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            1 |     7754 | 2024-09-03 | CYBERSHOKE Esports | L   | 0.004      | -            | -                | -                | -         |    -0.01 | lauNX, NBK-, Nivera, reiko, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
