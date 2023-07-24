# NEU-365P-385L-Spring-2024
Programming and Data Analysis for Modern Neuroscience

# Python Basics

1. Variables and the importance of choosing good names for them.
2. Basic data types: `int`, `float`, `bool`, `str` and `type` function
3. Comments and multi-line strings: `#`, `"""`
4. Basic operations: `+`, `-`, `*`, `/`, `**`
5. Logical comparisons: `==`, `!=`, `<`, `>`, `<=`, `>=`, `and`, `or`, `not`
6. `if`, `elif`, `else` blocks
7. Nested blocks
8. `list` and `tuple`
9. `sorted` and `reversed` functions
10. List unpacking: `*`
11. `zip`
12. List indexing and slicing: `[start]`, `[start:stop]`, `[start:stop:step]` <-- *stupid 0-based indexing*
13. Dictionary (key, value) pairs: `dict`
14. Dictionary indexing: `[key] = value`
15. `for` and `while` loop blocks
16. `range` and `len` functions
17. `def` function blocks
18. Default and named function arguments
19. Assignment vs. Mutation
20. `class` block
21. Module file
22. Package file hierarchy
23. `import` modules
24. Function `args` and `kwargs`
25. Generators: `yield`

# Data Toolkit
Familiarizing yourself with the tools listed below (I highly recommend going in the order presented) will prepare you to work with almost any data at any level in the Python environment. The most essential learning goals are listed along with each tool.

1. [list](https://docs.python.org/3/tutorial/introduction.html#lists): You will be able to work with lists of arbitrary items and use indexing/slicing to manipulate a subset of items from the list.
2. [dict](https://docs.python.org/3/tutorial/datastructures.html#dictionaries): You will be able to work with (key, value) pairs.
3. [numpy](https://numpy.org): You will be able to work with N-dimensional arrays (e.g., initialization, indexing/slicing, views, math, aggregation, logical masks, matrix multiplication). You will appreciate the power of N-D arrays for many types of data, and the speed and clarity of numpy vs. pure python.
4. [pandas](https://pandas.pydata.org): You will be able to work with dataframes (i.e., tables; indexing/slicing, to/from numpy, groupby, plot). You will appreciate the power of pandas dataframes for exploratory data analysis and see that pandas far exceeds the ability of programs like Excel to manage large tabular datasets.
5. [xarray](https://xarray.dev): You will appreciate the usefulness of N-D arrays with labeled dimensions. This is numpy + pandas to the next level.
6. [zarr](https://zarr.dev): You will be able to store data in a self-describing hierarchical format with chunked arrays either locally or in the cloud.
7. [dask](https://www.dask.org): You will be able to perform computations on datasets too large to fit into your local computer memory.

Some more resources that may be of interest:

- 🔗 [pydata](https://pydata.org): Community leveraging python to work with many types of data.
- 🔗 [parquet](https://parquet.apache.org): A modern and vastly superior format for storing large tabular datasets as compared to comma separated values (.csv).

# Data Visualization
1. [matplotlib](https://matplotlib.org)
2. [seaborn](https://seaborn.pydata.org)
3. [hvplot](https://hvplot.holoviz.org)
4. [napari](https://napari.org/stable/#)
5. [panel](https://panel.holoviz.org)
6. [PySide/PyQt](https://wiki.qt.io/Qt_for_Python)

[misleading graphs](https://en.wikipedia.org/wiki/Misleading_graph)

# Statistical Inference
1. [random variables]()
2. [probability]()
3. [Bayes Theorem]()
4. [probability distributions]()
5. [maximum likelihood]()
6. [sampling distribution]()
7. [Central Limit Theorem]()
8. [hypothesis testing]()
9. [pitfalls of p-values]()
10. [permutation test]()
11. [confidence interval]()
12. [bootstrap]()

[misuse of statistics](https://en.wikipedia.org/wiki/Misuse_of_statistics)

# Linear Models

# Regression

# Classification

# Clustering

# Dimensionality Reduction

# Neural Networks
