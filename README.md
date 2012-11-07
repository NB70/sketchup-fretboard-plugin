#sketchup-fretboard-plugin

![Fretboard generated in Sketchup using this plugin](http://www.guitar-list.com/sites/default/files/styles/article-pic/public/gearpics/fretboard.JPG)

A Sketchup plugin to automatically generate a conical tapered guitar fingerboard. The fret slots are not flat bottomed, but follow the radius of curvature of the fingerboard. In theory this should stop the frets from compressing the fingerboard by being hammered in too far.

##Installation
Download the latest version from http://www.guitar-list.com/download-software/conical-tapered-fretboard-plugin

Save the fretboard.rb file to your Sketchup plugins folder. If you have installed Sketchup on the C: drive then this folder will be at C:\program files\google\google sketchup 7\plugins. 

##Usage
After copying this file you should now a menu options in the Sketchup Draw menu to draw a fingerboard.

The script uses a number of parameters which you can change to your needs:

1. Scale length: the distance from the nut to the bridge.
2. Width at nut: the width of the fretboard at the nut end.
3. Radius at nut: the radius of curvature of the fretboard at the nut end.
4. Width at body: the width of the fretboard at the body end.
5. Radius at body: the radius of curvature of the fretboard at the body end (usually larger than the radius at nut in a conical fingerboard).
6. Board thickness at the nut: the thickness of the fretboard at its thickest point at the nut end.
7. Board thickness at the body: the thickness of the fretboard at its thickest point at the body end.
8. Number of frets: the number of frets required, this will affect the length of the fretboard.
9. Depth of fret-cut: how deep the fret slots cut into the fretboard
10. Width of fret-cut: width of the fret slots.
11. Width of the nut-slot
12. Depth of the nut-slot

The default values are for a Fender strat style fingerboard.The script creates a flat bottomed nut slot (like in Fender style fingerboards). To omit the nut slot set the width of nut slot parameter to zero.

You can also have the fret positions marked by single lines (perhaps more useful for a CAM program). 
To see only the fret-cut locations go to the "Window" menu of Sketchup select Layers an make sure only the "Fret_lines" layer is visible.
 
Also construction points are added in the common inlay positions to help you line up your inlays. Draw your inlay (a 2D face) then select the center and drag it to the construction point - using Sketchup's move tool.
