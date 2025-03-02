### Roster Details<br />
Team Name: Wave Esports<br />
Roster: DayMake, klyrO, sjN, syncD, XCR<br />
Global Rank: [338](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [220]( ../standings_europe.md)<br />
<br />
Final Rank Value:  628.8<br />
<br />
Final Rank Value (628.8) = Starting Rank Value (626.1) + Head To Head Adjustments (2.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.261[<sup>1</sup>](#table2)
- Bounty Collected: 0.186[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 626.1
- 400 + ( ( 0.113 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 626.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     3609 | 2024-11-11 | Team Fragster            | L   | 0.466      | -            | -                | -                | -         |    -7.91 | DayMake, klyrO, sjN, syncD, XCR |
|           22 |     4140 | 2024-11-02 | Permitta Esports         | L   | 0.406      | -            | -                | -                | -         |    -3.77 | Alxc, GHOST, sjN, syncD, XCR    |
|           21 |     4308 | 2024-10-30 | Sissi State Punks        | W   | 0.386      | 0.143        | 0.000 (0.000)    | 0.068 (0.004)    | 0 (0.000) |     5.38 | Alxc, klyrO, sjN, syncD, XCR    |
|           20 |     4355 | 2024-10-29 | SNOGARD Dragons          | W   | 0.380      | 0.143        | 0.000 (0.000)    | 0.039 (0.002)    | 0 (0.000) |     5.37 | Alxc, GHOST, sjN, syncD, XCR    |
|           19 |     4412 | 2024-10-28 | Permitta Esports         | L   | 0.374      | -            | -                | -                | -         |    -3.36 | Alxc, GHOST, sjN, syncD, XCR    |
|           18 |     4447 | 2024-10-27 | Regnum4Games             | L   | 0.367      | -            | -                | -                | -         |    -5.80 | Alxc, GHOST, sjN, syncD, XCR    |
|           17 |     4464 | 2024-10-27 | Reveal (German team)     | W   | 0.366      | 0.143        | 0.001 (0.000)    | 0.192 (0.010)    | 0 (0.000) |     5.97 | Alxc, GHOST, sjN, syncD, XCR    |
|           16 |     4501 | 2024-10-26 | Regnum4Games             | L   | 0.360      | -            | -                | -                | -         |    -5.78 | Alxc, GHOST, sjN, syncD, XCR    |
|           15 |     4593 | 2024-10-25 | MYinsanity               | W   | 0.352      | 0.143        | 0.002 (0.000)    | 0.086 (0.004)    | 0 (0.000) |     5.85 | Alxc, GHOST, sjN, syncD, XCR    |
|           14 |     4697 | 2024-10-22 | Regnum4Games             | W   | 0.333      | 0.143        | 0.002 (0.000)    | 0.115 (0.005)    | 0 (0.000) |     5.24 | Alxc, GHOST, sjN, syncD, XCR    |
|           13 |     4762 | 2024-10-20 | ALTERNATE aTTaX Evo      | W   | 0.320      | 0.143        | 0.001 (0.000)    | 0.184 (0.008)    | 0 (0.000) |     4.96 | Alxc, GHOST, sjN, syncD, XCR    |
|           12 |     5002 | 2024-10-16 | BIG                      | L   | 0.292      | -            | -                | -                | -         |    -0.07 | Alxc, GHOST, sjN, syncD, XCR    |
|           11 |     5111 | 2024-10-14 | Daystar                  | L   | 0.279      | -            | -                | -                | -         |    -4.11 | alxc, GHOST, sjN, syncD, XCR    |
|           10 |     5191 | 2024-10-12 | Ex-Dynamo Eclot Thunders | L   | 0.266      | -            | -                | -                | -         |    -4.63 | alxc, GHOST, sjN, syncD, XCR    |
|            9 |     5330 | 2024-10-09 | SNOGARD Dragons          | W   | 0.247      | 0.143        | 0.000 (0.000)    | 0.039 (0.001)    | 0 (0.000) |     3.52 | Alxc, GHOST, sjN, syncD, XCR    |
|            8 |     5724 | 2024-10-03 | KUUSAMO.gg               | W   | 0.205      | 0.278        | -                | 0.164 (0.009)    | 0 (0.000) |     2.20 | alxc, GHOST, sjN, syncD, XCR    |
|            7 |     5906 | 2024-09-30 | MYinsanity               | L   | 0.186      | -            | -                | -                | -         |    -2.77 | Alxc, GHOST, sjN, syncD, XCR    |
|            6 |     6456 | 2024-09-23 | XPERION NXT              | L   | 0.140      | -            | -                | -                | -         |    -2.11 | Alxc, GHOST, sjN, syncD, XCR    |
|            5 |     6812 | 2024-09-17 | MYinsanity               | W   | 0.100      | 0.143        | 0.002 (0.000)    | 0.086 (0.001)    | 0 (0.000) |     1.69 | Alxc, GHOST, sjN, syncD, XCR    |
|            4 |     6878 | 2024-09-16 | Regnum4Games             | W   | 0.093      | 0.143        | 0.002 (0.000)    | 0.115 (0.002)    | 0 (0.000) |     1.47 | Alxc, GHOST, sjN, syncD, XCR    |
|            3 |     7168 | 2024-09-11 | ESports Cologne          | W   | 0.060      | -            | -                | -                | -         |     0.56 | Alxc, GHOST, sjN, syncD, XCR    |
|            2 |     7243 | 2024-09-10 | Sissi State Punks        | W   | 0.053      | 0.143        | 0.000 (0.000)    | -                | -         |     0.77 | Alxc, GHOST, sjN, syncD, XCR    |
|            1 |     7664 | 2024-09-04 | Playing Ducks            | W   | 0.013      | -            | -                | -                | -         |     0.09 | Alxc, GHOST, sjN, syncD, XCR    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($504.48)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.686 | $157.57        | $108.17         |
| 2024-10-27 |      0.367 | $1,079.97      | $396.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
