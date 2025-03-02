### Roster Details<br />
Team Name: Mixzada<br />
Roster: Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS<br />
Global Rank: [397](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [250]( ../standings_europe.md)<br />
<br />
Final Rank Value:  598.5<br />
<br />
Final Rank Value (598.5) = Starting Rank Value (598.0) + Head To Head Adjustments (0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.228[<sup>1</sup>](#table2)
- Bounty Collected: 0.167[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.099<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 598.0
- 400 + ( ( 0.099 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 598.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3727 | 2024-11-09 | GTZ.ESPORTS      | L   | 0.452      | -            | -                | -                | -         |    -0.59 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            6 |     4554 | 2024-10-26 | GOOFYBOYZ        | L   | 0.357      | -            | -                | -                | -         |    -3.38 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            5 |     5200 | 2024-10-12 | Rhyno Youngsters | L   | 0.266      | -            | -                | -                | -         |    -2.48 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            4 |     5241 | 2024-10-12 | Turritos         | W   | 0.264      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     2.02 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            3 |     5257 | 2024-10-11 | GOOFYBOYZ        | W   | 0.259      | 0.143        | 0.003 (0.000)    | 0.183 (0.007)    | 0 (0.000) |     5.77 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            2 |     6063 | 2024-09-28 | Rhyno Esports    | L   | 0.171      | -            | -                | -                | -         |    -2.11 | Fenix, Ftu, GuimaBrother, KIMBARREiROS, Virgolino |
|            1 |     6110 | 2024-09-27 | TGD Pro          | W   | 0.167      | 0.143        | 0.000 (0.000)    | 0.047 (0.001)    | 0 (0.000) |     1.29 | Fenix, Ftu, GuimaBrother, KIMBARREiROS, Virgolino |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($141.10)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-22 |      0.539 | $261.78        | $141.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
