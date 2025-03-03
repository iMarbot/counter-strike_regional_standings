### Roster Details<br />
Team Name: InSanitY Sports<br />
Roster: cass1n, f4stzin, iDk, pesadelo, shz<br />
Global Rank: [276](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [54]( ../standings_americas.md)<br />
<br />
Final Rank Value:  664.5<br />
<br />
Final Rank Value (664.5) = Starting Rank Value (661.0) + Head To Head Adjustments (3.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 661.0
- 400 + ( ( 0.130 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 661.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     6402 | 2024-09-24 | Fluxo          | L   | 0.137      | -            | -                | -                | -         |    -0.81 | cass1n, f4stzin, iDk, pesadelo, shz |
|            7 |     6487 | 2024-09-23 | PaiN Gaming    | L   | 0.131      | -            | -                | -                | -         |    -0.02 | cass1n, f4stzin, iDk, pesadelo, shz |
|            6 |     6683 | 2024-09-19 | ODDIK          | W   | 0.106      | 0.450        | 0.028 (0.001)    | 0.518 (0.025)    | 0 (0.000) |     2.38 | cass1n, f4stzin, iDk, pesadelo, shz |
|            5 |     6686 | 2024-09-19 | ODDIK          | L   | 0.106      | -            | -                | -                | -         |    -0.97 | cass1n, f4stzin, iDk, pesadelo, shz |
|            4 |     6810 | 2024-09-17 | BESTIA         | L   | 0.093      | -            | -                | -                | -         |    -0.59 | cass1n, f4stzin, iDk, pesadelo, shz |
|            3 |     6813 | 2024-09-17 | BESTIA         | W   | 0.093      | 0.450        | 0.069 (0.003)    | 0.472 (0.020)    | 0 (0.000) |     2.34 | cass1n, f4stzin, iDk, pesadelo, shz |
|            2 |     7232 | 2024-09-10 | Sharks Esports | W   | 0.046      | 0.450        | 0.055 (0.001)    | 0.622 (0.013)    | 0 (0.000) |     1.29 | cass1n, f4stzin, iDk, pesadelo, shz |
|            1 |     7236 | 2024-09-10 | Sharks Esports | L   | 0.046      | -            | -                | -                | -         |    -0.17 | cass1n, f4stzin, iDk, pesadelo, shz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($935.83)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.312 | $3,000.00      | $935.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
