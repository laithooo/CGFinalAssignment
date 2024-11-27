# CGFinalAssignment
Youtube presentation link: https://youtu.be/3q5YVazkTvQ

The textures are also all able to be toggled off and on using "F1" keys.

Improvements:
Add new entire level for the game (Radio Tower Level/base of the enemies) to demonstrate what we have learned in the CG course 
Add new enemies with new purposes: robots that stand still but start moving once you get too close to add diversity in enemies
Working doors that take you to next level
Windows/Glass
Glowing Lanterns/glowing textures in the 2nd level
Replaced default skybox with dark texture with stars to simulate night time to add a feel of stealth
Added a transparent texture to an existing ghost enemy to simulate ghost transparency and catch them off-guard

Textures:
Since I am only one person, I made sure at least 50% of the scene used textures by giving textures to every environment block, only majority of enemies do not use textures due to limited time constraints. 
Most textures were made using Krita besides the ones I am referencing below.
I used a website called https://cpetry.github.io/NormalMap-Online/ in order to generate normal mapping for the textures I have made. All textures also have a uv slider.
Demonstrating how textures were made were all explained in the YouTube video along with the slides

Visual Effects:
Individual: 2 additional effects which are Glass and Particle Enhancement with shaders
Glass: was used to implement an element of realism and to also allow the player to see what awaits them around the corner and to prepare themselves to kill the upcoming enemy. Used regular texture while generating normal mapping alongside a transparency scale achieved using o.Alpha after o.Albedo in the void surf function to achieve the transparency scale
Particle enhancement with shaders: Glowing lantern + Moon effect used in the first and second levels. Glowing lantern and moon were achieved using texture + normal map but added a "Glow Color" as well as a "Glow intensity" in order to set how much the texture should emmit light.

All works (videos/gifs) have been shown in the video shown above




References:

Metal texture reference for the walls to also somewhat simulate metal walls that has a normal map that can be used to adjust the _Metallic scale.
https://www.vecteezy.com/photo/3096868-dark-concrete-texture-wall-background-black-grunge-cement-wall
Glass texture reference to simulate realistic glass textures and to also have a normal map that can emulate transparency effectively
https://3dtextures.me/2020/08/27/glass-frosted-001/
Leaves Texture reference for the tree leaves because drawing and emulating realistic leaves is going to be hard, and generating a normal would not be accurate either. So this reference solves both of these issues.
https://libreshot.com/green-leaves-texture/
