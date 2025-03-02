### Roster Details<br />
Team Name: ENRAGE<br />
Roster: blocker, hazza, miteww, niki1, tissue<br />
Global Rank: [305](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [204]( ../standings_europe.md)<br />
<br />
Final Rank Value:  645.5<br />
<br />
Final Rank Value (645.5) = Starting Rank Value (636.0) + Head To Head Adjustments (9.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.228[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 636.0
- 400 + ( ( 0.118 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 636.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      949 | 2025-02-04 | TEAM NEXT LEVEL     | L   | 1.000      | -            | -                | -                | -         |   -12.90 | blocker, hazza, miteww, niki1, tissue   |
|            5 |      957 | 2025-02-04 | FAVBET Team         | W   | 1.000      | 0.143        | 0.032 (0.005)    | 0.814 (0.116)    | 0 (0.000) |    24.93 | blocker, hazza, miteww, niki1, tissue   |
|            4 |      974 | 2025-02-04 | Flame Sharks        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.170 (0.024)    | 0 (0.000) |    15.62 | blocker, hazza, miteww, niki1, tissue   |
|            3 |     1869 | 2024-12-11 | Wu-Tang Clan        | L   | 0.667      | -            | -                | -                | -         |    -9.59 | blocker, hazza, miteww, niki1, tissue   |
|            2 |     2213 | 2024-12-04 | AMKAL ESPORTS       | L   | 0.620      | -            | -                | -                | -         |    -5.53 | blocker, hazza, miteww, niki1, tissue   |
|            1 |     5577 | 2024-10-05 | Dragon Esports Club | L   | 0.220      | -            | -                | -                | -         |    -2.96 | AwaykeN, blocker, niki1, Skrimo, tissue |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($138.76)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.694 | $200.00        | $138.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
