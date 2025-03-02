### Roster Details<br />
Team Name: Haspers Team<br />
Roster: AdrieN, hfah, Klameczka, mchk, tudsoN<br />
Global Rank: [393](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [249]( ../standings_europe.md)<br />
<br />
Final Rank Value:  600.8<br />
<br />
Final Rank Value (600.8) = Starting Rank Value (594.8) + Head To Head Adjustments (6.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.210[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.097<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 594.8
- 400 + ( ( 0.097 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 594.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     5068 | 2024-10-15 | GameAgents       | W   | 0.286      | 0.143        | 0.003 (0.000)    | 0.119 (0.005)    | 0 (0.000) |     5.64 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|           11 |     5195 | 2024-10-12 | AgenciUSB        | L   | 0.266      | -            | -                | -                | -         |    -5.38 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|           10 |     5222 | 2024-10-12 | GameAgents       | W   | 0.265      | 0.143        | 0.003 (0.000)    | 0.119 (0.005)    | 0 (0.000) |     5.37 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|            9 |     5565 | 2024-10-05 | Wolves eSports   | W   | 0.220      | 0.143        | 0.000 (0.000)    | 0.093 (0.003)    | 0 (0.000) |     2.42 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|            8 |     6814 | 2024-09-17 | UNiTY esports    | L   | 0.100      | -            | -                | -                | -         |    -0.64 | AdrieN, hfah, Klameczka, Markoś, sk1tt   |
|            7 |     7022 | 2024-09-14 | X-CITY           | L   | 0.078      | -            | -                | -                | -         |    -1.66 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            6 |     7167 | 2024-09-11 | GameAgents       | L   | 0.060      | -            | -                | -                | -         |    -0.71 | AdrieN, hfah, Klameczka, sk1tt, woozzzi  |
|            5 |     7177 | 2024-09-11 | Lan Party Hotel  | W   | 0.060      | 0.143        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.64 | AdrieN, hfah, Klameczka, sk1tt, woozzzi  |
|            4 |     7353 | 2024-09-08 | Grannys Knockers | W   | 0.038      | 0.270        | 0.001 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.64 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            3 |     7442 | 2024-09-07 | Panica.Gaming    | W   | 0.032      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.25 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            2 |     7458 | 2024-09-07 | Lazer Cats       | L   | 0.031      | -            | -                | -                | -         |    -0.33 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            1 |     7482 | 2024-09-07 | Illuminar Gaming | L   | 0.030      | -            | -                | -                | -         |    -0.17 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($57.71)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-08 |      0.038 | $1,500.00      | $57.71          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
