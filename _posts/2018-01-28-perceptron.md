---
title: "Linear Regression"
date: 2019-12-10
tags: [data wrangling, data science, messy data]
header:
  image: "/images/perceptron/percept.jpg"
excerpt: "Data Science, Machine Learning, AI"
mathjax: "true"
---



An [Exploratory Data Analysis](https://github.com/FTANKRA/Foster-Twumasi-Ankra) on South Africa Crime Statistics data.

In this project, basic python operations and EDAs were used. Some of these operations are outlined below.

<<<<<<< HEAD
**Joining datasets.**
=======
1. Joining datasets.
>>>>>>> 1f76d9f6ec46d8772c15749cb6100bd90979395a

```python
    Complete_Data=SA_Crime_Data.merge(Population_Data, on='Province')
```


<<<<<<< HEAD
**Summary statistics.**
=======
2. Summary statistics.
>>>>>>> 1f76d9f6ec46d8772c15749cb6100bd90979395a

```python
    Complete_Data.describe(include='all')
```

<<<<<<< HEAD
**Grouping data by variables.**
=======
3. Grouping data by variables.
>>>>>>> 1f76d9f6ec46d8772c15749cb6100bd90979395a

```python
    Province_Grouped=Complete_Data.groupby(['Province']).sum()
```

<<<<<<< HEAD
**Ranking observations in the data.**
=======
4. Ranking observations in the data.
>>>>>>> 1f76d9f6ec46d8772c15749cb6100bd90979395a

```python
    Crime_Mean.rank(ascending=0)
```

<<<<<<< HEAD
**Data Visualization(Histogram,Bar Chart, Time Series plot, Boxplot, etc).**
=======
5. Data Visualization(Histogram,Bar Chart, Time Series plot, Boxplot, etc).
>>>>>>> 1f76d9f6ec46d8772c15749cb6100bd90979395a

```python
    Complete_Data.boxplot(column=['Murder'])
```

<<<<<<< HEAD
**Correlations.**
=======
6. Correlations.
>>>>>>> 1f76d9f6ec46d8772c15749cb6100bd90979395a

```python
    Complete_Data.corr()
```
