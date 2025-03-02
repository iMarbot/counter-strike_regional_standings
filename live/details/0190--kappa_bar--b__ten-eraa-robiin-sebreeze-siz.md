### Roster Details<br />
Team Name: Kappa Bar<br />
Roster: Bååten, eraa, robiin, SeBreeZe, siz<br />
Global Rank: [190](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [138]( ../standings_europe.md)<br />
<br />
Final Rank Value:  716.2<br />
<br />
Final Rank Value (716.2) = Starting Rank Value (711.9) + Head To Head Adjustments (4.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.187[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.156<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.9
- 400 + ( ( 0.156 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 711.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     2982 | 2024-11-22 | Alliance        | L   | 0.539      | -            | -                | -                | -         |    -4.91 | Bååten, eraa, robiin, SeBreeZe, siz  |
|           12 |     3011 | 2024-11-21 | Johnny Speeds   | L   | 0.533      | -            | -                | -                | -         |    -3.98 | Bååten, eraa, robiin, SeBreeZe, siz  |
|           11 |     3054 | 2024-11-21 | Kario Mart      | W   | 0.531      | 0.143        | 0.004 (0.000)    | 0.064 (0.005)    | 1 (0.531) |     6.38 | Bååten, eraa, robiin, SeBreeZe, siz  |
|           10 |     3314 | 2024-11-16 | Northern Lights | W   | 0.500      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.500) |     3.92 | eraa, robiin, SeBreeZe, siz, Twinkey |
|            9 |     3818 | 2024-11-07 | Metizport       | L   | 0.441      | -            | -                | -                | -         |    -1.59 | eraa, robiin, SeBreeZe, siz, virree  |
|            8 |     3992 | 2024-11-04 | Lilmix          | W   | 0.420      | 0.143        | 0.001 (0.000)    | 0.025 (0.002)    | 0 (0.000) |     3.40 | b0bbzki, Bååten, eraa, robiin, siz   |
|            7 |     4550 | 2024-10-26 | EYEBALLERS      | L   | 0.358      | -            | -                | -                | -         |    -4.26 | eraa, Lekr0, robiin, Sapec, SeBreeZe |
|            6 |     5341 | 2024-10-09 | Megoshort       | W   | 0.246      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     1.66 | eraa, robiin, SeBreeZe, siz, virree  |
|            5 |     5417 | 2024-10-08 | Knaeskydd       | W   | 0.239      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.10 | eraa, robiin, SeBreeZe, siz, virree  |
|            4 |     6192 | 2024-09-26 | Kario Mart      | W   | 0.159      | 0.143        | 0.004 (0.000)    | 0.064 (0.001)    | 0 (0.000) |     1.91 | b0bbzki, Bååten, eraa, robiin, siz   |
|            3 |     7245 | 2024-09-10 | BLEKKSPRUTERS   | W   | 0.052      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.25 | eraa, Ludwig, robiin, siz, virree    |
|            2 |     7290 | 2024-09-09 | INFURITY Gaming | W   | 0.046      | 0.143        | 0.001 (0.000)    | 0.029 (0.000)    | 0 (0.000) |     0.50 | eraa, Ludwig, robiin, siz, virree    |
|            1 |     7663 | 2024-09-04 | Johnny Speeds   | L   | 0.013      | -            | -                | -                | -         |    -0.11 | b0bbzki, Bååten, eraa, robiin, siz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,320.82)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-23 |      0.546 | $2,265.27      | $1,237.56       |
| 2024-11-16 |      0.500 | $910.86        | $455.18         |
| 2024-11-09 |      0.453 | $1,387.18      | $628.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
