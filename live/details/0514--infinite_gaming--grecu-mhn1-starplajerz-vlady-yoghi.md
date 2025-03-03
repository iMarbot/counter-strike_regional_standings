### Roster Details<br />
Team Name: Infinite Gaming<br />
Roster: grecu, mhN1, starplajerz, vlady, Yoghi<br />
Global Rank: [514](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [319]( ../standings_europe.md)<br />
<br />
Final Rank Value:  500.3<br />
<br />
Final Rank Value (500.3) = Starting Rank Value (520.0) + Head To Head Adjustments (-19.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.060<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 520.0
- 400 + ( ( 0.060 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 520.0


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
|           12 |     1372 | 2024-12-24 | NEVERMORE (Ukrainian team) | L   | 0.744      | -            | -                | -                | -         |    -4.04 | grecu, mhN1, starplajerz, vlady, Yoghi |
|           11 |     1390 | 2024-12-23 | SkyFury                    | L   | 0.736      | -            | -                | -                | -         |    -6.81 | grecu, mhN1, starplajerz, vlady, Yoghi |
|           10 |     1406 | 2024-12-22 | NEVERMORE (Ukrainian team) | W   | 0.731      | 0.333        | 0.010 (0.002)    | 0.904 (0.220)    | 0 (0.000) |    19.11 | grecu, mhN1, starplajerz, vlady, Yoghi |
|            9 |     2414 | 2024-12-01 | Perfect Storm              | L   | 0.592      | -            | -                | -                | -         |    -5.04 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            8 |     2437 | 2024-12-01 | Theboyz                    | L   | 0.591      | -            | -                | -                | -         |    -5.82 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            7 |     2501 | 2024-11-30 | Nexus Gaming               | L   | 0.585      | -            | -                | -                | -         |    -0.57 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            6 |     2517 | 2024-11-30 | JackBoyz                   | L   | 0.585      | -            | -                | -                | -         |    -5.69 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            5 |     3037 | 2024-11-21 | Nexus Gaming               | L   | 0.525      | -            | -                | -                | -         |    -0.52 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            4 |     3104 | 2024-11-20 | ROUNDS                     | W   | 0.519      | 0.372        | 0.000 (0.000)    | 0.060 (0.012)    | 0 (0.000) |     8.09 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            3 |     3131 | 2024-11-20 | Lausanne-Sport Esports     | L   | 0.518      | -            | -                | -                | -         |    -6.79 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            2 |     3451 | 2024-11-14 | ADEPTS                     | L   | 0.478      | -            | -                | -                | -         |    -5.38 | CHANKY, Ed1m, grecu, mhN1, starplajerz |
|            1 |     3508 | 2024-11-13 | THE SPELLS                 | L   | 0.472      | -            | -                | -                | -         |    -6.25 | CHANKY, Ed1m, grecu, mhN1, starplajerz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
