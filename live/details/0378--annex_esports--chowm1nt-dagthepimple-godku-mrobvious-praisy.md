### Roster Details<br />
Team Name: Annex Esports<br />
Roster: Chowm1nt, DagThePimple, godkU, MrObvious, PRAISy<br />
Global Rank: [378](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [238]( ../standings_europe.md)<br />
<br />
Final Rank Value:  608.4<br />
<br />
Final Rank Value (608.4) = Starting Rank Value (632.4) + Head To Head Adjustments (-24.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.206[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.042[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.4
- 400 + ( ( 0.116 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 632.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     3644 | 2024-11-10 | ALASKA             | L   | 0.460      | -            | -                | -                | -         |    -1.19 | Chowm1nt, DagThePimple, godkU, MrObvious, PRAISy |
|           12 |     3660 | 2024-11-10 | TYREECESIMPSON     | W   | 0.460      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.45 | Chowm1nt, DagThePimple, godkU, MrObvious, PRAISy |
|           11 |     3822 | 2024-11-07 | ALASKA             | W   | 0.441      | 0.143        | 0.030 (0.002)    | 0.875 (0.055)    | 0 (0.000) |    12.87 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|           10 |     3866 | 2024-11-06 | 8Sins              | L   | 0.434      | -            | -                | -                | -         |    -1.97 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            9 |     3868 | 2024-11-06 | Glitchtech Esports | L   | 0.434      | -            | -                | -                | -         |    -7.97 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            8 |     3922 | 2024-11-05 | TRAXXXMANIA        | L   | 0.427      | -            | -                | -                | -         |    -5.34 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            7 |     3972 | 2024-11-04 | Dreams To Legends  | L   | 0.421      | -            | -                | -                | -         |    -6.67 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            6 |     3980 | 2024-11-04 | The Last Resort    | L   | 0.420      | -            | -                | -                | -         |    -4.92 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            5 |     4354 | 2024-10-29 | ROYALS             | L   | 0.381      | -            | -                | -                | -         |    -4.64 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            4 |     4539 | 2024-10-26 | TRAXXXMANIA        | L   | 0.358      | -            | -                | -                | -         |    -4.98 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            3 |     4558 | 2024-10-26 | Bravefart          | W   | 0.357      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 1 (0.357) |     2.74 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            2 |     4581 | 2024-10-25 | 8Sins              | L   | 0.353      | -            | -                | -                | -         |    -1.86 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            1 |     5045 | 2024-10-15 | Belfast Storm      | L   | 0.287      | -            | -                | -                | -         |    -3.54 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($47.41)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.366 | $129.61        | $47.41          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
