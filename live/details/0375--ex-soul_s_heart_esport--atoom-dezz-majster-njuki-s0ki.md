### Roster Details<br />
Team Name: Ex-Soul's Heart Esport<br />
Roster: atoom, dezz, Majster, njuki, s0ki<br />
Global Rank: [375](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [235]( ../standings_europe.md)<br />
<br />
Final Rank Value:  609.6<br />
<br />
Final Rank Value (609.6) = Starting Rank Value (631.4) + Head To Head Adjustments (-21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.201[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 631.4
- 400 + ( ( 0.116 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 631.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     3103 | 2024-11-20 | The Suspect                     | L   | 0.519      | -            | -                | -                | -         |    -5.83 | atoom, dezz, Majster, njuki, s0ki |
|           22 |     3117 | 2024-11-20 | Los kogutos                     | L   | 0.518      | -            | -                | -                | -         |    -2.76 | atoom, dezz, Majster, njuki, s0ki |
|           21 |     3202 | 2024-11-18 | Heimo Esports                   | L   | 0.505      | -            | -                | -                | -         |    -5.79 | atoom, dezz, Majster, njuki, s0ki |
|           20 |     3603 | 2024-11-11 | HOTU                            | L   | 0.459      | -            | -                | -                | -         |    -6.12 | atoom, dezz, Majster, njuki, s0ki |
|           19 |     3881 | 2024-11-06 | RUSTEC                          | L   | 0.425      | -            | -                | -                | -         |    -6.08 | atoom, dezz, Majster, njuki, s0ki |
|           18 |     3892 | 2024-11-06 | Passion UA                      | W   | 0.425      | 0.372        | 0.044 (0.007)    | 0.545 (0.086)    | 0 (0.000) |    11.94 | atoom, dezz, Majster, njuki, s0ki |
|           17 |     4302 | 2024-10-30 | GODSENT                         | L   | 0.379      | -            | -                | -                | -         |    -5.25 | atoom, dezz, Majster, njuki, s0ki |
|           16 |     4313 | 2024-10-30 | ALTERNATE aTTaX                 | L   | 0.378      | -            | -                | -                | -         |    -2.16 | atoom, dezz, Majster, njuki, s0ki |
|           15 |     4668 | 2024-10-23 | Kay Team                        | W   | 0.332      | 0.372        | 0.000 (0.000)    | 0.049 (0.006)    | 0 (0.000) |     3.66 | atoom, dezz, Majster, njuki, s0ki |
|           14 |     4673 | 2024-10-23 | TEAM NEXT LEVEL                 | L   | 0.331      | -            | -                | -                | -         |    -4.43 | atoom, dezz, Majster, njuki, s0ki |
|           13 |     5118 | 2024-10-14 | Ins (Polish team)               | L   | 0.271      | -            | -                | -                | -         |    -3.71 | atoom, dezz, Majster, njuki, s0ki |
|           12 |     5200 | 2024-10-12 | Los kogutos                     | W   | 0.258      | 0.143        | 0.032 (0.001)    | 0.515 (0.019)    | 0 (0.000) |     7.13 | atoom, dezz, Majster, njuki, s0ki |
|           11 |     5208 | 2024-10-12 | Ins (Polish team)               | L   | 0.258      | -            | -                | -                | -         |    -3.52 | atoom, dezz, Majster, njuki, s0ki |
|           10 |     5467 | 2024-10-07 | Mission Possible                | L   | 0.225      | -            | -                | -                | -         |    -4.53 | atoom, dezz, Majster, njuki, s0ki |
|            9 |     5471 | 2024-10-07 | Mollitiem                       | W   | 0.225      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.49 | atoom, dezz, Majster, njuki, s0ki |
|            8 |     6045 | 2024-09-28 | Ins (Polish team)               | W   | 0.164      | 0.143        | 0.004 (0.000)    | 0.274 (0.006)    | 0 (0.000) |     2.85 | atoom, dezz, Majster, njuki, s0ki |
|            7 |     6455 | 2024-09-23 | Rebels Gaming                   | L   | 0.132      | -            | -                | -                | -         |    -1.50 | atoom, dezz, Majster, njuki, s0ki |
|            6 |     6465 | 2024-09-23 | Dark Cloud Esports              | W   | 0.132      | 0.143        | 0.039 (0.001)    | 0.819 (0.015)    | 0 (0.000) |     3.16 | atoom, dezz, Majster, njuki, s0ki |
|            5 |     6886 | 2024-09-16 | Infinite Gaming                 | L   | 0.085      | -            | -                | -                | -         |    -1.51 | atoom, dezz, Majster, njuki, s0ki |
|            4 |     6929 | 2024-09-15 | Chroma                          | W   | 0.078      | 0.333        | 0.005 (0.000)    | 0.091 (0.002)    | 0 (0.000) |     1.42 | atoom, dezz, Majster, njuki, s0ki |
|            3 |     7258 | 2024-09-10 | Team Kosovo                     | L   | 0.044      | -            | -                | -                | -         |    -0.81 | atoom, dezz, Majster, njuki, s0ki |
|            2 |     7286 | 2024-09-09 | Donstu Esports                  | W   | 0.038      | 0.333        | 0.000 (0.000)    | 0.203 (0.003)    | 0 (0.000) |     0.39 | atoom, dezz, Majster, njuki, s0ki |
|            1 |     7574 | 2024-09-05 | Cerberus eSports (Russian team) | W   | 0.012      | 0.333        | 0.000 (0.000)    | 0.080 (0.000)    | 0 (0.000) |     0.17 | atoom, dezz, Majster, njuki, s0ki |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35.29)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.118 | $300.00        | $35.29          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
