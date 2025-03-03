### Roster Details<br />
Team Name: Five Handsome Guys<br />
Roster: BoGod, DeathFine, 偶然, 微笑, 郑州理智king<br />
Global Rank: [230](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [27]( ../standings_asia.md)<br />
<br />
Final Rank Value:  689.5<br />
<br />
Final Rank Value (689.5) = Starting Rank Value (686.2) + Head To Head Adjustments (3.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.239[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.083[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 686.2
- 400 + ( ( 0.143 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 686.2


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
|            7 |      864 | 2025-02-06 | Believe.        | L   | 1.000      | -            | -                | -                | -         |   -22.65 | BoGod, DeathFine, 偶然, 微笑, 郑州理智king      |
|            6 |      866 | 2025-02-06 | Butcher Legion  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     5.02 | BoGod, DeathFine, 偶然, 微笑, 郑州理智king      |
|            5 |      880 | 2025-02-05 | Change The Game | W   | 1.000      | 0.143        | 0.061 (0.009)    | 0.221 (0.032)    | 0 (0.000) |    18.02 | BoGod, DeathFine, 偶然, 微笑, 郑州理智king      |
|            4 |     3763 | 2024-11-09 | FengDa Gaming   | L   | 0.443      | -            | -                | -                | -         |    -6.79 | BoGod, DeathFine, mONESY, RosyClou9, 微笑 |
|            3 |     3772 | 2024-11-09 | Hunt Now        | W   | 0.442      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.51 | BoGod, DeathFine, mONESY, RosyClou9, 微笑 |
|            2 |     4493 | 2024-10-27 | Team Xinyang    | W   | 0.357      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 1 (0.357) |     4.33 | BoGod, DeathFine, Zpy, 微笑, 暴躁bb         |
|            1 |     4506 | 2024-10-26 | Team Zhengzhou  | W   | 0.354      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.354) |     1.86 | BoGod, DeathFine, Zpy, 微笑, 暴躁bb         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($212.71)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.449 | $139.29        | $62.55          |
| 2024-10-27 |      0.357 | $421.19        | $150.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
