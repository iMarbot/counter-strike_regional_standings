### Roster Details<br />
Team Name: 69peek<br />
Roster: bestzor, EXCALIBUR-17, noni, reyaan, sharico<br />
Global Rank: [140](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
<br />
Final Rank Value:  771.7<br />
<br />
Final Rank Value (771.7) = Starting Rank Value (762.5) + Head To Head Adjustments (9.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.235[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.301[<sup>2</sup>](#table1)

The average of these factors is 0.181<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 762.5
- 400 + ( ( 0.181 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 762.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1998 | 2024-12-08 | AimAssassins   | L   | 0.646      | -            | -                | -                | -         |    -5.81 | bestzor, EXCALIBUR-17, noni, reyaan, sharico |
|            5 |     2008 | 2024-12-08 | AimAssassins   | W   | 0.645      | 0.143        | 0.004 (0.000)    | 0.240 (0.022)    | 1 (0.645) |    14.83 | bestzor, EXCALIBUR-17, noni, reyaan, sharico |
|            4 |     2019 | 2024-12-08 | Yamato Esports | W   | 0.644      | 0.143        | 0.000 (0.000)    | 0.060 (0.006)    | 1 (0.644) |     3.73 | bestzor, EXCALIBUR-17, noni, reyaan, sharico |
|            3 |     2025 | 2024-12-08 | PH SunShine    | W   | 0.644      | 0.143        | 0.000 (0.000)    | 0.060 (0.006)    | 1 (0.644) |     5.23 | bestzor, EXCALIBUR-17, noni, reyaan, sharico |
|            2 |     2030 | 2024-12-07 | Asdmix         | W   | 0.644      | 0.143        | 0.000 (0.000)    | 0.090 (0.008)    | 1 (0.644) |     6.48 | bestzor, EXCALIBUR-17, noni, reyaan, sharico |
|            1 |     2034 | 2024-12-07 | PH SunShine    | L   | 0.643      | -            | -                | -                | -         |   -15.23 | bestzor, EXCALIBUR-17, noni, reyaan, sharico |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($190.52)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.646 | $294.74        | $190.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
