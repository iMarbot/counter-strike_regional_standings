### Roster Details<br />
Team Name: Haspers Team<br />
Roster: AdrieN, hfah, Klameczka, mchk, tudsoN<br />
Global Rank: [401](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [250]( ../standings_europe.md)<br />
<br />
Final Rank Value:  598.6<br />
<br />
Final Rank Value (598.6) = Starting Rank Value (592.6) + Head To Head Adjustments (6.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.206[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.096<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 592.6
- 400 + ( ( 0.096 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 592.6


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
|           12 |     5080 | 2024-10-15 | GameAgents       | W   | 0.278      | 0.143        | 0.003 (0.000)    | 0.111 (0.004)    | 0 (0.000) |     5.47 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|           11 |     5207 | 2024-10-12 | AgenciUSB        | L   | 0.258      | -            | -                | -                | -         |    -5.20 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|           10 |     5233 | 2024-10-12 | GameAgents       | W   | 0.257      | 0.143        | 0.003 (0.000)    | 0.111 (0.004)    | 0 (0.000) |     5.19 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|            9 |     5577 | 2024-10-05 | Wolves eSports   | W   | 0.212      | 0.143        | 0.000 (0.000)    | 0.094 (0.003)    | 0 (0.000) |     2.35 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|            8 |     6826 | 2024-09-17 | UNiTY esports    | L   | 0.092      | -            | -                | -                | -         |    -0.59 | AdrieN, hfah, Klameczka, Markoś, sk1tt   |
|            7 |     7034 | 2024-09-14 | X-CITY           | L   | 0.070      | -            | -                | -                | -         |    -1.48 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            6 |     7179 | 2024-09-11 | GameAgents       | L   | 0.052      | -            | -                | -                | -         |    -0.62 | AdrieN, hfah, Klameczka, sk1tt, woozzzi  |
|            5 |     7189 | 2024-09-11 | Lan Party Hotel  | W   | 0.052      | 0.143        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.56 | AdrieN, hfah, Klameczka, sk1tt, woozzzi  |
|            4 |     7365 | 2024-09-08 | Grannys Knockers | W   | 0.030      | 0.270        | 0.001 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.51 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            3 |     7454 | 2024-09-07 | Panica.Gaming    | W   | 0.024      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.19 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            2 |     7470 | 2024-09-07 | Lazer Cats       | L   | 0.023      | -            | -                | -                | -         |    -0.24 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            1 |     7494 | 2024-09-07 | Illuminar Gaming | L   | 0.022      | -            | -                | -                | -         |    -0.13 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45.42)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-08 |      0.030 | $1,500.00      | $45.42          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
