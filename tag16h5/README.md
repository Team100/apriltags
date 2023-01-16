To generate these files:

Download the [AprilRobotics png files](https://github.com/AprilRobotics/apriltag-imgs/tree/master/tag16h5).
These are tiny, 8x8 pixels.

Magnify them: mogrify -scale 7500% \*png .. this yields 600x600 images.

Print to pdf using default scaling, which seems to be 100 DPI.  I just did this one at a time since there aren't very many.

Then print the files: lp \*pdf
