### Roster Details<br />
Team Name: St4rboys<br />
Roster: Ang3l10wow, Bloody, hf, pavast4r, Sharpshooter<br />
Global Rank: [299](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [43]( ../standings_asia.md)<br />
<br />
Final Rank Value:  650.7<br />
<br />
Final Rank Value (650.7) = Starting Rank Value (645.2) + Head To Head Adjustments (5.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.266[<sup>1</sup>](#table2)
- Bounty Collected: 0.218[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 645.2
- 400 + ( ( 0.123 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 645.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1745 | 2024-12-13 | Big W           | L   | 0.675      | -            | -                | -                | -         |    -9.52 | Ang3l10wow, Bloody, hf, pavast4r, Sharpshooter    |
|            5 |     3182 | 2024-11-18 | Gods Reign      | W   | 0.509      | 0.262        | 0.018 (0.002)    | 0.407 (0.054)    | 0 (0.000) |    12.27 | Bloody, crony, hf, pavast4r, Sharpshooter         |
|            4 |     3184 | 2024-11-18 | Project Lethals | W   | 0.508      | 0.262        | 0.000 (0.000)    | 0.007 (0.001)    | 0 (0.000) |     3.22 | Bloody, crony, hf, pavast4r, Sharpshooter         |
|            3 |     4502 | 2024-10-26 | Gods Reign      | L   | 0.355      | -            | -                | -                | -         |    -2.29 | Ang3l10wow, Bloody, Empera, Scoffic, Sharpshooter |
|            2 |     6550 | 2024-09-21 | Gods Reign      | L   | 0.122      | -            | -                | -                | -         |    -0.72 | Ang3l10wow, Bloody, hf, Scoffic, Sharpshooter     |
|            1 |     6552 | 2024-09-21 | Victores Sumus  | W   | 0.121      | 0.262        | 0.006 (0.000)    | 0.173 (0.005)    | 0 (0.000) |     2.60 | Ang3l10wow, Bloody, hf, Scoffic, Sharpshooter     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($569.85)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-18 |      0.509 | $1,000.00      | $508.89         |
| 2024-09-21 |      0.122 | $500.00        | $60.96          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
