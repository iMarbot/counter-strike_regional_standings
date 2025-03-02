### Roster Details<br />
Team Name: Prototype Blaze<br />
Roster: ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  869.5<br />
<br />
Final Rank Value (869.5) = Starting Rank Value (866.8) + Head To Head Adjustments (2.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.221[<sup>2</sup>](#table1)

The average of these factors is 0.234<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 866.8
- 400 + ( ( 0.234 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 866.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     1033 | 2025-02-02 | Permitta W                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.140 (0.020)    | 0 (0.000) |     2.40 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            8 |     1052 | 2025-02-01 | Eco Warriors                | L   | 1.000      | -            | -                | -                | -         |   -18.31 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            7 |     1057 | 2025-02-01 | Artemis (Female team)       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     3.49 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            6 |     1084 | 2025-01-31 | OneDay                      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.149 (0.021)    | 0 (0.000) |     5.63 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            5 |     3437 | 2024-11-14 | Team Poland (Female team)   | L   | 0.486      | -            | -                | -                | -         |    -6.34 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            4 |     3475 | 2024-11-14 | Team Portugal (Female team) | W   | 0.484      | 0.557        | 0.029 (0.008)    | 0.067 (0.018)    | 1 (0.484) |     6.84 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            3 |     3517 | 2024-11-13 | Ex-Astralis Women           | W   | 0.477      | 0.557        | 0.010 (0.003)    | 0.085 (0.023)    | 1 (0.477) |     4.91 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            2 |     3610 | 2024-11-11 | Team Sweden (Female team)   | W   | 0.466      | 0.557        | 0.007 (0.002)    | 0.039 (0.010)    | 1 (0.466) |     3.09 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            1 |     3621 | 2024-11-11 | Messitas                    | W   | 0.465      | 0.557        | 0.000 (0.000)    | 0.047 (0.012)    | 1 (0.465) |     1.00 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,458.33)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.486 | $40,000.00     | $19,458.33      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
