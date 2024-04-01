Image to Sketch Converter

This Python script converts a regular image into a sketch-like representation using OpenCV. 
The resulting sketch gives a hand-drawn effect to the input image.

How It Works

The script loads the input image.
Converts the image to grayscale.
Inverts the colors of the grayscale image.
Applies Gaussian blur to the inverted grayscale image.
Inverts the blurred image again.
Divides the original grayscale image by the inverted blurred image to create a sketch-like effect.
Saves the resulting sketch as "sketch.png".
