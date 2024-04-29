# principles-of-data-analytics

This repository contains my project work for the Spring 2024 PRINCIPLES OF DATA ANALYTICS module at Atlantic Technological University. The project work itself is contained in the Jupyter notebook and the references are listed below.

## Table of Contents
- Introduction
- Imports
- Loading the dataset
- Examining the data
    - Examining the first penguin
    - Counting the species
    - Counting the population of each island
    - Counting the sexes
    - Describing the set
- Modelling the dataset
    - Types of variables
    - Plotting the species counts
    - Plotting the bill length
- Relationship between body mass and flipper length
- Conclusion

## Required software

The project is contained in a Jupyter notebook, so you'll need to install Python. I've used [Anaconda](https://www.anaconda.com/download) for this. You'll also need a notebook editor. I've used [Visual Studio Code](https://code.visualstudio.com/), but you can use whichever one you prefer. 

## References:
1. https://journal.r-project.org/articles/RJ-2022-020/RJ-2022-020.pdf (Horst et al, *Palmer Archipelago Penguins Data in the palmerpenguins R Package - An Alternative to Anderson’s Irises*)
1. *The species problem in Iris*, E. Anderson, 1936, *Annals of the Missouri Botanical Garden*, Volume 23, Issue 3, pages 457-469, 471-483, 485-501, 503-509 https://www.jstor.org/stable/2394164?origin=crossref%3Forigin%3Dcrossref&seq=1
1. https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0090081 (Gorman et al, *Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus Pygoscelis)*)
1. https://realpython.com/python-matplotlib-guide/#understanding-pltsubplots-notation (plotting in Matplotlib)
1. https://numpy.org/doc/stable/reference/generated/numpy.polyfit.html (use NumPy to fit a least squares polynomial)
1. https://numpy.org/doc/stable/reference/generated/numpy.corrcoef.html (use NumPy to calculate the correlation coefficient)
1. https://stackoverflow.com/questions/21827594/raise-linalgerrorsvd-did-not-converge-linalgerror-svd-did-not-converge-in-m#comment123702942_22523229 (how to remove NaN values to avoid "LinAlgError("SVD did not converge") LinAlgError: SVD did not converge" error)
1. https://stackoverflow.com/questions/51293196/attributeerror-numpy-ndarray-object-has-no-attribute-drop (NaN values need to be removed from a data frame before it's converted to a NumPy array, not after)
1. https://statistics.laerd.com/statistical-guides/pearson-correlation-coefficient-statistical-guide.php (what the correlation coefficient means)
1. https://stackoverflow.com/questions/16950074/valueerror-shape-mismatch-objects-cannot-be-broadcast-to-a-single-shape (both the x and y values need to be given as arrays to avoid "ValueError: shape mismatch: objects cannot be broadcast to a single shape" error)
1. https://matplotlib.org/stable/users/explain/axes/autoscale.html (adjusting the axis limits)
1. https://www.w3schools.com/python/matplotlib_bars.asp (plotting bar charts in Matplotlib)
1. https://www.w3schools.com/python/matplotlib_grid.asp (adding gridlines to plot)
1. https://matplotlib.org/stable/users/explain/quick_start.html#labelling-plots (adding text and labels to plots)
