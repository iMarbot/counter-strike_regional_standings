### Roster Details<br />
Team Name: Southern5<br />
Roster: Consp1racy, Dork, rMp, tjom, Trogie<br />
Global Rank: [428](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [70]( ../standings_asia.md)<br />
<br />
Final Rank Value:  578.5<br />
<br />
Final Rank Value (578.5) = Starting Rank Value (585.4) + Head To Head Adjustments (-6.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.214[<sup>1</sup>](#table2)
- Bounty Collected: 0.157[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.093<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 585.4
- 400 + ( ( 0.093 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 585.4


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
|            5 |     1931 | 2024-12-10 | Blou Bulle      | L   | 0.652      | -            | -                | -                | -         |    -9.81 | Consp1racy, Dork, rMp, tjom, Trogie     |
|            4 |     2224 | 2024-12-04 | Kipi            | W   | 0.612      | 0.250        | 0.000 (0.000)    | 0.027 (0.004)    | 0 (0.000) |     7.57 | Consp1racy, Dork, rMp, tjom, Trogie     |
|            3 |     2345 | 2024-12-02 | Kitsune Esports | L   | 0.598      | -            | -                | -                | -         |    -9.10 | Consp1racy, Dork, rMp, tjom, Trogie     |
|            2 |     2672 | 2024-11-27 | Realms Esports  | W   | 0.565      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.61 | Consp1racy, Dork, rMp, tjom, Trogie     |
|            1 |     7585 | 2024-09-05 | Kitsune Esports | L   | 0.012      | -            | -                | -                | -         |    -0.17 | Consp1racy, Dork, rMp, rol3xxxx, Trogie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($68.51)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.685 | $100.00        | $68.51          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
