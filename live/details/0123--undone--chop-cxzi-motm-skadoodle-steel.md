### Roster Details<br />
Team Name: Undone<br />
Roster: chop, cxzi, motm, Skadoodle, steel<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [25]( ../standings_americas.md)<br />
<br />
Final Rank Value:  795.2<br />
<br />
Final Rank Value (795.2) = Starting Rank Value (777.2) + Head To Head Adjustments (18.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.277[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.222[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.2
- 400 + ( ( 0.189 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 777.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     1666 | 2024-12-14 | Bad News Capybaras      | W   | 0.681      | 0.143        | 0.000 (0.000)    | 0.113 (0.011)    | 0 (0.000) |     7.01 | chop, cxzi, motm, Skadoodle, steel |
|           19 |     1749 | 2024-12-13 | SUPER EVIL GANG         | W   | 0.675      | 0.143        | 0.009 (0.001)    | 0.352 (0.034)    | 0 (0.000) |     9.01 | chop, cxzi, motm, Skadoodle, steel |
|           18 |     1755 | 2024-12-13 | Make Your Mind          | L   | 0.674      | -            | -                | -                | -         |   -11.37 | chop, cxzi, motm, Skadoodle, steel |
|           17 |     1759 | 2024-12-13 | ShanghaiSharks          | W   | 0.674      | 0.143        | 0.000 (0.000)    | 0.032 (0.003)    | 0 (0.000) |     2.27 | chop, cxzi, motm, Skadoodle, steel |
|           16 |     1764 | 2024-12-13 | OutGoing eSports        | W   | 0.674      | 0.143        | 0.001 (0.000)    | 0.056 (0.005)    | 0 (0.000) |     6.50 | chop, cxzi, motm, Skadoodle, steel |
|           15 |     1872 | 2024-12-11 | Bad News Capybaras      | W   | 0.661      | 0.143        | 0.000 (0.000)    | 0.113 (0.011)    | 0 (0.000) |     6.69 | chop, cxzi, motm, Skadoodle, steel |
|           14 |     1917 | 2024-12-10 | InControl               | W   | 0.654      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     2.06 | chop, cxzi, motm, Skadoodle, steel |
|           13 |     2005 | 2024-12-08 | Nouns Esports           | L   | 0.638      | -            | -                | -                | -         |    -7.29 | chop, cxzi, motm, steel, taggy     |
|           12 |     2050 | 2024-12-07 | MIGHT                   | W   | 0.634      | 0.384        | 0.002 (0.000)    | 0.489 (0.119)    | 1 (0.634) |     9.88 | chop, cxzi, motm, steel, taggy     |
|           11 |     2060 | 2024-12-07 | Fisher College          | W   | 0.634      | 0.384        | 0.008 (0.002)    | 0.324 (0.079)    | 1 (0.634) |    10.41 | chop, cxzi, motm, steel, taggy     |
|           10 |     2068 | 2024-12-07 | NRG                     | L   | 0.633      | -            | -                | -                | -         |    -4.17 | chop, cxzi, motm, steel, taggy     |
|            9 |     2118 | 2024-12-06 | Anti-Eco Club           | W   | 0.628      | -            | -                | -                | 1 (0.628) |     2.29 | chop, cxzi, motm, steel, taggy     |
|            8 |     2164 | 2024-12-05 | SUPER EVIL GANG         | L   | 0.621      | -            | -                | -                | -         |   -11.26 | chop, cxzi, motm, Skadoodle, steel |
|            7 |     2321 | 2024-12-02 | Make Your Mind          | L   | 0.601      | -            | -                | -                | -         |   -11.02 | chop, cxzi, motm, Skadoodle, steel |
|            6 |     2393 | 2024-12-01 | OutGoing eSports        | W   | 0.594      | 0.372        | 0.001 (0.000)    | 0.056 (0.012)    | 0 (0.000) |     6.09 | chop, cxzi, motm, Skadoodle, steel |
|            5 |     2582 | 2024-11-29 | Vibe (American team)    | W   | 0.581      | 0.372        | 0.000 (0.000)    | 0.069 (0.015)    | -         |     4.89 | chop, cxzi, motm, Skadoodle, steel |
|            4 |     2840 | 2024-11-23 | BLUEJAYS                | L   | 0.539      | -            | -                | -                | -         |    -1.99 | chop, cxzi, motm, Skadoodle, steel |
|            3 |     5953 | 2024-09-29 | Party Astronauts        | L   | 0.174      | -            | -                | -                | -         |    -2.76 | BeaKie, chop, cxzi, motm, stamina  |
|            2 |     6745 | 2024-09-18 | Mythic                  | W   | 0.099      | 0.371        | -                | 0.021 (0.001)    | -         |     0.56 | BeaKie, chop, cxzi, motm, stamina  |
|            1 |     6876 | 2024-09-16 | Penance (American Team) | W   | 0.086      | -            | -                | -                | -         |     0.29 | BeaKie, chop, cxzi, motm, stamina  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($801.04)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.641 | $1,250.00      | $801.04         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
