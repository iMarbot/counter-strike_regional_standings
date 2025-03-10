### Roster Details<br />
Team Name: CS2NEWS<br />
Roster: fostar, h4rn, H4SAN4TOR, kwezz, sstiNiX<br />
Global Rank: [469](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [291]( ../standings_europe.md)<br />
<br />
Final Rank Value:  542.4<br />
<br />
Final Rank Value (542.4) = Starting Rank Value (538.1) + Head To Head Adjustments (4.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.069<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 538.1
- 400 + ( ( 0.069 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 538.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1225 | 2025-01-08 | ECSTATIC      | L   | 0.843      | -            | -                | -                | -         |    -3.25 | fostar, h4rn, H4SAN4TOR, kwezz, sstiNiX          |
|            5 |     1237 | 2025-01-04 | Rhyno Esports | L   | 0.816      | -            | -                | -                | -         |    -3.87 | fostar, h4rn, H4SAN4TOR, kwezz, sstiNiX          |
|            4 |     1271 | 2024-12-29 | WOPA Esport   | W   | 0.777      | 0.417        | 0.032 (0.010)    | 0.777 (0.252)    | 0 (0.000) |    20.70 | fostar, h4rn, H4SAN4TOR, kwezz, sstiNiX          |
|            3 |     1335 | 2024-12-27 | KONO.ECF      | L   | 0.765      | -            | -                | -                | -         |   -10.18 | fostar, h4rn, H4SAN4TOR, kwezz, sstiNiX          |
|            2 |     2849 | 2024-11-23 | HOTU          | L   | 0.539      | -            | -                | -                | -         |    -4.37 | fostar, H4SAN4TOR, leri511, lollipop21k, sstiNiX |
|            1 |     2858 | 2024-11-23 | MOLEGAN       | W   | 0.538      | 0.262        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     5.26 | fostar, H4SAN4TOR, leri511, lollipop21k, sstiNiX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
