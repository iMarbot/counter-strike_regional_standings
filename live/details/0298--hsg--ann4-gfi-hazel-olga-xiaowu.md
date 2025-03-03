### Roster Details<br />
Team Name: HSG<br />
Roster: Ann4, GFi, Hazel, olga, XiaoWu<br />
Global Rank: [298](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [42]( ../standings_asia.md)<br />
<br />
Final Rank Value:  651.0<br />
<br />
Final Rank Value (651.0) = Starting Rank Value (641.4) + Head To Head Adjustments (9.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.267[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 641.4
- 400 + ( ( 0.121 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 641.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     4895 | 2024-10-18 | BIG EQUIPA            | W   | 0.298      | 0.328        | 0.021 (0.002)    | 0.057 (0.006)    | 0 (0.000) |     6.32 | Ann4, GFi, Hazel, olga, XiaoWu |
|            9 |     5545 | 2024-10-06 | OneDay                | W   | 0.217      | 0.250        | 0.000 (0.000)    | 0.148 (0.008)    | 0 (0.000) |     3.09 | Ann4, GFi, Hazel, olga, XiaoWu |
|            8 |     5599 | 2024-10-05 | SAW Myst              | W   | 0.211      | 0.250        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     1.90 | Ann4, GFi, Hazel, olga, XiaoWu |
|            7 |     5606 | 2024-10-05 | WOPA Impact           | W   | 0.211      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.38 | Ann4, GFi, Hazel, olga, XiaoWu |
|            6 |     6199 | 2024-09-26 | Nomercy (Female team) | L   | 0.151      | -            | -                | -                | -         |    -2.17 | Ann4, GFi, Hazel, olga, XiaoWu |
|            5 |     6704 | 2024-09-19 | Imperial Female       | L   | 0.105      | -            | -                | -                | -         |    -0.35 | Ann4, GFi, Hazel, olga, XiaoWu |
|            4 |     7052 | 2024-09-14 | Imperial Female       | L   | 0.070      | -            | -                | -                | -         |    -0.23 | Ann4, GFi, Hazel, olga, XiaoWu |
|            3 |     7140 | 2024-09-12 | K27 Female            | L   | 0.058      | -            | -                | -                | -         |    -0.76 | Ann4, GFi, Hazel, olga, XiaoWu |
|            2 |     7446 | 2024-09-07 | ENCE Athena           | W   | 0.024      | 0.294        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.26 | Ann4, GFi, Hazel, olga, XiaoWu |
|            1 |     7478 | 2024-09-07 | Kitchen Squad         | W   | 0.023      | 0.294        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.15 | Ann4, GFi, Hazel, olga, XiaoWu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($598.55)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.311 | $1,400.00      | $435.94         |
| 2024-10-06 |      0.217 | $750.00        | $162.60         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
