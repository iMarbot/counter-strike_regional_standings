### Roster Details<br />
Team Name: Rebound<br />
Roster: Ame935, evenope, Jam7ee, oddope, oNew<br />
Global Rank: [525](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [83]( ../standings_asia.md)<br />
<br />
Final Rank Value:  491.2<br />
<br />
Final Rank Value (491.2) = Starting Rank Value (507.3) + Head To Head Adjustments (-16.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.214[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 507.3
- 400 + ( ( 0.054 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 507.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     1862 | 2024-12-12 | Above The Rest (Australian team) | L   | 0.663      | -            | -                | -                | -         |   -10.62 | Ame935, evenope, Jam7ee, oddope, oNew |
|            8 |     1912 | 2024-12-11 | Shanghai Sharks                  | W   | 0.656      | 0.143        | 0.000 (0.000)    | 0.057 (0.005)    | 0 (0.000) |     9.95 | Ame935, evenope, Jam7ee, oddope, oNew |
|            7 |     1948 | 2024-12-10 | Above The Rest (Australian team) | L   | 0.649      | -            | -                | -                | -         |   -10.50 | Ame935, evenope, Jam7ee, oddope, oNew |
|            6 |     5650 | 2024-10-04 | Only One Word                    | L   | 0.208      | -            | -                | -                | -         |    -2.16 | 33ya, Ame935, evenope, Jam7ee, oddope |
|            5 |     5655 | 2024-10-04 | SemperFi Esports                 | L   | 0.207      | -            | -                | -                | -         |    -2.88 | 33ya, Ame935, evenope, Jam7ee, oddope |
|            4 |     6607 | 2024-09-21 | Justice For Tomorrow             | L   | 0.116      | -            | -                | -                | -         |    -1.19 | evenope, HanEver, oddope, oNew, Yuzi  |
|            3 |     7219 | 2024-09-11 | FreshFoodPeople                  | W   | 0.049      | 0.270        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.70 | evenope, HanEver, oddope, oNew, Yuzi  |
|            2 |     7329 | 2024-09-09 | Underground Esports Club         | W   | 0.036      | 0.270        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     0.40 | evenope, HanEver, oddope, oNew, Yuzi  |
|            1 |     7488 | 2024-09-07 | Gods Work                        | W   | 0.023      | 0.270        | 0.000 (0.000)    | 0.033 (0.000)    | 0 (0.000) |     0.25 | evenope, HanEver, oddope, oNew, Yuzi  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($69.67)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.116 | $600.00        | $69.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
