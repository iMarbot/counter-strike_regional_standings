### Roster Details<br />
Team Name: Northwest<br />
Roster: aspas, keyglock, ORIGLONIKO, sergelen19k, starDUST<br />
Global Rank: [618](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [101]( ../standings_asia.md)<br />
<br />
Final Rank Value:  392.9<br />
<br />
Final Rank Value (392.9) = Starting Rank Value (400.2) + Head To Head Adjustments (-7.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.2
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     2377 | 2024-12-02 | Eruption                | L   | 0.596      | -            | -                | -                | -         |    -1.09 | aspas, keyglock, ORIGLONIKO, sergelen19k, starDUST |
|            4 |     2382 | 2024-12-01 | Nomads (Mongolian team) | L   | 0.595      | -            | -                | -                | -         |    -6.04 | aspas, keyglock, ORIGLONIKO, sergelen19k, starDUST |
|            3 |     3279 | 2024-11-17 | Harizma                 | L   | 0.496      | -            | -                | -                | -         |    -2.23 | 290, aspas, keyglock, ORIGLONIKO, starDUST         |
|            2 |     3292 | 2024-11-17 | Tsegtaslal              | W   | 0.496      | 0.143        | 0.000 (0.000)    | 0.047 (0.003)    | 0 (0.000) |     7.69 | 290, aspas, keyglock, ORIGLONIKO, starDUST         |
|            1 |     3297 | 2024-11-16 | Nomads (Mongolian team) | L   | 0.496      | -            | -                | -                | -         |    -5.58 | 290, aspas, keyglock, ORIGLONIKO, starDUST         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
