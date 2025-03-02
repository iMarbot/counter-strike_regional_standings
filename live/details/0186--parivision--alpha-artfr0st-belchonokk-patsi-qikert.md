### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [186](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [134]( ../standings_europe.md)<br />
<br />
Final Rank Value:  722.7<br />
<br />
Final Rank Value (722.7) = Starting Rank Value (717.5) + Head To Head Adjustments (5.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 717.5
- 400 + ( ( 0.159 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 717.5


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
|           17 |     2998 | 2024-11-21 | TSM                 | L   | 0.537      | -            | -                | -                | -         |    -7.93 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           16 |     3056 | 2024-11-21 | Ninjas in Pyjamas   | L   | 0.531      | -            | -                | -                | -         |    -5.11 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           15 |     3065 | 2024-11-20 | Team Falcons        | L   | 0.530      | -            | -                | -                | -         |    -0.03 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           14 |     3856 | 2024-11-07 | Nemiga Gaming       | L   | 0.438      | -            | -                | -                | -         |    -2.10 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           13 |     3889 | 2024-11-06 | SINNERS Esports     | W   | 0.433      | 0.143        | 0.027 (0.002)    | 0.451 (0.028)    | 0 (0.000) |    10.04 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           12 |     4898 | 2024-10-18 | BC.Game Esports     | L   | 0.305      | -            | -                | -                | -         |    -1.49 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           11 |     4930 | 2024-10-17 | Fnatic              | L   | 0.299      | -            | -                | -                | -         |    -1.26 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           10 |     4986 | 2024-10-16 | Sashi Esport        | L   | 0.293      | -            | -                | -                | -         |    -2.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            9 |     5003 | 2024-10-16 | Team Solid          | W   | 0.292      | 0.624        | 0.023 (0.004)    | 0.561 (0.102)    | 1 (0.292) |     5.98 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            8 |     5060 | 2024-10-15 | Aurora Gaming       | W   | 0.286      | 0.500        | 0.019 (0.003)    | 0.516 (0.074)    | 0 (0.000) |     5.74 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            7 |     5622 | 2024-10-05 | 3DMAX               | L   | 0.217      | -            | -                | -                | -         |    -0.05 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            6 |     5734 | 2024-10-03 | Team Spirit Academy | W   | 0.204      | 0.435        | 0.068 (0.006)    | 0.714 (0.063)    | 0 (0.000) |     4.95 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            5 |     6272 | 2024-09-25 | Nemiga Gaming       | L   | 0.154      | -            | -                | -                | -         |    -0.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            4 |     6485 | 2024-09-23 | Monte               | L   | 0.138      | -            | -                | -                | -         |    -1.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            3 |     7131 | 2024-09-12 | GUN5 Esports        | L   | 0.066      | -            | -                | -                | -         |    -0.48 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            2 |     7205 | 2024-09-11 | 9INE                | W   | 0.058      | 0.384        | 0.011 (0.000)    | 0.222 (0.005)    | 0 (0.000) |     1.02 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|            1 |     7682 | 2024-09-04 | Monte               | W   | 0.011      | 0.384        | 0.029 (0.000)    | 0.242 (0.001)    | 0 (0.000) |     0.23 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,133.72)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.452 | $15.18         | $6.87           |
| 2024-10-20 |      0.319 | $5,000.00      | $1,594.44       |
| 2024-10-06 |      0.226 | $2,000.00      | $452.92         |
| 2024-09-26 |      0.159 | $500.00        | $79.49          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
