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


**Joining datasets.**

```python
    Complete_Data=SA_Crime_Data.merge(Population_Data, on='Province')
```



**Summary statistics.**

```python
    Complete_Data.describe(include='all')
```


**Grouping data by variables.**

```python
    Province_Grouped=Complete_Data.groupby(['Province']).sum()
```


**Ranking observations in the data.**

```python
    Crime_Mean.rank(ascending=0)
```


**Data Visualization(Histogram,Bar Chart, Time Series plot, Boxplot, etc).**

```python
    Complete_Data.boxplot(column=['Murder'])
```


**Correlations.**

```python
    Complete_Data.corr()
```
