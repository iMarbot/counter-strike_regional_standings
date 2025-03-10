### Roster Details<br />
Team Name: Ex-GODSENT<br />
Roster: Brillo, mogv, Silence, Svedjehed, titulus<br />
Global Rank: [448](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [278]( ../standings_europe.md)<br />
<br />
Final Rank Value:  561.9<br />
<br />
Final Rank Value (561.9) = Starting Rank Value (516.6) + Head To Head Adjustments (45.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.058<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 516.6
- 400 + ( ( 0.058 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 516.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |      985 | 2025-02-04 | 9INE                       | L   | 1.000      | -            | -                | -                | -         |    -3.24 | Brillo, mogv, Silence, Svedjehed, titulus |
|            8 |     1000 | 2025-02-04 | EYEBALLERS                 | W   | 1.000      | 0.143        | 0.019 (0.003)    | 0.350 (0.050)    | 0 (0.000) |    25.79 | Brillo, mogv, Silence, Svedjehed, titulus |
|            7 |     1472 | 2024-12-21 | Betclic Apogee Esports     | L   | 0.724      | -            | -                | -                | -         |    -3.25 | Brillo, mogv, Silence, TIM, tvs           |
|            6 |     1510 | 2024-12-20 | Mission Possible           | L   | 0.719      | -            | -                | -                | -         |   -11.40 | Brillo, mogv, robiin, Silence, tvs        |
|            5 |     1523 | 2024-12-20 | 500                        | L   | 0.717      | -            | -                | -                | -         |    -1.54 | Brillo, mogv, Silence, TIM, tvs           |
|            4 |     1776 | 2024-12-13 | NEVERMORE (Ukrainian team) | L   | 0.672      | -            | -                | -                | -         |    -3.56 | Brillo, mogv, Silence, TIM, tvs           |
|            3 |     1784 | 2024-12-13 | BadGuys                    | W   | 0.672      | 0.143        | 0.000 (0.000)    | 0.279 (0.027)    | 0 (0.000) |    12.33 | Brillo, mogv, Silence, TIM, tvs           |
|            2 |     1791 | 2024-12-13 | The Suspect                | W   | 0.672      | 0.143        | 0.003 (0.000)    | 0.216 (0.021)    | 0 (0.000) |    15.49 | Brillo, mogv, Silence, TIM, tvs           |
|            1 |     1795 | 2024-12-13 | Wu-Tang Clan               | W   | 0.671      | 0.143        | 0.001 (0.000)    | 0.216 (0.021)    | 0 (0.000) |    14.68 | Brillo, mogv, Silence, TIM, tvs           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
