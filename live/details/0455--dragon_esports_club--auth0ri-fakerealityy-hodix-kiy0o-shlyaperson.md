### Roster Details<br />
Team Name: Dragon Esports Club<br />
Roster: auth0ri, fakerealityy, hodix, Kiy0o, Shlyaperson<br />
Global Rank: [455](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [285]( ../standings_europe.md)<br />
<br />
Final Rank Value:  556.8<br />
<br />
Final Rank Value (556.8) = Starting Rank Value (560.9) + Head To Head Adjustments (-4.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.194[<sup>1</sup>](#table2)
- Bounty Collected: 0.128[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.081<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 560.9
- 400 + ( ( 0.081 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 560.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     5984 | 2024-09-29 | Fragmatic             | L   | 0.177      | -            | -                | -                | -         |    -2.73 | auth0ri, fakerealityy, hodix, Kiy0o, Shlyaperson  |
|            5 |     6987 | 2024-09-14 | Passion UA            | L   | 0.079      | -            | -                | -                | -         |    -0.17 | auth0ri, DMBPWR, fakerealityy, hodix, Shlyaperson |
|            4 |     7023 | 2024-09-14 | TryHearts             | L   | 0.078      | -            | -                | -                | -         |    -1.56 | auth0ri, DMBPWR, fakerealityy, hodix, Shlyaperson |
|            3 |     7390 | 2024-09-07 | Inroads Esports       | W   | 0.033      | 0.333        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.41 | auth0ri, DMBPWR, fakerealityy, hodix, Shlyaperson |
|            2 |     7591 | 2024-09-05 | THE GENTLEMEN ESPORTS | L   | 0.019      | -            | -                | -                | -         |    -0.20 | auth0ri, DMBPWR, fakerealityy, hodix, Shlyaperson |
|            1 |     7747 | 2024-09-03 | SINNERS Academy       | W   | 0.005      | 0.333        | 0.001 (0.000)    | 0.102 (0.000)    | 0 (0.000) |     0.11 | auth0ri, DMBPWR, fakerealityy, hodix, Shlyaperson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23.46)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-29 |      0.179 | $72.89         | $13.03          |
| 2024-09-15 |      0.086 | $120.84        | $10.43          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
