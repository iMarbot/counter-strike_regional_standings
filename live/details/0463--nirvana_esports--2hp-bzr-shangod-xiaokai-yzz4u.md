### Roster Details<br />
Team Name: Nirvana Esports<br />
Roster: 2HP, BZR, ShanGod, Xiaokai, Yzz4u<br />
Global Rank: [463](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [76]( ../standings_asia.md)<br />
<br />
Final Rank Value:  552.5<br />
<br />
Final Rank Value (552.5) = Starting Rank Value (576.9) + Head To Head Adjustments (-24.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.212[<sup>1</sup>](#table2)
- Bounty Collected: 0.138[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.088<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 576.9
- 400 + ( ( 0.088 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 576.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |      446 | 2025-02-14 | Boring Players          | L   | 1.000      | -            | -                | -                | -         |   -17.30 | 2HP, BZR, ShanGod, Xiaokai, Yzz4u   |
|            6 |      455 | 2025-02-14 | LaiShanHui              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.188 (0.027)    | 0 (0.000) |     8.66 | 2HP, BZR, ShanGod, Xiaokai, Yzz4u   |
|            5 |     1344 | 2024-12-27 | Teamwork (Chinese team) | L   | 0.763      | -            | -                | -                | -         |    -8.28 | 2HP, BZR, VodKe, Xiaokai•◡•, Yzz4u  |
|            4 |     1520 | 2024-12-20 | Nirik Gaming            | W   | 0.718      | 0.372        | 0.000 (0.000)    | 0.031 (0.008)    | 0 (0.000) |     6.62 | 2HP, BZR, VodKe, Xiaokai•◡•, Yzz4u  |
|            3 |     1905 | 2024-12-11 | TycooN                  | L   | 0.657      | -            | -                | -                | -         |   -12.81 | 2HP, BZR, VodKe, Xiaokai•◡•, Yzz4u  |
|            2 |     3760 | 2024-11-09 | 冯福山冯福令                  | L   | 0.443      | -            | -                | -                | -         |    -6.71 | 2HP, BZR, MashirOvO, VodKe, Xiaokai |
|            1 |     3764 | 2024-11-09 | TycooN                  | W   | 0.443      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.44 | 2HP, BZR, MashirOvO, VodKe, Xiaokai |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($62.55)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.449 | $139.29        | $62.55          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
