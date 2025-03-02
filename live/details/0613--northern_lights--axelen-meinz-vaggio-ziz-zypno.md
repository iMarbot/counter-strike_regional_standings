### Roster Details<br />
Team Name: Northern Lights<br />
Roster: Axelen, meinz, vaggio, ziz, Zypno<br />
Global Rank: [613](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [375]( ../standings_europe.md)<br />
<br />
Final Rank Value:  394.7<br />
<br />
Final Rank Value (394.7) = Starting Rank Value (400.1) + Head To Head Adjustments (-5.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.1
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     3537 | 2024-11-12 | Lemondogs            | L   | 0.473      | -            | -                | -                | -         |    -7.34 | Axelen, meinz, vaggio, ziz, Zypno |
|            8 |     4297 | 2024-10-30 | Lilmix               | L   | 0.387      | -            | -                | -                | -         |    -4.17 | Axelen, meinz, vaggio, ziz, Zypno |
|            7 |     4615 | 2024-10-24 | Deathsquad           | W   | 0.347      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     5.43 | Axelen, meinz, vaggio, ziz, Zypno |
|            6 |     4991 | 2024-10-16 | Lagby Gooners        | W   | 0.293      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.59 | Axelen, meinz, vaggio, ziz, Zypno |
|            5 |     5256 | 2024-10-11 | NIP Svea             | L   | 0.259      | -            | -                | -                | -         |    -4.09 | Axelen, meinz, vaggio, ziz, Zypno |
|            4 |     5564 | 2024-10-05 | GardenGarage         | L   | 0.220      | -            | -                | -                | -         |    -0.87 | Axelen, H0TI, meinz, vaggio, ziz  |
|            3 |     5846 | 2024-10-01 | Privateshow          | L   | 0.193      | -            | -                | -                | -         |    -2.07 | Axelen, meinz, vaggio, ziz, Zypno |
|            2 |     6827 | 2024-09-17 | Regeltre             | W   | 0.100      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     1.57 | Axelen, meinz, vaggio, ziz, Zypno |
|            1 |     7021 | 2024-09-14 | Venom (Swedish team) | W   | 0.078      | 0.143        | 0.000 (0.000)    | 0.063 (0.001)    | 0 (0.000) |     1.57 | Axelen, meinz, vaggio, ziz, Zypno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
