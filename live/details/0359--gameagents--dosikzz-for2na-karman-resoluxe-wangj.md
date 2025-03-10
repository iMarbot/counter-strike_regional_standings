### Roster Details<br />
Team Name: GameAgents<br />
Roster: dosikzz, for2na, KarmaN, ResoLuxe, WANGJ<br />
Global Rank: [359](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [230]( ../standings_europe.md)<br />
<br />
Final Rank Value:  621.3<br />
<br />
Final Rank Value (621.3) = Starting Rank Value (600.3) + Head To Head Adjustments (21.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.191[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 600.3
- 400 + ( ( 0.100 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 600.3


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
|           14 |     2334 | 2024-12-02 | ALTERNATE aTTaX       | L   | 0.599      | -            | -                | -                | -         |    -2.80 | dosikzz, for2na, KarmaN, ResoLuxe, WANGJ |
|           13 |     2490 | 2024-11-30 | Flame Sharks          | W   | 0.586      | 0.372        | 0.000 (0.000)    | 0.167 (0.036)    | 0 (0.000) |     9.99 | dosikzz, for2na, KarmaN, ResoLuxe, WANGJ |
|           12 |     2620 | 2024-11-28 | Nuclear TigeRES       | L   | 0.572      | -            | -                | -                | -         |    -4.63 | dosikzz, for2na, KarmaN, ResoLuxe, WANGJ |
|           11 |     5210 | 2024-10-12 | NOTTODAY              | L   | 0.258      | -            | -                | -                | -         |    -4.11 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|           10 |     5216 | 2024-10-12 | THE GENTLEMEN ESPORTS | W   | 0.257      | 0.215        | 0.001 (0.000)    | 0.263 (0.015)    | 0 (0.000) |     5.03 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            9 |     5225 | 2024-10-12 | Rejected by all       | W   | 0.257      | 0.215        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     1.89 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            8 |     5245 | 2024-10-12 | HyperSpirit           | W   | 0.256      | 0.215        | 0.004 (0.000)    | 0.119 (0.007)    | 0 (0.000) |     4.70 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            7 |     5899 | 2024-09-30 | G2 Ares               | W   | 0.179      | 0.143        | 0.001 (0.000)    | 0.257 (0.007)    | 0 (0.000) |     3.49 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            6 |     5902 | 2024-09-30 | Ex-ESC Gaming         | W   | 0.179      | 0.143        | 0.001 (0.000)    | 0.239 (0.006)    | 0 (0.000) |     3.21 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            5 |     5906 | 2024-09-30 | BAKS Esports          | W   | 0.179      | 0.143        | 0.000 (0.000)    | 0.151 (0.004)    | 0 (0.000) |     2.16 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            4 |     7309 | 2024-09-09 | Underrated            | W   | 0.038      | 0.221        | 0.002 (0.000)    | 0.268 (0.002)    | 0 (0.000) |     0.75 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            3 |     7318 | 2024-09-09 | CS2NEWS               | W   | 0.037      | 0.221        | 0.000 (0.000)    | 0.013 (0.000)    | 0 (0.000) |     0.50 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            2 |     7350 | 2024-09-08 | 500                   | W   | 0.032      | 0.221        | 0.093 (0.001)    | 1.000 (0.007)    | 0 (0.000) |     0.90 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |
|            1 |     7697 | 2024-09-04 | ALTERNATE aTTaX       | L   | 0.002      | -            | -                | -                | -         |    -0.01 | dosikzz, for2na, ResoLuxe, rinn, WANGJ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19.32)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-12 |      0.258 | $75.00         | $19.32          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
