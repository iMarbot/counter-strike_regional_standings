### Roster Details<br />
Team Name: Virtual Cottage<br />
Roster: aidKiT, AMANEK, EspiranTo, lunAtic, spardaus<br />
Global Rank: [470](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [292]( ../standings_europe.md)<br />
<br />
Final Rank Value:  540.6<br />
<br />
Final Rank Value (540.6) = Starting Rank Value (515.6) + Head To Head Adjustments (24.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.058<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 515.6
- 400 + ( ( 0.058 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 515.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      353 | 2025-02-16 | Mission Possible  | L   | 1.000      | -            | -                | -                | -         |   -13.88 | aidKiT, AMANEK, EspiranTo, lunAtic, spardaus |
|            5 |      408 | 2025-02-15 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -8.82 | aidKiT, AMANEK, EspiranTo, lunAtic, spardaus |
|            4 |      418 | 2025-02-15 | ALGO              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.094 (0.013)    | 0 (0.000) |    14.91 | aidKiT, AMANEK, EspiranTo, lunAtic, spardaus |
|            3 |      426 | 2025-02-15 | Eternal premium   | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.215 (0.031)    | 0 (0.000) |    22.53 | aidKiT, AMANEK, EspiranTo, lunAtic, spardaus |
|            2 |      485 | 2025-02-14 | ARCRED            | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.480 (0.069)    | 0 (0.000) |    26.07 | aidKiT, AMANEK, EspiranTo, lunAtic, spardaus |
|            1 |      759 | 2025-02-07 | AgenciUSB         | L   | 1.000      | -            | -                | -                | -         |   -15.87 | aidKiT, AMANEK, EspiranTo, lunAtic, spardaus |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
