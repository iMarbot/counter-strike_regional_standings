### Roster Details<br />
Team Name: MADNESS (Kosovar team)<br />
Roster: Defro, exIN, maifojtii, norkk, TNEG<br />
Global Rank: [485](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [301]( ../standings_europe.md)<br />
<br />
Final Rank Value:  527.7<br />
<br />
Final Rank Value (527.7) = Starting Rank Value (540.2) + Head To Head Adjustments (-12.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.070<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 540.2
- 400 + ( ( 0.070 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 540.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1450 | 2024-12-21 | The Suspect      | L   | 0.733      | -            | -                | -                | -         |    -6.24 | Defro, exIN, maifojtii, norkk, TNEG  |
|            9 |     3334 | 2024-11-16 | 0to100           | L   | 0.498      | -            | -                | -                | -         |    -3.60 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            8 |     4055 | 2024-11-03 | Kubix Esports    | L   | 0.413      | -            | -                | -                | -         |    -1.35 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            7 |     4806 | 2024-10-20 | Max Team         | W   | 0.318      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.18 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            6 |     5524 | 2024-10-06 | Zero Tenacity    | L   | 0.226      | -            | -                | -                | -         |    -0.95 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            5 |     5899 | 2024-09-30 | GameAgents       | L   | 0.187      | -            | -                | -                | -         |    -1.64 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            4 |     6368 | 2024-09-24 | GardenGarage     | L   | 0.146      | -            | -                | -                | -         |    -1.09 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            3 |     6378 | 2024-09-24 | Illuminar Gaming | L   | 0.146      | -            | -                | -                | -         |    -0.65 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            2 |     6973 | 2024-09-14 | TNC Esports      | W   | 0.080      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.79 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            1 |     7230 | 2024-09-10 | GOSTIVAR         | L   | 0.053      | -            | -                | -                | -         |    -0.95 | Defro, norkk, shuajbzz, TNEG, xonn1k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($920.42)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.740 | $521.51        | $386.09         |
| 2024-11-17 |      0.507 | $1,054.46      | $534.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
