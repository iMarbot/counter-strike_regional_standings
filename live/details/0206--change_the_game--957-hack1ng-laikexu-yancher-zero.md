### Roster Details<br />
Team Name: Change The Game<br />
Roster: 957, Hack1ng, LaiKeXu, yancher, zero<br />
Global Rank: [206](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [23]( ../standings_asia.md)<br />
<br />
Final Rank Value:  709.4<br />
<br />
Final Rank Value (709.4) = Starting Rank Value (790.0) + Head To Head Adjustments (-80.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.084[<sup>2</sup>](#table1)

The average of these factors is 0.195<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.0
- 400 + ( ( 0.195 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 790.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |       34 | 2025-02-26 | DogEvil               | L   | 1.000      | -            | -                | -                | -         |    -9.02 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|           13 |       48 | 2025-02-25 | FengDa Gaming         | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.550 (0.079)    | 0 (0.000) |    15.11 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|           12 |       54 | 2025-02-25 | Shika                 | L   | 1.000      | -            | -                | -                | -         |   -19.45 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|           11 |       74 | 2025-02-24 | Unsettled Resentment  | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.258 (0.037)    | 0 (0.000) |    16.95 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|           10 |      434 | 2025-02-15 | Loveset               | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |     5.65 | 957, Hack1ng, LaiKeXu, Yancher, zero    |
|            9 |      440 | 2025-02-15 | Team XDM              | L   | 1.000      | -            | -                | -                | -         |   -22.14 | 957, Hack1ng, LaiKeXu, Yancher, zero    |
|            8 |      444 | 2025-02-14 | Secret (Chinese team) | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.38 | 957, Hack1ng, LaiKeXu, Yancher, zero    |
|            7 |      452 | 2025-02-14 | Steel Helmet          | L   | 1.000      | -            | -                | -                | -         |   -22.92 | 957, Hack1ng, LaiKeXu, Yancher, zero    |
|            6 |      880 | 2025-02-05 | Five Handsome Guys    | L   | 1.000      | -            | -                | -                | -         |   -18.02 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|            5 |     1329 | 2024-12-27 | FengDa Gaming         | L   | 0.768      | -            | -                | -                | -         |   -13.22 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|            4 |     1434 | 2024-12-22 | Magic Cape            | L   | 0.729      | -            | -                | -                | -         |   -14.30 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|            3 |     1534 | 2024-12-19 | Dolphins Esports      | W   | 0.715      | 0.143        | 0.015 (0.002)    | 0.000 (0.000)    | 1 (0.715) |     5.36 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|            2 |     5635 | 2024-10-05 | Magic Cape            | L   | 0.209      | -            | -                | -                | -         |    -4.22 | 957, Hack1ng, LaiKeXu, LIngGod, yancher |
|            1 |     5697 | 2024-10-04 | StudFarm              | L   | 0.202      | -            | -                | -                | -         |    -4.71 | 957, Hack1ng, LaiKeXu, LIngGod, yancher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,139.28)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.769 | $685.04        | $526.82         |
| 2024-12-19 |      0.715 | $27,410.77     | $19,606.31      |
| 2024-10-06 |      0.216 | $28.50         | $6.15           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
