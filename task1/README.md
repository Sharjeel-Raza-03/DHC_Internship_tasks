# DevelopersHub AI/ML Engineering Internship

## Task 1: Exploring and Visualizing a Simple Dataset

### Objective

The objective of this task is to learn how to load, inspect, summarize, and visualize a simple dataset in order to understand data trends, feature distributions, and relationships between variables.

For this task, the Iris dataset is used. It is a popular beginner-friendly dataset in machine learning and data analysis.

---

## Dataset

### Dataset Name

Iris Dataset

### Dataset Source

The dataset can be loaded directly using the Seaborn library.

### Dataset Description

The Iris dataset contains measurements of iris flowers from three different species:

- Setosa
- Versicolor
- Virginica

The dataset includes the following columns:

- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species`

---

## Tools and Libraries Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## Steps Performed

### 1. Imported Required Libraries

The required Python libraries were imported for data analysis and visualization.

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

### 2. Loaded the Dataset

The Iris dataset was loaded using Seaborn.

```python
df = sns.load_dataset("iris")
```

### 3. Inspected the Dataset

The dataset was inspected using:

```python
df.shape
df.columns
df.head()
df.info()
df.describe()
```

These commands helped understand:

- Number of rows and columns
- Column names
- First few records
- Data types
- Summary statistics

### 4. Checked Missing Values

Missing values were checked using:

```python
df.isnull().sum()
```

### 5. Visualized the Dataset

Different visualizations were created to understand the dataset better.

#### Scatter Plots

Scatter plots were used to study relationships between features such as:

- Sepal length vs sepal width
- Petal length vs petal width

#### Histograms

Histograms were used to understand the distribution of numerical features.

#### Box Plots

Box plots were used to identify spread, median values, and possible outliers.

#### Pair Plot

A pair plot was used to visualize relationships between all numerical features.

#### Correlation Heatmap

A heatmap was used to understand correlations between numerical features.

---

## Key Findings

- The Iris dataset contains 150 rows and 5 columns.
- There are four numerical columns and one categorical column.
- The dataset has three flower species: Setosa, Versicolor, and Virginica.
- Petal length and petal width are useful features for separating the species.
- Setosa is visually easier to separate from the other two species.
- Box plots show the spread of feature values and help detect possible outliers.
- Histograms show how feature values are distributed across the dataset.
