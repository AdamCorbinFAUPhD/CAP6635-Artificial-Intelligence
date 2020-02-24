# StarCraft & Real-Time Al
This post is a short summary of some StarCraft AI from the book *How Smart Machines Think* 2018 and the recent article *How AlphaStar Became a StarCraft Grandmaster 2020*

## Background of StarCraft & Esports

StarCraft is an extremally popular game that was released in 1998 with more than 10 million copies. There are about 4.5 million from Korea where they the first to start to play competitively. In todays day we call this Esports which has grown exponentially over the past few years. One of the most popular player is Ninja who plays FortNite. There are even professional Esports teams where people will work together or train for competitions.

StarCraft is a real time strategy futuristic war game where the player build armies and control them to destroy the other players army. Its similar to Chess in the fact there are different types of players/pieces with strengths and weaknesses. StarCraft is not a turn based game, but more of a each player can play any actions when ever they want. Each time gathers supplies to advance and build up their army to try to take on the other players army.

# AI early on

It was interesting that early AI that was developed for the StarCraft bots had some human built-in strategies which were basically hard-coded. Maybe bots today start with this format as well.  Eventually they will do some simulations around those strategies to come up with optimized strategies. Without going into the technical details I couldn't really tell if they actually had some kind of intelligence and learning over time or they just continued to refine their strategies manually.

# AlphaStar 2020

Since the time of the book publishing there were 3 different larger competitors Xelnaga bot, AIUR bot, and Skynet bot. They were ranked as the level of a beginners. Fast-forward to today, AlphaStar has really ramped up their system and has reached Grandmaster level

## Technical
AlphaStar is a combination of multiple deep neural network Agents that work together to come up with its actions. They are trained by using a Deep Learning technique where there are large datasets of actual players actions data. Once it has been trained it can easily defeat Blizzards built in AI. From there AlphaStar plays against it self to then find more optimal solutions. Over time each of the agents will get better but there could end up being a triangle defeat where A beats B, B beats C, and C beats A.

DeepMind has come up with a way to split their ages into Main Agents and Exploiters. The Main Agents are used to try to be the best StarCraft players where as the Exploiters main job is to find the weaknesses for the Main Agents. From this perspective if you join forces the Main Agent could learn to defend from the Exploiter agents


## Defeating the players
There was a competition 2019 where 2 top players played AlphaStar in 5 1v1 games. AlphaStar easily defeated the players which had been the first time that a StarCraft AI had beaten top notch players. Some interesting things were the players did not play the same agent twice so the players couldn't use any weaknesses that they might have found from the previous matches. They also only could play on a single map since that was only what the agents were trained on.

## Hard core training

After the small competition AlphaStar created 3 different sets of agents. Supervised, Mid, and Final. Supervised was just from a large dataset, Mid was trained for 27 days, and Final which was trained for 44 days. They all performed well but the Final agent was the icing on the cake. DeepMind worked with Blizzard to add their agents to the servers to be able to play real people. After playing for about 60-90 games the Final agent earned the Grandmaster rank and ranked top 99.85% from the 90,000 players on the server.

Ranking image:
![Ranking image](https://lh3.googleusercontent.com/LEEKJoCvXdQlZhIjUDDaDyLtcBVQPHooKYcQVNZMLz1XGpaP99F6WBXVcQOr2eRXTikUNQiX6z78kHn5zuVVWQHD4C8ce0c1tsDm_o8=w1440-rw-v1)



# Further research

The articles and the book didn't dive too deeply into the technicality of how the AI was set up and evaluated. I did find that the articles referenced a paper published by DeepMind that looks to be a great start for more thorough research. Link to paper:
[Grandmaster level in StarCraft II using multi-agent reinforcement learning (Nature October 2019 Paper)](https://www.nature.com/articles/s41586-019-1724-z.epdf?author_access_token=lZH3nqPYtWJXfDA10W0CNNRgN0jAjWel9jnR3ZoTv0PSZcPzJFGNAZhOlk4deBCKzKm70KfinloafEF1bCCXL6IIHHgKaDkaTkBcTEv7aT-wqDoG1VeO9-wO3GEoAMF9bAOt7mJ0RWQnRVMbyfgH9A%3D%3D)

Sources:
1. [How AlphaStar Became a StarCraft Grandmaster](https://gamasutra.com/blogs/TommyThompson/20200213/358051/How_AlphaStar_Became_a_StarCraft_Grandmaster.php)

2. How Smart Machines Think-The MIT Press (2018) ISBN 9780262038409

3. [AlphaStar: Mastering the Real-Time Strategy Game StarCraft II](https://deepmind.com/blog/article/alphastar-mastering-real-time-strategy-game-starcraft-ii)
