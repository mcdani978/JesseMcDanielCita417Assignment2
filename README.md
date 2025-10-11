# JesseMcDanielCita417Assignment2

Video Demo Link - https://www.youtube.com/watch?v=iOi1FoCMoYI 

For my FPS enemy, I made an AI that can see the player using Unreal’s AI Perception system. When the enemy sees me, it starts chasing me using the NavMesh so it can move around the map without getting stuck. The enemy has an idle state when it can’t see me, and it switches to chase mode when it does.

For the attack, I used a simple setup where if I get too close to the enemy (or a certain object), my health goes down. The health bar on the screen shows my health going lower when I get hit. I picked this way because it was the easiest to understand and it works well for showing damage.

My system has a health component for the player, an AI controller for the enemy, and a small arena to test everything in. The enemy doesn’t attack too fast, and I added simple debug text to help me see when it’s detecting or chasing me. Everything works together so it feels like a basic FPS enemy that sees, moves, and attacks.
