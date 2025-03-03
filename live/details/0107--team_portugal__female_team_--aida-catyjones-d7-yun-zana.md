### Roster Details<br />
Team Name: Team Portugal (Female team)<br />
Roster: Aida, CatyJones, D7, yuN, Zana<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  837.8<br />
<br />
Final Rank Value (837.8) = Starting Rank Value (831.4) + Head To Head Adjustments (6.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.394[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.218[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 831.4
- 400 + ( ( 0.216 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 831.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     3471 | 2024-11-14 | Team USA (Female team)       | W   | 0.477      | 0.557        | 0.015 (0.004)    | 0.022 (0.006)    | 1 (0.477) |     3.63 | Aida, CatyJones, D7, yuN, Zana |
|            4 |     3487 | 2024-11-14 | Prototype Blaze              | L   | 0.476      | -            | -                | -                | -         |    -6.72 | Aida, CatyJones, D7, yuN, Zana |
|            3 |     3530 | 2024-11-13 | Team Australia (Female team) | W   | 0.469      | 0.557        | 0.007 (0.002)    | 0.043 (0.011)    | 1 (0.469) |     4.73 | Aida, CatyJones, D7, yuN, Zana |
|            2 |     3628 | 2024-11-11 | Team USA (Female team)       | W   | 0.458      | 0.557        | 0.015 (0.004)    | 0.022 (0.006)    | 1 (0.458) |     3.54 | Aida, CatyJones, D7, yuN, Zana |
|            1 |     3642 | 2024-11-11 | Team Hong Kong (Female team) | W   | 0.456      | 0.557        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.456) |     1.17 | Aida, CatyJones, D7, yuN, Zana |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,565.28)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.478 | $20,000.00     | $9,565.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
