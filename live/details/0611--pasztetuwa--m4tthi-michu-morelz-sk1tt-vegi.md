### Roster Details<br />
Team Name: Pasztetuwa<br />
Roster: m4tthi, MICHU, morelz, sk1tt, Vegi<br />
Global Rank: [611](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [371]( ../standings_europe.md)<br />
<br />
Final Rank Value:  396.4<br />
<br />
Final Rank Value (396.4) = Starting Rank Value (400.0) + Head To Head Adjustments (-3.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     5270 | 2024-10-11 | GardenGarage          | L   | 0.251      | -            | -                | -                | -         |    -1.01 | m4tthi, MICHU, morelz, sk1tt, Vegi       |
|            5 |     5289 | 2024-10-10 | GardenGarage          | L   | 0.245      | -            | -                | -                | -         |    -0.99 | m4tthi, MICHU, morelz, sk1tt, Vegi       |
|            4 |     5293 | 2024-10-10 | Ex-ENTERPRISE esports | L   | 0.245      | -            | -                | -                | -         |    -1.07 | m4tthi, MICHU, morelz, sk1tt, Vegi       |
|            3 |     5907 | 2024-09-30 | WladcaPiekiel         | L   | 0.179      | -            | -                | -                | -         |    -2.83 | m4tthi, MICHU, morelz, sk1tt, xKacpersky |
|            2 |     6042 | 2024-09-28 | Gleba                 | W   | 0.165      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.59 | m4tthi, MICHU, morelz, sk1tt, xKacpersky |
|            1 |     6982 | 2024-09-14 | GardenGarage          | L   | 0.072      | -            | -                | -                | -         |    -0.28 | dan1, m4tthi, morelz, oskarish, Vegi     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
