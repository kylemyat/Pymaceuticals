# Pymaceuticals

---
### Purpose
Analyze results of a study conducted on mice comparing the performance of various drugs on tumor growth.

### Description
Laguage used: Python
I imported data of mice identification from the Mouse_metadata.csv and data of study results from Study_results.csv.

I then merge the imported data into a single dataframe and clean the data using loc and iloc before finding the summary statistics.

### Analysis

When comparing Capomulin, Ramicane, Infubinol, and Ceftamin based on Final Tumor Volume, Ramicane seems to be the most effective treatment as it holds the lowest lower quartile of 31.57. Capomulin has very close effectiveness to Ramicane and may be slightly more consistent as it hold a smaller interquartile range by roughly 1.2.

The results of treatment using Capomulin and Ramicane are the most accurate of the 10 treatment methods as they hold the lowest standard error of the mean. A factor that may contribute to this could be the higher number of observed mouse timepoints compared to the other forms of treatment.

Ketapril had the least accurate results as it holds the highest variation, standard deviation, and standard error of the mean when analyzing average tumor volume.
