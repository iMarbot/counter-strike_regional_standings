### Roster Details<br />
Team Name: Mix52<br />
Roster: dosikzz, dukefissura, mo0N, OxygeN, rinn<br />
Global Rank: [154](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [113]( ../standings_europe.md)<br />
<br />
Final Rank Value:  758.8<br />
<br />
Final Rank Value (758.8) = Starting Rank Value (749.8) + Head To Head Adjustments (9.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.191[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.232[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 749.8
- 400 + ( ( 0.175 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 749.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     1729 | 2024-12-14 | Team Novaq             | L   | 0.676      | -            | -                | -                | -         |    -2.81 | dosikzz, dukefissura, mo0N, OxygeN, rinn     |
|            6 |     1740 | 2024-12-13 | ALLINNERS              | W   | 0.675      | 0.333        | 0.002 (0.001)    | 0.149 (0.033)    | 1 (0.675) |     9.98 | dosikzz, dukefissura, mo0N, OxygeN, rinn     |
|            5 |     1802 | 2024-12-13 | GamePoint (Uzbek team) | W   | 0.671      | 0.333        | 0.000 (0.000)    | 0.038 (0.009)    | 1 (0.671) |     6.96 | dosikzz, dukefissura, mo0N, OxygeN, rinn     |
|            4 |     1808 | 2024-12-13 | Team Novaq             | L   | 0.671      | -            | -                | -                | -         |    -2.45 | dosikzz, dukefissura, mo0N, OxygeN, rinn     |
|            3 |     2045 | 2024-12-07 | GamePoint (Uzbek team) | W   | 0.635      | 0.143        | 0.000 (0.000)    | 0.038 (0.003)    | 1 (0.635) |     6.83 | dosikzz, dukefissura, mo0N, OxygeN, rinn     |
|            2 |     2416 | 2024-12-01 | AK BARS                | L   | 0.592      | -            | -                | -                | -         |    -7.38 | dosikzz, dukefissura, exebatya, rinn, smiley |
|            1 |     2438 | 2024-12-01 | Team Novaq             | L   | 0.591      | -            | -                | -                | -         |    -2.06 | dosikzz, dukefissura, exebatya, rinn, smiley |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($683.19)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.683 | $1,000.00      | $683.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
