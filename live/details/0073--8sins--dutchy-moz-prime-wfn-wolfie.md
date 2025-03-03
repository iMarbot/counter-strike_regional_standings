### Roster Details<br />
Team Name: 8Sins<br />
Roster: Dutchy, moz, Prime, wfn, Wolfie<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  892.5<br />
<br />
Final Rank Value (892.5) = Starting Rank Value (915.7) + Head To Head Adjustments (-23.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.303[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.474[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 915.7
- 400 + ( ( 0.258 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 915.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      119 | 2025-02-23 | ALASKA                    | L   | 1.000      | -            | -                | -                | -         |   -16.20 | Dutchy, moz, Prime, wfn, Wolfie  |
|           14 |      164 | 2025-02-22 | ALASKA                    | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.867 (0.124)    | 1 (1.000) |    14.53 | Dutchy, moz, Prime, wfn, Wolfie  |
|           13 |      171 | 2025-02-22 | ANTARCTICA (British team) | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.122 (0.017)    | 1 (1.000) |     8.06 | Dutchy, moz, Prime, wfn, Wolfie  |
|           12 |      195 | 2025-02-21 | DUSTY                     | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.141 (0.020)    | 1 (1.000) |    11.58 | Dutchy, moz, Prime, wfn, Wolfie  |
|           11 |      784 | 2025-02-07 | RUBY                      | L   | 1.000      | -            | -                | -                | -         |   -22.31 | Dutchy, moz, Prime, wfn, Wolfie  |
|           10 |     3087 | 2024-11-20 | Belfast Storm             | L   | 0.519      | -            | -                | -                | -         |   -11.77 | coldpera, f0cus, moz, Prime, wfn |
|            9 |     3833 | 2024-11-07 | The Last Resort           | L   | 0.432      | -            | -                | -                | -         |   -10.26 | coldpera, f0cus, moz, Prime, wfn |
|            8 |     3877 | 2024-11-06 | Belfast Storm             | W   | 0.426      | 0.143        | 0.002 (0.000)    | 0.160 (0.010)    | 0 (0.000) |     3.42 | coldpera, f0cus, moz, Prime, wfn |
|            7 |     3878 | 2024-11-06 | Annex Esports             | W   | 0.426      | 0.143        | 0.000 (0.000)    | 0.058 (0.004)    | 0 (0.000) |     1.93 | coldpera, f0cus, moz, Prime, wfn |
|            6 |     3933 | 2024-11-05 | ROYALS                    | W   | 0.419      | 0.143        | 0.004 (0.000)    | 0.200 (0.012)    | 0 (0.000) |     3.09 | coldpera, f0cus, moz, Prime, wfn |
|            5 |     4494 | 2024-10-27 | Verdant fe                | L   | 0.356      | -            | -                | -                | -         |    -8.69 | f0cus, Menace, moz, Prime, wfn   |
|            4 |     4511 | 2024-10-26 | The Last Resort           | W   | 0.352      | 0.143        | 0.001 (0.000)    | 0.159 (0.008)    | 1 (0.352) |     2.78 | f0cus, Menace, moz, Prime, wfn   |
|            3 |     4524 | 2024-10-26 | The Last Resort           | W   | 0.351      | 0.143        | 0.000 (0.000)    | 0.042 (0.002)    | 1 (0.351) |     1.83 | f0cus, Menace, moz, Prime, wfn   |
|            2 |     4550 | 2024-10-26 | ALASKA                    | L   | 0.350      | -            | -                | -                | -         |    -2.98 | f0cus, Menace, moz, Prime, wfn   |
|            1 |     4593 | 2024-10-25 | Annex Esports             | W   | 0.345      | 0.143        | 0.000 (0.000)    | 0.058 (0.003)    | 1 (0.345) |     1.81 | f0cus, Menace, moz, Prime, wfn   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,662.20)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $1,326.20      | $1,326.20       |
| 2024-10-27 |      0.358 | $939.67        | $336.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
