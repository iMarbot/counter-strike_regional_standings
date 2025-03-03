### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, emy, GooseBreeder, marie, vanessa<br />
Global Rank: [353](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [74]( ../standings_americas.md)<br />
<br />
Final Rank Value:  624.6<br />
<br />
Final Rank Value (624.6) = Starting Rank Value (656.9) + Head To Head Adjustments (-32.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.197[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 656.9
- 400 + ( ( 0.128 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 656.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      627 | 2025-02-09 | Exceritus        | L   | 1.000      | -            | -                | -                | -         |   -16.15 | BiBiAhn, emy, GooseBreeder, marie, vanessa  |
|           11 |      682 | 2025-02-08 | InControl        | L   | 1.000      | -            | -                | -                | -         |   -16.24 | BiBiAhn, emy, GooseBreeder, marie, vanessa  |
|           10 |     2919 | 2024-11-23 | Eco Warriors     | L   | 0.536      | -            | -                | -                | -         |    -5.40 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|            9 |     3001 | 2024-11-22 | Fluxo Demons     | L   | 0.530      | -            | -                | -                | -         |    -5.63 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|            8 |     4881 | 2024-10-18 | Aware Impact     | W   | 0.300      | 0.333        | 0.001 (0.000)    | 0.007 (0.001)    | 0 (0.000) |     3.87 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|            7 |     5755 | 2024-10-02 | Blue Otter Karma | W   | 0.193      | 0.333        | 0.001 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     2.54 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|            6 |     6180 | 2024-09-26 | Lotus            | W   | 0.153      | 0.333        | 0.001 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     2.01 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|            5 |     6676 | 2024-09-19 | Supernova Comets | W   | 0.107      | 0.333        | 0.011 (0.000)    | 0.263 (0.009)    | 0 (0.000) |     2.03 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|            4 |     6924 | 2024-09-15 | Arf Squad        | L   | 0.079      | -            | -                | -                | -         |    -1.48 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|            3 |     6971 | 2024-09-14 | Supernova Comets | W   | 0.074      | 0.250        | 0.011 (0.000)    | 0.263 (0.005)    | 0 (0.000) |     1.41 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|            2 |     7171 | 2024-09-11 | Nouns.fe         | W   | 0.053      | 0.333        | 0.001 (0.000)    | 0.070 (0.001)    | 0 (0.000) |     0.74 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|            1 |     7648 | 2024-09-04 | TSM Impact       | W   | 0.006      | 0.333        | 0.001 (0.000)    | 0.021 (0.000)    | 0 (0.000) |     0.09 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,197.60)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.544 | $4,000.00      | $2,177.78       |
| 2024-09-15 |      0.079 | $250.00        | $19.83          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
