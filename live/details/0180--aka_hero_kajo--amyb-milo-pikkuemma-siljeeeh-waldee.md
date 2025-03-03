### Roster Details<br />
Team Name: AKA HERO KAJO<br />
Roster: amyb, miLo, pikkuemma, Siljeeeh, Waldee<br />
Global Rank: [180](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [130]( ../standings_europe.md)<br />
<br />
Final Rank Value:  725.6<br />
<br />
Final Rank Value (725.6) = Starting Rank Value (740.5) + Head To Head Adjustments (-14.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.165[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 740.5
- 400 + ( ( 0.170 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 740.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      846 | 2025-02-06 | Also                       | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.195 (0.028)    | 0 (0.000) |    12.01 | amyb, miLo, pikkuemma, Siljeeeh, Waldee |
|           12 |      896 | 2025-02-05 | Elite Klan Violet          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     4.16 | amyb, miLo, pikkuemma, Siljeeeh, Waldee |
|           11 |     1097 | 2025-01-31 | SAW Myst                   | L   | 0.999      | -            | -                | -                | -         |   -24.16 | amyb, miLo, pikkuemma, Siljeeeh, Waldee |
|           10 |     1705 | 2024-12-14 | Nomercy (Female team)      | L   | 0.678      | -            | -                | -                | -         |   -11.97 | amyb, miLo, pikkuemma, Siljeeeh, Waldee |
|            9 |     2017 | 2024-12-08 | Nomercy (Female team)      | L   | 0.638      | -            | -                | -                | -         |   -11.93 | amyb, miLo, pikkuemma, tinjau, Waldee   |
|            8 |     2089 | 2024-12-07 | Permitta W                 | W   | 0.631      | 0.250        | 0.003 (0.000)    | 0.169 (0.027)    | 0 (0.000) |     6.53 | amyb, miLo, pikkuemma, tinjau, Waldee   |
|            7 |     2092 | 2024-12-07 | Needachance                | W   | 0.631      | 0.250        | 0.000 (0.000)    | 0.032 (0.005)    | 0 (0.000) |     2.40 | amyb, miLo, pikkuemma, tinjau, Waldee   |
|            6 |     2527 | 2024-11-30 | Take Flyte Female          | L   | 0.585      | -            | -                | -                | -         |   -10.43 | amyb, miLo, pikkuemma, Siljeeeh, Waldee |
|            5 |     2533 | 2024-11-30 | Elite Klan Violet          | W   | 0.585      | 0.250        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     2.12 | amyb, miLo, pikkuemma, Siljeeeh, Waldee |
|            4 |     4488 | 2024-10-27 | Ex-Astralis Women          | W   | 0.357      | 0.143        | 0.010 (0.001)    | 0.083 (0.004)    | 1 (0.357) |     5.54 | amyb, miLo, Pikkuems, Siljeeeh, Waldee  |
|            3 |     4499 | 2024-10-27 | Team Sweden (Female team)  | W   | 0.356      | 0.143        | 0.007 (0.000)    | 0.038 (0.002)    | 1 (0.356) |     3.84 | amyb, miLo, Pikkuems, Siljeeeh, Waldee  |
|            2 |     4537 | 2024-10-26 | Team Iceland (Female team) | W   | 0.350      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.350) |     1.36 | amyb, miLo, Pikkuems, Siljeeeh, Waldee  |
|            1 |     4575 | 2024-10-25 | Ex-Astralis Women          | W   | 0.348      | 0.143        | 0.010 (0.000)    | 0.083 (0.004)    | 1 (0.348) |     5.61 | amyb, miLo, Pikkuems, Siljeeeh, Waldee  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,335.20)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.638 | $250.00        | $159.41         |
| 2024-10-27 |      0.357 | $3,295.33      | $1,175.79       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
