### Roster Details<br />
Team Name: Five Handsome Guys<br />
Roster: BoGod, DeathFine, 偶然, 微笑, 郑州理智king<br />
Global Rank: [226](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [27]( ../standings_asia.md)<br />
<br />
Final Rank Value:  689.7<br />
<br />
Final Rank Value (689.7) = Starting Rank Value (686.4) + Head To Head Adjustments (3.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.239[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.085[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 686.4
- 400 + ( ( 0.143 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 686.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |      852 | 2025-02-06 | Believe.        | L   | 1.000      | -            | -                | -                | -         |   -22.66 | BoGod, DeathFine, 偶然, 微笑, 郑州理智king      |
|            6 |      854 | 2025-02-06 | Butcher Legion  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     5.01 | BoGod, DeathFine, 偶然, 微笑, 郑州理智king      |
|            5 |      868 | 2025-02-05 | Change The Game | W   | 1.000      | 0.143        | 0.061 (0.009)    | 0.221 (0.032)    | 0 (0.000) |    17.96 | BoGod, DeathFine, 偶然, 微笑, 郑州理智king      |
|            4 |     3751 | 2024-11-09 | FengDa Gaming   | L   | 0.451      | -            | -                | -                | -         |    -6.93 | BoGod, DeathFine, mONESY, RosyClou9, 微笑 |
|            3 |     3760 | 2024-11-09 | Hunt Now        | W   | 0.451      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.57 | BoGod, DeathFine, mONESY, RosyClou9, 微笑 |
|            2 |     4481 | 2024-10-27 | Team Xinyang    | W   | 0.365      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 1 (0.365) |     4.43 | BoGod, DeathFine, Zpy, 微笑, 暴躁bb         |
|            1 |     4494 | 2024-10-26 | Team Zhengzhou  | W   | 0.362      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.362) |     1.90 | BoGod, DeathFine, Zpy, 微笑, 暴躁bb         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($217.30)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.457 | $139.29        | $63.69          |
| 2024-10-27 |      0.365 | $421.19        | $153.62         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
