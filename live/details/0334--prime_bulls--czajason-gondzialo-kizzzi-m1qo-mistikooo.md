### Roster Details<br />
Team Name: Prime Bulls<br />
Roster: Czajason, Gondzialo, Kizzzi, m1qo, Mistikooo<br />
Global Rank: [334](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [218]( ../standings_europe.md)<br />
<br />
Final Rank Value:  631.7<br />
<br />
Final Rank Value (631.7) = Starting Rank Value (633.5) + Head To Head Adjustments (-1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.228[<sup>1</sup>](#table2)
- Bounty Collected: 0.158[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.081[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 633.5
- 400 + ( ( 0.117 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 633.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1620 | 2024-12-15 | GardenGarage     | L   | 0.693      | -            | -                | -                | -         |    -7.88 | Czajason, Gondzialo, Kizzzi, m1qo, Mistikooo |
|            4 |     1634 | 2024-12-15 | LODIS Academy    | W   | 0.692      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.692) |     4.54 | Czajason, Gondzialo, Kizzzi, m1qo, Mistikooo |
|            3 |     5422 | 2024-10-08 | Mission Possible | L   | 0.239      | -            | -                | -                | -         |    -4.79 | Czajason, Gondzialo, Kizzzi, m1qo, Mistikooo |
|            2 |     5454 | 2024-10-07 | GardenGarage     | W   | 0.234      | 0.143        | 0.001 (0.000)    | 0.413 (0.014)    | 0 (0.000) |     4.81 | Czajason, Gondzialo, Kizzzi, m1qo, Mistikooo |
|            1 |     5456 | 2024-10-07 | Pasztetuwa       | W   | 0.233      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.56 | Czajason, Gondzialo, Kizzzi, m1qo, Mistikooo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($136.51)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.693 | $197.01        | $136.51         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
