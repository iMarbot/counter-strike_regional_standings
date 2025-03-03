### Roster Details<br />
Team Name: Team Sweden (Female team)<br />
Roster: Emmsan, jenkon, juliano, Nea, zAAz<br />
Global Rank: [338](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [219]( ../standings_europe.md)<br />
<br />
Final Rank Value:  630.7<br />
<br />
Final Rank Value (630.7) = Starting Rank Value (634.3) + Head To Head Adjustments (-3.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.149[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 634.3
- 400 + ( ( 0.117 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 634.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3523 | 2024-11-13 | Team Poland (Female team)     | L   | 0.470      | -            | -                | -                | -         |    -2.28 | Emmsan, jenkon, juliano, Nea, zAAz |
|            6 |     3555 | 2024-11-12 | Team Kazakhstan (Female team) | W   | 0.464      | 0.557        | 0.000 (0.000)    | 0.022 (0.006)    | 1 (0.464) |     3.60 | Emmsan, jenkon, juliano, Nea, zAAz |
|            5 |     3622 | 2024-11-11 | Prototype Blaze               | L   | 0.458      | -            | -                | -                | -         |    -3.04 | Emmsan, jenkon, juliano, Nea, zAAz |
|            4 |     3632 | 2024-11-11 | Team Kazakhstan (Female team) | W   | 0.457      | 0.557        | 0.000 (0.000)    | 0.022 (0.006)    | 1 (0.457) |     3.50 | Emmsan, jenkon, juliano, Nea, zAAz |
|            3 |     4499 | 2024-10-27 | AKA HERO KAJO                 | L   | 0.356      | -            | -                | -                | -         |    -3.84 | Emmsan, jenkon, Millz, Nea, Twodes |
|            2 |     4538 | 2024-10-26 | Ex-Astralis Women             | L   | 0.350      | -            | -                | -                | -         |    -3.88 | Emmsan, jenkon, Millz, Nea, Twodes |
|            1 |     4556 | 2024-10-26 | Team Iceland (Female team)    | W   | 0.350      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.350) |     2.31 | Emmsan, jenkon, Millz, Nea, Twodes |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,391.32)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.478 | $5,000.00      | $2,391.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
