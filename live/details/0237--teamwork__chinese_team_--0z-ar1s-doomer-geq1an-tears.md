### Roster Details<br />
Team Name: Teamwork (Chinese team)<br />
Roster: 0z, Ar1s, Doomer, Geq1an, TEARS<br />
Global Rank: [237](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [29]( ../standings_asia.md)<br />
<br />
Final Rank Value:  686.3<br />
<br />
Final Rank Value (686.3) = Starting Rank Value (690.0) + Head To Head Adjustments (-3.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.400[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 690.0
- 400 + ( ( 0.145 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 690.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     1279 | 2024-12-28 | FengDa Gaming      | L   | 0.776      | -            | -                | -                | -         |   -10.74 | 0z, Ar1s, Doomer, Geq1an, TEARS |
|            7 |     1281 | 2024-12-28 | IM-Man Zhou Li     | W   | 0.775      | 0.143        | 0.001 (0.000)    | 0.026 (0.003)    | 0 (0.000) |    10.53 | 0z, Ar1s, Doomer, Geq1an, TEARS |
|            6 |     1344 | 2024-12-27 | Nirvana Esports    | W   | 0.763      | 0.372        | 0.000 (0.000)    | 0.101 (0.029)    | 0 (0.000) |     8.28 | 0z, Ar1s, Doomer, Geq1an, TEARS |
|            5 |     1388 | 2024-12-23 | FengDa Gaming      | L   | 0.737      | -            | -                | -                | -         |   -11.03 | 0z, Ar1s, Doomer, Geq1an, TEARS |
|            4 |     1555 | 2024-12-19 | Nalakuvara Gaming  | W   | 0.710      | 0.372        | 0.000 (0.000)    | 0.085 (0.023)    | 0 (0.000) |     7.09 | 0z, Ar1s, Doomer, Geq1an, TEARS |
|            3 |     1898 | 2024-12-11 | Joker Gaming       | W   | 0.657      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.56 | 0z, Ar1s, Doomer, Geq1an, TEARS |
|            2 |     2696 | 2024-11-26 | Lynn Vision Gaming | L   | 0.561      | -            | -                | -                | -         |    -5.09 | 0z, Ar1s, Doomer, Geq1an, TEARS |
|            1 |     2750 | 2024-11-26 | TYLOO              | L   | 0.556      | -            | -                | -                | -         |    -6.30 | 0z, Ar1s, Doomer, Geq1an, TEARS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,461.10)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-27 |      0.763 | $13,702.00     | $10,461.10      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
