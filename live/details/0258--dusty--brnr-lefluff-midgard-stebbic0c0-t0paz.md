### Roster Details<br />
Team Name: DUSTY<br />
Roster: brnr, leFluff, Midgard, StebbiC0C0, T0PAZ<br />
Global Rank: [258](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [180]( ../standings_europe.md)<br />
<br />
Final Rank Value:  675.0<br />
<br />
Final Rank Value (675.0) = Starting Rank Value (693.2) + Head To Head Adjustments (-18.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.058[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.2
- 400 + ( ( 0.147 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 693.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     2868 | 2024-11-23 | KUUSAMO.gg          | L   | 0.546      | -            | -                | -                | -         |   -12.15 | brnr, leFluff, Midgard, StebbiC0C0, T0PAZ  |
|            8 |     2869 | 2024-11-23 | PCIFIC Espor        | W   | 0.546      | 0.284        | 0.004 (0.001)    | 0.254 (0.039)    | 0 (0.000) |    10.36 | brnr, leFluff, Midgard, StebbiC0C0, T0PAZ  |
|            7 |     2958 | 2024-11-22 | KUUSAMO.gg          | L   | 0.540      | -            | -                | -                | -         |   -12.40 | brnr, leFluff, Midgard, StebbiC0C0, T0PAZ  |
|            6 |     3306 | 2024-11-16 | Þór                 | W   | 0.500      | 0.143        | 0.004 (0.000)    | 0.022 (0.002)    | 1 (0.500) |     6.93 | brnr, EddezeNNN, Midgard, StebbiC0C0, TH0R |
|            5 |     3390 | 2024-11-15 | ENTERPRISE Genesis  | L   | 0.492      | -            | -                | -                | -         |    -8.79 | brnr, Midgard, PANDAZ, StebbiC0C0, TH0R    |
|            4 |     3539 | 2024-11-12 | Metizport X         | W   | 0.473      | 0.278        | 0.001 (0.000)    | 0.221 (0.029)    | 0 (0.000) |     6.84 | brnr, EddezeNNN, Midgard, StebbiC0C0, TH0R |
|            3 |     3669 | 2024-11-10 | GamerLegion Academy | L   | 0.459      | -            | -                | -                | -         |    -9.57 | brnr, Midgard, Pressi, StebbiC0C0, TH0R    |
|            2 |     3881 | 2024-11-06 | Metizport X         | W   | 0.433      | 0.278        | 0.001 (0.000)    | 0.221 (0.027)    | 0 (0.000) |     6.24 | brnr, Midgard, PANDAZ, StebbiC0C0, TH0R    |
|            1 |     5416 | 2024-10-08 | Sampi NEXT          | L   | 0.239      | -            | -                | -                | -         |    -5.67 | brnr, Midgard, Pressi, StebbiC0C0, T0PAZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,179.43)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-16 |      0.500 | $4,358.87      | $2,179.43       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
