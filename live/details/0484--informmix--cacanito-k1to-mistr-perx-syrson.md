### Roster Details<br />
Team Name: Informmix<br />
Roster: CacaNito, k1to, MistR, PerX, syrsoN<br />
Global Rank: [484](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [300]( ../standings_europe.md)<br />
<br />
Final Rank Value:  529.1<br />
<br />
Final Rank Value (529.1) = Starting Rank Value (510.6) + Head To Head Adjustments (18.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 510.6
- 400 + ( ( 0.055 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 510.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |      202 | 2025-02-21 | BASEMENT BOYS        | L   | 1.000      | -            | -                | -                | -         |   -19.36 | CacaNito, k1to, MistR, PerX, syrsoN   |
|            4 |      208 | 2025-02-21 | POLET                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    15.71 | CacaNito, k1to, MistR, PerX, syrsoN   |
|            3 |      244 | 2025-02-20 | Inner Circle Esports | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.187 (0.027)    | 0 (0.000) |    15.23 | CacaNito, k1to, MistR, PerX, syrsoN   |
|            2 |      962 | 2025-02-04 | Ex-Illuminar Gaming  | L   | 1.000      | -            | -                | -                | -         |   -20.12 | CacaNito, MistR, PerX, syrsoN, tiziaN |
|            1 |      990 | 2025-02-04 | Rhyno Esports        | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.447 (0.064)    | 0 (0.000) |    27.00 | CacaNito, MistR, PerX, syrsoN, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
