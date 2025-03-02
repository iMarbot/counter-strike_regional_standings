### Roster Details<br />
Team Name: XPERION NXT<br />
Roster: jansen, pxsl, Rhyzar, sheezy, tlx<br />
Global Rank: [269](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [187]( ../standings_europe.md)<br />
<br />
Final Rank Value:  668.1<br />
<br />
Final Rank Value (668.1) = Starting Rank Value (643.4) + Head To Head Adjustments (24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.267[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 643.4
- 400 + ( ( 0.122 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 643.4


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
|           23 |     1872 | 2024-12-11 | WOPA Esport                     | L   | 0.667      | -            | -                | -                | -         |    -6.16 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           22 |     1920 | 2024-12-10 | ZennoX                          | W   | 0.660      | 0.333        | 0.001 (0.000)    | 0.085 (0.019)    | 0 (0.000) |    10.38 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           21 |     2001 | 2024-12-08 | NewBALLS                        | W   | 0.646      | 0.333        | 0.001 (0.000)    | 0.272 (0.059)    | 0 (0.000) |    10.58 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           20 |     2323 | 2024-12-02 | AMKAL ESPORTS                   | L   | 0.607      | -            | -                | -                | -         |    -5.77 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           19 |     2508 | 2024-11-30 | BRUTE                           | W   | 0.593      | 0.333        | 0.004 (0.001)    | 0.345 (0.068)    | 0 (0.000) |    10.96 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           18 |     2610 | 2024-11-28 | FALKE ESPORTS                   | W   | 0.580      | 0.333        | 0.000 (0.000)    | 0.042 (0.008)    | 0 (0.000) |     3.90 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           17 |     4061 | 2024-11-03 | Permitta Esports                | L   | 0.412      | -            | -                | -                | -         |    -3.89 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           16 |     4141 | 2024-11-02 | SNOGARD Dragons                 | W   | 0.406      | 0.143        | 0.000 (0.000)    | 0.039 (0.002)    | 0 (0.000) |     5.40 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           15 |     4191 | 2024-11-01 | BIG                             | L   | 0.400      | -            | -                | -                | -         |    -0.11 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           14 |     4294 | 2024-10-30 | ALTERNATE aTTaX                 | L   | 0.387      | -            | -                | -                | -         |    -2.30 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           13 |     4430 | 2024-10-28 | BIG                             | L   | 0.373      | -            | -                | -                | -         |    -0.10 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           12 |     4732 | 2024-10-21 | Permitta Esports                | L   | 0.326      | -            | -                | -                | -         |    -3.20 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           11 |     5103 | 2024-10-14 | Regnum4Games                    | W   | 0.279      | 0.143        | 0.002 (0.000)    | 0.115 (0.005)    | 0 (0.000) |     4.12 | jansen, pxsl, Rhyzar, sheezy, tlx |
|           10 |     5337 | 2024-10-09 | Sissi State Punks               | L   | 0.246      | -            | -                | -                | -         |    -4.34 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            9 |     5907 | 2024-09-30 | ESports Cologne                 | W   | 0.186      | -            | -                | -                | 0 (0.000) |     1.60 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            8 |     6456 | 2024-09-23 | Wave Esports                    | W   | 0.140      | 0.143        | 0.001 (0.000)    | 0.113 (0.002)    | 0 (0.000) |     2.11 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            7 |     6752 | 2024-09-18 | SNOGARD Dragons                 | W   | 0.106      | 0.143        | 0.000 (0.000)    | 0.039 (0.001)    | 0 (0.000) |     1.45 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            6 |     6925 | 2024-09-15 | Infinite Gaming                 | L   | 0.086      | -            | -                | -                | -         |    -1.57 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            5 |     7063 | 2024-09-13 | Rejected by all                 | W   | 0.073      | -            | -                | -                | 0 (0.000) |     0.63 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            4 |     7184 | 2024-09-11 | Cerberus eSports (Russian team) | W   | 0.059      | 0.333        | 0.000 (0.000)    | 0.081 (0.002)    | -         |     0.81 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            3 |     7295 | 2024-09-09 | Kubix Esports                   | L   | 0.046      | -            | -                | -                | -         |    -0.24 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            2 |     7570 | 2024-09-05 | BAKS Esports                    | W   | 0.020      | 0.333        | -                | 0.153 (0.001)    | -         |     0.21 | jansen, pxsl, Rhyzar, sheezy, tlx |
|            1 |     7644 | 2024-09-04 | MYinsanity                      | W   | 0.013      | 0.143        | 0.002 (0.000)    | -                | -         |     0.22 | jansen, pxsl, Rhyzar, sheezy, tlx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($595.61)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.692 | $600.00        | $415.33         |
| 2024-12-14 |      0.686 | $262.62        | $180.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
