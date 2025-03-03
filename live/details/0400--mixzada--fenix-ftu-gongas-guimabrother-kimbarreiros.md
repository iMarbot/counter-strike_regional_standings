### Roster Details<br />
Team Name: Mixzada<br />
Roster: Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS<br />
Global Rank: [400](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [249]( ../standings_europe.md)<br />
<br />
Final Rank Value:  598.6<br />
<br />
Final Rank Value (598.6) = Starting Rank Value (598.1) + Head To Head Adjustments (0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.229[<sup>1</sup>](#table2)
- Bounty Collected: 0.167[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.099<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 598.1
- 400 + ( ( 0.099 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 598.1


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
|            7 |     3739 | 2024-11-09 | GTZ.ESPORTS      | L   | 0.444      | -            | -                | -                | -         |    -0.58 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            6 |     4566 | 2024-10-26 | GOOFYBOYZ        | L   | 0.349      | -            | -                | -                | -         |    -3.31 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            5 |     5212 | 2024-10-12 | Rhyno Youngsters | L   | 0.257      | -            | -                | -                | -         |    -2.42 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            4 |     5253 | 2024-10-12 | Turritos         | W   | 0.256      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.96 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            3 |     5269 | 2024-10-11 | GOOFYBOYZ        | W   | 0.251      | 0.143        | 0.003 (0.000)    | 0.179 (0.006)    | 0 (0.000) |     5.58 | Fenix, Ftu, GongaS, GuimaBrother, KIMBARREiROS    |
|            2 |     6075 | 2024-09-28 | Rhyno Esports    | L   | 0.163      | -            | -                | -                | -         |    -2.02 | Fenix, Ftu, GuimaBrother, KIMBARREiROS, Virgolino |
|            1 |     6122 | 2024-09-27 | TGD Pro          | W   | 0.158      | 0.143        | 0.000 (0.000)    | 0.046 (0.001)    | 0 (0.000) |     1.22 | Fenix, Ftu, GuimaBrother, KIMBARREiROS, Virgolino |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($138.96)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-22 |      0.531 | $261.78        | $138.96         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
