# image_segmentation
We conducted an experiment with wheat, whose purpose was to characterize the root architecture of different wheat lines. 
After dismantling the experiment, we were left with images of the soil blocks (formerly wheat roots growing in pots) which I analyze in the code in front of you. 
Some technical details - we took 8 photos from 8 angles for each pot, when there are 8 pots for each genotype. 
The code goes through and associates each image with a genotype in an Excel table, performs segmentation automatically on all images so that a mask remains with only root pixels, which we count in different ways and perform a statistical analysis to characterize the root architecture.
In addition, I added a code that we used in order to check the angel of primary roots in wheat.
