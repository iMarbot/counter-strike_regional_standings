### Roster Details<br />
Team Name: 5 - 1 and dead<br />
Roster: Brocke, Praze, Sonyes, Time-Warrior, Walk-it-back<br />
Global Rank: [388](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [83]( ../standings_americas.md)<br />
<br />
Final Rank Value:  604.3<br />
<br />
Final Rank Value (604.3) = Starting Rank Value (598.8) + Head To Head Adjustments (5.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.242[<sup>1</sup>](#table2)
- Bounty Collected: 0.156[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.099<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 598.8
- 400 + ( ( 0.099 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 598.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     6555 | 2024-09-21 | 1gang      | W   | 0.120      | 0.310        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.82 | Brocke, Praze, Sonyes, Time-Warrior, Walk-it-back |
|            4 |     6617 | 2024-09-20 | Thegns     | W   | 0.114      | 0.310        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.69 | Brocke, Praze, Sonyes, Time-Warrior, Walk-it-back |
|            3 |     6670 | 2024-09-19 | Bomb Squad | W   | 0.107      | 0.310        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     1.58 | Brocke, Praze, Sonyes, Time-Warrior, Walk-it-back |
|            2 |     6734 | 2024-09-18 | PowerMode  | W   | 0.100      | 0.310        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     1.46 | Brocke, Praze, Sonyes, Time-Warrior, Walk-it-back |
|            1 |     7121 | 2024-09-12 | Thegns     | L   | 0.060      | -            | -                | -                | -         |    -1.00 | Brocke, Praze, Sonyes, Time-Warrior, Walk-it-back |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($240.56)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.120 | $2,000.00      | $240.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
