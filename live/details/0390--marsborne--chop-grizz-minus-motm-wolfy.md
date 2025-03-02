### Roster Details<br />
Team Name: Marsborne<br />
Roster: chop, Grizz, Minus, motm, WolfY<br />
Global Rank: [390](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [81]( ../standings_americas.md)<br />
<br />
Final Rank Value:  602.3<br />
<br />
Final Rank Value (602.3) = Starting Rank Value (520.8) + Head To Head Adjustments (81.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.060<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 520.8
- 400 + ( ( 0.060 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 520.8


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
|            9 |      543 | 2025-02-11 | Nouns Esports   | L   | 1.000      | -            | -                | -                | -         |    -6.74 | chop, Grizz, Minus, motm, WolfY |
|            8 |      548 | 2025-02-11 | NRG             | L   | 1.000      | -            | -                | -                | -         |    -3.01 | chop, Grizz, Minus, motm, WolfY |
|            7 |      571 | 2025-02-10 | M80             | L   | 1.000      | -            | -                | -                | -         |    -3.82 | chop, Minus, motm, steel, WolfY |
|            6 |      575 | 2025-02-10 | MCS Gaming      | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.344 (0.049)    | 0 (0.000) |    16.59 | chop, Minus, motm, steel, WolfY |
|            5 |      612 | 2025-02-09 | M80             | L   | 1.000      | -            | -                | -                | -         |    -3.65 | chop, Minus, motm, steel, WolfY |
|            4 |      650 | 2025-02-08 | Nouns Esports   | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.328 (0.047)    | 0 (0.000) |    25.86 | chop, Grizz, Minus, motm, WolfY |
|            3 |      654 | 2025-02-08 | Getting Info    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.093 (0.013)    | 0 (0.000) |    13.81 | chop, Grizz, Minus, motm, WolfY |
|            2 |      666 | 2025-02-08 | MCS Gaming      | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.344 (0.049)    | 0 (0.000) |    19.01 | chop, Minus, motm, steel, WolfY |
|            1 |      730 | 2025-02-07 | Alter Iron Club | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.356 (0.051)    | 0 (0.000) |    23.49 | chop, Grizz, Minus, motm, WolfY |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
