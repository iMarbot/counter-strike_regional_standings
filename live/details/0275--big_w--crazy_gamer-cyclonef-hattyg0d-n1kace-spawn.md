### Roster Details<br />
Team Name: Big W<br />
Roster: Crazy_Gamer, CycloneF, hattyg0d, N1kace, SpawN<br />
Global Rank: [275](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [38]( ../standings_asia.md)<br />
<br />
Final Rank Value:  666.3<br />
<br />
Final Rank Value (666.3) = Starting Rank Value (686.5) + Head To Head Adjustments (-20.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.208[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 686.5
- 400 + ( ( 0.143 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 686.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |       24 | 2025-02-28 | Victores Sumus   | L   | 1.000      | -            | -                | -                | -         |   -16.27 | Crazy_Gamer, CycloneF, hattyg0d, N1kace, SpawN |
|            7 |       35 | 2025-02-26 | Flashback Gaming | L   | 1.000      | -            | -                | -                | -         |   -12.17 | Crazy_Gamer, CycloneF, hattyg0d, N1kace, SpawN |
|            6 |     1736 | 2024-12-14 | Gods Reign       | L   | 0.676      | -            | -                | -                | -         |    -6.25 | Crazy_Gamer, CycloneF, hattygOD, N1kace, SpawN |
|            5 |     1745 | 2024-12-13 | St4rboys         | W   | 0.675      | 0.262        | 0.002 (0.000)    | 0.053 (0.009)    | 0 (0.000) |     9.52 | Crazy_Gamer, CycloneF, hattygOD, N1kace, SpawN |
|            4 |     3306 | 2024-11-16 | Flashback Gaming | L   | 0.495      | -            | -                | -                | -         |    -5.61 | Crazy_Gamer, CycloneF, hattygOD, N1kace, SpawN |
|            3 |     3361 | 2024-11-16 | Gods Reign       | W   | 0.489      | 0.143        | 0.018 (0.001)    | 0.407 (0.028)    | 1 (0.489) |    11.37 | Crazy_Gamer, CycloneF, hattygOD, N1kace, SpawN |
|            2 |     4501 | 2024-10-27 | Gods Reign       | L   | 0.356      | -            | -                | -                | -         |    -2.72 | clouda, Crazy_Gamer, CycloneF, EmbeR, SpawN    |
|            1 |     4503 | 2024-10-26 | ROG Academy      | W   | 0.355      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.86 | clouda, Crazy_Gamer, CycloneF, EmbeR, SpawN    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,674.49)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-01 |      1.000 | $572.64        | $572.64         |
| 2024-12-14 |      0.676 | $500.00        | $337.89         |
| 2024-11-16 |      0.495 | $1,183.74      | $586.14         |
| 2024-10-27 |      0.356 | $500.00        | $177.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
