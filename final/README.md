Angel Cromwell
GALACTIC GETAWAY


This game is an endless side-scrolling runner-type game.
Dodge asteroids and collect stars by moving with the SPACE(hehe) button, and try to go the farthest you can! The asteroids slowly get more intense as you go further into space

The first thing completed was creating the ship and coding the movement using gravity, velocity, and lift. Then it was on to the background stars. The setup I have continuously spawns randomly sized stars randomly on the y-axis at the width of the page. Then these stars move to the left at random speeds, making it look like the character is moving. This, along with the movement on the ship, gives the player the feeling they are flying the ship forward through the stars despite only moving up and down.

With the ship movement done, I started working on the collectable stars. These stars are drawn with the function drawStar and are spawned randomly on the y-axis. Unlike the asteroids that are made later, the stars do not have random speeds. I liked that the speed they are at makes them look like they are not moving, and the ship is the one moving towards them.

After the stars were done, I worked on creating and implementing the asteroids. It uses very similar code to the collectable stars, but it differs in the way that colliding with them ends the game. They also travel at different speeds, which makes them look like their shooting towards the ship. Another unique thing is that as the game time goes on, they spawn more frequently. I think this was one of the harder parts of this project.

At this point, the asteroids would end the game during a collision, but there was no way to restart. This is when I also added the star counter and distance counter that show up on the screen. Now the SPACE(hehe) button restarts the game, but also the end game screen shows your final amount of stars collected and distance travelled. For some reason trying to figure out the preGame menu was a little difficult. I was able to use some of the code from the endgame portion. But I kept running into the issue where the preGame menu would be fine and working, but if I left it running, eventually the game would end. This told me that although the asteroids were not being drawn, the code that dealt with spawning was still running. It turned out to just be a placement issue with the code. After moving the preGame code, it works just fine.

The final step was just making little tweaks with movement and spawning to make the game experience better and smoother.

I am pretty happy with the final product. Pretty early on, I realised that spawning enemy ships would probably be a bigger task than I could do given the time, but dodging asteroids was a good plan B, and I think the gameplay feels nice and immersive. Playing it myself, it really does feel like the ship is the one moving forward, which I am very proud of. If I were to work on this in the future, I would definitely try to figure out how to create a high score value that keeps your highest score. Maybe even do some sort of shop where you can buy asteroid lasers with the stars you collect, so they are not as useless. I do think the only issue with the gameplay currently is that the stars are pretty useless to collect.
