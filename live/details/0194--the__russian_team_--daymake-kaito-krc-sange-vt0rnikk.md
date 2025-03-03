### Roster Details<br />
Team Name: THE (Russian team)<br />
Roster: DayMake, kaito, krc, Sange, vt0rnikk<br />
Global Rank: [194](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [140]( ../standings_europe.md)<br />
<br />
Final Rank Value:  713.3<br />
<br />
Final Rank Value (713.3) = Starting Rank Value (655.2) + Head To Head Adjustments (58.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.231[<sup>1</sup>](#table2)
- Bounty Collected: 0.253[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 655.2
- 400 + ( ( 0.128 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 655.2


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
|           18 |      731 | 2025-02-08 | DogEvil                 | L   | 1.000      | -            | -                | -                | -         |    -9.95 | DayMake, kaito, krc, Sange, vt0rnikk |
|           17 |      812 | 2025-02-07 | Rare Atom               | W   | 1.000      | 0.143        | 0.063 (0.009)    | 0.578 (0.083)    | 0 (0.000) |    25.71 | DayMake, kaito, krc, Sange, vt0rnikk |
|           16 |     1649 | 2024-12-15 | FengDa Gaming           | W   | 0.683      | 0.143        | 0.008 (0.001)    | 0.550 (0.054)    | 0 (0.000) |    11.04 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           15 |     1722 | 2024-12-14 | Rare Atom               | L   | 0.677      | -            | -                | -                | -         |    -3.32 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           14 |     1813 | 2024-12-13 | DEWA United             | W   | 0.670      | 0.143        | 0.000 (0.000)    | 0.158 (0.015)    | 0 (0.000) |     7.42 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           13 |     1855 | 2024-12-12 | Never Say Never-        | W   | 0.663      | 0.143        | 0.002 (0.000)    | 0.119 (0.011)    | 0 (0.000) |     8.92 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           12 |     1901 | 2024-12-11 | Rare Atom               | L   | 0.657      | -            | -                | -                | -         |    -3.13 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           11 |     1942 | 2024-12-10 | Noobs But Diligent      | W   | 0.650      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     5.29 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|           10 |     2101 | 2024-12-07 | T9IIIeJIoBeCbI          | W   | 0.630      | 0.233        | 0.000 (0.000)    | 0.059 (0.009)    | 0 (0.000) |     8.07 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            9 |     2113 | 2024-12-06 | GAMUZO eSports          | W   | 0.628      | 0.233        | 0.000 (0.000)    | -                | 0 (0.000) |     5.77 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            8 |     2174 | 2024-12-05 | Nalakuvara Gaming       | L   | 0.617      | -            | -                | -                | -         |   -11.65 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            7 |     2237 | 2024-12-04 | Vizora Esports          | W   | 0.610      | 0.250        | 0.000 (0.000)    | 0.122 (0.019)    | 0 (0.000) |     5.08 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            6 |     2286 | 2024-12-03 | Victores Sumus          | W   | 0.604      | 0.250        | 0.006 (0.001)    | 0.173 (0.026)    | 0 (0.000) |    11.25 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            5 |     2542 | 2024-11-30 | Never Say Never-        | L   | 0.584      | -            | -                | -                | -         |   -10.30 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            4 |     3352 | 2024-11-16 | Harizma                 | L   | 0.490      | -            | -                | -                | -         |    -6.48 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            3 |     3356 | 2024-11-16 | SUBUTAI                 | W   | 0.490      | 0.143        | 0.001 (0.000)    | 0.051 (0.004)    | 0 (0.000) |     4.79 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            2 |     3358 | 2024-11-16 | Nomads (Mongolian team) | W   | 0.489      | 0.143        | -                | 0.407 (0.028)    | -         |     5.06 | d0RREN, kaito, krc, Sange, vt0rnikk  |
|            1 |     3372 | 2024-11-15 | The QUBE Esports        | W   | 0.489      | 0.143        | -                | 0.147 (0.010)    | -         |     4.54 | d0RREN, kaito, krc, Sange, vt0rnikk  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($157.60)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-07 |      0.630 | $250.00        | $157.60         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
