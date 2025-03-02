### Roster Details<br />
Team Name: Team Falcons<br />
Roster: dupreeh, maden, Magisk, s1mple, Snappi<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [119]( ../standings_europe.md)<br />
<br />
Final Rank Value:  745.8<br />
<br />
Final Rank Value (745.8) = Starting Rank Value (732.7) + Head To Head Adjustments (13.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.066[<sup>2</sup>](#table1)

The average of these factors is 0.167<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 732.7
- 400 + ( ( 0.167 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 732.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     3168 | 2024-11-19 | GamerLegion   | L   | 0.517      | -            | -                | -                | -         |    -0.17 | dupreeh, maden, Magisk, s1mple, Snappi   |
|           13 |     3217 | 2024-11-17 | SAW           | L   | 0.510      | -            | -                | -                | -         |    -0.62 | dupreeh, maden, Magisk, s1mple, Snappi   |
|           12 |     3251 | 2024-11-17 | FaZe Clan     | L   | 0.505      | -            | -                | -                | -         |    -0.03 | dupreeh, maden, Magisk, s1mple, Snappi   |
|           11 |     3291 | 2024-11-16 | Dynamo Eclot  | W   | 0.503      | 0.143        | 0.127 (0.009)    | 0.703 (0.051)    | 1 (0.503) |    13.58 | dupreeh, maden, Magisk, s1mple, Snappi   |
|           10 |     4547 | 2024-10-26 | Eternal Fire  | L   | 0.358      | -            | -                | -                | -         |    -0.02 | dupreeh, maden, Magisk, s1mple, Snappi   |
|            9 |     4604 | 2024-10-25 | SAW           | L   | 0.351      | -            | -                | -                | -         |    -0.38 | dupreeh, maden, Magisk, s1mple, Snappi   |
|            8 |     4738 | 2024-10-21 | Virtus.pro    | L   | 0.326      | -            | -                | -                | -         |    -0.06 | dupreeh, maden, Magisk, s1mple, Snappi   |
|            7 |     4755 | 2024-10-21 | 3DMAX         | L   | 0.324      | -            | -                | -                | -         |    -0.10 | dupreeh, maden, Magisk, s1mple, Snappi   |
|            6 |     6227 | 2024-09-26 | FaZe Clan     | L   | 0.158      | -            | -                | -                | -         |    -0.01 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            5 |     6320 | 2024-09-25 | Natus Vincere | L   | 0.151      | -            | -                | -                | -         |    -0.02 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            4 |     7029 | 2024-09-14 | RED Canids    | L   | 0.078      | -            | -                | -                | -         |    -0.83 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            3 |     7100 | 2024-09-13 | Virtus.pro    | L   | 0.071      | -            | -                | -                | -         |    -0.01 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            2 |     7146 | 2024-09-12 | ATOX Esports  | W   | 0.065      | 0.889        | 0.064 (0.004)    | 0.604 (0.035)    | 1 (0.065) |     1.81 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            1 |     7202 | 2024-09-11 | FURIA         | L   | 0.058      | -            | -                | -                | -         |    -0.03 | dupreeh, maden, Magisk, Snappi, SunPayus |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,444.81)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.367 | $2,000.00      | $733.15         |
| 2024-09-29 |      0.179 | $10,000.00     | $1,786.11       |
| 2024-09-22 |      0.132 | $7,000.00      | $925.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
