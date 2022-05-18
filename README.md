# Python crash-course for beginners
A brief intro to python course based on [this undergrad-level astronomy python minicourse](https://github.com/jbchampagne/pythontutorials), plus a supplementary series of notebooks explaining filtering with Fourier transforms

Please note that these notebooks were built to be run via Google Colaboratory, but they work just fine with jupyter notebooks. You can download these and upload them to Colab and use as intended, or open with Jupyter and just ignore the extra steps in the importing of files.

## Intro to Python course
This directory has a 3-day introduction to python course intended for high-school-level students (no prior coding assumed). The course is quite condensed, but provides basic working understanding of handling data in python. Each day has interactive questions within the "lecture," so instructors should pause and let students work these problems individually or together as you go along. The solutions to these problems are in the "solutions" directory.

2020:
---
Days 1 and 2 were each taught in ~90 minute interactive sessions over zoom in August 2020. Day 3 was not taught, but given to students as optional extra content.

2021
---
All three days were taught in-person and synchronously virtually, each in a 2 hour session.

Here is a summary of the sections included

### Day 1
* Importing packages
* Setting variables
* Variable types
* Python arithmetic
* Arrays: populating, indexing, manipulation and attributes

### Day 2
* If statements
* For loops
* User-defined functions
* Plotting basics

### Day 3
* Loading in data from files
* What is a Gaussian?
* Fitting a function to data
* Plotting 2D image data
* Taking 1D lineouts of 2D data

This version is probably going to be broken up into a 5-day series when it is taught again this summer.

## Filtering with Fourier transforms
This is a mini-course for students after they have completed at least Days 1 and 2 of the Intro to Python course above. The order of the modules is the following

1. Loading_and_displaying_images.ipynb
2. Fourier_transforms.ipynb
3. Filtering_with_Fourier_transforms.ipynb

The first module demonstrates how to load images in Google Colab and python, and how to plot 2d image data. The second module introduces the concept of Fourier transforms, and gives interactive examples of taking Fourier transforms of both 1D and 2D data. The third module shows how one can use Fourier space to remove certain signals from either 1D or 2D data.

Each module has exercises at the end, but no solutions are provided. Students were encouraged to experiment with these questions as mini research projects. The end product of the filtering method on the data is part of the analysis done in [this paper](https://doi.org/10.1109/TPS.2020.3020000) I published in 2020.

There is also the Fourier 1-day Lesson, which is basically a compilation of all three modules with more detail. This is aimed at an undergraduate level.

If you plan to use this or have any questions, let me know! I can be reached at hhasson@ur.rochester.edu.
