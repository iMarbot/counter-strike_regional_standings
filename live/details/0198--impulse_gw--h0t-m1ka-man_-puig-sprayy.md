### Roster Details<br />
Team Name: Impulse GW<br />
Roster: h0t, M1KA, Mané, PUIG, Sprayy<br />
Global Rank: [198](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [142]( ../standings_europe.md)<br />
<br />
Final Rank Value:  712.6<br />
<br />
Final Rank Value (712.6) = Starting Rank Value (731.9) + Head To Head Adjustments (-19.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.138[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 731.9
- 400 + ( ( 0.166 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 731.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     1303 | 2024-12-28 | CHAOX ESPORTS           | W   | 0.771      | 0.291        | 0.002 (0.001)    | 0.000 (0.000)    | 1 (0.771) |     6.69 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           18 |     1455 | 2024-12-21 | The Agency Clan         | L   | 0.725      | -            | -                | -                | -         |    -7.33 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           17 |     2331 | 2024-12-02 | ZOTIX                   | L   | 0.599      | -            | -                | -                | -         |   -12.01 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           16 |     2630 | 2024-11-28 | Ex-ESC Gaming           | L   | 0.572      | -            | -                | -                | -         |   -10.92 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           15 |     2959 | 2024-11-22 | KUUSAMO.gg              | W   | 0.532      | 0.284        | 0.000 (0.000)    | 0.162 (0.024)    | 0 (0.000) |     3.84 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           14 |     2965 | 2024-11-22 | PCIFIC Espor            | W   | 0.532      | 0.284        | 0.004 (0.001)    | 0.251 (0.038)    | 0 (0.000) |     8.85 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           13 |     4060 | 2024-11-03 | The Agency Clan         | L   | 0.405      | -            | -                | -                | -         |    -4.32 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           12 |     4092 | 2024-11-03 | Rhyno Youngsters        | W   | 0.403      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.403) |     1.75 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           11 |     4371 | 2024-10-29 | GOOFYBOYZ               | L   | 0.372      | -            | -                | -                | -         |    -5.47 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           10 |     4419 | 2024-10-28 | The Agency Clan         | L   | 0.366      | -            | -                | -                | -         |    -4.09 | h0t, M1KA, Mané, PUIG, Sprayy     |
|            9 |     4702 | 2024-10-22 | RogerBall               | W   | 0.325      | 0.143        | 0.000 (0.000)    | 0.030 (0.001)    | 0 (0.000) |     2.18 | h0t, M1KA, Mané, PUIG, Sprayy     |
|            8 |     4716 | 2024-10-22 | GOOFYBOYZ               | W   | 0.324      | 0.143        | 0.003 (0.000)    | 0.179 (0.008)    | 0 (0.000) |     5.37 | h0t, M1KA, Mané, PUIG, Sprayy     |
|            7 |     4851 | 2024-10-19 | SSKT                    | W   | 0.305      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.32 | h0t, M1KA, Mané, PUIG, Sprayy     |
|            6 |     5232 | 2024-10-12 | Rhyno Youngsters        | L   | 0.257      | -            | -                | -                | -         |    -3.77 | h0t, Horsalo, M1KA, PUIG, Sprayy  |
|            5 |     5262 | 2024-10-11 | 100K                    | W   | 0.252      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.08 | h0t, Horsalo, M1KA, PUIG, Sprayy  |
|            4 |     6087 | 2024-09-28 | Rhyno Esports           | L   | 0.163      | -            | -                | -                | -         |    -1.73 | h0t, Horsalo, M1KA, PUIG, Sprayy  |
|            3 |     6141 | 2024-09-27 | Turritos                | W   | 0.158      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     0.68 | h0t, Horsalo, M1KA, PUIG, Sprayy  |
|            2 |     7356 | 2024-09-08 | SQUAD (Portuguese team) | L   | 0.031      | -            | -                | -                | -         |    -0.79 | h0t, M1KA, PUIG, SeabraEZ, Sprayy |
|            1 |     7432 | 2024-09-07 | EXSAD Gaming            | L   | 0.024      | -            | -                | -                | -         |    -0.62 | h0t, M1KA, PUIG, SeabraEZ, Sprayy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,137.42)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.771 | $2,607.14      | $2,010.88       |
| 2024-12-22 |      0.732 | $52.15         | $38.20          |
| 2024-11-03 |      0.406 | $217.62        | $88.35          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
