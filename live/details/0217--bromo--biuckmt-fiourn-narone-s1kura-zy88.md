### Roster Details<br />
Team Name: Bromo<br />
Roster: Biuckmt, FIOURN, NARONE, S1kura, Zy88<br />
Global Rank: [217](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [25]( ../standings_asia.md)<br />
<br />
Final Rank Value:  698.0<br />
<br />
Final Rank Value (698.0) = Starting Rank Value (697.6) + Head To Head Adjustments (0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.358[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 697.6
- 400 + ( ( 0.149 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 697.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     1234 | 2024-12-30 | E9 Esports              | L   | 0.796      | -            | -                | -                | -         |   -18.80 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            7 |     1307 | 2024-12-28 | DogEvil                 | L   | 0.778      | -            | -                | -                | -         |    -8.90 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            6 |     1336 | 2024-12-27 | Unsettled Resentment    | L   | 0.771      | -            | -                | -                | -         |   -11.76 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            5 |     2348 | 2024-12-02 | Nomads (Mongolian team) | W   | 0.605      | 0.143        | 0.000 (0.000)    | 0.407 (0.035)    | 0 (0.000) |     4.75 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            4 |     2352 | 2024-12-02 | The Huns Esports        | W   | 0.605      | 0.143        | 0.025 (0.002)    | 0.557 (0.048)    | 0 (0.000) |    13.63 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            3 |     2355 | 2024-12-02 | SUBUTAI                 | W   | 0.604      | 0.143        | 0.001 (0.000)    | 0.051 (0.004)    | 0 (0.000) |     4.67 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            2 |     2363 | 2024-12-02 | Eruption                | W   | 0.604      | 0.143        | 0.014 (0.001)    | 0.552 (0.048)    | 0 (0.000) |    13.99 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            1 |     2367 | 2024-12-01 | Aogiri                  | W   | 0.604      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.87 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,458.37)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.797 | $6,849.13      | $5,458.37       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
