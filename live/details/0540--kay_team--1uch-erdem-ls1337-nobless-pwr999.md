### Roster Details<br />
Team Name: Kay Team<br />
Roster: 1uch, Erdem, ls1337, NoBless, pwr999<br />
Global Rank: [540](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [334]( ../standings_europe.md)<br />
<br />
Final Rank Value:  484.4<br />
<br />
Final Rank Value (484.4) = Starting Rank Value (507.2) + Head To Head Adjustments (-22.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 507.2
- 400 + ( ( 0.054 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 507.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     3036 | 2024-11-21 | ALTERNATE aTTaX        | L   | 0.525      | -            | -                | -                | -         |    -1.32 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           19 |     3107 | 2024-11-20 | HyperSpirit            | L   | 0.519      | -            | -                | -                | -         |    -4.64 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           18 |     3204 | 2024-11-18 | Lausanne-Sport Esports | L   | 0.505      | -            | -                | -                | -         |    -6.36 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           17 |     3382 | 2024-11-15 | Lazer Cats             | L   | 0.485      | -            | -                | -                | -         |    -3.07 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           16 |     3392 | 2024-11-15 | Permitta Esports       | L   | 0.485      | -            | -                | -                | -         |    -2.42 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           15 |     3452 | 2024-11-14 | GODSENT                | L   | 0.478      | -            | -                | -                | -         |    -4.05 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           14 |     4305 | 2024-10-30 | GTZ.ESPORTS            | L   | 0.379      | -            | -                | -                | -         |    -0.27 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           13 |     4423 | 2024-10-28 | THE SPELLS             | L   | 0.365      | -            | -                | -                | -         |    -5.08 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           12 |     4441 | 2024-10-28 | Lilmix                 | L   | 0.365      | -            | -                | -                | -         |    -3.76 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           11 |     4668 | 2024-10-23 | Ex-Soul's Heart Esport | L   | 0.332      | -            | -                | -                | -         |    -3.66 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           10 |     4722 | 2024-10-22 | FLuffy Gangsters       | L   | 0.324      | -            | -                | -                | -         |    -1.74 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            9 |     4743 | 2024-10-21 | XP Academy             | L   | 0.318      | -            | -                | -                | -         |    -4.44 | 1uch, Erdem, NoBless, pfq, pwr999    |
|            8 |     4806 | 2024-10-20 | Nexus Gaming           | L   | 0.311      | -            | -                | -                | -         |    -0.32 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            7 |     4843 | 2024-10-19 | K27                    | W   | 0.305      | 0.333        | 0.008 (0.001)    | 0.769 (0.078)    | 0 (0.000) |     8.68 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            6 |     4904 | 2024-10-18 | BC.Game Esports        | L   | 0.297      | -            | -                | -                | -         |    -1.36 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            5 |     4955 | 2024-10-17 | Viperio                | W   | 0.290      | 0.333        | 0.002 (0.000)    | 0.404 (0.039)    | 0 (0.000) |     7.27 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            4 |     5081 | 2024-10-15 | RUSTEC                 | W   | 0.278      | 0.333        | 0.000 (0.000)    | 0.216 (0.020)    | 0 (0.000) |     4.97 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            3 |     5125 | 2024-10-14 | FLuffy Gangsters       | L   | 0.270      | -            | -                | -                | -         |    -1.40 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            2 |     6055 | 2024-09-28 | 777 Esports            | L   | 0.164      | -            | -                | -                | -         |    -1.63 | 1uch, Erdem, NoBless, pfq, pwr999    |
|            1 |     6063 | 2024-09-28 | Oshikousei             | W   | 0.164      | 0.215        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.82 | 1uch, Erdem, NoBless, pfq, pwr999    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
