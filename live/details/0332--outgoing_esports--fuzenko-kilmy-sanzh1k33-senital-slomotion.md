### Roster Details<br />
Team Name: OutGoing eSports<br />
Roster: Fuzenko, kilmy, Sanzh1k33, senital, slomotion<br />
Global Rank: [332](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [215]( ../standings_europe.md)<br />
<br />
Final Rank Value:  633.6<br />
<br />
Final Rank Value (633.6) = Starting Rank Value (640.9) + Head To Head Adjustments (-7.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.261[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 640.9
- 400 + ( ( 0.120 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 640.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1764 | 2024-12-13 | Undone          | L   | 0.674      | -            | -                | -                | -         |    -6.50 | Fuzenko, kilmy, Sanzh1k33, senital, slomotion |
|            4 |     2205 | 2024-12-04 | Bad Boys        | L   | 0.614      | -            | -                | -                | -         |    -9.29 | Fuzenko, kilmy, malfik, senital, slomotion    |
|            3 |     2256 | 2024-12-03 | Final Form      | W   | 0.608      | 0.372        | 0.000 (0.000)    | 0.056 (0.013)    | 0 (0.000) |     4.07 | Fuzenko, kilmy, malfik, senital, slomotion    |
|            2 |     2393 | 2024-12-01 | Undone          | L   | 0.594      | -            | -                | -                | -         |    -6.09 | Fuzenko, kilmy, malfik, senital, slomotion    |
|            1 |     2583 | 2024-11-29 | SUPER EVIL GANG | W   | 0.580      | 0.372        | 0.009 (0.002)    | 0.352 (0.076)    | 0 (0.000) |    10.47 | Fuzenko, kilmy, malfik, senital, slomotion    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($480.63)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.641 | $750.00        | $480.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
