### Roster Details<br />
Team Name: Team Sweden (Female team)<br />
Roster: Emmsan, jenkon, juliano, Nea, zAAz<br />
Global Rank: [335](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [219]( ../standings_europe.md)<br />
<br />
Final Rank Value:  631.3<br />
<br />
Final Rank Value (631.3) = Starting Rank Value (635.0) + Head To Head Adjustments (-3.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.318[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.151[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 635.0
- 400 + ( ( 0.118 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 635.0


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
|            7 |     3511 | 2024-11-13 | Team Poland (Female team)     | L   | 0.478      | -            | -                | -                | -         |    -2.32 | Emmsan, jenkon, juliano, Nea, zAAz |
|            6 |     3543 | 2024-11-12 | Team Kazakhstan (Female team) | W   | 0.473      | 0.557        | 0.000 (0.000)    | 0.022 (0.006)    | 1 (0.473) |     3.66 | Emmsan, jenkon, juliano, Nea, zAAz |
|            5 |     3610 | 2024-11-11 | Prototype Blaze               | L   | 0.466      | -            | -                | -                | -         |    -3.09 | Emmsan, jenkon, juliano, Nea, zAAz |
|            4 |     3620 | 2024-11-11 | Team Kazakhstan (Female team) | W   | 0.465      | 0.557        | 0.000 (0.000)    | 0.022 (0.006)    | 1 (0.465) |     3.56 | Emmsan, jenkon, juliano, Nea, zAAz |
|            3 |     4487 | 2024-10-27 | AKA HERO KAJO                 | L   | 0.364      | -            | -                | -                | -         |    -3.92 | Emmsan, jenkon, Millz, Nea, Twodes |
|            2 |     4526 | 2024-10-26 | Ex-Astralis Women             | L   | 0.359      | -            | -                | -                | -         |    -3.97 | Emmsan, jenkon, Millz, Nea, Twodes |
|            1 |     4544 | 2024-10-26 | Team Iceland (Female team)    | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.358) |     2.36 | Emmsan, jenkon, Millz, Nea, Twodes |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,432.29)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.486 | $5,000.00      | $2,432.29       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
