### Roster Details<br />
Team Name: Flame Sharks<br />
Roster: 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza<br />
Global Rank: [364](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [233]( ../standings_europe.md)<br />
<br />
Final Rank Value:  615.7<br />
<br />
Final Rank Value (615.7) = Starting Rank Value (647.6) + Head To Head Adjustments (-31.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.226[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 647.6
- 400 + ( ( 0.124 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 647.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      241 | 2025-02-20 | Wolves eSports        | L   | 1.000      | -            | -                | -                | -         |   -21.48 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           23 |      456 | 2025-02-14 | ALGO                  | L   | 1.000      | -            | -                | -                | -         |   -21.59 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           22 |      621 | 2025-02-09 | K27                   | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.776 (0.111)    | 0 (0.000) |    21.40 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           21 |      629 | 2025-02-09 | FLuffy Gangsters      | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.925 (0.132)    | 0 (0.000) |    22.53 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           20 |      974 | 2025-02-04 | ENRAGE                | L   | 1.000      | -            | -                | -                | -         |   -15.62 | 7tetsu, PsychoDoctor, Vopsick, xm1nd, Yakuza |
|           19 |     1679 | 2024-12-14 | Underrated            | L   | 0.687      | -            | -                | -                | -         |   -10.05 | 7tetsu, HEiS, PsychoDoctor, xm1nd, Yakuza    |
|           18 |     2478 | 2024-11-30 | GameAgents            | L   | 0.594      | -            | -                | -                | -         |   -10.09 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           17 |     2722 | 2024-11-26 | FLuffy Gangsters      | L   | 0.567      | -            | -                | -                | -         |    -4.41 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           16 |     2835 | 2024-11-23 | FLuffy Gangsters      | L   | 0.547      | -            | -                | -                | -         |    -4.49 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           15 |     2840 | 2024-11-23 | 4z                    | W   | 0.547      | 0.262        | 0.004 (0.001)    | 0.142 (0.020)    | 0 (0.000) |     8.52 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           14 |     3019 | 2024-11-21 | Nuclear TigeRES       | W   | 0.533      | 0.372        | 0.004 (0.001)    | 0.586 (0.116)    | 0 (0.000) |    12.06 | 7tetsu, Dis1, verbal4buser, xm1nd, Yakuza    |
|           13 |     4551 | 2024-10-26 | Aimhaus               | L   | 0.358      | -            | -                | -                | -         |    -8.12 | 7tetsu, Dis1, Wadeshot, xm1nd, Yakuza        |
|           12 |     6009 | 2024-09-28 | K27                   | L   | 0.173      | -            | -                | -                | -         |    -0.97 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|           11 |     6029 | 2024-09-28 | MASONIC               | W   | 0.173      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.09 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|           10 |     6519 | 2024-09-22 | NewBALLS              | L   | 0.132      | -            | -                | -                | -         |    -2.00 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            9 |     6572 | 2024-09-21 | Ex-DOSKI              | W   | 0.126      | 0.143        | 0.000 (0.000)    | 0.020 (0.000)    | 0 (0.000) |     0.79 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            8 |     6753 | 2024-09-18 | THE GENTLEMEN ESPORTS | L   | 0.106      | -            | -                | -                | -         |    -1.48 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            7 |     6819 | 2024-09-17 | Infinite Gaming       | W   | 0.100      | 0.333        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.32 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            6 |     6873 | 2024-09-16 | QUAZAR                | L   | 0.093      | -            | -                | -                | -         |    -1.22 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            5 |     7072 | 2024-09-13 | THE GENTLEMEN ESPORTS | W   | 0.073      | 0.333        | 0.001 (0.000)    | 0.269 (0.007)    | 0 (0.000) |     1.28 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            4 |     7275 | 2024-09-09 | XI Esport             | W   | 0.047      | 0.333        | 0.001 (0.000)    | 0.287 (0.004)    | 0 (0.000) |     0.80 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            3 |     7494 | 2024-09-06 | Team PeeP             | L   | 0.027      | -            | -                | -                | -         |    -0.59 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            2 |     7505 | 2024-09-06 | Team OWL              | W   | 0.026      | 0.221        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     0.23 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |
|            1 |     7567 | 2024-09-05 | GoodCall              | W   | 0.020      | 0.333        | -                | 0.002 (0.000)    | -         |     0.16 | 7tetsu, Dis1, reNIK, xm1nd, Yakuza           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($125.83)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.126 | $1,000.00      | $125.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
