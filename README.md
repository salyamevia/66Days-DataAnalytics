# 66Days-DataAnalytics

Sharing my journey of #66DaysOfData on learning data analytics!

| Index | Resouce                                                                   |
| ----- | ------------------------------------------------------------------------- |
| 1     | [Kaggle Intro to SQL](https://www.kaggle.com/learn/intro-to-sql)          |
| 2     | [Kaggle Advanced SQL](https://www.kaggle.com/learn/advanced-sql)          |
| 3     | [FreeCodeCamp Data Analysis](https://www.youtube.com/watch?v=r-uOLxNrNk8) |
| 4     | [FreeCodeCamp Tableau](https://www.youtube.com/watch?v=TPMlZxRRaBQ)       |
| 5     | [Tableau eLearning](https://elearning.tableau.com/)                       |

> **Day 1 of 66DaysOfData**

- **Big Query:** Using Google Cloud Big Query to understand the basics of data such as the table, fields, and how to list each item.
- **SQL:** Learned how to use `SELECT`, `FROM`, `WHERE`, `GROUP BY`, `HAVING`, `COUNT`, and `ORDER BY`. I noticed the similarity between `WHERE` and `HAVING`. The clause `WHERE` works on every row on the table whereas the clause `HAVING` works for aggregated data generated by `GROUP BY`.
- Resources:
  - [Kaggle Intro to SQL](https://www.kaggle.com/learn/intro-to-sql)

![Image](./images/day1.png)

> **Day 2 of 66DaysOfData**

- **SQL**: Learned how to use `WITH...AS`, `LIKE`, and `JOIN` functions.
- **Tableau**: Experimented with the application. Still working on to do the Explanatory Data Analysis (EDA) on Google Colab because I have prior experience with it.
- Resources:
  - [Kaggle Intro to SQL](https://www.kaggle.com/learn/intro-to-sql)

![Image](./images/day2-1.png)
![Image](./images/day2-2.png)
![Image](./images/day2-3.png)

> **Day 3 of 66DaysOfData**

- **SQL**: Learned how to use different types of `JOIN` functions and `UNION`. Both are quite similar in terms of usage, however the `JOIN` functions combine tables while `UNION` function combines queries.
- Resources:
  - [Kaggle Advanced SQL](https://www.kaggle.com/learn/advanced-sql)

![Image](./images/day3.png)

> **Day 4 of 66DaysOfData**

- **SQL**: Learned how to use SQL analytics functions such as `AVG`, `SUM`, `MAX`, and `MIN` with the help of the `OVER` function. There are more analytical navigation functions such as `LAG` and `LEAD` that will correspond to the before or after the entry within the table. There was also the `RANK` functions that gives a ranking to the table.
- Resources:
  - [Kaggle Advanced SQL](https://www.kaggle.com/learn/advanced-sql)

![Image](./images/day4.png)

> **Day 5 of 66Days of Data**

- **Data Literacy** is the ability to explore, understand, and communicate with data.

  When doing this process, it is important we ask good questions. Good questions are specific, narrow, and targetered. For example, "How are the health benefits for a dog owner compared to non dog owners in the US?" is considered a good question compared to "How beneficial is having a dog in our lifestyle?". Good questions come from several characteristics such as interest, curiosity, immagination, open mindness and flexibility, methodological, data analysis, and more.

  Ultimately, within data literacy, we try to work our processes with data, but what is "data"? Data is composed of facts that consists of qualitative or quantitative characteristics.

- **Well Structured Data** includes characteristics such as volume (contains a large amount of data for analysis), clarity (information and labels contained are clear and does not use unnecessary codes or uncommon acronyms), history (contains data that have a big time range), transparency (the source of the data is transparent to everyone), and consistency (data values and types are consistent throughout the dataset).

  Structually, each column within the data represents a type of an observations with values and different types should go to different columns.

  There are two ways to handle unstructured data, pivot and split. Pivot is to turn columns into rows and vice versa. While split is to split values from one column into two, and so on depending on the needs.

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)

![Image](./images/day5.png)

> **Day 6 of 66DaysOfData**

- **SQL**: Learned about REPEATED values and RECORD types in SQL schemas. Also, understanding how to extracted them with the `UNNEST` command. Ended the study with learning how to write efficient queries. Several ways to do this includes to filter the important fields before doing a join and to not use a 1:1 join.
- Resources:

  - [Kaggle Advanced SQL](https://www.kaggle.com/learn/advanced-sql)

  ![Image](./images/day6.png)

  > **Brief Break**

  I did a little break from this challenge, however during the time I learned how to use **Google Data Studio**. This is the first visualization I have made! _p.s. I am quite happy with it._

  ![Image](./images/gds.png)
  _This is just a preview and not the full viz._

  [Visualization Link](https://datastudio.google.com/reporting/062c342c-52ab-4c3d-b4a2-d1170fbe93bd)

> **Day 7 of 66DaysOfData**

- **Variable types** are split between <ins>qualitative</ins> and <ins>quantitative</ins>. Qualitative types are divided into two groups based on if they can be ranked or not, nominal (cannot be ranked) and ordinal (can be ranked) types. Examples of a nominal value is the names of a fruit while an ordinal value are the options for customer satisfaction survey (amusing or disappointing).

  When creation the visualization for these types, we can aggregate quantitative values (such as with average or sum).

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)

> **Day 8 of 66DaysOfData**

- **Aggregation** is a process of grouping data together. There are various ways to aggregate data, such as using the `average` or `mean`, `sum`, `median`, `count`, and even `maximum` or `minimum` values. The motivation for aggreation is when we want to look at multiple values as a singular group. For example we have the data of life expentancy for each gender and we want to see the life expentancy in general. To achieve this, we can aggregate the values.

- **Granularity** measures how detailed is the data. For example, aggregated data have a low granularity and vice versa. One of the motivation for having a high granularity is to better predict the correlation between features.

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)

> **Day 9 of 66DaysOfData**

- **Distributions** can be represented with visualizations. In doing so we need to divide it by the variable type, discrete or continuous values.

  Discrete values can be represented with a frequency and proportion table. Frequency is measuring the total amount of the category item, while proportion is measuring the amount of that category item to the total item count.

  Continuous values can be represented with histograms and box plots. With histograms, it uses bins to create a "range" within the values. While box plots uses percentiles to see the distribution and finding outliers.

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)

> **Day 10 of 66DaysOfData**

- **Variance** measures the spread of the data. While **standard deviation** is the square root of variance and measures the dispertion of the spread.
- We can use a **density curve** to check the continous distribution or to check _all_ possibble values. There's a special curve named the **normal distribution** that usually closely approximates the natural phenomenon. We can use the normal distribution to calculate the probability of something happening in real world. To add to this, we can use the **confidence of interval** to calculate the margin of error (e.g. how likely it is that out probability will happen?)
- **Hypothesis testing** is when we want to statistically test if our hypothesis is true or not. We start with a <ins>null heyphothesis</ins> and <ins>alternative hypothesis</ins>. To determine which one is "correct", we can set a threshold with the **p-value**. However, there are many researches that have stated p-values can be manipulated or "hacked" to receive a certain hypothesis.

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)

> **Day 11 of 66DaysOfData**

- **Correlation** are a way to calculate the relationship between two variables. This is usually done visually by a scatter plot or statistically with Pearson's correlation. However, correlation does not answer the how or why (causation). To make this value meaningful, we need to ensure that it uses quantitative values, a linear model, and there are no outliers in the data.

- **Regression** is a way to predict values by using a linear model (predicts Y value from X).

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)

> **Day 12 of 66DaysOfData**

- Tableau accepts datasets from various sources such as spreadsheet files, relational databases, cloud storages, statistical tables (e.g. R generated files), and many others.
- In Tableau, **Dimensions** are qualitative variables while **Measures** are quantitative variables.

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)

> **Day 13 of 66DaysOfData**

- The advantage of using visualizations for conveying information is that human mind tends to focus on pre-attentive visual cues. For example:

  - Line height (Great for quantitative data)
  - Line width (Limited use for qualitative data)
  - Shape, using different shapes for each data type (Great for qualitative data)
  - Colors, using different colors for each data type (Great for qualitative data)
  - Transparency (Limited use for qualitative data)
  - Position, e.g. higher values would have higher positions (Great for quantitative data)
  - Size (Great for qualitative data)

  And many others.

- When reading charts, we need to ask questions to fully understand the chart such as what does it represent, what patterns can we see, is that all of the information, and so on.

  After that, we also need to be wary of misleading visualziations such as charts without zero (in the quantitative axis), using the wrong type of chart (using line chart to represent categorical data instead of a bar chart), confusing color scheme (using darker colors to represent lower density when the focus is the higher density values), and so on.

- There are different types of charts:

  - Line chart, used to view trends over a period of time
  - Bar chart, used to view categorical data
  - Heatmap, used to view relationships between two factors
  - Highlight chart, gives details to heatmaps
  - Histogram, used to view distribution of the data
  - Box chart, used to view distribution of a section from the data
  - Scatterplot, used to view relationships between two quantitative values
  - Treemap, used to view the percentage compared to all

  And many others.

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)

> **Day 14 of 66DaysOfData**

- The general workflow in Tableau are connect to the data source, analyze the data, and share. These processes can be more iterative rather than linear. In Tableau, we can connect to a local file, data server, and others.

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)

> **Day 15 of 66DaysOfData**

- Data preparation is a key process to be done before the analysis to allow Analysts find more precise insights faster. This stage includes manipulating the data by shaping, filtering, and others.
- Side note: I have downloaded Tableau Prep Builder and will experiment with it tomorrow! Let's go!

- Resources:
  - [Tableau eLearning](https://elearning.tableau.com/)
