### Roster Details<br />
Team Name: Lotus<br />
Roster: abby, cyclone, gadfly, tokkis, Zazu<br />
Global Rank: [392](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [84]( ../standings_americas.md)<br />
<br />
Final Rank Value:  603.4<br />
<br />
Final Rank Value (603.4) = Starting Rank Value (620.5) + Head To Head Adjustments (-17.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.165[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.110<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 620.5
- 400 + ( ( 0.110 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 620.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1060 | 2025-02-01 | Ghost Gaming       | L   | 1.000      | -            | -                | -                | -         |   -20.53 | abby, cyclone, gadfly, tokkis, Zazu   |
|            9 |     1283 | 2024-12-28 | Team Jayne         | W   | 0.774      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.44 | abby, cyclone, gadfly, tokkis, Zazu   |
|            8 |     1616 | 2024-12-15 | Supernova Comets   | L   | 0.687      | -            | -                | -                | -         |    -6.43 | abby, cyclone, gadfly, tokkis, Zazu   |
|            7 |     1674 | 2024-12-14 | Unjustified Impact | W   | 0.680      | 0.250        | 0.000 (0.000)    | 0.063 (0.011)    | 0 (0.000) |     7.06 | abby, cyclone, gadfly, tokkis, Zazu   |
|            6 |     2402 | 2024-12-01 | Supernova Comets   | L   | 0.593      | -            | -                | -                | -         |    -5.90 | abby, AVA174, milo, tokkis, Zazu      |
|            5 |     2468 | 2024-11-30 | Unjustified Impact | W   | 0.587      | 0.250        | 0.000 (0.000)    | 0.063 (0.009)    | 0 (0.000) |     6.46 | abby, AVA174, milo, tokkis, Zazu      |
|            4 |     3233 | 2024-11-17 | Supernova Comets   | L   | 0.500      | -            | -                | -                | -         |    -5.17 | abby, gadfly, MegaGeese, tokkis, Zazu |
|            3 |     3313 | 2024-11-16 | Equity Gaming      | W   | 0.493      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.44 | abby, gadfly, MegaGeese, tokkis, Zazu |
|            2 |     4039 | 2024-11-03 | Supernova Comets   | L   | 0.407      | -            | -                | -                | -         |    -4.38 | abby, Fawx, gadfly, tokkis, Zazu      |
|            1 |     4109 | 2024-11-02 | JuicY KittY        | W   | 0.400      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.83 | abby, Fawx, gadfly, tokkis, Zazu      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($740.03)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.774 | $250.00        | $193.47         |
| 2024-12-15 |      0.687 | $250.00        | $171.74         |
| 2024-12-01 |      0.593 | $250.00        | $148.23         |
| 2024-11-17 |      0.500 | $250.00        | $124.97         |
| 2024-11-03 |      0.407 | $250.00        | $101.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
