sketchup-fretboard-plugin
=========================

A Sketchup plugin to automatically generate a conical tapered guitar fingerboard. The fret slots are not flat bottomed, but follow the radius of curvature of the fingerboard. In theory this should stop the frets from compressing the fingerboard by being hammered in too far.

##Installation
Download the latest version from http://www.guitar-list.com/download-software/conical-tapered-fretboard-plugin

Save the fretboard.rb file to your Sketchup plugins folder. If you have installed Sketchup on the C: drive then this folder will be at C:\program files\google\google sketchup 7\plugins. 

##Usage
After copying this file you should now a menu options in the Sketchup Draw menu to draw a fingerboard.

The script uses a number of parameters which you can change to your needs:

        Scale length: the distance from the nut to the bridge.
        Width at nut: the width of the fretboard at the nut end.
        Radius at nut: the radius of curvature of the fretboard at the nut end.
        Width at body: the width of the fretboard at the body end (usually wider than at the nut end in a tapered fingerboard).
        Radius at body: the radius of curvature of the fretboard at the body end (usually larger than the radius at nut in a conical fingerboard).
        Board thickness: the thickness of the fretboard at its thickest point.
        Number of frets: the number of frets required, this will affect the length of the fretboard.
        Depth of fret-cut: how deep the fret slots cut into the fretboard
        Width of fret-cut: width of the fret slots.
        Width of the nut-slot
        Depth of the nut-slot


The default values are for a Fender strat style fingerboard.The script creates a flat bottomed nut slot (like in Fender style fingerboards). To omit the nut slot set the width of nut slot parameter to zero.

You can also have the fret positions marked by single lines (perhaps more useful for a CAM program). Set the width of the fret-cut to zero. To see only the fret-cut locations go to the "Window" menu of Sketchup select Layers an make sure only the "Fret_slot" layer is visible. 
