### Roster Details<br />
Team Name: Error404<br />
Roster: cox, MonsterJD, N1ghtey, oxygen, skize<br />
Global Rank: [603](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [367]( ../standings_europe.md)<br />
<br />
Final Rank Value:  402.4<br />
<br />
Final Rank Value (402.4) = Starting Rank Value (400.0) + Head To Head Adjustments (2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     5495 | 2024-10-07 | Dark Cloud Esports | L   | 0.224      | -            | -                | -                | -         |    -0.61 | cox, MonsterJD, N1ghtey, oxygen, skize |
|            4 |     5928 | 2024-09-30 | Sampi NEXT         | W   | 0.178      | 0.143        | 0.000 (0.000)    | 0.022 (0.001)    | 0 (0.000) |     3.56 | cox, MonsterJD, N1ghtey, oxygen, skize |
|            3 |     6379 | 2024-09-24 | GOSTIVAR           | L   | 0.138      | -            | -                | -                | -         |    -1.61 | cox, MonsterJD, N1ghtey, oxygen, skize |
|            2 |     6394 | 2024-09-24 | Devils.one         | L   | 0.138      | -            | -                | -                | -         |    -0.84 | cox, MonsterJD, N1ghtey, oxygen, skize |
|            1 |     6571 | 2024-09-21 | Lombard            | W   | 0.119      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.87 | cox, MonsterJD, N1ghtey, oxygen, skize |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
