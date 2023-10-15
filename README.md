# FreeCAD Electrical Components
Not quite sure if this will even end up being more than one component but I figured I'd make the repository name future proof.

I plan on making a keyboard and figured I'd give the Rose Lighting HD108-RGB5050 LEDs a go. They seem to be more or less the same as APA102 - but better.
So this 3D model probably works fine for APA102 as well as they look most identical as well. I think I got all the dimensions according to the spec sheet found here:

https://www.rose-lighting.com/wp-content/uploads/sites/53/2022/07/HD108-Specificaion-V1.2.pdf
![](https://i.imgur.com/rAmFSNO.png)

The little 'triangle' notch isn't mentioned in the spec sheet as to how big or deep it is - so I made a guess.
# Files

* The .FCStd file is to be used with FreeCAD
* The .step file is a colored file with the dimensions in millimeters and imports just fine in KiCAD. If you want to 'reverse' mount the LED, setting the Z-offset to 2.17mm whilst importing the file seems to work rather nicely.

## Unlicense(d)
Feel free to do whatever you want the files found here.
I didn't want the hassle of figuring out who needs credits to use a 3D-model so I made my own. 
