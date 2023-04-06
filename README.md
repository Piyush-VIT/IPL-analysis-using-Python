# IPL-analysis-using-Python
Data Analysis in Python
This project demonstrates how to get started with Data Analysis in Python using the following packages:

- numpy
- pandas
- matplotlib
- seaborn

The dataset used for this project is the IPL (Indian Premier League) Dataset, sourced from cricsheet and posted on Kaggle Datasets.

# Questions
In this notebook, we will attempt to answer the following questions:

- How many matches are in the dataset?
- How many seasons are in the dataset?
- Which team won by the maximum runs?
- Which team won by the maximum wicket?
- Which team won by the closest margin (minimum runs)?
- Which team won by the minimum wicket?
- Which season had the most number of matches?
- Which IPL team is more successful?
- Has toss-winning helped in winning matches?
# Required Packages
We will be using the following Python packages in this project:
```
import numpy as np # numerical computing 
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
import matplotlib.pyplot as plt #visualization
import seaborn as sns #modern visualization
```
- We will also be using the darkgrid style for Seaborn plots and setting the figure size to (14, 8).

```
sns.set_style("darkgrid")
plt.rcParams['figure.figsize'] = (14, 8)
```
# Reading the dataset

- We will read the dataset from the matches.csv file using Pandas and then display the dimensions of the dataset and the first five rows.
```
matches = pd.read_csv('D:\IPL analysis in jupyter (project)\data_analysis\matches.csv')
print(matches.shape)  # dimensions of the dataset
matches.head()
```
- We will also display the summary statistics of the dataset using describe() and the column information using info().
```
matches.describe()
matches.info()
```
Note: The file path used in this project is an example and may need to be modified to reflect the actual file path on your machine.
