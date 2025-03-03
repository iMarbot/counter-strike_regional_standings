### Roster Details<br />
Team Name: Dragon Esports Club<br />
Roster: auth0ri, fakerealityy, hodix, Kiy0o, Shlyaperson<br />
Global Rank: [522](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [325]( ../standings_europe.md)<br />
<br />
Final Rank Value:  493.4<br />
<br />
Final Rank Value (493.4) = Starting Rank Value (496.6) + Head To Head Adjustments (-3.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.193[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.048<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 496.6
- 400 + ( ( 0.048 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 496.6


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
|            5 |     5996 | 2024-09-29 | Fragmatic             | L   | 0.169      | -            | -                | -                | -         |    -2.14 | auth0ri, fakerealityy, hodix, Kiy0o, Shlyaperson  |
|            4 |     6999 | 2024-09-14 | Passion UA            | L   | 0.071      | -            | -                | -                | -         |    -0.11 | auth0ri, DMBPWR, fakerealityy, hodix, Shlyaperson |
|            3 |     7035 | 2024-09-14 | TryHearts             | L   | 0.070      | -            | -                | -                | -         |    -1.21 | auth0ri, DMBPWR, fakerealityy, hodix, Shlyaperson |
|            2 |     7402 | 2024-09-07 | Inroads Esports       | W   | 0.025      | 0.333        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.38 | auth0ri, DMBPWR, fakerealityy, hodix, Shlyaperson |
|            1 |     7603 | 2024-09-05 | THE GENTLEMEN ESPORTS | L   | 0.011      | -            | -                | -                | -         |    -0.09 | auth0ri, DMBPWR, fakerealityy, hodix, Shlyaperson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21.87)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-29 |      0.171 | $72.89         | $12.43          |
| 2024-09-15 |      0.078 | $120.84        | $9.44           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
