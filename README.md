# On Board Apollo 11
## Description and objectives
This project was made for the class _Réalité virtuelle et augmentée_ given by Isaac Pante at UNIL.

The objective was to create a VR scene using the A-Frame framework.

This project uses a 3D scan of the interior of the Apollo 11 command module and the audio of the nasa radio to immerse the users in the Apollo 11.
To add some interactivity, the users can click on the radio, to play music or on the right joystick to change the orbit distance of the module.

The module and the moon are at 10'000th of their real scale.
![Little demo](https://github.com/Squidez/VR-project/blob/main/assets/readme/demo.gif)
## Installation requirements
The website is live at https://squidez.github.io/Apollo-11-VR/ or you can clone the project and excecute _index.html_.
 
## Package
This project uses the A-Frame package: https://aframe.io/

## Ressources
All the used ressources are licensed under Creative Commons Attribution.

**Models:**
* Command Module, Apollo 11: https://3d.si.edu/object/3d/command-module-apollo-11:d8c63e8a-4ebc-11ea-b77f-2e728ce88125
* Stylized Cassette Player by Nahuel Ivan Alvarez: https://sketchfab.com/3d-models/stylized-cassette-player-df662fdc2e6943b8bedc797b1134fceb

**Textures**
* Moon texture: https://svs.gsfc.nasa.gov/4720

**Musics and audio**
* Apollo 11 - Day 3: https://www.nasa.gov/content/apollo-11-audio-highlights
* Burning Trapezoid of Fire - Kevin Macleod
* Fake It Til You Fake It - Kevin Macleod
* Hold on a sec - Bryan Teoh
* The Celebrated Minue for Piano - Rafael Krux

## Issues

When entering the VR mode on smartphone, the camera changes its position and goes out of the command module. I think this is due to the fact that the position is overridden when entering VR mode. I tried to resolve the problem by changing the position of the entity "holding" the camera, when entering VR mode, but the problem persisted.
