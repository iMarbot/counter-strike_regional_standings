### Roster Details<br />
Team Name: Yamato Esports<br />
Roster: Beyond3r, deffeys, raiNyyy, singulier, t0mmyyy<br />
Global Rank: [512](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [317]( ../standings_europe.md)<br />
<br />
Final Rank Value:  502.0<br />
<br />
Final Rank Value (502.0) = Starting Rank Value (514.2) + Head To Head Adjustments (-12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.228[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.057<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 514.2
- 400 + ( ( 0.057 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 514.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1923 | 2024-12-10 | SHOO7ERS  | L   | 0.652      | -            | -                | -                | -         |    -5.82 | Beyond3r, deffeys, raiNyyy, singulier, t0mmyyy |
|            5 |     3336 | 2024-11-16 | DEPO      | L   | 0.491      | -            | -                | -                | -         |    -3.07 | deffeys, raiNyyy, saywin, singulier, t0mmyyy   |
|            4 |     3350 | 2024-11-16 | ALLINNERS | L   | 0.490      | -            | -                | -                | -         |    -3.42 | deffeys, raiNyyy, saywin, singulier, t0mmyyy   |
|            3 |     3852 | 2024-11-07 | DEPO      | L   | 0.431      | -            | -                | -                | -         |    -2.71 | Beyond3r, deffeys, kaelz7z, raiNyyy, t0mmyyy   |
|            2 |     4021 | 2024-11-04 | BERMOOD   | W   | 0.411      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     4.57 | Beyond3r, deffeys, kaelz7z, raiNyyy, t0mmyyy   |
|            1 |     4162 | 2024-11-02 | AK BARS   | L   | 0.397      | -            | -                | -                | -         |    -1.74 | Beyond3r, deffeys, kaelz7z, raiNyyy, t0mmyyy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($137.13)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.686 | $200.00        | $137.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
