### Roster Details<br />
Team Name: Ex-GODSENT<br />
Roster: Brillo, mogv, Silence, Svedjehed, titulus<br />
Global Rank: [444](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [277]( ../standings_europe.md)<br />
<br />
Final Rank Value:  562.2<br />
<br />
Final Rank Value (562.2) = Starting Rank Value (516.5) + Head To Head Adjustments (45.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.058<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 516.5
- 400 + ( ( 0.058 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 516.5


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
|            9 |      973 | 2025-02-04 | 9INE                       | L   | 1.000      | -            | -                | -                | -         |    -3.21 | Brillo, mogv, Silence, Svedjehed, titulus |
|            8 |      988 | 2025-02-04 | EYEBALLERS                 | W   | 1.000      | 0.143        | 0.019 (0.003)    | 0.356 (0.051)    | 0 (0.000) |    25.81 | Brillo, mogv, Silence, Svedjehed, titulus |
|            7 |     1460 | 2024-12-21 | Betclic Apogee Esports     | L   | 0.732      | -            | -                | -                | -         |    -3.27 | Brillo, mogv, Silence, TIM, tvs           |
|            6 |     1498 | 2024-12-20 | Mission Possible           | L   | 0.727      | -            | -                | -                | -         |   -11.50 | Brillo, mogv, robiin, Silence, tvs        |
|            5 |     1511 | 2024-12-20 | 500                        | L   | 0.726      | -            | -                | -                | -         |    -1.56 | Brillo, mogv, Silence, TIM, tvs           |
|            4 |     1764 | 2024-12-13 | NEVERMORE (Ukrainian team) | L   | 0.681      | -            | -                | -                | -         |    -3.59 | Brillo, mogv, Silence, TIM, tvs           |
|            3 |     1772 | 2024-12-13 | BadGuys                    | W   | 0.680      | 0.143        | 0.000 (0.000)    | 0.281 (0.027)    | 0 (0.000) |    12.50 | Brillo, mogv, Silence, TIM, tvs           |
|            2 |     1779 | 2024-12-13 | The Suspect                | W   | 0.680      | 0.143        | 0.003 (0.000)    | 0.220 (0.021)    | 0 (0.000) |    15.70 | Brillo, mogv, Silence, TIM, tvs           |
|            1 |     1783 | 2024-12-13 | Wu-Tang Clan               | W   | 0.680      | 0.143        | 0.001 (0.000)    | 0.218 (0.021)    | 0 (0.000) |    14.86 | Brillo, mogv, Silence, TIM, tvs           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
