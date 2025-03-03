### Roster Details<br />
Team Name: SAUCEMEN<br />
Roster: Jouko, Louna, Sami, Tommy, VertZu<br />
Global Rank: [628](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [383]( ../standings_europe.md)<br />
<br />
Final Rank Value:  367.6<br />
<br />
Final Rank Value (367.6) = Starting Rank Value (400.6) + Head To Head Adjustments (-32.9)<br />

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
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.6


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
|           11 |      305 | 2025-02-17 | ENCE Academy    | L   | 1.000      | -            | -                | -                | -         |    -2.32 | Jouko, Louna, Sami, Tommy, VertZu |
|           10 |      597 | 2025-02-10 | Ex-UHKA eSports | L   | 1.000      | -            | -                | -                | -         |    -9.34 | Jouko, Louna, Sami, Tommy, VertZu |
|            9 |      853 | 2025-02-06 | JANO Esports    | L   | 1.000      | -            | -                | -                | -         |    -3.12 | Jouko, Louna, Sami, Tommy, VertZu |
|            8 |     1044 | 2025-02-02 | Heimo Esports   | L   | 1.000      | -            | -                | -                | -         |    -3.65 | Jouko, Louna, Sami, Tommy, VertZu |
|            7 |     1110 | 2025-01-30 | FCottoNd        | L   | 0.991      | -            | -                | -                | -         |   -13.85 | Jouko, Louna, Sami, Tommy, VertZu |
|            6 |     1132 | 2025-01-27 | Smuuttikusilkki | L   | 0.972      | -            | -                | -                | -         |   -11.41 | Jouko, Louna, Sami, Tommy, VertZu |
|            5 |     1147 | 2025-01-25 | HAVU            | L   | 0.956      | -            | -                | -                | -         |    -5.83 | Jouko, Louna, Sami, Tommy, VertZu |
|            4 |     1162 | 2025-01-19 | Retired5        | W   | 0.918      | 0.143        | 0.000 (0.000)    | 0.086 (0.011)    | 0 (0.000) |    14.66 | Jouko, Louna, Sami, Tommy, VertZu |
|            3 |     1165 | 2025-01-19 | Roots Gaming    | W   | 0.918      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    14.40 | Jouko, Louna, Sami, Tommy, VertZu |
|            2 |     2329 | 2024-12-02 | YENKEE Academy  | L   | 0.599      | -            | -                | -                | -         |    -9.19 | Jouko, Louna, Sami, Tommy, VertZu |
|            1 |     2676 | 2024-11-27 | Ex-ESC Gaming   | L   | 0.565      | -            | -                | -                | -         |    -3.30 | Jouko, Louna, Sami, Tommy, VertZu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
