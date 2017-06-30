# FAST-ChainViewer

Use this graphical utility to visualize the unsupervised output of our Fast Automated Spike Tracker [FAST](https://github.com/Olveczky-Lab/FAST) spike-sorting algorithm. Using a combination of automatic and manual procedures, you can interactively merge spike 'chains' that should belong to the same cluster as well as split chains corresponding to two or more incorrectly merged units.


## Installation

- You will need a computer running Matlab 2016a or later. 

- Depending on the size of your datasets, you may require a decent amount of memory and a desktop graphics card. For loading 3 month long tetrode recordings, we require at least 32 GB RAM. An SSD is also helpful to speed up loading/saving data to disk.

- In order to split clusters that have been incorrectly merged by the automatic steps of FAST, we suggest downloading the spike-sorting software, [MClust](http://redishlab.neuroscience.umn.edu/MClust/MClust.html) (A. D. Redish et al). We have provided a loading engine **ChainSplitter_LE.m** that should be placed in the MClust Loading Engines folder - this will let you load the *\*.s* files generated by ChainViewer (see Instructions below for more details). Make sure that MClust saves time-stamps of the final clusters with 64 bit precision.


## Automatic Step





## GUI

