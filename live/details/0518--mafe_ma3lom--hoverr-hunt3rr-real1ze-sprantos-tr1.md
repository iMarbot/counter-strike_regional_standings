### Roster Details<br />
Team Name: MAFE MA3LOM<br />
Roster: hoveRR, HunT3Rr, REAL1ZE, sprantos, tr1<br />
Global Rank: [518](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [82]( ../standings_asia.md)<br />
<br />
Final Rank Value:  496.6<br />
<br />
Final Rank Value (496.6) = Starting Rank Value (508.6) + Head To Head Adjustments (-12.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.161[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 508.6
- 400 + ( ( 0.054 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 508.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     2876 | 2024-11-23 | Onyx Ravens     | L   | 0.538      | -            | -                | -                | -         |    -4.75 | hoveRR, HunT3Rr, REAL1ZE, sprantos, tr1 |
|            6 |     2972 | 2024-11-22 | Al-Ittihad      | L   | 0.531      | -            | -                | -                | -         |    -4.37 | hoveRR, HunT3Rr, REAL1ZE, sprantos, tr1 |
|            5 |     3394 | 2024-11-15 | GTZ.ESPORTS     | L   | 0.485      | -            | -                | -                | -         |    -0.40 | BOROS, HuNt3R, REAL1ZE, sprantos, tr1   |
|            4 |     3405 | 2024-11-15 | Team Chile      | L   | 0.484      | -            | -                | -                | -         |    -7.13 | BOROS, HuNt3R, REAL1ZE, sprantos, tr1   |
|            3 |     3468 | 2024-11-14 | ALTERNATE aTTaX | L   | 0.477      | -            | -                | -                | -         |    -1.50 | BOROS, HuNt3R, REAL1ZE, sprantos, tr1   |
|            2 |     3474 | 2024-11-14 | Team Hungary    | L   | 0.477      | -            | -                | -                | -         |    -2.69 | BOROS, HuNt3R, REAL1ZE, sprantos, tr1   |
|            1 |     3481 | 2024-11-14 | Team Kosovo     | W   | 0.477      | 0.617        | 0.000 (0.000)    | 0.004 (0.001)    | 1 (0.477) |     8.81 | BOROS, HuNt3R, REAL1ZE, sprantos, tr1   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
