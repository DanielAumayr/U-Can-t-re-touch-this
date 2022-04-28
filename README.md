# U-Can-t-re-touch-this
Data set of the paper U-Can't (re)touch this – A Deep Learning
Approach for Detecting Image Retouching from Daniela Aumayr and Pascal Schöttle.

## Data set

First, we used scikit-image (skimage) to crop the original images from RAISE to a square format, resize them to 256x256 pixel and then save them in JPEG format with quality factor 100.
Since Snapseed is a mobile application, the Android emulator Bluestacks is used to edit the photos with Snapseed. In Snapseed, we processed the 1 000 images with nine different filters, creating a data set of 10 000 images in total.

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
