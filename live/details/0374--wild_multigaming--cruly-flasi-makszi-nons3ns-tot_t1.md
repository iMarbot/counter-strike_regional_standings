### Roster Details<br />
Team Name: WiLD MultiGaming<br />
Roster: cruly, flasi, makszi, NONS3NS, ToT_T1<br />
Global Rank: [374](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [237]( ../standings_europe.md)<br />
<br />
Final Rank Value:  610.2<br />
<br />
Final Rank Value (610.2) = Starting Rank Value (611.3) + Head To Head Adjustments (-1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.228[<sup>1</sup>](#table2)
- Bounty Collected: 0.144[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.051[<sup>2</sup>](#table1)

The average of these factors is 0.106<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 611.3
- 400 + ( ( 0.106 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 611.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     5545 | 2024-10-06 | Békéscsabai E-Sport Egyesület | L   | 0.224      | -            | -                | -                | -         |    -3.25 | cruly, flasi, makszi, NONS3NS, ToT_T1    |
|            5 |     5566 | 2024-10-05 | Positive Vibes                | W   | 0.220      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 1 (0.220) |     3.22 | cruly, flasi, makszi, NONS3NS, ToT_T1    |
|            4 |     5609 | 2024-10-05 | Honvéd Esport                 | L   | 0.218      | -            | -                | -                | -         |    -2.95 | cruly, flasi, makszi, NONS3NS, ToT_T1    |
|            3 |     5625 | 2024-10-05 | Positive Vibes                | W   | 0.217      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 1 (0.217) |     3.19 | cruly, flasi, makszi, NONS3NS, ToT_T1    |
|            2 |     6825 | 2024-09-17 | Dark Cloud Esports            | L   | 0.100      | -            | -                | -                | -         |    -0.69 | flasi, makszi, martinez, NONS3NS, ToT_T1 |
|            1 |     7231 | 2024-09-10 | GameAgents                    | L   | 0.053      | -            | -                | -                | -         |    -0.67 | flasi, makszi, martinez, NONS3NS, ToT_T1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($138.65)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-06 |      0.225 | $615.08        | $138.65         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
