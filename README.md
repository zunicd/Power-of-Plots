# Power-of-Plots

### Objective

What good is data without a good plot to tell the story?

The fictional pharmaceutical company Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In its animal study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

In addition to a top-level summary of the study results, we are going to generate all the calculations, tables and figures needed for the technical report of the study:

-  A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM (standard error of the mean) of the tumor volume for each drug regimen.

- A bar plot  that shows the number of data points for each treatment regimen.

  **NOTE:** Two identical plots were generated, using both, Pandas' `.plot()` and Matplotlib's `pyplot`.

- A pie plot that shows the distribution of female or male mice in the study.

  **NOTE:** Two identical plots were generated, using both, Pandas' `.plot()` and Matplotlib's `pyplot`.

- Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

- A box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the 

- A line plot of time point versus tumor volume for a single mouse treated with Capomulin.

- A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

- Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

### Tools / Techniques Used:

- Python

- Pandas

- Matplotlib

- SciPy
- Jupyter Notebook



### About Data

 Two datasets have been provided for this project. 

1. <u>***data/Mouse_metadata.csv***</u> contains mice information:

-  **Number of records:**      249
- **Columns**:
  -  Mouse ID
  - Drug Regimen
  - Sex
  - Age_months
  - Weight (g)

2. <u>***data/Study_results.csv***</u> contains study results:

-  **Number of records:**      1893

- **Columns**:
  - Mouse ID
  - Timepoint
  - Tumor Volume (mm3)
  - Metastatic Sites