### Roster Details<br />
Team Name: AimAssassins<br />
Roster: Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  933.3<br />
<br />
Final Rank Value (933.3) = Starting Rank Value (930.7) + Head To Head Adjustments (2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.530[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.7
- 400 + ( ( 0.265 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 930.7


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
|           12 |     1663 | 2024-12-15 | Team Novaq         | L   | 0.682      | -            | -                | -                | -         |    -6.13 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|           11 |     1727 | 2024-12-14 | AK BARS            | L   | 0.676      | -            | -                | -                | -         |   -13.19 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|           10 |     1819 | 2024-12-13 | ALLINNERS          | W   | 0.669      | 0.333        | 0.002 (0.001)    | 0.149 (0.033)    | 1 (0.669) |     4.98 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|            9 |     1827 | 2024-12-12 | DEPO               | W   | 0.668      | 0.333        | 0.006 (0.001)    | 0.291 (0.065)    | 1 (0.668) |     6.20 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|            8 |     2010 | 2024-12-08 | 69peek             | W   | 0.638      | 0.143        | 0.001 (0.000)    | 0.119 (0.011)    | 1 (0.638) |     5.76 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            7 |     2014 | 2024-12-08 | Asdmix             | W   | 0.638      | 0.143        | 0.000 (0.000)    | 0.090 (0.008)    | 1 (0.638) |     3.07 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            6 |     2020 | 2024-12-08 | 69peek             | L   | 0.637      | -            | -                | -                | -         |   -14.62 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            5 |     2024 | 2024-12-08 | Dmoai              | W   | 0.637      | 0.143        | 0.000 (0.000)    | 0.089 (0.008)    | 1 (0.637) |     1.65 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            4 |     2041 | 2024-12-07 | PH SunShine        | W   | 0.636      | 0.143        | 0.000 (0.000)    | 0.060 (0.005)    | 1 (0.636) |     2.18 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            3 |     2047 | 2024-12-07 | Asdmix             | W   | 0.635      | 0.143        | 0.000 (0.000)    | 0.090 (0.008)    | 1 (0.635) |     2.81 | Al1eNN, Aldikon, bluewat3r, Botpa1, proksa |
|            2 |     2412 | 2024-12-01 | RAGE (Kazakh team) | W   | 0.592      | 0.143        | 0.005 (0.000)    | 0.179 (0.015)    | 0 (0.000) |     6.13 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |
|            1 |     2440 | 2024-12-01 | MYSKILL            | W   | 0.591      | 0.143        | 0.002 (0.000)    | 0.127 (0.011)    | 0 (0.000) |     3.80 | Al1eNN, Aldikon, ARSPOWER, Botpa1, dan4o   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,401.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.683 | $1,500.00      | $1,024.79       |
| 2024-12-08 |      0.638 | $589.48        | $376.20         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
