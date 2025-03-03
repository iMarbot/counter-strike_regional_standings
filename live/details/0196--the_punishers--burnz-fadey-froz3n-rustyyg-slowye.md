### Roster Details<br />
Team Name: The Punishers<br />
Roster: burnz, Fadey, FROZ3N, RustyYG, SloWye<br />
Global Rank: [196](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
<br />
Final Rank Value:  712.8<br />
<br />
Final Rank Value (712.8) = Starting Rank Value (679.3) + Head To Head Adjustments (33.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.3
- 400 + ( ( 0.140 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 679.3


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
|           11 |     1629 | 2024-12-15 | Kitsune Esports | W   | 0.685      | 0.250        | 0.001 (0.000)    | 0.096 (0.016)    | 0 (0.000) |     7.82 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|           10 |     2226 | 2024-12-04 | Kitsune Esports | W   | 0.612      | 0.250        | 0.001 (0.000)    | 0.096 (0.015)    | 0 (0.000) |     7.10 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            9 |     2344 | 2024-12-02 | Blou Bulle      | W   | 0.599      | 0.250        | 0.000 (0.000)    | 0.085 (0.013)    | 0 (0.000) |     6.98 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            8 |     2670 | 2024-11-27 | Avasive         | W   | 0.565      | -            | -                | -                | 0 (0.000) |     2.94 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            7 |     5993 | 2024-09-29 | Exceed          | W   | 0.169      | 0.143        | 0.002 (0.000)    | 0.016 (0.000)    | 1 (0.169) |     2.26 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            6 |     6089 | 2024-09-28 | Monarch Realm   | W   | 0.163      | 0.143        | 0.001 (0.000)    | 0.015 (0.000)    | 1 (0.163) |     2.10 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            5 |     6173 | 2024-09-26 | Kitsune Esports | W   | 0.155      | 0.143        | 0.001 (0.000)    | 0.096 (0.002)    | 1 (0.155) |     1.97 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            4 |     6518 | 2024-09-22 | Kitsune Esports | W   | 0.125      | 0.250        | 0.001 (0.000)    | 0.096 (0.003)    | 0 (0.000) |     1.60 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            3 |     7300 | 2024-09-09 | Exceed          | W   | 0.038      | 0.250        | 0.002 (0.000)    | 0.016 (0.000)    | 0 (0.000) |     0.52 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            2 |     7593 | 2024-09-05 | Nixuh           | W   | 0.012      | 0.250        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     0.14 | burnz, Fadey, FROZ3N, RustyYG, SloWye |
|            1 |     7662 | 2024-09-04 | Kitsune Esports | W   | 0.005      | 0.250        | 0.001 (0.000)    | 0.096 (0.000)    | -         |     0.06 | burnz, Fadey, FROZ3N, RustyYG, SloWye |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,889.27)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.685 | $500.00        | $342.57         |
| 2024-09-29 |      0.169 | $8,763.65      | $1,484.34       |
| 2024-09-22 |      0.125 | $500.00        | $62.36          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
