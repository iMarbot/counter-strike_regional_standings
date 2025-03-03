### Roster Details<br />
Team Name: Sharks Youngsters<br />
Roster: futoi, kenznk, Lacerda, Longo, Nicks<br />
Global Rank: [452](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [100]( ../standings_americas.md)<br />
<br />
Final Rank Value:  559.2<br />
<br />
Final Rank Value (559.2) = Starting Rank Value (580.1) + Head To Head Adjustments (-20.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.201[<sup>1</sup>](#table2)
- Bounty Collected: 0.154[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.090<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 580.1
- 400 + ( ( 0.090 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 580.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     1625 | 2024-12-15 | New Generation Academy  | L   | 0.685      | -            | -                | -                | -         |    -9.56 | futoi, kenznk, Lacerda, Longo, Nicks |
|           13 |     2409 | 2024-12-01 | Team Leveling           | L   | 0.592      | -            | -                | -                | -         |   -10.96 | futoi, kenznk, Lacerda, Longo, Nicks |
|           12 |     2481 | 2024-11-30 | INTERDIT                | W   | 0.586      | 0.143        | 0.000 (0.000)    | 0.155 (0.013)    | 0 (0.000) |     9.97 | futoi, kenznk, Lacerda, Longo, Nicks |
|           11 |     2503 | 2024-11-30 | DB Peek Esports         | L   | 0.585      | -            | -                | -                | -         |    -8.21 | futoi, kenznk, Lacerda, Longo, Nicks |
|           10 |     3707 | 2024-11-09 | Team Leveling           | W   | 0.446      | 0.143        | 0.000 (0.000)    | 0.155 (0.010)    | 0 (0.000) |     5.59 | futoi, kenznk, Lacerda, Longo, Nicks |
|            9 |     3716 | 2024-11-09 | América eSports         | W   | 0.445      | 0.143        | 0.000 (0.000)    | 0.426 (0.027)    | 0 (0.000) |     7.29 | futoi, kenznk, Lacerda, Longo, Nicks |
|            8 |     4195 | 2024-11-01 | AMIGOS (Brazilian team) | L   | 0.392      | -            | -                | -                | -         |    -7.29 | futoi, kenznk, Lacerda, Longo, Nicks |
|            7 |     4288 | 2024-10-30 | MIBR Academy            | L   | 0.380      | -            | -                | -                | -         |    -4.20 | futoi, kenznk, Lacerda, Longo, Nicks |
|            6 |     4418 | 2024-10-28 | 20/70                   | L   | 0.366      | -            | -                | -                | -         |    -4.74 | futoi, kenznk, Lacerda, Longo, Nicks |
|            5 |     4701 | 2024-10-22 | Galorys Academy         | L   | 0.325      | -            | -                | -                | -         |    -4.35 | futoi, kenznk, Lacerda, Longo, Nicks |
|            4 |     5054 | 2024-10-15 | Myth e-Sports           | W   | 0.279      | 0.143        | 0.000 (0.000)    | 0.078 (0.003)    | 0 (0.000) |     4.66 | futoi, hug1, kenznk, Longo, Nicks    |
|            3 |     5061 | 2024-10-15 | SoJoga                  | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.031 (0.001)    | 0 (0.000) |     4.18 | futoi, hug1, kenznk, Longo, Nicks    |
|            2 |     6631 | 2024-09-20 | AMIGOS (Brazilian team) | L   | 0.112      | -            | -                | -                | -         |    -2.21 | futoi, kenznk, Longo, Nicks, Tineu   |
|            1 |     6880 | 2024-09-16 | Floripa Stars           | L   | 0.085      | -            | -                | -                | -         |    -1.06 | futoi, kenznk, Longo, Nicks, Tineu   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34.03)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.685 | $49.65         | $34.03          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
