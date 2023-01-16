to generate these files:

* follow the directions [here to make tiny PNGs](https://github.com/AprilRobotics/apriltag-generation)
* follow the directions [here to make PDFs](https://github.com/rgov/apriltag-pdfs)

I ended up with this command line for the pdf conversion:

convert tag21_07_00000.png -density 300 -scale 26246% -gravity center -extent 2550x3300 -gravity south -annotate +0+75 'Circle21h7 200mm id=0'  tag21_07_00000_big.pdf
