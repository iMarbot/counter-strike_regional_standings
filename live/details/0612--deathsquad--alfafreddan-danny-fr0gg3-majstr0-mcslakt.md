### Roster Details<br />
Team Name: Deathsquad<br />
Roster: AlfaFreddan, Danny, FR0GG3, majstr0, Mcslakt<br />
Global Rank: [612](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [372]( ../standings_europe.md)<br />
<br />
Final Rank Value:  395.3<br />
<br />
Final Rank Value (395.3) = Starting Rank Value (400.0) + Head To Head Adjustments (-4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     4627 | 2024-10-24 | Northern Lights | L   | 0.339      | -            | -                | -                | -         |    -5.30 | AlfaFreddan, Danny, FR0GG3, majstr0, Mcslakt |
|            4 |     4902 | 2024-10-18 | Kario Mart      | L   | 0.298      | -            | -                | -                | -         |    -2.10 | AlfaFreddan, Danny, FR0GG3, majstr0, Mcslakt |
|            3 |     5286 | 2024-10-10 | Regeltre        | W   | 0.245      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     3.86 | AlfaFreddan, Danny, FR0GG3, majstr0, Mcslakt |
|            2 |     6603 | 2024-09-21 | Showmakerz      | L   | 0.116      | -            | -                | -                | -         |    -0.90 | AlfaFreddan, Danny, FR0GG3, majstr0, Mcslakt |
|            1 |     7519 | 2024-09-06 | Lemondogs       | L   | 0.018      | -            | -                | -                | -         |    -0.28 | AlfaFreddan, Danny, FR0GG3, majstr0, Mcslakt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
