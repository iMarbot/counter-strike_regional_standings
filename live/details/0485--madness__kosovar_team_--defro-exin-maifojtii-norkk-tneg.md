### Roster Details<br />
Team Name: MADNESS (Kosovar team)<br />
Roster: Defro, exIN, maifojtii, norkk, TNEG<br />
Global Rank: [485](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [300]( ../standings_europe.md)<br />
<br />
Final Rank Value:  528.2<br />
<br />
Final Rank Value (528.2) = Starting Rank Value (540.5) + Head To Head Adjustments (-12.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.070<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 540.5
- 400 + ( ( 0.070 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 540.5


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
|           10 |     1462 | 2024-12-21 | The Suspect      | L   | 0.724      | -            | -                | -                | -         |    -6.21 | Defro, exIN, maifojtii, norkk, TNEG  |
|            9 |     3346 | 2024-11-16 | 0to100           | L   | 0.490      | -            | -                | -                | -         |    -3.56 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            8 |     4067 | 2024-11-03 | Kubix Esports    | L   | 0.404      | -            | -                | -                | -         |    -1.33 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            7 |     4818 | 2024-10-20 | Max Team         | W   | 0.310      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.09 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            6 |     5536 | 2024-10-06 | Zero Tenacity    | L   | 0.217      | -            | -                | -                | -         |    -0.94 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            5 |     5911 | 2024-09-30 | GameAgents       | L   | 0.178      | -            | -                | -                | -         |    -1.60 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            4 |     6380 | 2024-09-24 | GardenGarage     | L   | 0.138      | -            | -                | -                | -         |    -1.03 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            3 |     6390 | 2024-09-24 | Illuminar Gaming | L   | 0.138      | -            | -                | -                | -         |    -0.62 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            2 |     6985 | 2024-09-14 | TNC Esports      | W   | 0.072      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.71 | Defro, norkk, shuajbzz, TNEG, xonn1k |
|            1 |     7242 | 2024-09-10 | GOSTIVAR         | L   | 0.045      | -            | -                | -                | -         |    -0.80 | Defro, norkk, shuajbzz, TNEG, xonn1k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($907.51)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.732 | $521.51        | $381.81         |
| 2024-11-17 |      0.499 | $1,054.46      | $525.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
