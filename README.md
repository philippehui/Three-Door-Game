# Three-Door-Game
## Story Background
- It comes from a statistical puzzle: The Monty Hall problem.
- Suppose you're on a game show, and you're given the choice of three doors: Behind one door is a car; behind the others, goats. You pick a door, say No. 1, and the host, who knows what's behind the doors, opens another door, say No. 3, which has a goat. He then says to you, "Do you want to pick door No. 2?" Is it to your advantage to switch your choice?
## Question 1:Three Door Game without Cost
- Let's assume we have three doors, behind one door is $1.00. The other two doors have nothing behind them. The host of the game knows where the dollar is. After you choose one door, the host opens an empty door for you.
- Build simulator to play N (make it 1000) rounds with each of the following strategies:
  The stick to your guns strategy -- don't change doors with new information;
  The "switch to the new door strategy" -- where you always switch to the last door once you get information from the host;
![screen shot 2018-09-30 at 3 36 56 pm](https://user-images.githubusercontent.com/31684373/46263656-c1df3680-c4c6-11e8-9356-4eada77de108.png)
- Conclusion:The switch strategy, which earns about 660 dollars after 1000 games is better than stick strategy which earns about 330 after 1000 games.
