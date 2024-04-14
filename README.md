# principles-of-data-analytics

This repository contains my project work for the Spring 2024 PRINCIPLES OF DATA ANALYTICS module at Atlantic Technological University. The project work itself is contained in the Jupyter notebook and the references are listed below.

## Table of Contents
- Imports
- Load the dataset
- Examine the data
    - Examining the first penguin
    - Counting the sexes
    - Counting the species
    - Counting the population of each island
    - Describing the set
- Modeling the dataset
    - Types of variable
    - Plotting the species counts
- Correlation between body mass and flipper length

## Required software

The project is contained in a Jupyter notebook, so you'll need to install Python. I've used [Anaconda](https://www.anaconda.com/download) for this. You'll also need a notebook editor. I've used [Visual Studio Code](https://code.visualstudio.com/), but you can use whichever one you prefer. 

## References:
1. https://realpython.com/python-matplotlib-guide/#understanding-pltsubplots-notation (plotting in Matplotlib)
1. https://www.geeksforgeeks.org/how-to-plot-bar-graph-in-python-using-csv-file/ (plotting bar chart from a CSV file)
1. https://numpy.org/doc/stable/reference/generated/numpy.polyfit.html (use NumPy to fit a least squares polynomial)
1. https://numpy.org/doc/stable/reference/generated/numpy.corrcoef.html (use NumPy to calculate the correlation coefficient)
1. https://stackoverflow.com/questions/21827594/raise-linalgerrorsvd-did-not-converge-linalgerror-svd-did-not-converge-in-m#comment123702942_22523229 (how to remove NaN values to avoid "LinAlgError("SVD did not converge") LinAlgError: SVD did not converge" error)
1. https://stackoverflow.com/questions/51293196/attributeerror-numpy-ndarray-object-has-no-attribute-drop (NaN values need to be removed from a data frame before it's converted to a NumPy array, not after)
1. https://statistics.laerd.com/statistical-guides/pearson-correlation-coefficient-statistical-guide.php (what the correlation coefficient means)
1. https://stackoverflow.com/questions/16950074/valueerror-shape-mismatch-objects-cannot-be-broadcast-to-a-single-shape (both the x and y values need to be given as arrays to avoid "ValueError: shape mismatch: objects cannot be broadcast to a single shape" error)