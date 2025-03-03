### Roster Details<br />
Team Name: POOHANK<br />
Roster: Aura, BerkanBey, BoZZo, KatzRead, suisha<br />
Global Rank: [451](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [281]( ../standings_europe.md)<br />
<br />
Final Rank Value:  560.1<br />
<br />
Final Rank Value (560.1) = Starting Rank Value (575.2) + Head To Head Adjustments (-15.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.187[<sup>1</sup>](#table2)
- Bounty Collected: 0.162[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.088<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 575.2
- 400 + ( ( 0.088 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 575.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     2495 | 2024-11-30 | Regnum4Games    | L   | 0.586      | -            | -                | -                | -         |    -7.32 | Aura, BerkanBey, BoZZo, KatzRead, suisha   |
|            5 |     2642 | 2024-11-28 | Donstu Esports  | L   | 0.572      | -            | -                | -                | -         |   -10.84 | Aura, BerkanBey, BoZZo, KatzRead, suisha   |
|            4 |     5716 | 2024-10-03 | 777 Esports     | L   | 0.200      | -            | -                | -                | -         |    -2.55 | Aura, BerkanBey, BoZZo, KatzRead, suisha   |
|            3 |     6054 | 2024-09-28 | Underrated      | W   | 0.164      | 0.215        | 0.002 (0.000)    | 0.268 (0.009)    | 0 (0.000) |     3.42 | Aura, BerkanBey, BoZZo, KatzRead, suisha   |
|            2 |     6069 | 2024-09-28 | Infinite Gaming | W   | 0.163      | 0.215        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     2.68 | Aura, BerkanBey, BoZZo, KatzRead, suisha   |
|            1 |     7403 | 2024-09-07 | GoodCall        | L   | 0.025      | -            | -                | -                | -         |    -0.52 | Aura, BerkanBey, BoZZo, KatzRead, LORDLPAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14.99)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-03 |      0.200 | $75.00         | $14.99          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
