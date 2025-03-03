### Roster Details<br />
Team Name: RED Canids Academy<br />
Roster: edv, FasteR, gtw, n0page, sanc<br />
Global Rank: [176](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  733.3<br />
<br />
Final Rank Value (733.3) = Starting Rank Value (685.0) + Head To Head Adjustments (48.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.302[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.0
- 400 + ( ( 0.142 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 685.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |     1834 | 2024-12-12 | Players (Brazilian team) | L   | 0.666      | -            | -                | -                | -         |    -9.26 | edv, FasteR, gtw, n0page, sanc    |
|           27 |     1889 | 2024-12-11 | MIBR Academy             | W   | 0.659      | 0.143        | 0.001 (0.000)    | 0.464 (0.044)    | 0 (0.000) |     9.46 | edv, FasteR, gtw, n0page, sanc    |
|           26 |     1982 | 2024-12-08 | AMIGOS (Brazilian team)  | W   | 0.640      | -            | -                | -                | 0 (0.000) |     4.67 | edv, FasteR, gtw, n0page, sanc    |
|           25 |     2135 | 2024-12-06 | Pugdesonesto             | W   | 0.625      | -            | -                | -                | 0 (0.000) |     3.96 | edv, FasteR, gtw, n0page, sanc    |
|           24 |     2268 | 2024-12-03 | 9z Academy               | L   | 0.606      | -            | -                | -                | -         |   -11.39 | edv, FasteR, gtw, n0page, sanc    |
|           23 |     2508 | 2024-11-30 | Players (Brazilian team) | W   | 0.585      | 0.143        | 0.008 (0.001)    | 0.632 (0.053)    | 0 (0.000) |    10.32 | edv, FasteR, gtw, n0page, sanc    |
|           22 |     2590 | 2024-11-29 | Galorys Academy          | W   | 0.579      | -            | -                | -                | 0 (0.000) |     6.67 | edv, FasteR, gtw, n0page, sanc    |
|           21 |     2665 | 2024-11-27 | AMIGOS (Brazilian team)  | W   | 0.566      | -            | -                | -                | 0 (0.000) |     4.35 | edv, FasteR, gtw, n0page, sanc    |
|           20 |     3085 | 2024-11-20 | PaiN Gaming Academy      | W   | 0.519      | 0.143        | -                | 0.219 (0.016)    | 0 (0.000) |     3.77 | edv, FasteR, gtw, n0page, sanc    |
|           19 |     3385 | 2024-11-15 | Players (Brazilian team) | W   | 0.485      | 0.143        | 0.008 (0.001)    | 0.632 (0.044)    | 0 (0.000) |     8.61 | edv, FasteR, gtw, n0page, sanc    |
|           18 |     3705 | 2024-11-09 | MIBR Academy             | L   | 0.446      | -            | -                | -                | -         |    -7.40 | edv, FasteR, gtw, n0page, sanc    |
|           17 |     3795 | 2024-11-08 | AMIGOS (Brazilian team)  | W   | 0.439      | -            | -                | -                | 0 (0.000) |     3.64 | edv, FasteR, gtw, n0page, sanc    |
|           16 |     4051 | 2024-11-03 | UNO MILLE                | L   | 0.405      | -            | -                | -                | -         |    -5.99 | edv, FasteR, gtw, n0page, sanc    |
|           15 |     4110 | 2024-11-02 | Intense Game             | W   | 0.400      | 0.333        | 0.003 (0.000)    | 0.192 (0.026)    | 0 (0.000) |     5.90 | edv, FasteR, gtw, n0page, sanc    |
|           14 |     4285 | 2024-10-30 | Dusty Roots              | W   | 0.380      | 0.333        | 0.009 (0.001)    | 0.366 (0.046)    | -         |     6.95 | edv, FasteR, gtw, n0page, sanc    |
|           13 |     4289 | 2024-10-30 | Intense Game             | L   | 0.380      | -            | -                | -                | -         |    -6.45 | edv, FasteR, gtw, n0page, sanc    |
|           12 |     4434 | 2024-10-28 | Galorys Academy          | W   | 0.365      | -            | -                | -                | -         |     4.80 | edv, FasteR, gtw, n0page, sanc    |
|           11 |     4654 | 2024-10-23 | UNO MILLE                | W   | 0.332      | 0.333        | 0.010 (0.001)    | 0.522 (0.058)    | -         |     5.74 | edv, FasteR, gtw, n0page, sanc    |
|           10 |     4704 | 2024-10-22 | 20/70                    | W   | 0.325      | -            | -                | -                | -         |     4.39 | edv, FasteR, gtw, n0page, sanc    |
|            9 |     4978 | 2024-10-16 | 20/70                    | W   | 0.287      | 0.333        | 0.001 (0.000)    | 0.286 (0.027)    | -         |     3.97 | edv, FasteR, gtw, n0page, sanc    |
|            8 |     4985 | 2024-10-16 | Bounty Hunters Esports   | L   | 0.286      | -            | -                | -                | -         |    -5.03 | edv, FasteR, gtw, n0page, sanc    |
|            7 |     5721 | 2024-10-03 | Galorys Academy          | L   | 0.199      | -            | -                | -                | -         |    -3.60 | edv, FasteR, gtw, n0page, sanc    |
|            6 |     5769 | 2024-10-02 | Dusty Roots              | W   | 0.192      | 0.333        | 0.009 (0.001)    | 0.366 (0.023)    | -         |     3.85 | edv, FasteR, gtw, n0page, sanc    |
|            5 |     6260 | 2024-09-25 | Intense Game             | W   | 0.147      | 0.333        | 0.003 (0.000)    | -                | -         |     2.14 | edv, FasteR, gtw, n0page, sanc    |
|            4 |     6472 | 2024-09-23 | PaiN Gaming Academy      | W   | 0.132      | -            | -                | -                | -         |     1.11 | edv, FasteR, n0page, sanc, santos |
|            3 |     6740 | 2024-09-18 | UNO MILLE                | W   | 0.100      | 0.333        | 0.010 (0.000)    | 0.522 (0.017)    | -         |     1.81 | edv, FasteR, gtw, n0page, sanc    |
|            2 |     6746 | 2024-09-18 | 20/70                    | W   | 0.099      | -            | -                | -                | -         |     1.43 | edv, FasteR, gtw, n0page, sanc    |
|            1 |     7657 | 2024-09-04 | Yawara E-Sports          | L   | 0.005      | -            | -                | -                | -         |    -0.08 | edv, FasteR, gtw, n0page, sanc    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,594.18)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-30 |      0.585 | $1,339.06      | $783.91         |
| 2024-11-03 |      0.405 | $2,000.00      | $810.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
