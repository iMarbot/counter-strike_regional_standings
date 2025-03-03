### Roster Details<br />
Team Name: Team Hungary<br />
Roster: Aaron, coolio, kory, noleN, xavi<br />
Global Rank: [126](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
<br />
Final Rank Value:  792.2<br />
<br />
Final Rank Value (792.2) = Starting Rank Value (766.4) + Head To Head Adjustments (25.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.183[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.272[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 766.4
- 400 + ( ( 0.183 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 766.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     3395 | 2024-11-15 | ALTERNATE aTTaX               | L   | 0.485      | -            | -                | -                | -         |    -5.06 | Aaron, coolio, kory, noleN, xavi  |
|           11 |     3406 | 2024-11-15 | Team Kosovo                   | W   | 0.484      | 0.617        | 0.000 (0.000)    | 0.004 (0.001)    | 1 (0.484) |     3.28 | Aaron, coolio, kory, noleN, xavi  |
|           10 |     3470 | 2024-11-14 | Team Chile                    | W   | 0.477      | 0.617        | 0.000 (0.000)    | 0.045 (0.013)    | 1 (0.477) |     2.88 | Aaron, coolio, kory, noleN, xavi  |
|            9 |     3474 | 2024-11-14 | MAFE MA3LOM                   | W   | 0.477      | 0.617        | 0.000 (0.000)    | 0.022 (0.007)    | 1 (0.477) |     2.69 | Aaron, coolio, kory, noleN, xavi  |
|            8 |     3482 | 2024-11-14 | GTZ.ESPORTS                   | L   | 0.477      | -            | -                | -                | -         |    -1.68 | Aaron, coolio, kory, noleN, xavi  |
|            7 |     3731 | 2024-11-09 | Budapest Five                 | W   | 0.445      | 0.143        | 0.002 (0.000)    | 0.071 (0.005)    | 1 (0.445) |     4.62 | Aaron, balage, Kamion, kory, xavi |
|            6 |     3758 | 2024-11-09 | SKIBIDIES                     | W   | 0.443      | 0.143        | 0.001 (0.000)    | 0.052 (0.003)    | 1 (0.443) |     3.94 | Aaron, balage, Kamion, kory, xavi |
|            5 |     4296 | 2024-10-30 | ManageYself                   | W   | 0.379      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.75 | Aaron, coolio, Kamion, kory, xavi |
|            4 |     4322 | 2024-10-30 | Myztro Gaming                 | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     2.85 | Aaron, coolio, Kamion, kory, xavi |
|            3 |     4606 | 2024-10-25 | Budapest Five                 | W   | 0.344      | 0.143        | 0.002 (0.000)    | 0.071 (0.004)    | 0 (0.000) |     3.60 | Aaron, coolio, Kamion, kory, xavi |
|            2 |     4661 | 2024-10-23 | SKIBIDIES                     | W   | 0.332      | 0.143        | 0.001 (0.000)    | 0.052 (0.002)    | 0 (0.000) |     3.24 | Aaron, coolio, Kamion, kory, xavi |
|            1 |     4776 | 2024-10-20 | Békéscsabai E-Sport Egyesület | W   | 0.312      | 0.143        | 0.000 (0.000)    | 0.034 (0.002)    | 0 (0.000) |     2.65 | Aaron, coolio, Kamion, kory, xavi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($729.57)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.445 | $1,053.31      | $468.31         |
| 2024-11-01 |      0.392 | $666.10        | $261.26         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
