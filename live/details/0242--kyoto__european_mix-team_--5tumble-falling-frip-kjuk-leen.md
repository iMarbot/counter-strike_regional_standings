### Roster Details<br />
Team Name: Kyoto (European mix-team)<br />
Roster: 5tumble, Falling, Frip, kjuK, LeeN<br />
Global Rank: [242](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [171]( ../standings_europe.md)<br />
<br />
Final Rank Value:  681.3<br />
<br />
Final Rank Value (681.3) = Starting Rank Value (670.2) + Head To Head Adjustments (11.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.2
- 400 + ( ( 0.135 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 670.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3937 | 2024-11-05 | Kubix Esports    | L   | 0.427      | -            | -                | -                | -         |    -2.74 | 5tumble, Falling, Frip, kjuK, LeeN |
|            6 |     4350 | 2024-10-29 | Devils.one       | W   | 0.381      | 0.143        | 0.001 (0.000)    | 0.073 (0.004)    | 0 (0.000) |     5.67 | 5tumble, Falling, Frip, kjuK, LeeN |
|            5 |     5099 | 2024-10-14 | Devils.one       | W   | 0.280      | 0.143        | 0.001 (0.000)    | 0.073 (0.003)    | 0 (0.000) |     4.27 | 5tumble, Falling, Frip, kjuK, LeeN |
|            4 |     5838 | 2024-10-01 | Illuminar Gaming | L   | 0.193      | -            | -                | -                | -         |    -1.51 | 5tumble, Falling, Frip, kjuK, LeeN |
|            3 |     6363 | 2024-09-24 | UNiTY esports    | W   | 0.146      | 0.143        | 0.025 (0.001)    | 0.412 (0.009)    | 0 (0.000) |     3.35 | 5tumble, Falling, Frip, kjuK, LeeN |
|            2 |     6383 | 2024-09-24 | Sampi NEXT       | W   | 0.146      | 0.143        | 0.000 (0.000)    | 0.024 (0.001)    | 0 (0.000) |     1.29 | 5tumble, Falling, Frip, kjuK, LeeN |
|            1 |     6969 | 2024-09-14 | Sampi NEXT       | W   | 0.080      | 0.143        | 0.000 (0.000)    | 0.024 (0.000)    | 0 (0.000) |     0.70 | 5tumble, Falling, Frip, kjuK, LeeN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,469.85)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-16 |      0.499 | $8,962.94      | $4,469.85       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
