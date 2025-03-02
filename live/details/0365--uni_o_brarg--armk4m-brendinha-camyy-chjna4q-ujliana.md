### Roster Details<br />
Team Name: União BRARG<br />
Roster: armk4m, Brendinha, cAmyy, chjna4Q, ujliana<br />
Global Rank: [365](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [76]( ../standings_americas.md)<br />
<br />
Final Rank Value:  614.4<br />
<br />
Final Rank Value (614.4) = Starting Rank Value (623.1) + Head To Head Adjustments (-8.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.256[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.112<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 623.1
- 400 + ( ( 0.112 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 623.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     4169 | 2024-11-01 | Metanoia Female                   | W   | 0.401      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.87 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|           18 |     4173 | 2024-11-01 | Metanoia Female                   | W   | 0.401      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.94 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|           17 |     4177 | 2024-11-01 | Peak Academy Female               | L   | 0.401      | -            | -                | -                | -         |    -6.25 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|           16 |     4181 | 2024-11-01 | Peak Academy Female               | L   | 0.400      | -            | -                | -                | -         |    -6.47 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|           15 |     4343 | 2024-10-29 | Fluxo Demons                      | L   | 0.381      | -            | -                | -                | -         |    -3.66 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|           14 |     4346 | 2024-10-29 | Fluxo Demons                      | L   | 0.381      | -            | -                | -                | -         |    -3.76 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|           13 |     4396 | 2024-10-28 | Fire in The Hole (Brazilian team) | W   | 0.375      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.56 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|           12 |     4399 | 2024-10-28 | Fire in The Hole (Brazilian team) | W   | 0.374      | 0.143        | -                | 0.018 (0.001)    | 0 (0.000) |     2.61 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|           11 |     4875 | 2024-10-18 | MIBR Female                       | L   | 0.307      | -            | -                | -                | -         |    -4.65 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|           10 |     5712 | 2024-10-03 | Atrix Esports                     | W   | 0.207      | 0.323        | 0.005 (0.000)    | 0.215 (0.014)    | 0 (0.000) |     3.65 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|            9 |     6111 | 2024-09-27 | Thekillaz                         | L   | 0.167      | -            | -                | -                | -         |    -2.74 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|            8 |     6180 | 2024-09-26 | FURIA Esports Female              | L   | 0.160      | -            | -                | -                | -         |    -0.59 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|            7 |     6354 | 2024-09-24 | Capivaras                         | W   | 0.147      | 0.143        | 0.001 (0.000)    | 0.039 (0.001)    | 0 (0.000) |     1.67 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|            6 |     6439 | 2024-09-23 | Thekillaz                         | L   | 0.140      | -            | -                | -                | -         |    -2.31 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|            5 |     6738 | 2024-09-18 | Thekillaz                         | W   | 0.107      | 0.323        | 0.001 (0.000)    | 0.067 (0.002)    | 0 (0.000) |     1.63 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|            4 |     6964 | 2024-09-14 | Atrix Esports                     | W   | 0.081      | 0.143        | 0.005 (0.000)    | 0.215 (0.002)    | 0 (0.000) |     1.44 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|            3 |     6968 | 2024-09-14 | Peak Academy Female               | W   | 0.081      | 0.143        | 0.001 (0.000)    | 0.117 (0.001)    | 0 (0.000) |     1.24 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|            2 |     7121 | 2024-09-12 | Capivaras                         | W   | 0.067      | 0.323        | 0.001 (0.000)    | 0.039 (0.001)    | 0 (0.000) |     0.78 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |
|            1 |     7557 | 2024-09-05 | Peak Academy Female               | W   | 0.020      | 0.323        | 0.001 (0.000)    | -                | -         |     0.32 | armk4m, Brendinha, cAmyy, chjna4Q, ujliana |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($414.56)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-18 |      0.307 | $1,350.00      | $414.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
