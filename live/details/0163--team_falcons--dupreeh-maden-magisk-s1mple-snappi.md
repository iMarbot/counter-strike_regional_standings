### Roster Details<br />
Team Name: Team Falcons<br />
Roster: dupreeh, maden, Magisk, s1mple, Snappi<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [120]( ../standings_europe.md)<br />
<br />
Final Rank Value:  743.6<br />
<br />
Final Rank Value (743.6) = Starting Rank Value (730.8) + Head To Head Adjustments (12.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 730.8
- 400 + ( ( 0.165 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 730.8


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
|           14 |     3180 | 2024-11-19 | GamerLegion   | L   | 0.509      | -            | -                | -                | -         |    -0.16 | dupreeh, maden, Magisk, s1mple, Snappi   |
|           13 |     3229 | 2024-11-17 | SAW           | L   | 0.502      | -            | -                | -                | -         |    -0.60 | dupreeh, maden, Magisk, s1mple, Snappi   |
|           12 |     3263 | 2024-11-17 | FaZe Clan     | L   | 0.497      | -            | -                | -                | -         |    -0.02 | dupreeh, maden, Magisk, s1mple, Snappi   |
|           11 |     3303 | 2024-11-16 | Dynamo Eclot  | W   | 0.495      | 0.143        | 0.128 (0.009)    | 0.692 (0.049)    | 1 (0.495) |    13.37 | dupreeh, maden, Magisk, s1mple, Snappi   |
|           10 |     4559 | 2024-10-26 | Eternal Fire  | L   | 0.349      | -            | -                | -                | -         |    -0.02 | dupreeh, maden, Magisk, s1mple, Snappi   |
|            9 |     4616 | 2024-10-25 | SAW           | L   | 0.343      | -            | -                | -                | -         |    -0.37 | dupreeh, maden, Magisk, s1mple, Snappi   |
|            8 |     4750 | 2024-10-21 | Virtus.pro    | L   | 0.318      | -            | -                | -                | -         |    -0.06 | dupreeh, maden, Magisk, s1mple, Snappi   |
|            7 |     4767 | 2024-10-21 | 3DMAX         | L   | 0.316      | -            | -                | -                | -         |    -0.09 | dupreeh, maden, Magisk, s1mple, Snappi   |
|            6 |     6239 | 2024-09-26 | FaZe Clan     | L   | 0.149      | -            | -                | -                | -         |    -0.01 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            5 |     6332 | 2024-09-25 | Natus Vincere | L   | 0.143      | -            | -                | -                | -         |    -0.02 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            4 |     7041 | 2024-09-14 | RED Canids    | L   | 0.070      | -            | -                | -                | -         |    -0.75 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            3 |     7112 | 2024-09-13 | Virtus.pro    | L   | 0.063      | -            | -                | -                | -         |    -0.01 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            2 |     7158 | 2024-09-12 | ATOX Esports  | W   | 0.056      | 0.889        | 0.064 (0.003)    | 0.601 (0.030)    | 1 (0.056) |     1.58 | dupreeh, maden, Magisk, Snappi, SunPayus |
|            1 |     7214 | 2024-09-11 | FURIA         | L   | 0.050      | -            | -                | -                | -         |    -0.03 | dupreeh, maden, Magisk, Snappi, SunPayus |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,289.12)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.358 | $2,000.00      | $716.76         |
| 2024-09-29 |      0.170 | $10,000.00     | $1,704.17       |
| 2024-09-22 |      0.124 | $7,000.00      | $868.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
