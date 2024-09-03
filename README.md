# portfolio

## Exploratoty data analysis
### Data_First 10 rows.
'House Price India.csv' dataset.
![df0__head](https://github.com/user-attachments/assets/e796dbd0-2c4c-4a9b-a3de-72005b74b6c4)

### Check for missing data

![check for missing data](https://github.com/user-attachments/assets/02e43541-8a31-40dc-82ed-e2d298dd71ef)


### Data visualizattion:Box plot
A boxplot, also known as a box-and-whisker plot, is a way to visually show the distribution of numerical data. It displays the following key statistics:

Median: The middle value of the data, represented by a line inside the box.
Quartiles: The box itself represents the interquartile range (IQR), which contains the middle 50% of the data. The bottom of the box is the first quartile (25th percentile), and the top is the third quartile (75th percentile).
Whiskers: Lines extending from the box show the range of the data, excluding outliers. They typically extend to 1.5 times the IQR from the box edges.
Outliers: Individual data points beyond the whiskers are plotted as dots, indicating potential outliers.
Boxplots are useful for:

Comparing distributions: You can easily see differences in median, spread, and skewness between groups by placing multiple boxplots side-by-side.
Identifying outliers: Outliers are clearly marked, allowing you to investigate them further.
Understanding data range and variability: The box and whiskers provide a quick overview of the data's spread.


![boxplot](https://github.com/user-attachments/assets/28c80d76-f517-45e1-b4bc-36d4b7d1cb63)

### Data visualizattion:  Heatmap Corelation
A heatmap correlation is a graphical representation of a correlation matrix. It uses color to show the strength of the relationship between multiple numerical variables. Red usually indicates a positive correlation, blue a negative correlation, and the intensity of the color represents the strength of the correlation.

In this heatmapz it was generated using the seaborn library to visualize the correlations between numerical columns in the 'House Price India.csv' dataset.
![heatmap](https://github.com/user-attachments/assets/ca467df7-fd38-4517-9a99-b4bbf7ffaa70)

### Data visualizattion: 3d Stacked bar plot
A 3D stacked bar plot is a way to visualize data with 3 dimensions. Imagine a regular bar chart, but now each bar can be divided into segments, and these bars are arranged in a 3D space. This helps to show how a quantity is composed of different parts, and how these parts vary across two other categories.

For example, in this plot, 'Price' varies with 'lot area' and 'living area'. Each bar represents a combination of 'lot area' and 'living area', and the height of the bar is the average 'Price'. The bar is then segmented to show how the 'Price' is distributed.

![3d sacked bar_House price](https://github.com/user-attachments/assets/cd3db0e7-ec92-4e41-9d35-57260e09838f)
![3d sacked bar_House price_2](https://github.com/user-attachments/assets/7eb16af1-c3b6-4d38-89ab-3f26fa866967)

