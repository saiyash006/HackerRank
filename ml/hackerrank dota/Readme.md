# Dota2Prediction

Solve the Problem on [HackerRank](https://www.hackerrank.com/challenges/dota2prediction/problem?isFullScreen=true) 

Game Description:

Gabe plays [Defence of the Ancients](http://en.wikipedia.org/wiki/Dota) with 9 friends in two 5-player teams.

Players choose unique heroes from a pool of 100. Since players have similar skill levels, hero selection influences game outcomes. Gabe wants to predict winners based on hero picks.

**Game Data**

A dataset of 15,000 past games is available as [training data](https://s3.amazonaws.com/hr-testcases/368/assets/trainingdata.txt). Each line contains 10 hero names (including spaces, apostrophes, and hyphens) and the winning team number.

Each line lists team 1's heroes, team 2's heroes, and the winner (1 or 2).

**Challenge**

Predict the winning team for K games using the training data. Your score depends on prediction accuracy.

**Input**

Line 1: Integer K (games to predict)
Next K lines: 10 comma-separated hero names

**Output**

For each game: Print winning team (1 or 2)

**Constraints**

1 ≤ K ≤ 3000

**Sample Input**

5

Spectre,Nature's Prophet,Ogre Magi,Nyx Assassin,Kunkka,Lone Druid,Windrunner,Disruptor,Juggernaut,Naga Siren

Windrunner,Medusa,Zeus,Shadow Fiend,Troll Warlord,Bounty Hunter,Pudge,Lycanthrope,Riki,Pugna

Ogre Magi,Sniper,Rubick,Lifestealer,Treant Protector,Slardar,Lion,Shadow Fiend,Weaver,Nature's Prophet

Sniper,Nyx Assassin,Lich,Axe,Necrolyte,Magnus,Juggernaut,Dazzle,Tinker,Nature's Prophet

Lina,Nature's Prophet,Chaos Knight,Gyrocopter,Invoker,Sven,Broodmother,Necrolyte,Undying,Windrunner

**Sample Output**

1

1

1

1

1

**Scoring**

Score = 100 * ((#correct - #incorrect) / total)

Score is 0 if less than 50% correct. Only the hidden test case counts. Sample case is for testing only.