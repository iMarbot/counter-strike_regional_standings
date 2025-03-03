### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [189](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [135]( ../standings_europe.md)<br />
<br />
Final Rank Value:  720.8<br />
<br />
Final Rank Value (720.8) = Starting Rank Value (716.1) + Head To Head Adjustments (4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.312[<sup>1</sup>](#table2)
- Bounty Collected: 0.260[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.033[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 716.1
- 400 + ( ( 0.158 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 716.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     3010 | 2024-11-21 | TSM                 | L   | 0.528      | -            | -                | -                | -         |    -7.81 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           16 |     3068 | 2024-11-21 | Ninjas in Pyjamas   | L   | 0.523      | -            | -                | -                | -         |    -5.07 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           15 |     3077 | 2024-11-20 | Team Falcons        | L   | 0.522      | -            | -                | -                | -         |    -0.02 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           14 |     3868 | 2024-11-07 | Nemiga Gaming       | L   | 0.429      | -            | -                | -                | -         |    -2.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           13 |     3901 | 2024-11-06 | SINNERS Esports     | W   | 0.425      | 0.143        | 0.027 (0.002)    | 0.446 (0.027)    | 0 (0.000) |     9.85 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           12 |     4910 | 2024-10-18 | BC.Game Esports     | L   | 0.297      | -            | -                | -                | -         |    -1.44 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           11 |     4942 | 2024-10-17 | Fnatic              | L   | 0.291      | -            | -                | -                | -         |    -1.23 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           10 |     4998 | 2024-10-16 | Sashi Esport        | L   | 0.285      | -            | -                | -                | -         |    -2.01 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            9 |     5015 | 2024-10-16 | Team Solid          | W   | 0.284      | 0.624        | 0.023 (0.004)    | 0.555 (0.098)    | 1 (0.284) |     5.82 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            8 |     5072 | 2024-10-15 | Aurora Gaming       | W   | 0.278      | 0.500        | 0.019 (0.003)    | 0.514 (0.071)    | 0 (0.000) |     5.58 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            7 |     5634 | 2024-10-05 | 3DMAX               | L   | 0.209      | -            | -                | -                | -         |    -0.05 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            6 |     5746 | 2024-10-03 | Team Spirit Academy | W   | 0.196      | 0.435        | 0.068 (0.006)    | 0.702 (0.060)    | 0 (0.000) |     4.74 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            5 |     6284 | 2024-09-25 | Nemiga Gaming       | L   | 0.145      | -            | -                | -                | -         |    -0.73 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            4 |     6497 | 2024-09-23 | Monte               | L   | 0.130      | -            | -                | -                | -         |    -1.35 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            3 |     7143 | 2024-09-12 | GUN5 Esports        | L   | 0.058      | -            | -                | -                | -         |    -0.42 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            2 |     7217 | 2024-09-11 | 9INE                | W   | 0.050      | 0.384        | 0.011 (0.000)    | 0.217 (0.004)    | 0 (0.000) |     0.87 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            1 |     7694 | 2024-09-04 | Monte               | W   | 0.003      | 0.384        | 0.029 (0.000)    | 0.235 (0.000)    | 0 (0.000) |     0.06 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,072.14)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.444 | $15.18         | $6.74           |
| 2024-10-20 |      0.311 | $5,000.00      | $1,553.47       |
| 2024-10-06 |      0.218 | $2,000.00      | $436.53         |
| 2024-09-26 |      0.151 | $500.00        | $75.39          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
