# U-Can-t-re-touch-this
Data set of the paper U-Can't (re)touch this – A Deep Learning
Approach for Detecting Image Retouching from Daniela Aumayr and Pascal Schöttle for [ICIAP2021](https://www.iciap2021.org/).

https://doi.org/10.1007/978-3-031-06430-2_11

## Data set

First, we used scikit-image (skimage) to crop the original images from [RAISE](http://loki.disi.unitn.it/RAISE/) to a square format, resize them to 256x256 pixel and then save them in JPEG format with quality factor 100.
Since Snapseed is a mobile application, the Android emulator [Bluestacks](https://www.bluestacks.com/de/index.html) is used to edit the photos with [Snapseed](https://snapseed.online/). In Snapseed, we processed the 1 000 images with nine different filters, creating a data set of 10 000 images in total.

The filters we used to create our retouched images (see Figure 1) are numbered as follows:

01 Original – original image

02 Smooth – blur

03 Pop – higher contrast

04 Accentuate – higher contrast and more intensive colours

05 Morning – bottom part of image has warm colouring

06 DramaDark – higher contrast, image will be darker

07 Vintage – Vintage Look, brown-filter

08 Retrolux8 – image gets a used look, like old pictures

09 Crunch3 – image gets a texture and dark vignette

10 Grain104 – grain is added to image
