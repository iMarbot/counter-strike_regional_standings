### Roster Details<br />
Team Name: TopTab Club<br />
Roster: ADntZ, datet, keembo, maQuein, observerward<br />
Global Rank: [522](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [325]( ../standings_europe.md)<br />
<br />
Final Rank Value:  494.8<br />
<br />
Final Rank Value (494.8) = Starting Rank Value (492.1) + Head To Head Adjustments (2.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.183[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.046<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 492.1
- 400 + ( ( 0.046 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 492.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1434 | 2024-12-21 | Avtostopom Po Galaktike | L   | 0.734      | -            | -                | -                | -         |    -7.66 | ADntZ, datet, keembo, maQuein, observerward  |
|            5 |     1678 | 2024-12-14 | Hesta                   | L   | 0.687      | -            | -                | -                | -         |    -4.83 | ADntZ, feetje, keembo, maQuein, observerward |
|            4 |     1685 | 2024-12-14 | RUSTEC                  | W   | 0.687      | 0.250        | 0.002 (0.000)    | 0.100 (0.017)    | 0 (0.000) |    15.03 | ADntZ, feetje, keembo, maQuein, observerward |
|            3 |     7280 | 2024-09-09 | GardenGarage            | L   | 0.047      | -            | -                | -                | -         |    -0.28 | ADntZ, keembo, maQuein, observerward, rezn9  |
|            2 |     7413 | 2024-09-07 | Playfire                | W   | 0.033      | 0.333        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.56 | ADntZ, keembo, maQuein, observerward, rezn9  |
|            1 |     7734 | 2024-09-03 | Chroma                  | L   | 0.006      | -            | -                | -                | -         |    -0.05 | ADntZ, keembo, maQuein, observerward, rezn9  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
