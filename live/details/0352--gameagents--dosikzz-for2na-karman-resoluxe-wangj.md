### Roster Details<br />
Team Name: GameAgents<br />
Roster: dosikzz, for2na, KarmaN, ResoLuxe, WANGJ<br />
Global Rank: [352](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [227]( ../standings_europe.md)<br />
<br />
Final Rank Value:  623.7<br />
<br />
Final Rank Value (623.7) = Starting Rank Value (601.7) + Head To Head Adjustments (22.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.191[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.101<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 601.7
- 400 + ( ( 0.101 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 601.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     2322 | 2024-12-02 | ALTERNATE aTTaX       | L   | 0.607      | -            | -                | -                | -         |    -2.84 | dosikzz, for2na, KarmaN, ResoLuxe, WANGJ |
|           13 |     2478 | 2024-11-30 | Flame Sharks          | W   | 0.594      | 0.372        | 0.000 (0.000)    | 0.170 (0.038)    | 0 (0.000) |    10.09 | dosikzz, for2na, KarmaN, ResoLuxe, WANGJ |
|           12 |     2608 | 2024-11-28 | Nuclear TigeRES       | L   | 0.580      | -            | -                | -                | -         |    -4.75 | dosikzz, for2na, KarmaN, ResoLuxe, WANGJ |
|           11 |     5198 | 2024-10-12 | NOTTODAY              | L   | 0.266      | -            | -                | -                | -         |    -4.27 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|           10 |     5204 | 2024-10-12 | THE GENTLEMEN ESPORTS | W   | 0.266      | 0.215        | 0.001 (0.000)    | 0.269 (0.015)    | 0 (0.000) |     5.19 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            9 |     5213 | 2024-10-12 | Rejected by all       | W   | 0.265      | 0.215        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     1.93 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            8 |     5233 | 2024-10-12 | HyperSpirit           | W   | 0.265      | 0.215        | 0.004 (0.000)    | 0.121 (0.007)    | 0 (0.000) |     4.82 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            7 |     5887 | 2024-09-30 | G2 Ares               | W   | 0.188      | 0.143        | 0.001 (0.000)    | 0.261 (0.007)    | 0 (0.000) |     3.64 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            6 |     5890 | 2024-09-30 | Ex-ESC Gaming         | W   | 0.187      | 0.143        | 0.001 (0.000)    | 0.243 (0.007)    | 0 (0.000) |     3.35 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            5 |     5894 | 2024-09-30 | BAKS Esports          | W   | 0.187      | 0.143        | 0.000 (0.000)    | 0.153 (0.004)    | 0 (0.000) |     2.24 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            4 |     7297 | 2024-09-09 | Underrated            | W   | 0.046      | 0.221        | 0.002 (0.000)    | 0.271 (0.003)    | 0 (0.000) |     0.91 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            3 |     7305 | 2024-09-09 | CS2NEWS               | W   | 0.045      | 0.221        | 0.000 (0.000)    | 0.014 (0.000)    | 0 (0.000) |     0.61 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            2 |     7338 | 2024-09-08 | 500                   | W   | 0.040      | 0.221        | 0.091 (0.001)    | 1.000 (0.009)    | 0 (0.000) |     1.13 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            1 |     7685 | 2024-09-04 | ALTERNATE aTTaX       | L   | 0.011      | -            | -                | -                | -         |    -0.04 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19.93)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-12 |      0.266 | $75.00         | $19.93          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
