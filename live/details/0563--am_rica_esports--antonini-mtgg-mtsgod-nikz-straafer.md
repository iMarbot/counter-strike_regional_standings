### Roster Details<br />
Team Name: América eSports<br />
Roster: antonini, MTGG, mtsGOD, nikz, Straafer<br />
Global Rank: [563](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [130]( ../standings_americas.md)<br />
<br />
Final Rank Value:  469.2<br />
<br />
Final Rank Value (469.2) = Starting Rank Value (472.1) + Head To Head Adjustments (-2.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.144[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.036<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 472.1
- 400 + ( ( 0.036 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 472.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     5394 | 2024-10-08 | INTERDIT                | L   | 0.241      | -            | -                | -                | -         |    -2.38 | antonini, MTGG, mtsGOD, nikz, Straafer |
|            6 |     5559 | 2024-10-05 | Nitro.GG                | L   | 0.221      | -            | -                | -                | -         |    -1.67 | antonini, MTGG, mtsGOD, nikz, Straafer |
|            5 |     5572 | 2024-10-05 | ATIRA FOFO              | W   | 0.220      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.78 | antonini, MTGG, mtsGOD, nikz, Straafer |
|            4 |     7161 | 2024-09-11 | Yawara E-Sports         | L   | 0.061      | -            | -                | -                | -         |    -0.45 | Flip, MTGG, mtsGOD, nikz, Straafer     |
|            3 |     7386 | 2024-09-07 | AMIGOS (Brazilian team) | L   | 0.034      | -            | -                | -                | -         |    -0.51 | MTGG, mtsGOD, nikz, Straafer, Thuister |
|            2 |     7389 | 2024-09-07 | Nova holanda            | L   | 0.033      | -            | -                | -                | -         |    -0.56 | MTGG, mtsGOD, nikz, Straafer, Thuister |
|            1 |     7703 | 2024-09-03 | VELOX Argentina         | L   | 0.007      | -            | -                | -                | -         |    -0.08 | MTGG, mtsGOD, nikz, Straafer, Thuister |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.40)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-03 |      0.007 | $53.11         | $0.40           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
