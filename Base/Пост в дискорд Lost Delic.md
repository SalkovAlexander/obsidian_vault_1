---
tags: []
alliaces: []
---
2022-10-23
01:14
***
###### Tags: #
***
# Пост в дискорд Lost Delic
***
Hi all, I'm AASalkov, a 3D modeler and @Fireks buddy
@Fireks said that if I wrote a post in this channel about creating 3D graphics for our gamejam project, it might be of interest to the community.
We only had 72 hours, and given our love of sleep, that time could be divided into two. The challenge before me was to make graphics that would harmoniously complement the gameplay of our project in such a short time. I decided that the action of the game will take place in space, the player will move between the houses, located on islands that fly in outer space.
![[Pasted image 20221023025014.png]]
I started creating graphics by modeling  houses
![[Pasted image 20221023012340.png]]
I started with primitives that repeated the shape of the house, then I made models of windows and doors and just copied them for the whole building, the roof consists and a lot of identical elements
![[Pasted image 20221023012610.png]] ![[Pasted image 20221023012630.png]]
At the modeling stage I broke all the geometry into material groups, so that later in Unity I could just assign different materials to different geometry groups and not bother with texturing, because we only have 72 hours! This principle was applied to all the models in the game.
 The glass in the windows was also made a separate geometry, so that you could just assign them a different material than the walls.
This is how the house looks like in Unity.
![[Pasted image 20221023025321.png]]
You can notice that the walls got a relief, I added it with a normal map which I plugged into the wall material
![[Pasted image 20221023013206.png]]
It was a good time saver!
Then I had to create something on which to stand houses - space islands. At first I tried to make them out of lots of separate pieces of geometry - rocks, and it turned out very bad, then I went the other way - to create a new geometry from the old one, and this is what came out
![[Pasted image 20221023014904.png]]
![[Pasted image 20221023015057.png]]
From this island I assembled 4 islands of different sizes. ![[Pasted image 20221023015125.png]]
We have houses, we have islands, but how can ordinary houses stand in outer space? They can't. So I decided to make special domes with houses inside them. End up with something like this![[Pasted image 20221023015416.png]]
The frame is a primitive socker ball, which I left only the ribs, the dome is a subdivided cube.
All this splendor together looks like this
![[Animation1.gif]]
in Unity
![[Pasted image 20221023015856.png]]
Something had to connect the islands, and the bridges were that something. Since we needed many bridges, and modelling each bridge separately is a silly thing to do, I decided to make several modules, from which a variety of different bridges would be assembled
![[Pasted image 20221023020217.png]]
![[Pasted image 20221023020243.png]]
From these blocks it was possible to make bridges of the necessary configurations for us
![[Pasted image 20221023020724.png]]
![[Pasted image 20221023021327.png]]
Then I made environment objects to somehow enliven the world
![[Pasted image 20221023020832.png]]
![[Pasted image 20221023021131.png]]
Because of my laziness, I only made 1 stone, so I had to come up with something
![[Pasted image 20221023021232.png]]
![[Pasted image 20221023021354.png]]
1 stone multiplied by many different transformations = many different stones)))
So what kind of game can exist without characters!?
Our game is about the postman, so I started with his creation.
![[Pasted image 20221023021512.png]]
![[Pasted image 20221023021523.png]]
The postman had to be animated, so I had to create a skeleton and assign weights
![[Pasted image 20221023021702.png]]
The creation of the animation
![[Animation2.gif]]
![[Pasted image 20221023024318.png]]
And the final version)
![[Animation3.gif]]
Kind of reminds me of hardbass
[https://www.youtube.com/watch?v=y90yaLFoYoA&ab_channel=Benz1209](https://www.youtube.com/watch?v=y90yaLFoYoA&ab_channel=Benz1209 "https://www.youtube.com/watch?v=y90yaLFoYoA&ab_channel=Benz1209")
![[Pasted image 20221023022113.png]]
![[Pasted image 20221023023013.png]]

So how can we do without enemies? We decided that the space mailman should be hunted by space dogs!
Beginning at
![[Pasted image 20221023022354.png]]
Unlike the island, the dog was easier to make from separate pieces of geometry, which were later combined into one large and complex piece
![[Pasted image 20221023022605.png]]
There was no time to do a running animation (actually I was lazy), so the dogs moved around with jet propulsion. 
And this is what our dog's sweaty workout , all to finally catch and eat the mailman!
![[Animation4.gif]]
![[Pasted image 20221023023144.png]]
Then, I am, a big fan of beautiful pictures, added post-processing effects
![[Pasted image 20221023023249.png]]
But my work at the jam didn't end there, I was responsible for keeping the @Fireks morale up! 
We don't plan to give up on the project, we're already fine-tuning it. I've just created a portal that will allow the poor mailman to teleport around the map
![[Pasted image 20221023030636.png]]
![[ezgif.com-gif-maker 1.gif]]

![[Pasted image 20221023024527.png]]


***
###### Zero-Links
-
***
###### Links
-