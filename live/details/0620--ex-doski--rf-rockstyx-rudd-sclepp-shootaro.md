### Roster Details<br />
Team Name: Ex-DOSKI<br />
Roster: Rf, rockStyX, rudd, sclepp, Shootaro<br />
Global Rank: [620](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [378]( ../standings_europe.md)<br />
<br />
Final Rank Value:  388.5<br />
<br />
Final Rank Value (388.5) = Starting Rank Value (400.1) + Head To Head Adjustments (-11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.1
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     2428 | 2024-12-01 | Team Genesium              | L   | 0.592      | -            | -                | -                | -         |    -3.08 | Rf, rockStyX, rudd, sclepp, Shootaro   |
|            6 |     2717 | 2024-11-26 | FALKE ESPORTS              | L   | 0.559      | -            | -                | -                | -         |    -8.58 | Rf, rockStyX, rudd, sclepp, Shootaro   |
|            5 |     2853 | 2024-11-23 | NEVERMORE (Ukrainian team) | L   | 0.539      | -            | -                | -                | -         |    -2.01 | Rf, rockStyX, rudd, sclepp, Shootaro   |
|            4 |     4027 | 2024-11-04 | XGOD ARENA                 | L   | 0.410      | -            | -                | -                | -         |    -3.29 | Rf, rockStyX, rudd, sclepp, Shootaro   |
|            3 |     4029 | 2024-11-04 | Team M33                   | W   | 0.410      | 0.143        | 0.000 (0.000)    | 0.028 (0.002)    | 0 (0.000) |     6.43 | Rf, rockStyX, rudd, sclepp, Shootaro   |
|            2 |     6584 | 2024-09-21 | Flame Sharks               | L   | 0.118      | -            | -                | -                | -         |    -0.74 | denji, Rf, rockStyX, rudd, sclepp      |
|            1 |     7404 | 2024-09-07 | Ex-UHKA eSports            | L   | 0.025      | -            | -                | -                | -         |    -0.28 | denji, rockStyX, rudd, s1nside, sclepp |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
