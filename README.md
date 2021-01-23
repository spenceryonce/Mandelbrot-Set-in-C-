# Mandelbrot-Set-in-C++

## What it does
This app creates a mandelbrot set in the form of a .ppm file. At the moment, you can define the height and width of the image you would like to produce. Be careful
running anything that is above 1500 x 1500 as ppm files tend to be quite long. For instance, to find the total number of lines within a ppm file, you can take the height and width and multiply
them and then add 3. That is the total number of lines required for the file. I tried to make a 4000 x 4000 image, and it took quite some time, considering that there were 
16,000,003 lines haha. 

## Goals
1. To be able to zoom into the mandelbrot set, as well as display a rainbow of color depending on the iteration depth.
2. To be able to produce a live viewer that you can fly around in and in realtime update the iteration depth and rerender the scene in front of you.

## How to Use
1. Use your favorite c++ compiler to compile and run the mandelbrot.cpp file.
2. You should see a new file with the extension .ppm. That is the mandelbrot image. To view this image, open in Gimp, or there are tons of online viewers for PPM files. 


Hope you enjoy!
