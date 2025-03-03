### Roster Details<br />
Team Name: Revenant Esports<br />
Roster: lauNX, NBK-, Neityu, Nivera, reiko<br />
Global Rank: [513](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [318]( ../standings_europe.md)<br />
<br />
Final Rank Value:  500.6<br />
<br />
Final Rank Value (500.6) = Starting Rank Value (500.4) + Head To Head Adjustments (0.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 500.4
- 400 + ( ( 0.050 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 500.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     6539 | 2024-09-22 | Team Space      | L   | 0.123      | -            | -                | -                | -         |    -1.96 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            8 |     6595 | 2024-09-21 | GUN5 Esports    | L   | 0.117      | -            | -                | -                | -         |    -0.31 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            7 |     7012 | 2024-09-14 | SINNERS Esports | W   | 0.071      | 0.384        | 0.027 (0.001)    | 0.446 (0.012)    | 0 (0.000) |     2.03 | lauNX, NBK-, Neityu, Nivera, reiko |
|            6 |     7259 | 2024-09-10 | Insilio         | L   | 0.044      | -            | -                | -                | -         |    -0.36 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            5 |     7311 | 2024-09-09 | EYEBALLERS      | L   | 0.038      | -            | -                | -                | -         |    -0.18 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            4 |     7471 | 2024-09-07 | AMKAL ESPORTS   | W   | 0.023      | 0.384        | 0.002 (0.000)    | 0.674 (0.006)    | 0 (0.000) |     0.59 | 0SAMAS, lauNX, NBK-, Nivera, reiko |
|            3 |     7525 | 2024-09-06 | JANO Esports    | W   | 0.018      | 0.435        | 0.022 (0.000)    | 0.440 (0.003)    | 0 (0.000) |     0.52 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            2 |     7602 | 2024-09-05 | Preasy Esport   | L   | 0.011      | -            | -                | -                | -         |    -0.05 | lauNX, NBK-, Nivera, reiko, tiziaN |
|            1 |     7641 | 2024-09-05 | Tricked Esport  | L   | 0.009      | -            | -                | -                | -         |    -0.04 | lauNX, NBK-, Nivera, reiko, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
