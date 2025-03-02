### Roster Details<br />
Team Name: Impulse GW<br />
Roster: h0t, M1KA, Mané, PUIG, Sprayy<br />
Global Rank: [198](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [144]( ../standings_europe.md)<br />
<br />
Final Rank Value:  712.2<br />
<br />
Final Rank Value (712.2) = Starting Rank Value (732.1) + Head To Head Adjustments (-19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.139[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 732.1
- 400 + ( ( 0.166 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 732.1


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
|           19 |     1291 | 2024-12-28 | CHAOX ESPORTS           | W   | 0.779      | 0.291        | 0.002 (0.001)    | 0.000 (0.000)    | 1 (0.779) |     6.76 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           18 |     1443 | 2024-12-21 | The Agency Clan         | L   | 0.733      | -            | -                | -                | -         |    -7.37 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           17 |     2319 | 2024-12-02 | ZOTIX                   | L   | 0.607      | -            | -                | -                | -         |   -12.18 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           16 |     2618 | 2024-11-28 | Ex-ESC Gaming           | L   | 0.580      | -            | -                | -                | -         |   -11.07 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           15 |     2947 | 2024-11-22 | KUUSAMO.gg              | W   | 0.540      | 0.284        | 0.000 (0.000)    | 0.164 (0.025)    | 0 (0.000) |     3.90 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           14 |     2953 | 2024-11-22 | PCIFIC Espor            | W   | 0.540      | 0.284        | 0.004 (0.001)    | 0.254 (0.039)    | 0 (0.000) |     9.01 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           13 |     4048 | 2024-11-03 | The Agency Clan         | L   | 0.413      | -            | -                | -                | -         |    -4.38 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           12 |     4080 | 2024-11-03 | Rhyno Youngsters        | W   | 0.411      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.411) |     1.79 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           11 |     4359 | 2024-10-29 | GOOFYBOYZ               | L   | 0.380      | -            | -                | -                | -         |    -5.58 | h0t, M1KA, Mané, PUIG, Sprayy     |
|           10 |     4407 | 2024-10-28 | The Agency Clan         | L   | 0.374      | -            | -                | -                | -         |    -4.17 | h0t, M1KA, Mané, PUIG, Sprayy     |
|            9 |     4690 | 2024-10-22 | RogerBall               | W   | 0.334      | 0.143        | 0.000 (0.000)    | 0.030 (0.001)    | 0 (0.000) |     2.24 | h0t, M1KA, Mané, PUIG, Sprayy     |
|            8 |     4704 | 2024-10-22 | GOOFYBOYZ               | W   | 0.333      | 0.143        | 0.003 (0.000)    | 0.183 (0.009)    | 0 (0.000) |     5.52 | h0t, M1KA, Mané, PUIG, Sprayy     |
|            7 |     4839 | 2024-10-19 | SSKT                    | W   | 0.313      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.36 | h0t, M1KA, Mané, PUIG, Sprayy     |
|            6 |     5221 | 2024-10-12 | Rhyno Youngsters        | L   | 0.265      | -            | -                | -                | -         |    -3.88 | h0t, Horsalo, M1KA, PUIG, Sprayy  |
|            5 |     5250 | 2024-10-11 | 100K                    | W   | 0.260      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.12 | h0t, Horsalo, M1KA, PUIG, Sprayy  |
|            4 |     6075 | 2024-09-28 | Rhyno Esports           | L   | 0.171      | -            | -                | -                | -         |    -1.80 | h0t, Horsalo, M1KA, PUIG, Sprayy  |
|            3 |     6129 | 2024-09-27 | Turritos                | W   | 0.166      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     0.71 | h0t, Horsalo, M1KA, PUIG, Sprayy  |
|            2 |     7344 | 2024-09-08 | SQUAD (Portuguese team) | L   | 0.039      | -            | -                | -                | -         |    -0.99 | h0t, M1KA, PUIG, SeabraEZ, Sprayy |
|            1 |     7420 | 2024-09-07 | EXSAD Gaming            | L   | 0.032      | -            | -                | -                | -         |    -0.83 | h0t, M1KA, PUIG, SeabraEZ, Sprayy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,161.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.779 | $2,607.14      | $2,032.24       |
| 2024-12-22 |      0.741 | $52.15         | $38.62          |
| 2024-11-03 |      0.414 | $217.62        | $90.13          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
