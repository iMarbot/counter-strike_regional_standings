### Roster Details<br />
Team Name: Canon Event<br />
Roster: CC3ptic, Crackbaby, FAZZ, mitzy, Supers<br />
Global Rank: [531](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [84]( ../standings_asia.md)<br />
<br />
Final Rank Value:  487.9<br />
<br />
Final Rank Value (487.9) = Starting Rank Value (511.5) + Head To Head Adjustments (-23.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.223[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.5
- 400 + ( ( 0.056 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 511.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1083 | 2025-01-31 | PrevailANZ           | L   | 1.000      | -            | -                | -                | -         |   -17.80 | CC3ptic, Crackbaby, FAZZ, mitzy, Supers |
|            5 |     2830 | 2024-11-23 | Justice For Tomorrow | L   | 0.541      | -            | -                | -                | -         |    -5.45 | CC3ptic, Crackbaby, FAZZ, mitzy, Supers |
|            4 |     2927 | 2024-11-22 | Rooster 2            | W   | 0.535      | 0.264        | 0.000 (0.000)    | 0.025 (0.004)    | 0 (0.000) |     6.13 | CC3ptic, Crackbaby, FAZZ, mitzy, Supers |
|            3 |     2934 | 2024-11-22 | Vantage Esports      | L   | 0.534      | -            | -                | -                | -         |    -5.23 | CC3ptic, Crackbaby, FAZZ, mitzy, Supers |
|            2 |     7224 | 2024-09-11 | Milkmen              | L   | 0.049      | -            | -                | -                | -         |    -0.87 | CC3ptic, Kras, mitzy, Redav, Supers     |
|            1 |     7489 | 2024-09-07 | FreshFoodPeople      | L   | 0.023      | -            | -                | -                | -         |    -0.40 | CC3ptic, Kras, mitzy, Phek, Supers      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($105.74)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-23 |      0.542 | $195.00        | $105.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
