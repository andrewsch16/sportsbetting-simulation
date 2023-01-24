# sportsbetting-simulation
A way to run a simulation for the expected profit from EV betting over time!

To run just click code > download zip > click on main.html and run in any browser!

<i> Feel free to reach out to me on discord with any questions/help - Vadable#5332 </i>

Just input your starting amount, win rate, and amount of bets and see a simulation of how much $$ you would make!

<b><i>All percentages need to be input as a value between 0-100. For example 56 as 56% </b></i>

this is using binomial distribution and is simulating <b>using prizepicks on a 5-pick flex play. </b>

NOTE - to calculate how much you would make with a specific edge, make sure you add the edge ON TOP of the vig added by prizepicks. For example if you wanted to simulate with a 3% edge on each bet, you would need to input 57% because it's ~54.4% that prize picks has at your breakeven win %.

more options coming soon including use for different sportsbooks and ability to adjust odds to be used for all length flex plays.

you can see the odds and calculate EV using this spreadsheet -- (credit to @AlexMonahan100 on twitter for making this!)

https://docs.google.com/spreadsheets/d/1Ql7TGK7w0HmiloejMgtGM8tNBxLOr4Yz7ONI1LNNnE8/edit?usp=sharing

the "payout model" simulates a prizepicks 5-flex play, which is as follows

0/5 - 0% return 
1/5 - 0% return 
2/5 - 0% return 
3/5 - 40% return 
4/5 - 100% return 
5/5 - 900% return 

<b> -Added feature to run an average of multiple instances at once and show an average of them all! </b>


