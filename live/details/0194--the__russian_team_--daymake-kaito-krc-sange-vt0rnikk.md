### Roster Details<br />
Team Name: THE (Russian team)<br />
Roster: DayMake, kaito, krc, Sange, vt0rnikk<br />
Global Rank: [194](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [141]( ../standings_europe.md)<br />
<br />
Final Rank Value:  713.6<br />
<br />
Final Rank Value (713.6) = Starting Rank Value (654.8) + Head To Head Adjustments (58.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.231[<sup>1</sup>](#table2)
- Bounty Collected: 0.253[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.8
- 400 + ( ( 0.128 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 654.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      719 | 2025-02-08 | DogEvil                 | L   | 1.000      | -            | -                | -                | -         |    -9.94 | DayMake, kaito, krc, Sange, vt0rnikk |
|           17 |      800 | 2025-02-07 | Rare Atom               | W   | 1.000      | 0.143        | 0.063 (0.009)    | 0.581 (0.083)    | 0 (0.000) |    25.73 | DayMake, kaito, krc, Sange, vt0rnikk |
|           16 |     1637 | 2024-12-15 | FengDa Gaming           | W   | 0.692      | 0.143        | 0.008 (0.001)    | 0.553 (0.055)    | 0 (0.000) |    11.16 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           15 |     1710 | 2024-12-14 | Rare Atom               | L   | 0.685      | -            | -                | -                | -         |    -3.35 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           14 |     1801 | 2024-12-13 | DEWA United             | W   | 0.678      | 0.143        | 0.000 (0.000)    | 0.161 (0.016)    | 0 (0.000) |     7.54 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           13 |     1843 | 2024-12-12 | Never Say Never-        | W   | 0.672      | 0.143        | 0.002 (0.000)    | 0.120 (0.012)    | 0 (0.000) |     9.02 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           12 |     1889 | 2024-12-11 | Rare Atom               | L   | 0.665      | -            | -                | -                | -         |    -3.15 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           11 |     1930 | 2024-12-10 | Noobs But Diligent      | W   | 0.658      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     5.36 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           10 |     2089 | 2024-12-07 | T9IIIeJIoBeCbI          | W   | 0.639      | 0.233        | 0.000 (0.000)    | 0.060 (0.009)    | 0 (0.000) |     8.18 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            9 |     2101 | 2024-12-06 | GAMUZO eSports          | W   | 0.637      | 0.233        | 0.000 (0.000)    | -                | 0 (0.000) |     5.85 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            8 |     2162 | 2024-12-05 | Nalakuvara Gaming       | L   | 0.625      | -            | -                | -                | -         |   -11.80 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            7 |     2225 | 2024-12-04 | Vizora Esports          | W   | 0.618      | 0.250        | 0.000 (0.000)    | 0.122 (0.019)    | 0 (0.000) |     5.15 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            6 |     2274 | 2024-12-03 | Victores Sumus          | W   | 0.612      | 0.250        | 0.006 (0.001)    | 0.174 (0.027)    | 0 (0.000) |    11.35 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            5 |     2530 | 2024-11-30 | Never Say Never-        | L   | 0.592      | -            | -                | -                | -         |   -10.45 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            4 |     3340 | 2024-11-16 | Harizma                 | L   | 0.498      | -            | -                | -                | -         |    -6.55 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            3 |     3344 | 2024-11-16 | SUBUTAI                 | W   | 0.498      | 0.143        | 0.001 (0.000)    | 0.051 (0.004)    | 0 (0.000) |     4.86 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            2 |     3346 | 2024-11-16 | Nomads (Mongolian team) | W   | 0.498      | 0.143        | -                | 0.407 (0.029)    | -         |     5.14 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            1 |     3360 | 2024-11-15 | The QUBE Esports        | W   | 0.497      | 0.143        | -                | 0.149 (0.011)    | -         |     4.62 | d0RREN, kaito, krc, Sange, vt0rnikk  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($159.65)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-07 |      0.639 | $250.00        | $159.65         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
