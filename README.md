# BlenderACESLauncher

BlenderACESLauncher is a small applet that launches Blender with an OCIO override. BlenderACESLauncher is configured to pull an ACES config.ocio from RenderManProServer-24.3, but can easily be adapted to use a config.ocio from anywhere.

### Usage
If you already have RenderManProServer-24.3 and Blender installed in your Applications folder, opening `Blender with Aces.app` will launch Blender with the ACES OCIO override enabled.

### Customization
If you wish to modify the config you can manually edit paths in `main.scpt`, located in `Blender with Aces.app/Contents/Resources/Scripts`

> Hint: To access the inner workings of the .app to change configuration options, right click on the applet and chose `Show Package Contents`

### Support
Should you require support or encounter a bug, post an issue ticket or contact me on Discord at `thedude7054#0001`


**That's it!**