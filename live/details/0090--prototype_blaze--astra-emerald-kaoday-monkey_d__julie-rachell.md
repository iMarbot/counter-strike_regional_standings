### Roster Details<br />
Team Name: Prototype Blaze<br />
Roster: ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  868.4<br />
<br />
Final Rank Value (868.4) = Starting Rank Value (865.8) + Head To Head Adjustments (2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.218[<sup>2</sup>](#table1)

The average of these factors is 0.233<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 865.8
- 400 + ( ( 0.233 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 865.8


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
|            9 |     1045 | 2025-02-02 | Permitta W                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |     2.41 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            8 |     1064 | 2025-02-01 | Eco Warriors                | L   | 1.000      | -            | -                | -                | -         |   -18.30 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            7 |     1069 | 2025-02-01 | Artemis (Female team)       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     3.51 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            6 |     1096 | 2025-01-31 | OneDay                      | W   | 0.999      | 0.143        | 0.000 (0.000)    | 0.148 (0.021)    | 0 (0.000) |     5.65 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            5 |     3449 | 2024-11-14 | Team Poland (Female team)   | L   | 0.478      | -            | -                | -                | -         |    -6.24 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            4 |     3487 | 2024-11-14 | Team Portugal (Female team) | W   | 0.476      | 0.557        | 0.029 (0.008)    | 0.066 (0.017)    | 1 (0.476) |     6.72 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            3 |     3529 | 2024-11-13 | Ex-Astralis Women           | W   | 0.469      | 0.557        | 0.010 (0.003)    | 0.083 (0.022)    | 1 (0.469) |     4.83 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            2 |     3622 | 2024-11-11 | Team Sweden (Female team)   | W   | 0.458      | 0.557        | 0.007 (0.002)    | 0.038 (0.010)    | 1 (0.458) |     3.04 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            1 |     3633 | 2024-11-11 | Messitas                    | W   | 0.457      | 0.557        | 0.000 (0.000)    | 0.047 (0.012)    | 1 (0.457) |     0.98 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,130.56)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.478 | $40,000.00     | $19,130.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
