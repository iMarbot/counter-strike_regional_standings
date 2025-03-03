### Roster Details<br />
Team Name: Make Your Mind<br />
Roster: HorizoN, karv3r, Rulik, S0ph3R, s1rena<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  768.9<br />
<br />
Final Rank Value (768.9) = Starting Rank Value (706.7) + Head To Head Adjustments (62.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.7
- 400 + ( ( 0.153 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 706.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1755 | 2024-12-13 | Undone               | W   | 0.674      | 0.143        | 0.002 (0.000)    | 0.282 (0.027)    | 0 (0.000) |    11.37 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|           11 |     1758 | 2024-12-13 | Final Form           | W   | 0.674      | 0.143        | 0.001 (0.000)    | 0.073 (0.007)    | 0 (0.000) |     6.72 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|           10 |     1766 | 2024-12-13 | Axolotls             | W   | 0.674      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.62 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            9 |     1978 | 2024-12-08 | SUPER EVIL GANG      | W   | 0.641      | 0.372        | 0.009 (0.002)    | 0.352 (0.084)    | 0 (0.000) |     9.98 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            8 |     2253 | 2024-12-03 | Chicken Coop Esports | W   | 0.608      | 0.372        | 0.006 (0.001)    | 0.187 (0.042)    | 0 (0.000) |     8.87 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            7 |     2321 | 2024-12-02 | Undone               | W   | 0.601      | 0.372        | 0.002 (0.001)    | 0.282 (0.063)    | 0 (0.000) |    11.02 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            6 |     2392 | 2024-12-01 | HoleSmokers          | W   | 0.594      | 0.372        | 0.000 (0.000)    | 0.027 (0.006)    | 0 (0.000) |     2.86 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            5 |     2574 | 2024-11-29 | LOSTHILLS            | W   | 0.581      | 0.372        | -                | 0.026 (0.006)    | 0 (0.000) |     2.80 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            4 |     2776 | 2024-11-24 | MCS Gaming           | W   | 0.548      | 0.233        | 0.003 (0.000)    | 0.343 (0.044)    | 0 (0.000) |     7.26 | HorizoN, karv3r, Rulik, s1rena, stanf1x |
|            3 |     2778 | 2024-11-24 | Milky Gooners        | W   | 0.547      | 0.233        | 0.000 (0.000)    | -                | 0 (0.000) |     4.15 | HorizoN, karv3r, Rulik, s1rena, stanf1x |
|            2 |     2939 | 2024-11-22 | Blahaj               | L   | 0.534      | -            | -                | -                | -         |   -12.35 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            1 |     2945 | 2024-11-22 | Immigrants Peek      | W   | 0.534      | 0.143        | 0.001 (0.000)    | 0.366 (0.028)    | -         |     6.91 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,622.73)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.641 | $7,000.00      | $4,485.83       |
| 2024-11-24 |      0.548 | $250.00        | $136.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
