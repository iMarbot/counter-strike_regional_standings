### Roster Details<br />
Team Name: KILLBOX<br />
Roster: falqen, Gibsand, hampz, mille, Timothybtw<br />
Global Rank: [569](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [348]( ../standings_europe.md)<br />
<br />
Final Rank Value:  456.5<br />
<br />
Final Rank Value (456.5) = Starting Rank Value (469.7) + Head To Head Adjustments (-13.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.139[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.035<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 469.7
- 400 + ( ( 0.035 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 469.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     4155 | 2024-11-02 | Preasy Esport        | L   | 0.397      | -            | -                | -                | -         |    -1.74 | falqen, Gibsand, hampz, mille, Timothybtw |
|            8 |     4629 | 2024-10-24 | Venom (Swedish team) | L   | 0.338      | -            | -                | -                | -         |    -4.72 | falqen, Gibsand, mille, nOLS, PornyBig    |
|            7 |     5078 | 2024-10-15 | NIP Svea             | L   | 0.278      | -            | -                | -                | -         |    -5.15 | falqen, Gibsand, mille, nOLS, PornyBig    |
|            6 |     5264 | 2024-10-11 | Lagby Gooners        | W   | 0.251      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.23 | falqen, Gibsand, mille, nOLS, PornyBig    |
|            5 |     5666 | 2024-10-04 | Lemondogs            | L   | 0.205      | -            | -                | -                | -         |    -3.82 | falqen, Gibsand, mille, nOLS, PornyBig    |
|            4 |     6304 | 2024-09-25 | Lilmix               | L   | 0.145      | -            | -                | -                | -         |    -1.97 | falqen, Gibsand, mille, nOLS, PornyBig    |
|            3 |     6926 | 2024-09-15 | Pikejagarna          | L   | 0.078      | -            | -                | -                | -         |    -1.48 | falqen, Gibsand, mille, nOLS, PornyBig    |
|            2 |     6988 | 2024-09-14 | Venom (Swedish team) | W   | 0.072      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.91 | falqen, Gibsand, mille, nOLS, PornyBig    |
|            1 |     6990 | 2024-09-14 | Showmakerz           | W   | 0.072      | 0.143        | 0.001 (0.000)    | 0.034 (0.000)    | 0 (0.000) |     1.53 | falqen, Gibsand, mille, nOLS, PornyBig    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
