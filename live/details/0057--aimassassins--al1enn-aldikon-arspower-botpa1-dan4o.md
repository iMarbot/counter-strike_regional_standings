### Roster Details<br />
Team Name: AimAssassins<br />
Roster: Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o<br />
Global Rank: [57](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  935.1<br />
<br />
Final Rank Value (935.1) = Starting Rank Value (932.5) + Head To Head Adjustments (2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.534[<sup>2</sup>](#table1)

The average of these factors is 0.267<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 932.5
- 400 + ( ( 0.267 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 932.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1651 | 2024-12-15 | Team Novaq         | L   | 0.691      | -            | -                | -                | -         |    -6.17 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|           11 |     1715 | 2024-12-14 | AK BARS            | L   | 0.685      | -            | -                | -                | -         |   -13.35 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|           10 |     1807 | 2024-12-13 | ALLINNERS          | W   | 0.678      | 0.333        | 0.002 (0.001)    | 0.151 (0.034)    | 1 (0.678) |     5.01 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|            9 |     1815 | 2024-12-12 | DEPO               | W   | 0.677      | 0.333        | 0.006 (0.001)    | 0.297 (0.067)    | 1 (0.677) |     6.30 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|            8 |     1998 | 2024-12-08 | 69peek             | W   | 0.646      | 0.143        | 0.001 (0.000)    | 0.120 (0.011)    | 1 (0.646) |     5.81 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            7 |     2002 | 2024-12-08 | Asdmix             | W   | 0.646      | 0.143        | 0.000 (0.000)    | 0.090 (0.008)    | 1 (0.646) |     3.09 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            6 |     2008 | 2024-12-08 | 69peek             | L   | 0.645      | -            | -                | -                | -         |   -14.83 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            5 |     2012 | 2024-12-08 | Dmoai              | W   | 0.645      | 0.143        | 0.000 (0.000)    | 0.090 (0.008)    | 1 (0.645) |     1.66 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            4 |     2029 | 2024-12-07 | PH SunShine        | W   | 0.644      | 0.143        | 0.000 (0.000)    | 0.060 (0.006)    | 1 (0.644) |     2.19 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            3 |     2035 | 2024-12-07 | Asdmix             | W   | 0.643      | 0.143        | 0.000 (0.000)    | 0.090 (0.008)    | 1 (0.643) |     2.82 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            2 |     2400 | 2024-12-01 | RAGE (Kazakh team) | W   | 0.600      | 0.143        | 0.005 (0.000)    | 0.182 (0.016)    | 0 (0.000) |     6.22 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|            1 |     2428 | 2024-12-01 | MYSKILL            | W   | 0.599      | 0.143        | 0.002 (0.000)    | 0.129 (0.011)    | 0 (0.000) |     3.86 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,418.12)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.691 | $1,500.00      | $1,037.08       |
| 2024-12-08 |      0.646 | $589.48        | $381.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
