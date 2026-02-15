This repository will have many assets I will make during my life, The first here is a skybox that has an "Elden Ring" look alike
skybox, but no volumetric clouds yet.

HOW TO USE THIS:
(1) import into unity by dragging into project
(2) open the shader graph called "Cloudy Sky" or something close to that
(3) there will be a gradient that is changeable, this is the sky colour.
(4) find a color that you want and save.
(5) open "Windows", "Rendering", "Lighting" and then go to environment and drag the material into the skybox. there you go!

(EXTRA) there is another shader graph group, use that to get a cool effects that almost looks like northern lights.
(EXTRA) There is a problem though, but easy fix, just add a node called "safe normalizer" and drag the output into the input where the
(EXTRA) divide node has the top input. There is a note close to it :]