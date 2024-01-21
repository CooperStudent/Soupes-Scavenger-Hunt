This is my game is Soupé's Scavenger Hunt!  You play as a sentient soup golem on a hunt for ingredients for his next batch of soup.  This character is from my current DND campaign, which Soupé is one of our companions.

The player uses basic WASD controls to move the character from a top down POV.  Your goal for the game is to collect 3 ingredients , in under 10 seconds to win the game.  The timer is an important aspect of the game, if the timer hits zero you lose. There are chickens patroling some areas that are your enemies, if they touch you, you lose!

For the basic requirements, here is a drop down list of all of the basic parts of this project and how I achieved them within this games creation...

BASIC REQUIREMENTS


	My game is played in Unity 2D from a top-down POV. You are the only player in the game. The controls are displayed right before the game starts, you can move with WASD.The game has a 2 second delay before the game starts, the gameplay timer is exactly 10 seconds, and there is a 2 second delay after the game ends before it brings you back to the main menu. In the 2 second delay before the game starts, a text box with very simple instructions appears as well as a audio clip of someone telling you to "Get ready". The clear win state of the game is the only objective, to collect 3 ingredients before the time expires.  There are two loss states, the timer reaching 0 or getting hit by an enemy. After you win or lose, an endgame display is shown telling you if you win or if you lost, after 2 seconds you are brought back to the main menu. I have never actually worked in Unity 2D until this point, I have only done the tutorials in Unity 3D, so I created myown simple fun idea to do for 2D gameplay and didnt take any inspiration from the tutorials in any way that I am aware of.

AUDIO REQUIREMENTS

After the two second delay is over, the minigame music begins.  I found fun, fast paced, retro sounding music on a royalty free site online.  It immediately starts when you can move and ends when a endgame state happens, helping the player understand when they can play. During the 2 second delay at the start of the game, the player hears a "Get Ready" voiceline, preparing them for the start of the game. When you collect your third item, a high pitched reward noise plays, but if you run out of time or get hit by an enemy, a lower pitch loss sound plays. When the player picks up any collectible on the map, a bubble popping kind of noise plays. This sound has a fun cartoony effect, represents picking up well, and matches the aesthetic of the game.

VISUAL REQUIREMENTS

I created my own tilemap for the game, that is a very simple grassy flower filled field.  I made 3 seperate but similar tiles in Asesprite and used them alternating to create a good but simple background. I also created the player character sprite, Soupé, in Aseprite.  I am not the best 2D artist so I felt pixel art would look the best, I modeled him with my DND friends feedback in mind and he turned out just like we wanted. I created a very simple 2d particle effect for all of the collectibles to have, they are very little stars created in Aseprite. As for UI in the game, the timer text gameplay information is the most important UI aspect as it counts down from 10 until the player loses or collects enough items to win.