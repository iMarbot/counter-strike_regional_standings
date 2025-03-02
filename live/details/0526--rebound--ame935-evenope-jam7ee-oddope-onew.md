### Roster Details<br />
Team Name: Rebound<br />
Roster: Ame935, evenope, Jam7ee, oddope, oNew<br />
Global Rank: [526](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [83]( ../standings_asia.md)<br />
<br />
Final Rank Value:  491.4<br />
<br />
Final Rank Value (491.4) = Starting Rank Value (507.6) + Head To Head Adjustments (-16.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.215[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 507.6
- 400 + ( ( 0.054 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 507.6


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
|            9 |     1850 | 2024-12-12 | Above The Rest (Australian team) | L   | 0.671      | -            | -                | -                | -         |   -10.75 | Ame935, evenope, Jam7ee, oddope, oNew |
|            8 |     1900 | 2024-12-11 | Shanghai Sharks                  | W   | 0.664      | 0.143        | 0.000 (0.000)    | 0.057 (0.005)    | 0 (0.000) |    10.06 | Ame935, evenope, Jam7ee, oddope, oNew |
|            7 |     1936 | 2024-12-10 | Above The Rest (Australian team) | L   | 0.657      | -            | -                | -                | -         |   -10.63 | Ame935, evenope, Jam7ee, oddope, oNew |
|            6 |     5638 | 2024-10-04 | Only One Word                    | L   | 0.216      | -            | -                | -                | -         |    -2.25 | 33ya, Ame935, evenope, Jam7ee, oddope |
|            5 |     5643 | 2024-10-04 | SemperFi Esports                 | L   | 0.215      | -            | -                | -                | -         |    -3.00 | 33ya, Ame935, evenope, Jam7ee, oddope |
|            4 |     6595 | 2024-09-21 | Justice For Tomorrow             | L   | 0.124      | -            | -                | -                | -         |    -1.27 | evenope, HanEver, oddope, oNew, Yuzi  |
|            3 |     7207 | 2024-09-11 | FreshFoodPeople                  | W   | 0.058      | 0.270        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.82 | evenope, HanEver, oddope, oNew, Yuzi  |
|            2 |     7317 | 2024-09-09 | Underground Esports Club         | W   | 0.044      | 0.270        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     0.49 | evenope, HanEver, oddope, oNew, Yuzi  |
|            1 |     7476 | 2024-09-07 | Gods Work                        | W   | 0.031      | 0.270        | 0.000 (0.000)    | 0.034 (0.000)    | 0 (0.000) |     0.35 | evenope, HanEver, oddope, oNew, Yuzi  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($74.58)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.124 | $600.00        | $74.58          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
