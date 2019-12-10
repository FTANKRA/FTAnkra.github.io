---
title: "Linear Regression"
date: 2018-01-28
tags: [data wrangling, data science, messy data]
header:
  image: "/images/perceptron/percept.jpg"
excerpt: "Data Science, Machine Learning, AI"
mathjax: "true"
---

# H1 Heading

## H2 Heading

### H3 Heading

Here's some basic text.

And here's some *italics*

Here's some **bold** text.

What about a [link](https://github.com/dataoptimal)?

Here's a bulleted list:
* First item
+ Second item
- Third item

Here's a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
    import numpy as np

    def test_function(x, y):
      z = np.sum(x,y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

Here's some inline code `x+y`.

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg" alt="linearly separable data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg)

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$



##  [Project One](https://github.com/FTANKRA/Foster-Twumasi-Ankra)  
An Exploratory Data Analysis on South Africa Crime Statistics data.

In this project, basic python operations and EDAs were used. Some of these operations are outlined below.

1. Joining datasets.

```python
    Complete_Data=SA_Crime_Data.merge(Population_Data, on='Province')
```

2. Summary statistics.

```python
    Complete_Data.describe(include='all')
```

3. Grouping data by variables.

```python
    Province_Grouped=Complete_Data.groupby(['Province']).sum()
```

4. Ranking observations in the data.

```python
    Crime_Mean.rank(ascending=0)
```

5. Data Visualization(Histogram,Bar Chart, Time Series plot, Boxplot, etc).

```python
    Complete_Data.boxplot(column=['Murder'])
```

6. Correlations.

```python
    Complete_Data.corr()
```
