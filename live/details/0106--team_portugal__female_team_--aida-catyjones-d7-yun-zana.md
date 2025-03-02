### Roster Details<br />
Team Name: Team Portugal (Female team)<br />
Roster: Aida, CatyJones, D7, yuN, Zana<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  838.8<br />
<br />
Final Rank Value (838.8) = Starting Rank Value (832.4) + Head To Head Adjustments (6.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.394[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.221[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 832.4
- 400 + ( ( 0.216 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 832.4


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
|            5 |     3459 | 2024-11-14 | Team USA (Female team)       | W   | 0.485      | 0.557        | 0.014 (0.004)    | 0.022 (0.006)    | 1 (0.485) |     3.69 | Aida, CatyJones, D7, yuN, Zana |
|            4 |     3475 | 2024-11-14 | Prototype Blaze              | L   | 0.484      | -            | -                | -                | -         |    -6.84 | Aida, CatyJones, D7, yuN, Zana |
|            3 |     3518 | 2024-11-13 | Team Australia (Female team) | W   | 0.477      | 0.557        | 0.007 (0.002)    | 0.044 (0.012)    | 1 (0.477) |     4.80 | Aida, CatyJones, D7, yuN, Zana |
|            2 |     3616 | 2024-11-11 | Team USA (Female team)       | W   | 0.466      | 0.557        | 0.014 (0.004)    | 0.022 (0.006)    | 1 (0.466) |     3.60 | Aida, CatyJones, D7, yuN, Zana |
|            1 |     3630 | 2024-11-11 | Team Hong Kong (Female team) | W   | 0.464      | 0.557        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.464) |     1.19 | Aida, CatyJones, D7, yuN, Zana |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,729.17)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.486 | $20,000.00     | $9,729.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
