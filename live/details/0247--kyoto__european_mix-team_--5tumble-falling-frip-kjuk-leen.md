### Roster Details<br />
Team Name: Kyoto (European mix-team)<br />
Roster: 5tumble, Falling, Frip, kjuK, LeeN<br />
Global Rank: [247](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [171]( ../standings_europe.md)<br />
<br />
Final Rank Value:  680.6<br />
<br />
Final Rank Value (680.6) = Starting Rank Value (670.2) + Head To Head Adjustments (10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.191[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.2
- 400 + ( ( 0.135 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 670.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3949 | 2024-11-05 | Kubix Esports    | L   | 0.418      | -            | -                | -                | -         |    -2.70 | 5tumble, Falling, Frip, kjuK, LeeN |
|            6 |     4362 | 2024-10-29 | Devils.one       | W   | 0.373      | 0.143        | 0.001 (0.000)    | 0.068 (0.004)    | 0 (0.000) |     5.51 | 5tumble, Falling, Frip, kjuK, LeeN |
|            5 |     5111 | 2024-10-14 | Devils.one       | W   | 0.271      | 0.143        | 0.001 (0.000)    | 0.068 (0.003)    | 0 (0.000) |     4.12 | 5tumble, Falling, Frip, kjuK, LeeN |
|            4 |     5850 | 2024-10-01 | Illuminar Gaming | L   | 0.185      | -            | -                | -                | -         |    -1.47 | 5tumble, Falling, Frip, kjuK, LeeN |
|            3 |     6375 | 2024-09-24 | UNiTY esports    | W   | 0.138      | 0.143        | 0.025 (0.001)    | 0.403 (0.008)    | 0 (0.000) |     3.15 | 5tumble, Falling, Frip, kjuK, LeeN |
|            2 |     6395 | 2024-09-24 | Sampi NEXT       | W   | 0.138      | 0.143        | 0.000 (0.000)    | 0.022 (0.000)    | 0 (0.000) |     1.21 | 5tumble, Falling, Frip, kjuK, LeeN |
|            1 |     6981 | 2024-09-14 | Sampi NEXT       | W   | 0.072      | 0.143        | 0.000 (0.000)    | 0.022 (0.000)    | 0 (0.000) |     0.63 | 5tumble, Falling, Frip, kjuK, LeeN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,396.40)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-16 |      0.491 | $8,962.94      | $4,396.40       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
