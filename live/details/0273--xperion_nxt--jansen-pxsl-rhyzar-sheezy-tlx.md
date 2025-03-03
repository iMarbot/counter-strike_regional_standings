### Roster Details<br />
Team Name: XPERION NXT<br />
Roster: jansen, pxsl, Rhyzar, sheezy, tlx<br />
Global Rank: [273](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [186]( ../standings_europe.md)<br />
<br />
Final Rank Value:  667.4<br />
<br />
Final Rank Value (667.4) = Starting Rank Value (643.5) + Head To Head Adjustments (23.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.267[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 643.5
- 400 + ( ( 0.122 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 643.5


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
|           23 |     1884 | 2024-12-11 | WOPA Esport                     | L   | 0.659      | -            | -                | -                | -         |    -6.08 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           22 |     1932 | 2024-12-10 | ZennoX                          | W   | 0.652      | 0.333        | 0.001 (0.000)    | 0.084 (0.018)    | 0 (0.000) |    10.26 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           21 |     2013 | 2024-12-08 | NewBALLS                        | W   | 0.638      | 0.333        | 0.001 (0.000)    | 0.268 (0.057)    | 0 (0.000) |    10.44 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           20 |     2335 | 2024-12-02 | AMKAL ESPORTS                   | L   | 0.599      | -            | -                | -                | -         |    -5.74 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           19 |     2520 | 2024-11-30 | BRUTE                           | W   | 0.585      | 0.333        | 0.004 (0.001)    | 0.341 (0.066)    | 0 (0.000) |    10.82 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           18 |     2622 | 2024-11-28 | FALKE ESPORTS                   | W   | 0.572      | 0.333        | 0.000 (0.000)    | 0.041 (0.008)    | 0 (0.000) |     3.84 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           17 |     4073 | 2024-11-03 | Permitta Esports                | L   | 0.404      | -            | -                | -                | -         |    -3.82 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           16 |     4153 | 2024-11-02 | SNOGARD Dragons                 | W   | 0.397      | 0.143        | 0.000 (0.000)    | 0.037 (0.002)    | 0 (0.000) |     5.30 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           15 |     4203 | 2024-11-01 | BIG                             | L   | 0.392      | -            | -                | -                | -         |    -0.11 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           14 |     4306 | 2024-10-30 | ALTERNATE aTTaX                 | L   | 0.379      | -            | -                | -                | -         |    -2.27 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           13 |     4442 | 2024-10-28 | BIG                             | L   | 0.365      | -            | -                | -                | -         |    -0.10 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           12 |     4744 | 2024-10-21 | Permitta Esports                | L   | 0.318      | -            | -                | -                | -         |    -3.13 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           11 |     5115 | 2024-10-14 | Regnum4Games                    | W   | 0.271      | 0.143        | 0.002 (0.000)    | 0.112 (0.004)    | 0 (0.000) |     4.01 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           10 |     5349 | 2024-10-09 | Sissi State Punks               | L   | 0.238      | -            | -                | -                | -         |    -4.20 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            9 |     5919 | 2024-09-30 | ESports Cologne                 | W   | 0.178      | -            | -                | -                | 0 (0.000) |     1.53 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            8 |     6468 | 2024-09-23 | Wave Esports                    | W   | 0.132      | 0.143        | 0.002 (0.000)    | 0.110 (0.002)    | 0 (0.000) |     1.99 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            7 |     6764 | 2024-09-18 | SNOGARD Dragons                 | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.037 (0.001)    | 0 (0.000) |     1.34 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            6 |     6937 | 2024-09-15 | Infinite Gaming                 | L   | 0.078      | -            | -                | -                | -         |    -1.43 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            5 |     7075 | 2024-09-13 | Rejected by all                 | W   | 0.065      | -            | -                | -                | 0 (0.000) |     0.56 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            4 |     7196 | 2024-09-11 | Cerberus eSports (Russian team) | W   | 0.051      | 0.333        | 0.000 (0.000)    | 0.080 (0.001)    | -         |     0.70 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            3 |     7307 | 2024-09-09 | Kubix Esports                   | L   | 0.038      | -            | -                | -                | -         |    -0.20 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            2 |     7582 | 2024-09-05 | BAKS Esports                    | W   | 0.012      | 0.333        | -                | 0.151 (0.001)    | -         |     0.12 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            1 |     7656 | 2024-09-04 | MYinsanity                      | W   | 0.005      | 0.143        | 0.002 (0.000)    | -                | -         |     0.08 | jansen, pxsl, Rhyzar, sheezy, tlx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($588.54)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.684 | $600.00        | $410.42         |
| 2024-12-14 |      0.678 | $262.62        | $178.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
