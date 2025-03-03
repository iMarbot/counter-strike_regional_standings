### Roster Details<br />
Team Name: Rejected by all<br />
Roster: Aspera, Mirsser, MoNaTy, Quazer, zazzer<br />
Global Rank: [565](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [347]( ../standings_europe.md)<br />
<br />
Final Rank Value:  466.2<br />
<br />
Final Rank Value (466.2) = Starting Rank Value (467.5) + Head To Head Adjustments (-1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.135[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.034<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 467.5
- 400 + ( ( 0.034 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 467.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     7037 | 2024-09-14 | LookingForOrg (Turkish team) | L   | 0.070      | -            | -                | -                | -         |    -1.30 | Aspera, Mirsser, MoNaTy, Quazer, zazzer |
|            6 |     7075 | 2024-09-13 | XPERION NXT                  | L   | 0.065      | -            | -                | -                | -         |    -0.56 | Aspera, Mirsser, MoNaTy, Quazer, zazzer |
|            5 |     7184 | 2024-09-11 | Divergent                    | W   | 0.052      | 0.333        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.84 | Aspera, Mirsser, MoNaTy, Quazer, zazzer |
|            4 |     7289 | 2024-09-09 | QUAZAR                       | L   | 0.038      | -            | -                | -                | -         |    -0.25 | Aspera, Mirsser, MoNaTy, Quazer, zazzer |
|            3 |     7347 | 2024-09-08 | Underrated                   | L   | 0.032      | -            | -                | -                | -         |    -0.22 | Aspera, Mirsser, MoNaTy, Quazer, zazzer |
|            2 |     7518 | 2024-09-06 | FLuffy Gangsters             | L   | 0.018      | -            | -                | -                | -         |    -0.08 | Aspera, Mirsser, MoNaTy, Quazer, zazzer |
|            1 |     7581 | 2024-09-05 | Playfire                     | W   | 0.012      | 0.333        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.21 | Aspera, Mirsser, MoNaTy, Quazer, zazzer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
