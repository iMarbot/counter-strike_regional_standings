### Roster Details<br />
Team Name: Team Czech Republic<br />
Roster: Darber, NEOFRAG, olik, pandi7o, PerdY<br />
Global Rank: [171](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [126]( ../standings_europe.md)<br />
<br />
Final Rank Value:  736.8<br />
<br />
Final Rank Value (736.8) = Starting Rank Value (726.3) + Head To Head Adjustments (10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.216[<sup>1</sup>](#table2)
- Bounty Collected: 0.245[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.169[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 726.3
- 400 + ( ( 0.163 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 726.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     3398 | 2024-11-15 | The Huns Esports    | W   | 0.492      | 0.617        | 0.025 (0.008)    | 0.557 (0.169)    | 1 (0.492) |    11.73 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            8 |     3406 | 2024-11-15 | Dusty Roots         | L   | 0.491      | -            | -                | -                | -         |    -7.41 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            7 |     3416 | 2024-11-14 | Partizan Esports    | L   | 0.488      | -            | -                | -                | -         |    -1.97 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            6 |     3489 | 2024-11-13 | SINNERS Academy     | W   | 0.480      | 0.617        | 0.001 (0.000)    | 0.102 (0.030)    | 1 (0.480) |     7.40 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            5 |     3499 | 2024-11-13 | Kitsune Esports     | W   | 0.480      | 0.617        | 0.001 (0.000)    | 0.098 (0.029)    | 1 (0.480) |     5.23 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            4 |     4993 | 2024-10-16 | Devils.one          | W   | 0.293      | 0.278        | 0.001 (0.000)    | 0.073 (0.006)    | 0 (0.000) |     3.92 | fazery, NEOFRAG, olik, pandi7o, woozzzi |
|            3 |     5073 | 2024-10-15 | 777 Esports         | L   | 0.285      | -            | -                | -                | -         |    -5.25 | fazery, NEOFRAG, olik, pandi7o, woozzzi |
|            2 |     5265 | 2024-10-11 | Sampi NEXT          | W   | 0.259      | 0.278        | 0.000 (0.000)    | 0.024 (0.002)    | 0 (0.000) |     1.83 | fazery, NEOFRAG, olik, pandi7o, woozzzi |
|            1 |     5348 | 2024-10-09 | ALTERNATE aTTaX Evo | L   | 0.245      | -            | -                | -                | -         |    -4.97 | fazery, NEOFRAG, olik, pandi7o, woozzzi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($78.19)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.313 | $250.00        | $78.19          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
