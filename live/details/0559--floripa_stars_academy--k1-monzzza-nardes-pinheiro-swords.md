### Roster Details<br />
Team Name: Floripa Stars Academy<br />
Roster: k1, monzzza, nardes, pinheiro, swords<br />
Global Rank: [559](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [128]( ../standings_americas.md)<br />
<br />
Final Rank Value:  472.8<br />
<br />
Final Rank Value (472.8) = Starting Rank Value (479.0) + Head To Head Adjustments (-6.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.154[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.040<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 479.0
- 400 + ( ( 0.040 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 479.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     2061 | 2024-12-07 | Southampton     | L   | 0.641      | -            | -                | -                | -         |   -12.35 | k1, monzzza, nardes, pinheiro, swords      |
|            5 |     2068 | 2024-12-07 | INS4NI Academy  | W   | 0.640      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.80 | k1, monzzza, nardes, pinheiro, swords      |
|            4 |     2247 | 2024-12-03 | TROPA DO TACO   | L   | 0.615      | -            | -                | -                | -         |    -3.28 | monzzza, nardes, pinheiro, Rkzinho, swords |
|            3 |     3782 | 2024-11-08 | MIBR Academy    | L   | 0.447      | -            | -                | -                | -         |    -3.41 | monzzza, nardes, pinheiro, Rkzinho, swords |
|            2 |     3826 | 2024-11-07 | América eSports | W   | 0.441      | 0.242        | 0.000 (0.000)    | 0.429 (0.046)    | 0 (0.000) |     9.16 | monzzza, nardes, pinheiro, Rkzinho, swords |
|            1 |     4117 | 2024-11-02 | INTERDIT        | L   | 0.407      | -            | -                | -                | -         |    -4.14 | monzzza, nardes, pinheiro, Rkzinho, swords |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
