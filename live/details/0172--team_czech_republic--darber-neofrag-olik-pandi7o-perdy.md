### Roster Details<br />
Team Name: Team Czech Republic<br />
Roster: Darber, NEOFRAG, olik, pandi7o, PerdY<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [126]( ../standings_europe.md)<br />
<br />
Final Rank Value:  735.5<br />
<br />
Final Rank Value (735.5) = Starting Rank Value (725.0) + Head To Head Adjustments (10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.216[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.167[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 725.0
- 400 + ( ( 0.162 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 725.0


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
|            9 |     3410 | 2024-11-15 | The Huns Esports    | W   | 0.484      | 0.617        | 0.025 (0.007)    | 0.553 (0.165)    | 1 (0.484) |    11.53 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            8 |     3418 | 2024-11-15 | Dusty Roots         | L   | 0.483      | -            | -                | -                | -         |    -7.25 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            7 |     3428 | 2024-11-14 | Partizan Esports    | L   | 0.480      | -            | -                | -                | -         |    -1.94 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            6 |     3501 | 2024-11-13 | SINNERS Academy     | W   | 0.472      | 0.617        | 0.001 (0.000)    | 0.101 (0.029)    | 1 (0.472) |     7.30 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            5 |     3511 | 2024-11-13 | Kitsune Esports     | W   | 0.471      | 0.617        | 0.001 (0.000)    | 0.096 (0.028)    | 1 (0.471) |     5.15 | Darber, NEOFRAG, olik, pandi7o, PerdY   |
|            4 |     5005 | 2024-10-16 | Devils.one          | W   | 0.285      | 0.278        | 0.001 (0.000)    | 0.068 (0.005)    | 0 (0.000) |     3.78 | fazery, NEOFRAG, olik, pandi7o, woozzzi |
|            3 |     5085 | 2024-10-15 | 777 Esports         | L   | 0.277      | -            | -                | -                | -         |    -5.10 | fazery, NEOFRAG, olik, pandi7o, woozzzi |
|            2 |     5277 | 2024-10-11 | Sampi NEXT          | W   | 0.250      | 0.278        | 0.000 (0.000)    | 0.022 (0.002)    | 0 (0.000) |     1.77 | fazery, NEOFRAG, olik, pandi7o, woozzzi |
|            1 |     5360 | 2024-10-09 | ALTERNATE aTTaX Evo | L   | 0.237      | -            | -                | -                | -         |    -4.80 | fazery, NEOFRAG, olik, pandi7o, woozzzi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($76.15)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.305 | $250.00        | $76.15          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
