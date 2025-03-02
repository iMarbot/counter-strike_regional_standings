### Roster Details<br />
Team Name: SIUUUUUU<br />
Roster: ArtwOo, Jerppa, Keksimage, mat, stunt<br />
Global Rank: [600](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [366]( ../standings_europe.md)<br />
<br />
Final Rank Value:  402.9<br />
<br />
Final Rank Value (402.9) = Starting Rank Value (400.3) + Head To Head Adjustments (2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.3
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     5918 | 2024-09-30 | HAVU            | L   | 0.185      | -            | -                | -                | -         |    -1.14 | ArtwOo, Jerppa, Keksimage, mat, stunt |
|            4 |     5972 | 2024-09-29 | Heimo Esports   | L   | 0.178      | -            | -                | -                | -         |    -0.70 | ArtwOo, Jerppa, Keksimage, mat, stunt |
|            3 |     6476 | 2024-09-23 | Smuuttikusilkki | W   | 0.139      | 0.143        | 0.000 (0.000)    | 0.224 (0.004)    | 0 (0.000) |     2.62 | ArtwOo, Jerppa, Keksimage, mat, stunt |
|            2 |     6893 | 2024-09-16 | KUUSAMO.gg      | W   | 0.092      | 0.143        | 0.000 (0.000)    | 0.164 (0.002)    | 0 (0.000) |     1.89 | ArtwOo, Jerppa, Keksimage, mat, stunt |
|            1 |     7134 | 2024-09-12 | JANO Esports    | L   | 0.066      | -            | -                | -                | -         |    -0.11 | ArtwOo, Jerppa, Keksimage, mat, stunt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
