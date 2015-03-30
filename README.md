When you make bar charts of line graphs, or any other visualizations that need axis, you need to set the range of numbers that you want to put on an axis.

You can simply set the range of axis values exactly same as the data range. However, often you want to set the distance of ticks and the highest value larger than the maximum number in the dataset.

Also, for the easier understanding for the data range, it is often recommended to set the step between two ticks as "a rounded number" such as 1, 2, 5, 10, 20, 50, 100 (i.e., 2 * 10^n, 5 * 10^n, 10^n).

This smart tick function (getSmartTick) returns a desirable range of data, cut by the most appopriate rounded step.