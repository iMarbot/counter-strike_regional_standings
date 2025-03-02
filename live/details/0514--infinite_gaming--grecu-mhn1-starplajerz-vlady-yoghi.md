### Roster Details<br />
Team Name: Infinite Gaming<br />
Roster: grecu, mhN1, starplajerz, vlady, Yoghi<br />
Global Rank: [514](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [320]( ../standings_europe.md)<br />
<br />
Final Rank Value:  501.2<br />
<br />
Final Rank Value (501.2) = Starting Rank Value (520.1) + Head To Head Adjustments (-18.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.060<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 520.1
- 400 + ( ( 0.060 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 520.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1360 | 2024-12-24 | NEVERMORE (Ukrainian team) | L   | 0.752      | -            | -                | -                | -         |    -4.09 | grecu, mhN1, starplajerz, vlady, Yoghi |
|           11 |     1378 | 2024-12-23 | SkyFury                    | L   | 0.744      | -            | -                | -                | -         |    -6.92 | grecu, mhN1, starplajerz, vlady, Yoghi |
|           10 |     1394 | 2024-12-22 | NEVERMORE (Ukrainian team) | W   | 0.739      | 0.333        | 0.010 (0.002)    | 0.911 (0.224)    | 0 (0.000) |    19.31 | grecu, mhN1, starplajerz, vlady, Yoghi |
|            9 |     2402 | 2024-12-01 | Perfect Storm              | L   | 0.600      | -            | -                | -                | -         |    -5.14 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            8 |     2425 | 2024-12-01 | Theboyz                    | L   | 0.599      | -            | -                | -                | -         |    -5.93 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            7 |     2489 | 2024-11-30 | Nexus Gaming               | L   | 0.594      | -            | -                | -                | -         |    -0.58 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            6 |     2505 | 2024-11-30 | JackBoyz                   | L   | 0.593      | -            | -                | -                | -         |    -5.80 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            5 |     3025 | 2024-11-21 | Nexus Gaming               | L   | 0.533      | -            | -                | -                | -         |    -0.53 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            4 |     3092 | 2024-11-20 | ROUNDS                     | W   | 0.527      | 0.372        | 0.000 (0.000)    | 0.061 (0.012)    | 0 (0.000) |     8.22 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            3 |     3119 | 2024-11-20 | Lausanne-Sport Esports     | L   | 0.526      | -            | -                | -                | -         |    -6.91 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            2 |     3439 | 2024-11-14 | ADEPTS                     | L   | 0.486      | -            | -                | -                | -         |    -4.21 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            1 |     3496 | 2024-11-13 | THE SPELLS                 | L   | 0.480      | -            | -                | -                | -         |    -6.30 | CHANKY, Ed1m, grecu, mhN1, starplajerz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
