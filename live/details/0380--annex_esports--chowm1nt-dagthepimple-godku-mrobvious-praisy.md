### Roster Details<br />
Team Name: Annex Esports<br />
Roster: Chowm1nt, DagThePimple, godkU, MrObvious, PRAISy<br />
Global Rank: [380](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [238]( ../standings_europe.md)<br />
<br />
Final Rank Value:  608.6<br />
<br />
Final Rank Value (608.6) = Starting Rank Value (632.1) + Head To Head Adjustments (-23.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.206[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.041[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.1
- 400 + ( ( 0.116 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 632.1


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
|           13 |     3656 | 2024-11-10 | ALASKA             | L   | 0.452      | -            | -                | -                | -         |    -1.15 | Chowm1nt, DagThePimple, godkU, MrObvious, PRAISy |
|           12 |     3672 | 2024-11-10 | TYREECESIMPSON     | W   | 0.452      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.38 | Chowm1nt, DagThePimple, godkU, MrObvious, PRAISy |
|           11 |     3834 | 2024-11-07 | ALASKA             | W   | 0.432      | 0.143        | 0.031 (0.002)    | 0.867 (0.054)    | 0 (0.000) |    12.64 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|           10 |     3878 | 2024-11-06 | 8Sins              | L   | 0.426      | -            | -                | -                | -         |    -1.93 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            9 |     3880 | 2024-11-06 | Glitchtech Esports | L   | 0.425      | -            | -                | -                | -         |    -7.83 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            8 |     3934 | 2024-11-05 | TRAXXXMANIA        | L   | 0.419      | -            | -                | -                | -         |    -5.26 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            7 |     3984 | 2024-11-04 | Dreams To Legends  | L   | 0.412      | -            | -                | -                | -         |    -6.55 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            6 |     3992 | 2024-11-04 | The Last Resort    | L   | 0.412      | -            | -                | -                | -         |    -4.82 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            5 |     4366 | 2024-10-29 | ROYALS             | L   | 0.372      | -            | -                | -                | -         |    -4.57 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            4 |     4551 | 2024-10-26 | TRAXXXMANIA        | L   | 0.350      | -            | -                | -                | -         |    -4.89 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            3 |     4570 | 2024-10-26 | Bravefart          | W   | 0.349      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 1 (0.349) |     2.68 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            2 |     4593 | 2024-10-25 | 8Sins              | L   | 0.345      | -            | -                | -                | -         |    -1.81 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |
|            1 |     5057 | 2024-10-15 | Belfast Storm      | L   | 0.278      | -            | -                | -                | -         |    -3.44 | Chowm1nt, DagThePimple, godkU, m0g, MrObvious    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46.34)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.358 | $129.61        | $46.34          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
