This repository will have many assets I will make during my life, The first here is a skybox that has an "Elden Ring" look alike
skybox, but no volumetric clouds yet.

- CONTENT LIST -
HOW TO USE SHADERS:
* Skybox
* Ocean 1

HOW TO USE PLAYER MECH CODES:
* Surround detection & npc dialogue


------------- HOW TO USE SHADERS -------------

----- HOW TO USE SKYBOX -----
(1) import into unity by dragging into project
(2) open the shader graph called "Cloudy Sky" or something close to that
(3) there will be a gradient that is changeable, this is the sky color.
(4) find a color that you want and save.
(5) open "Windows", "Rendering", "Lighting" and then go to environment and drag the material into the skybox. there you go!


----- HOW TO USE OCEAN1 -----
(1) import into unity by dragging into project.
(2) find the material from the import that looks nothing like an ocean.
(3) Make a plane in unity by clicking "Create" -> 3D Object -> Plane. 
[Alternatively, make a plane in blender or other 3d program, and use this instead].
(4) Drag the ocean material onto the plane object.
(5) Click on the material to change different settings.

[EXTRA] The ocean 1 shader requires 2 ocean normal maps, you can make these yourself, or download from internett.



------------- HOW TO USE PLAYER MECH CODES -------------

----- HOW TO USE SURROUND DETECT AND DIALOGUE -----
(1) import into unity by dragging into project
(2) drag the dialogue script on the Desired object (NPC)
(3) in the inspector, write the text you want: press + to add more text
(4) add "surround detect" script to your player. The player needs a rigid body (inside this script there is an explanation on 
how to use this script when using a Character Controller as well)

(5) lastly, make a tag, and put the correct tag on your NPC :]

[EXTRA] you will need to make a UI, and have some "TextMeshPro" text, just drag those into the inspector slot on you player (Surround Detect script)