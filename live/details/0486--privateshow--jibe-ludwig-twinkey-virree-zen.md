### Roster Details<br />
Team Name: Privateshow<br />
Roster: JiBe, Ludwig, Twinkey, virree, zen<br />
Global Rank: [486](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [301]( ../standings_europe.md)<br />
<br />
Final Rank Value:  527.0<br />
<br />
Final Rank Value (527.0) = Starting Rank Value (519.8) + Head To Head Adjustments (7.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.239[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.060<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 519.8
- 400 + ( ( 0.060 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 519.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     4011 | 2024-11-04 | Alliance             | L   | 0.412      | -            | -                | -                | -         |    -1.52 | JiBe, Ludwig, Twinkey, virree, zen |
|            4 |     4254 | 2024-10-31 | Venom (Swedish team) | W   | 0.385      | 0.143        | 0.000 (0.000)    | 0.062 (0.003)    | 0 (0.000) |     5.76 | JiBe, Ludwig, Twinkey, virree, zen |
|            3 |     5858 | 2024-10-01 | Northern Lights      | W   | 0.185      | 0.143        | 0.000 (0.000)    | 0.037 (0.001)    | 0 (0.000) |     1.98 | JiBe, Ludwig, Twinkey, virree, zen |
|            2 |     6772 | 2024-09-18 | NIP Svea             | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.047 (0.001)    | 0 (0.000) |     1.04 | JiBe, Ludwig, Twinkey, virree, zen |
|            1 |     7588 | 2024-09-05 | Alliance             | L   | 0.012      | -            | -                | -                | -         |    -0.04 | JiBe, Ludwig, Twinkey, virree, zen |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($216.18)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-13 |      0.472 | $458.19        | $216.18         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
