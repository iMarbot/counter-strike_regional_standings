### Roster Details<br />
Team Name: JackBoyz<br />
Roster: 7kick, ERSIN, jaxi, regali, taken<br />
Global Rank: [300](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [200]( ../standings_europe.md)<br />
<br />
Final Rank Value:  649.9<br />
<br />
Final Rank Value (649.9) = Starting Rank Value (651.0) + Head To Head Adjustments (-1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.180[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 651.0
- 400 + ( ( 0.125 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 651.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1700 | 2024-12-14 | Aimclub         | L   | 0.678      | -            | -                | -                | -         |    -5.73 | 7kick, ERSIN, jaxi, regali, taken |
|            4 |     2426 | 2024-12-01 | Theboyz         | W   | 0.592      | 0.143        | 0.003 (0.000)    | 0.085 (0.007)    | 0 (0.000) |     9.16 | 7kick, ERSIN, jaxi, regali, taken |
|            3 |     2443 | 2024-12-01 | Perfect Storm   | L   | 0.591      | -            | -                | -                | -         |    -8.99 | 7kick, ERSIN, jaxi, regali, taken |
|            2 |     2517 | 2024-11-30 | Infinite Gaming | W   | 0.585      | 0.143        | 0.000 (0.000)    | 0.059 (0.005)    | 0 (0.000) |     5.69 | 7kick, ERSIN, jaxi, regali, taken |
|            1 |     2535 | 2024-11-30 | Nexus Gaming    | L   | 0.584      | -            | -                | -                | -         |    -1.27 | 7kick, ERSIN, jaxi, regali, taken |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,515.96)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.684 | $3,676.66      | $2,515.96       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
