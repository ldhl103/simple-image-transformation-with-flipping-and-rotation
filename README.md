# simple-image-transformation-with-flipping-and-rotation

![Imgur](https://i.imgur.com/vg4TaJO.jpg)
This repository inspired by : [labelImg](https://github.com/tzutalin/labelImg)


### Introduction

Collecting more source images as much as possible is better for deep learning. However, we may not easily to collect thousands of images by ourselves.

If you only have a little images, you can use this repository to turn your every image into 8 results(include upside down and rotate). It is suitable for some simple training test in deep learning.

### prerequisite

1. TensorFlow[(see installation here)](https://www.tensorflow.org/install/pip)
2. Python 3


### How to use

1. your source data should be put in the ./source_images, and you need:
 (1) your source image
 (2) your xml file corrosponding to your source image (generated by [labelImg](https://github.com/tzutalin/labelImg))
 
2. execute the program:
    python3 image_trasfer.py

then you can check your ./destination_images generated the files including rotated and flipped images.



