
<!-- README.md is generated from README.Rmd. Please edit that file -->
horst-package
=============

This is a collection of functions used by me and my colleagues in [Pschological Diagnostics](https://www.psychologie.hu-berlin.de/de/personal/91680294) at Humboldt-University of Berlin.

Until now, there are only very few functions and most of them are tailored to a specific problem, relying on input from specific functions from other packages (see respective help-pages).

Note: Dependencies need to be installed and loaded manually!

-   **corHist** A histogram of correlations on level-1 and level-2.
-   **omegaW** A function to compute Omega's W.
-   **simpsonCor** A plot that allows discovering the Simpsons Paradox.
-   **getTable** A function that produces a correlation table in Excel which is close enough to an APA correlation table for further editing.
-   **matchItems** Based on the `psych` package, this function adds items from a codebook to the result of an efa.
-   **plotMod** Plots an interaction on three dimensions, one being coloured dots.
-   **renameCodebook** Using a codebook (for example from excel), function changes names in a data set according to the codebook.
-   **findMis** finds missing data (or other entries that can be specified) in any given data set.
-   **vlookup** An immplementation of the VLOOKUP function from Excel.
-   **lmerSimple** A function to run lmer-models from character strings.
-   **lmerPlottt** A function to plot *t*-values of fixed effects from `lmer`-models
-   **tStats** A function to extract *t*-statistics (*t*, *df*, *p*) from a t.test to plot it, use it in word or latex.
-   **withinFun** Apply a function to each entry in a nested data frame, i. e. compute the mean of a measurement for each subject in a longitudinal study.
-   **nestedAlpha** A function to compute alpha for nested scales, for example in multilevel data.
-   **valid\_recode** Recodes values according to a predefined vector of elements into 1 and 0 (useful for recoding values of an knowledge test with open questions).

Installing the package:
-----------------------

Run the following code lines:

    install.packages("devtools")
    library(devtools)
    devtools::install_github("kthorstmann/horst")
