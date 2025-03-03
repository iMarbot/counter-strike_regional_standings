### Roster Details<br />
Team Name: Turritos<br />
Roster: arki, Carta, JaaviiiZen, Losdey, Sil3nT<br />
Global Rank: [616](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [375]( ../standings_europe.md)<br />
<br />
Final Rank Value:  393.8<br />
<br />
Final Rank Value (393.8) = Starting Rank Value (400.0) + Head To Head Adjustments (-6.3)<br />

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


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     4848 | 2024-10-19 | KlAnPeDrAjAs  | L   | 0.305      | -            | -                | -                | -         |    -4.76 | arki, Carta, JaaviiiZen, Losdey, Sil3nT    |
|            6 |     5253 | 2024-10-12 | Mixzada       | L   | 0.256      | -            | -                | -                | -         |    -1.96 | arki, Carta, JaaviiiZen, Losdey, Sil3nT    |
|            5 |     6141 | 2024-09-27 | Impulse GW    | L   | 0.158      | -            | -                | -                | -         |    -0.68 | Carta, DeathZz, JaaviiiZen, Losdey, Sil3nT |
|            4 |     6700 | 2024-09-19 | Rhyno Esports | L   | 0.105      | -            | -                | -                | -         |    -0.60 | Carta, JaaviiiZen, Losdey, Nanitos, Sil3nT |
|            3 |     6753 | 2024-09-18 | TGD Pro       | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.046 (0.001)    | 0 (0.000) |     1.54 | Carta, JaaviiiZen, Losdey, Nanitos, Sil3nT |
|            2 |     6881 | 2024-09-16 | Rhyno Esports | L   | 0.085      | -            | -                | -                | -         |    -0.20 | Carta, JaaviiiZen, Losdey, Nanitos, Sil3nT |
|            1 |     7427 | 2024-09-07 | AL-QATRAO     | W   | 0.025      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.39 | Carta, JaaviiiZen, Losdey, Nanitos, Sil3nT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
