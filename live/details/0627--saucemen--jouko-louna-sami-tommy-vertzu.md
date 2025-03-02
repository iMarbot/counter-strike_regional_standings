### Roster Details<br />
Team Name: SAUCEMEN<br />
Roster: Jouko, Louna, Sami, Tommy, VertZu<br />
Global Rank: [627](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [384]( ../standings_europe.md)<br />
<br />
Final Rank Value:  367.6<br />
<br />
Final Rank Value (367.6) = Starting Rank Value (400.6) + Head To Head Adjustments (-33.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.6
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      293 | 2025-02-17 | ENCE Academy    | L   | 1.000      | -            | -                | -                | -         |    -2.30 | Jouko, Louna, Sami, Tommy, VertZu |
|           10 |      585 | 2025-02-10 | Ex-UHKA eSports | L   | 1.000      | -            | -                | -                | -         |    -9.31 | Jouko, Louna, Sami, Tommy, VertZu |
|            9 |      841 | 2025-02-06 | JANO Esports    | L   | 1.000      | -            | -                | -                | -         |    -3.11 | Jouko, Louna, Sami, Tommy, VertZu |
|            8 |     1032 | 2025-02-02 | Heimo Esports   | L   | 1.000      | -            | -                | -                | -         |    -3.60 | Jouko, Louna, Sami, Tommy, VertZu |
|            7 |     1098 | 2025-01-30 | FCottoNd        | L   | 0.999      | -            | -                | -                | -         |   -13.94 | Jouko, Louna, Sami, Tommy, VertZu |
|            6 |     1120 | 2025-01-27 | Smuuttikusilkki | L   | 0.980      | -            | -                | -                | -         |   -11.46 | Jouko, Louna, Sami, Tommy, VertZu |
|            5 |     1135 | 2025-01-25 | HAVU            | L   | 0.965      | -            | -                | -                | -         |    -5.90 | Jouko, Louna, Sami, Tommy, VertZu |
|            4 |     1150 | 2025-01-19 | Retired5        | W   | 0.926      | 0.143        | 0.000 (0.000)    | 0.086 (0.011)    | 0 (0.000) |    14.79 | Jouko, Louna, Sami, Tommy, VertZu |
|            3 |     1153 | 2025-01-19 | Roots Gaming    | W   | 0.926      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    14.53 | Jouko, Louna, Sami, Tommy, VertZu |
|            2 |     2317 | 2024-12-02 | YENKEE Academy  | L   | 0.607      | -            | -                | -                | -         |    -9.31 | Jouko, Louna, Sami, Tommy, VertZu |
|            1 |     2664 | 2024-11-27 | Ex-ESC Gaming   | L   | 0.573      | -            | -                | -                | -         |    -3.35 | Jouko, Louna, Sami, Tommy, VertZu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
