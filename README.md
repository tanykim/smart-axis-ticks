When you make bar charts or line graphs, or any other visualizations that need axes, you need to set the range of numbers on an axis.

You can simply set the range of axis values exactly same as the data range. However, often you want to set the highest value larger than the maximum number in the dataset.

Also, for the easier understanding for the data range, it is often recommended to set the distance between the nearby two ticks "a rounded number" such as 1, 2, 5, 10, 20, 50, 100 (i.e., 2 * 10^n, 5 * 10^n, 10^n).

This smart tick function (getSmartTick) generates a desirable range of data, cut by the most appopriate rounded step depending on the maximum value of the given dataset.