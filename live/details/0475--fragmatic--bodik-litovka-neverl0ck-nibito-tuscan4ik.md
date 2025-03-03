### Roster Details<br />
Team Name: Fragmatic<br />
Roster: bodik, Litovka, neverl0ck, nibito, Tuscan4ik<br />
Global Rank: [475](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [295]( ../standings_europe.md)<br />
<br />
Final Rank Value:  536.8<br />
<br />
Final Rank Value (536.8) = Starting Rank Value (565.8) + Head To Head Adjustments (-29.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.200[<sup>1</sup>](#table2)
- Bounty Collected: 0.128[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.083<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 565.8
- 400 + ( ( 0.083 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 565.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1466 | 2024-12-21 | C.S.D.E                    | L   | 0.724      | -            | -                | -                | -         |    -7.60 | bodik, Litovka, neverl0ck, nibito, Tuscan4ik |
|            9 |     1477 | 2024-12-21 | SkyFury                    | L   | 0.724      | -            | -                | -                | -         |    -7.73 | bodik, Litovka, neverl0ck, nibito, Tuscan4ik |
|            8 |     1492 | 2024-12-21 | WildHunt                   | W   | 0.723      | 0.143        | 0.000 (0.000)    | 0.034 (0.004)    | 0 (0.000) |     6.86 | bodik, Litovka, neverl0ck, nibito, Tuscan4ik |
|            7 |     2523 | 2024-11-30 | VOID GAMING (Russian team) | L   | 0.585      | -            | -                | -                | -         |   -11.81 | bodik, Litovka, t3zisswes, Tuscan4ik, xxlafy |
|            6 |     2554 | 2024-11-30 | ROYALS                     | L   | 0.583      | -            | -                | -                | -         |    -6.07 | bodik, Litovka, t3zisswes, Tuscan4ik, xxlafy |
|            5 |     2639 | 2024-11-28 | ZennoX                     | L   | 0.572      | -            | -                | -                | -         |    -7.19 | bodik, Litovka, t3zisswes, Tuscan4ik, xxlafy |
|            4 |     2677 | 2024-11-27 | BAKS Esports               | W   | 0.565      | 0.333        | 0.000 (0.000)    | 0.151 (0.028)    | 0 (0.000) |     7.85 | bodik, Litovka, t3zisswes, Tuscan4ik, xxlafy |
|            3 |     2688 | 2024-11-27 | Dark Cloud Esports         | L   | 0.564      | -            | -                | -                | -         |    -2.90 | bodik, Litovka, t3zisswes, Tuscan4ik, xxlafy |
|            2 |     5974 | 2024-09-29 | Podpivasi                  | L   | 0.171      | -            | -                | -                | -         |    -2.63 | bodik, Litovka, mattloo, shiny, Tuscan4ik    |
|            1 |     5996 | 2024-09-29 | Dragon Esports Club        | W   | 0.169      | 0.143        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     2.14 | bodik, Litovka, mattloo, shiny, Tuscan4ik    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33.15)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-29 |      0.171 | $194.36        | $33.15          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
