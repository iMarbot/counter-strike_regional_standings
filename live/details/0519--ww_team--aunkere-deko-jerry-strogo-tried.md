### Roster Details<br />
Team Name: WW Team<br />
Roster: Aunkere, deko, Jerry, StRoGo, tried<br />
Global Rank: [519](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [322]( ../standings_europe.md)<br />
<br />
Final Rank Value:  495.2<br />
<br />
Final Rank Value (495.2) = Starting Rank Value (501.8) + Head To Head Adjustments (-6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 501.8
- 400 + ( ( 0.051 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 501.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     1794 | 2024-12-13 | BadGuys            | L   | 0.671      | -            | -                | -                | -         |    -7.84 | Aunkere, deko, Jerry, StRoGo, tried  |
|           16 |     3565 | 2024-11-12 | BC.Game Esports    | L   | 0.463      | -            | -                | -                | -         |    -2.02 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|           15 |     3614 | 2024-11-11 | FLuffy Gangsters   | L   | 0.458      | -            | -                | -                | -         |    -2.55 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|           14 |     5030 | 2024-10-16 | Johnny Speeds      | L   | 0.283      | -            | -                | -                | -         |    -0.85 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|           13 |     5455 | 2024-10-08 | Dynamo Eclot       | L   | 0.229      | -            | -                | -                | -         |    -0.31 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|           12 |     5969 | 2024-09-29 | Monte Gen          | L   | 0.171      | -            | -                | -                | -         |    -3.51 | Aunkere, ct0m, kelieN, StRoGo, tried |
|           11 |     6167 | 2024-09-27 | Endpoint           | W   | 0.156      | 0.435        | 0.009 (0.001)    | 0.377 (0.026)    | 0 (0.000) |     3.98 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|           10 |     6333 | 2024-09-25 | Passion UA         | L   | 0.143      | -            | -                | -                | -         |    -0.23 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|            9 |     6485 | 2024-09-23 | FAVBET Team        | L   | 0.131      | -            | -                | -                | -         |    -0.56 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|            8 |     6545 | 2024-09-22 | HOTU               | W   | 0.122      | 0.143        | 0.003 (0.000)    | 0.768 (0.013)    | 0 (0.000) |     3.00 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|            7 |     6767 | 2024-09-18 | K27                | W   | 0.098      | 0.143        | 0.008 (0.000)    | 0.769 (0.011)    | 0 (0.000) |     2.84 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|            6 |     6850 | 2024-09-17 | Ex-GR Gaming       | W   | 0.091      | 0.143        | 0.012 (0.000)    | 0.100 (0.001)    | 0 (0.000) |     2.16 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|            5 |     6900 | 2024-09-16 | CYBERSHOKE Esports | L   | 0.085      | -            | -                | -                | -         |    -0.84 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|            4 |     6909 | 2024-09-16 | BOGATYRI           | W   | 0.084      | 0.443        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.95 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|            3 |     6915 | 2024-09-16 | CYBERSHOKE Esports | L   | 0.083      | -            | -                | -                | -         |    -0.31 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|            2 |     7276 | 2024-09-10 | GTZ.ESPORTS        | L   | 0.042      | -            | -                | -                | -         |    -0.02 | Aunkere, ct0m, Jerry, StRoGo, tried  |
|            1 |     7332 | 2024-09-09 | TALON              | L   | 0.036      | -            | -                | -                | -         |    -0.47 | Aunkere, ct0m, Jerry, StRoGo, tried  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
