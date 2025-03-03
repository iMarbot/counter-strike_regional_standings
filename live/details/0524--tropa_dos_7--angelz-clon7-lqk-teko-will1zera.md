### Roster Details<br />
Team Name: TROPA DOS 7<br />
Roster: angelz, CloN7, Lqk, TEKO, will1ZERA<br />
Global Rank: [524](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [118]( ../standings_americas.md)<br />
<br />
Final Rank Value:  491.3<br />
<br />
Final Rank Value (491.3) = Starting Rank Value (488.7) + Head To Head Adjustments (2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.177[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.044<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 488.7
- 400 + ( ( 0.044 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 488.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     6678 | 2024-09-19 | X7 Team              | W   | 0.106      | 0.250        | 0.000 (0.000)    | 0.054 (0.001)    | 0 (0.000) |     2.31 | angelz, CloN7, Lqk, TEKO, will1ZERA |
|            4 |     6688 | 2024-09-19 | Galorys Academy      | L   | 0.106      | -            | -                | -                | -         |    -0.99 | angelz, CloN7, Lqk, TEKO, will1ZERA |
|            3 |     7125 | 2024-09-12 | 9z Academy           | W   | 0.060      | 0.250        | 0.001 (0.000)    | 0.384 (0.006)    | 0 (0.000) |     1.38 | angelz, CloN7, Lqk, TEKO, will1ZERA |
|            2 |     7129 | 2024-09-12 | Floripa Stars        | L   | 0.059      | -            | -                | -                | -         |    -0.53 | angelz, CloN7, Lqk, TEKO, will1ZERA |
|            1 |     7564 | 2024-09-05 | FURIA Esports Female | W   | 0.013      | 0.250        | 0.064 (0.000)    | 0.218 (0.001)    | 0 (0.000) |     0.38 | angelz, CloN7, Lqk, TEKO, will1ZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
