### Roster Details<br />
Team Name: Marsborne<br />
Roster: chop, Grizz, Minus, motm, WolfY<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  903.9<br />
<br />
Final Rank Value (903.9) = Starting Rank Value (888.2) + Head To Head Adjustments (15.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.051[<sup>2</sup>](#table1)
- LAN Wins: 0.351[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 888.2
- 400 + ( ( 0.244 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 888.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |        0 | 2025-03-02 | BLUEJAYS        | L   | 1.000      | -            | -                | -                | -         |    -9.31 | chop, Grizz, Minus, motm, WolfY |
|           12 |        1 | 2025-03-02 | Getting Info    | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.309 (0.103)    | 1 (1.000) |    15.21 | chop, Grizz, Minus, motm, WolfY |
|           11 |        5 | 2025-03-01 | Wanted Goons    | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.141 (0.047)    | 1 (1.000) |     5.17 | chop, Grizz, Minus, motm, WolfY |
|           10 |        9 | 2025-03-01 | SUPER EVIL GANG | W   | 1.000      | 0.333        | 0.009 (0.003)    | 0.352 (0.117)    | 1 (1.000) |     8.07 | chop, Grizz, Minus, motm, WolfY |
|            9 |      555 | 2025-02-11 | Nouns Esports   | L   | 1.000      | -            | -                | -                | -         |   -16.36 | chop, Grizz, Minus, motm, WolfY |
|            8 |      560 | 2025-02-11 | NRG             | L   | 1.000      | -            | -                | -                | -         |   -10.50 | chop, Grizz, Minus, motm, WolfY |
|            7 |      583 | 2025-02-10 | M80             | L   | 1.000      | -            | -                | -                | -         |   -12.76 | chop, Minus, motm, steel, WolfY |
|            6 |      587 | 2025-02-10 | MCS Gaming      | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.343 (0.049)    | 0 (0.000) |     5.59 | chop, Minus, motm, steel, WolfY |
|            5 |      624 | 2025-02-09 | M80             | L   | 1.000      | -            | -                | -                | -         |   -13.65 | chop, Minus, motm, steel, WolfY |
|            4 |      662 | 2025-02-08 | Nouns Esports   | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.327 (0.047)    | 0 (0.000) |    13.97 | chop, Grizz, Minus, motm, WolfY |
|            3 |      666 | 2025-02-08 | Getting Info    | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.309 (0.044)    | 0 (0.000) |    15.18 | chop, Grizz, Minus, motm, WolfY |
|            2 |      678 | 2025-02-08 | MCS Gaming      | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.343 (0.049)    | 0 (0.000) |     5.90 | chop, Minus, motm, steel, WolfY |
|            1 |      742 | 2025-02-07 | SUPER EVIL GANG | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.352 (0.050)    | 0 (0.000) |     9.25 | chop, Grizz, Minus, motm, WolfY |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,500.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-02 |      1.000 | $2,500.00      | $2,500.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
