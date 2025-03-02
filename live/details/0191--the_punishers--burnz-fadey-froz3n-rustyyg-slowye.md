### Roster Details<br />
Team Name: The Punishers<br />
Roster: burnz, Fadey, FROZ3N, RustyYG, SloWye<br />
Global Rank: [191](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
<br />
Final Rank Value:  715.4<br />
<br />
Final Rank Value (715.4) = Starting Rank Value (681.1) + Head To Head Adjustments (34.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.189[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.1
- 400 + ( ( 0.141 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 681.1


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
|           11 |     1617 | 2024-12-15 | Kitsune Esports | W   | 0.693      | 0.250        | 0.001 (0.000)    | 0.098 (0.017)    | 0 (0.000) |     7.85 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|           10 |     2214 | 2024-12-04 | Kitsune Esports | W   | 0.620      | 0.250        | 0.001 (0.000)    | 0.098 (0.015)    | 0 (0.000) |     7.14 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            9 |     2332 | 2024-12-02 | Blou Bulle      | W   | 0.607      | 0.250        | 0.000 (0.000)    | 0.086 (0.013)    | 0 (0.000) |     7.00 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            8 |     2658 | 2024-11-27 | Avasive         | W   | 0.574      | -            | -                | -                | 0 (0.000) |     2.94 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            7 |     5981 | 2024-09-29 | Exceed          | W   | 0.178      | 0.143        | 0.002 (0.000)    | 0.017 (0.000)    | 1 (0.178) |     2.37 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            6 |     6077 | 2024-09-28 | Monarch Realm   | W   | 0.171      | 0.143        | 0.001 (0.000)    | 0.016 (0.000)    | 1 (0.171) |     2.20 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            5 |     6161 | 2024-09-26 | Kitsune Esports | W   | 0.163      | 0.143        | 0.001 (0.000)    | 0.098 (0.002)    | 1 (0.163) |     2.07 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            4 |     6506 | 2024-09-22 | Kitsune Esports | W   | 0.133      | 0.250        | 0.001 (0.000)    | 0.098 (0.003)    | 0 (0.000) |     1.70 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            3 |     7288 | 2024-09-09 | Exceed          | W   | 0.046      | 0.250        | 0.002 (0.000)    | 0.017 (0.000)    | 0 (0.000) |     0.63 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            2 |     7581 | 2024-09-05 | Nixuh           | W   | 0.020      | 0.250        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.24 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            1 |     7650 | 2024-09-04 | Kitsune Esports | W   | 0.013      | 0.250        | 0.001 (0.000)    | 0.098 (0.000)    | -         |     0.17 | burnz, Fadey, FROZ3N, RustyYG, SloWye |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,969.28)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.693 | $500.00        | $346.67         |
| 2024-09-29 |      0.178 | $8,763.65      | $1,556.16       |
| 2024-09-22 |      0.133 | $500.00        | $66.46          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
