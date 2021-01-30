# Python for high schoolers
A brief intro to python course based on [this undergrad-level astronomy python minicourse](https://github.com/jbchampagne/pythontutorials), as well as a series of notebooks explaining filtering with Fourier transforms

Please note that these notebooks were built to be run via Google Colaboratory, but they work just fine with jupyter notebooks. You can download these and upload them to Colab and use as intended, or open with Jupyter and just change the import statements for the files used.

## Intro to Python course
This directory has a 3-day introduction to python course for high-school-level students (no prior coding assumed). The course is quite condensed, and some concepts may be too high level for some high schoolers (especially Day 3). Each day has interactive questions within the "lecture," so instructors should pause and let students work these problems individually or together as you go along. The solutions to these problems are in the "solutions" directory.

Days 1 and 2 were each taught in ~90 minute interactive sessions over zoom in August 2020. Day 3 was not taught, but given to students as optional extra content. The Exercises.ipynb file has some practice problems corresponding to each day, and Exercises_with_solutions.ipynb has the solutions to those.

## Filtering with Fourier transforms
This is a mini-course for students after they have completed at least Days 1 and 2 of the Intro to Python course above. The order of the modules is the following

1. Loading_and_displaying_images.ipynb
2. Fourier_transforms.ipynb
3. Filtering_with_Fourier_transforms.ipynb

The first module demonstrates how to load images in Google Colab and python, and how to plot 2d image data. The second module introduces the concept of Fourier transforms, and gives interactive examples of taking Fourier transforms of both 1D and 2D data. The final module shows how one can use Fourier space to remove certain signals from either 1D or 2D data.

Each module has exercises at the end, but no solutions are provided. Students were encouraged to experiment with these questions as mini research projects. The end product of the filtering method on the data is part of the analysis done in [this paper](https://doi.org/10.1109/TPS.2020.3020000) I published in 2020.
