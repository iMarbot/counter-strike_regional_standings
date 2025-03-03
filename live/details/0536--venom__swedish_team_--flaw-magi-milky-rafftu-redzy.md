### Roster Details<br />
Team Name: Venom (Swedish team)<br />
Roster: flaw, magi, milky, rafftu, redzy<br />
Global Rank: [536](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [332]( ../standings_europe.md)<br />
<br />
Final Rank Value:  485.4<br />
<br />
Final Rank Value (485.4) = Starting Rank Value (475.3) + Head To Head Adjustments (10.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.150[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.038<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 475.3
- 400 + ( ( 0.038 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 475.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     4814 | 2024-10-20 | Alliance    | L   | 0.310      | -            | -                | -                | -         |    -0.93 | flaw, magi, milky, rafftu, redzy |
|            5 |     4862 | 2024-10-19 | Pikejagarna | W   | 0.304      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     3.77 | flaw, magi, milky, rafftu, redzy |
|            4 |     5006 | 2024-10-16 | Alliance    | L   | 0.285      | -            | -                | -                | -         |    -0.85 | flaw, magi, milky, rafftu, redzy |
|            3 |     5068 | 2024-10-15 | Lemondogs   | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     4.37 | flaw, magi, milky, rafftu, redzy |
|            2 |     6707 | 2024-09-19 | Metizport X | W   | 0.104      | 0.143        | 0.001 (0.000)    | 0.218 (0.003)    | 0 (0.000) |     2.42 | flaw, magi, milky, rafftu, redzy |
|            1 |     6757 | 2024-09-18 | WARCUBE     | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.23 | flaw, magi, milky, rafftu, redzy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
