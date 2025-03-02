### Roster Details<br />
Team Name: Little Red Door<br />
Roster: CRUC1AL, Keoz, MisteM, misutaaa, rallen<br />
Global Rank: [392](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [248]( ../standings_europe.md)<br />
<br />
Final Rank Value:  601.3<br />
<br />
Final Rank Value (601.3) = Starting Rank Value (540.3) + Head To Head Adjustments (61.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.070<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 540.3
- 400 + ( ( 0.070 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 540.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |      294 | 2025-02-17 | CYBERSHOKE Esports         | L   | 1.000      | -            | -                | -                | -         |    -5.28 | CRUC1AL, Keoz, MisteM, misutaaa, rallen    |
|            7 |      346 | 2025-02-16 | BANNDA                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.06 | CRUC1AL, Keoz, MisteM, misutaaa, rallen    |
|            6 |      464 | 2025-02-14 | KONO.ECF                   | L   | 1.000      | -            | -                | -                | -         |   -11.69 | CRUC1AL, MisteM, misutaaa, rallen, REDSTAR |
|            5 |      659 | 2025-02-08 | Zero Tenacity              | L   | 1.000      | -            | -                | -                | -         |    -6.10 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |
|            4 |      665 | 2025-02-08 | NEVERMORE (Ukrainian team) | L   | 1.000      | -            | -                | -                | -         |    -6.87 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |
|            3 |      683 | 2025-02-08 | Team Novaq                 | W   | 1.000      | 0.143        | 0.030 (0.004)    | 0.396 (0.057)    | 0 (0.000) |    29.79 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |
|            2 |      694 | 2025-02-08 | SINNERS Esports            | W   | 1.000      | 0.143        | 0.027 (0.004)    | 0.451 (0.064)    | 0 (0.000) |    26.97 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |
|            1 |      771 | 2025-02-07 | ALASKA                     | W   | 1.000      | 0.143        | 0.030 (0.004)    | 0.875 (0.125)    | 0 (0.000) |    27.08 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
