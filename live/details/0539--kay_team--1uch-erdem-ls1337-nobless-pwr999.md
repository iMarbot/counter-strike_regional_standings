### Roster Details<br />
Team Name: Kay Team<br />
Roster: 1uch, Erdem, ls1337, NoBless, pwr999<br />
Global Rank: [539](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [335]( ../standings_europe.md)<br />
<br />
Final Rank Value:  484.6<br />
<br />
Final Rank Value (484.6) = Starting Rank Value (507.5) + Head To Head Adjustments (-22.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 507.5
- 400 + ( ( 0.054 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 507.5


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
|           20 |     3024 | 2024-11-21 | ALTERNATE aTTaX        | L   | 0.533      | -            | -                | -                | -         |    -1.33 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           19 |     3095 | 2024-11-20 | HyperSpirit            | L   | 0.527      | -            | -                | -                | -         |    -4.71 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           18 |     3192 | 2024-11-18 | Lausanne-Sport Esports | L   | 0.514      | -            | -                | -                | -         |    -6.45 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           17 |     3370 | 2024-11-15 | Lazer Cats             | L   | 0.494      | -            | -                | -                | -         |    -3.11 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           16 |     3380 | 2024-11-15 | Permitta Esports       | L   | 0.493      | -            | -                | -                | -         |    -2.45 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           15 |     3440 | 2024-11-14 | GODSENT                | L   | 0.486      | -            | -                | -                | -         |    -4.08 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           14 |     4293 | 2024-10-30 | GTZ.ESPORTS            | L   | 0.387      | -            | -                | -                | -         |    -0.27 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           13 |     4411 | 2024-10-28 | THE SPELLS             | L   | 0.374      | -            | -                | -                | -         |    -5.18 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           12 |     4429 | 2024-10-28 | Lilmix                 | L   | 0.373      | -            | -                | -                | -         |    -3.86 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           11 |     4656 | 2024-10-23 | Ex-Soul's Heart Esport | L   | 0.340      | -            | -                | -                | -         |    -3.75 | 1uch, Erdem, NoBless, pfq, pwr999    |
|           10 |     4710 | 2024-10-22 | FLuffy Gangsters       | L   | 0.332      | -            | -                | -                | -         |    -1.77 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            9 |     4731 | 2024-10-21 | XP Academy             | L   | 0.326      | -            | -                | -                | -         |    -4.55 | 1uch, Erdem, NoBless, pfq, pwr999    |
|            8 |     4794 | 2024-10-20 | Nexus Gaming           | L   | 0.319      | -            | -                | -                | -         |    -0.33 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            7 |     4831 | 2024-10-19 | K27                    | W   | 0.313      | 0.333        | 0.008 (0.001)    | 0.776 (0.081)    | 0 (0.000) |     8.91 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            6 |     4892 | 2024-10-18 | BC.Game Esports        | L   | 0.306      | -            | -                | -                | -         |    -1.40 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            5 |     4943 | 2024-10-17 | Viperio                | W   | 0.298      | 0.333        | 0.002 (0.000)    | 0.411 (0.041)    | 0 (0.000) |     7.49 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            4 |     5069 | 2024-10-15 | RUSTEC                 | W   | 0.286      | 0.333        | 0.000 (0.000)    | 0.217 (0.021)    | 0 (0.000) |     5.12 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            3 |     5113 | 2024-10-14 | FLuffy Gangsters       | L   | 0.278      | -            | -                | -                | -         |    -1.43 | 1uch, Erdem, ls1337, NoBless, pwr999 |
|            2 |     6043 | 2024-09-28 | 777 Esports            | L   | 0.172      | -            | -                | -                | -         |    -1.71 | 1uch, Erdem, NoBless, pfq, pwr999    |
|            1 |     6051 | 2024-09-28 | Oshikousei             | W   | 0.172      | 0.215        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.91 | 1uch, Erdem, NoBless, pfq, pwr999    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
