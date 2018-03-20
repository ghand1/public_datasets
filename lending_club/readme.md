## Lending Club Loan Data
For this notebook, I conduct some hypothesis testing and exploratory analysis on [loan data from the Lending Club](https://www.kaggle.com/wendykan/lending-club-loan-data). This is a large dataset with a number of features. Fortunately, the Kaggle user hosting this dataset offers a comprehensive dictionary of the features.
For this notebook, I reduce the number of observations and remove most of the features. There is a great deal that can be discovered from this dataset, but I chose to go to a more narrow path to conduct some hypothesis testing on features between loans that are in good status (paid off, on-time, etc.) vs. loans that are in bad status (default, late, etc).

Requirements:

* R Programming
* ggplot2
* e1071
* simpleboot
* MASS
* caret
* mlbench
* MLmetrics
