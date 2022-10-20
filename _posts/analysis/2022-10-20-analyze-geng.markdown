---
layout: post
title:  "Gen.G - Faze Clan: RLCS NA Fall Open Analysis"
date:   2022-10-20 10:00 -0400
categories: analysis Gen.G Faze NA Fall Open
---

Gen.G cruised their way through the North American Fall Open, except when they played Faze Clan. What was different about their matchup against Faze?

When ApparentlyJack and Noly made the jump from EU to NA there was natural interest in how two players who had been around the top of the EU ladder would fare jumping to a new region. When they added Chronic, a 1s main from the bubble scene, and got picked up by Gen.G, there was greater interest _and_ greater confusion. Gen.G mostly ended up cruising in their first tournament, making a surprise run to the grand finals and only losing two series along the way. Both of those losses were to Faze Clan though, one in their very first match of Swiss, and one in the Grand Finals. Faze played Gen.G differently than every other team Gen.G had to face, and even made some key adjustments from their first series to their last.

The major differences for Gen.G when they played against Faze were how the teams rotated behind the ball. Gen.G played their entire tournament "behind the ball," compared to their opponents, ensuring that they were more often the team with two players back to defend. That changed against Faze, who were more content than any other opponent to play 2 behind the ball and force Gen.G to be the team taking the upfield initiative. 

![Gen.G/Opponent Time Behind Ball Ratio]({{site.url}}/{{site.baseurl}}/assets/images/2022-10-20-analyze-geng/Gen.G Time Behind Ball.png)

This forced Gen.G into a difficult balance: they had to figure out ways to score against two defenders while also being aware that any one Faze player was capable of the solo play that would unlock the Gen.G defense. The natural way to attack this problem is to control possession and boost, especially in the attacking zone, but Gen.G weren't able to own both of those axes. Through the semifinal round, Gen.G had held about 8% more boost than their opponent, but against Faze, Gen.G had less than 25 boost for **20% more time** than Faze and lost the boost battle overall.

![Gen.G Time Below 25 Boost]({{site.url}}/{{site.baseurl}}/assets/images/2022-10-20-analyze-geng/Gen.G Time Boost0 To25.png)

One thing Faze improved from the Swiss matchup to the Grand Finals was the amount they were able to protect their own corner boosts. Gen.G stole big boosts from Faze over 40% more often in the first matchup, but in the repeat Faze was able to flip that and steal 15% more big boosts than Gen.G.

![Gen.G/Opponent Big Boost Stolen Ratio]({{site.url}}/{{site.baseurl}}/assets/images/2022-10-20-analyze-geng/Gen.G Amount Stolen Big.png)

This resulted in a pretty impotent Gen.G offense. Because they weren't able to starve out Faze they were forced into taking more of their shots from defendable positions, and Faze were consistent in making those saves. Gen.G had owned the shooting percentage battle against everyone else, but against Faze they just weren't able to shoot nearly as effectively, partially because they weren't able to generate assisted goals.

![Gen.G/Opponent Shooting Percentage Ratio]({{site.url}}/{{site.baseurl}}/assets/images/2022-10-20-analyze-geng/Gen.G Shooting Percentage.png)
![Gen.G Assists Per Goal]({{site.url}}/{{site.baseurl}}/assets/images/2022-10-20-analyze-geng/Gen.G Assists Per Goal.png)

If teams can recognize Gen.G's tendency to own the boost game and force them to stretch into less comfortable situations, we could see Gen.G struggle a bit more in this second Regional. Gen.G had a wonderful start in their first North American main event, but without a better low-boost offense or new ways to balance their own boost usage, teams that scout them well could knock the European transplants down a peg.

See my workflow on my [GitHub](https://github.com/mod-gg/rl/blob/main/rl/geng-faze-fall-open.py)