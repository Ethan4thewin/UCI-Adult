# UCI-Adult
Exploring Income Disparity and Model Performance in the UCI Adult Dataset: An Analysis of Demographics and Tree-Based Models

- adult.data: dataset that serves as a training set, 2/3 of the whole.
- adult.test: dataset that serves as a test set, 1/3 of the whole.
- adultnames.txt: The original information of the dataset.
- data.csv: dataset that was cleaned and used throughout the notebook.
- data_with_missing_values.csv: dataset that was cleaned, but missing values are left as is.
- datamodel_only.ipynb: A notebook file contains only the data modelling part.
- tree.dot: An example of tree-based decision making of the decision tree with more than 50 levels.
  One of the way to visualize is to use online tools such as [Graphviz Online](https://dreampuf.github.io/GraphvizOnline/) here.
- uci_adult.ipynb: A notebook file contains all the code.

Version of packages at the time of running:
- Numpy 1.20.3
- Pandas 2.0.0
- Matplotlib 3.4.2
- Sklearn 1.0.2

The script is expected to run without any additional modifications.
Sidenote: Total runtime of the 2 algorithms is around 38 - 40 minutes on a quad-core processor, 8GB of DDR4 RAM, and NVMe M.2 SSD. GPU was not utilized during runtime.

References:
[Adult. UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/2/adult)
