# Spark: The Definitive Guide (Andreu's guide)

I took the liberty of forking the [official repo](https://github.com/databricks/Spark-The-Definitive-Guide) of the book and adding some helpful notebooks for my future self, as well as focusing on the `pyspark` implementation. The notebooks are to be run on a local Spark installation, just for learning purposes.
I focused on `pyspark.sql` and `pyspark.ml` packages.

In this sense, I have also adapted and fixed some examples that would work -or were only shown- for Scala and port them to Python.

# Notebooks structure

- [Chapter 2](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter2.ipynb) is a gentle introduction to Spark and shows how to use the `SparkSession` on a Jupyter Notebook.
- [Chapter 4](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter4.ipynb) is so small that you can completely ignore it.
- [Chapter 5](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter5.ipynb) is pretty useful, it shows how to use and select Rows, Columns, Dataframes, `select()` and `selectExpr()`, manipulating columns (adding, removing, filtering, renaming, casting) on DataFrames and operations over DataFrames (sorting, counting, unions, splits).
- [Chapter 6](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter6.ipynb) demos working with different types of data inside DataFrames: integers, numbers, strings, datetimes, booleans). It also features how to handle missing data and how to manipulate complex types (`struct`, `array` and `map`).
- [Chapter 7](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter7.ipynb) shows how to perform aggregations, windows, rollups, pivots and alikes over DataFrames.
- [Chapter 8](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter8.ipynb) is reserved for performing joins on DataFrames.
- [Chapter 9](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter9.ipynb) deals with I/O concepts (loading and storing data). This notebooks shows as well how to load the Spark Session so it can talk to SQL databases.
- [Chapter 24](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter24.ipynb) demos a Machine Learning Pipeline based on Logistic Regression and covers some bugs in the hypeparameter retrieval.
- [Chapter 25](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter25.ipynb) is a showroom for feature extraction using Spark's ML.
- [Chapter 26](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter26.ipynb) shows how to use the most common classifiers. In all honesty, the difficulty in this chapter lies in understanding the math behind the classifiers and possiblt navigating the APIs to configure them. Note that some evaluation metrics in the current version of spark are only available for RDDs (mlllib).
- [Chapter 27](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter27.ipynb) demoes classical regression algorithms.
- [This ML pipeline on a Kaggle Housing dataset](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/MLpipelineKaggleHousing.ipynb) ties it all together and does feature extraction, cross-validation, test dataset evaluation over the performance of various regression algorithms using an example dataset from Kaggle (housing price prediction).
- [Chapter 29](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter29.ipynb) is a simple showroom of basic clustering algorithms (aka unsupervised learning).
- [Chapter 29](https://github.com/drublackberry/Spark-The-Definitive-Guide/blob/master/notebook/Chapter30.ipynb) shows how to launch GraphFrames on a notebook and to run queries, motif finding and algorithms on the graph itself.


Work is still on-going.

# The book

[Spark: The Definitive Guide](http://shop.oreilly.com/product/0636920034957.do) by Bill Chambers and Matei Zaharia. 

![Spark: The Definitive Guide](https://images-na.ssl-images-amazon.com/images/I/51z7TzI-Y3L._SX379_BO1,204,203,200_.jpg)