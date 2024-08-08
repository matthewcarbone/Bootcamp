<div align=center>

# Introduction to Machine Learning

</div>

This module will contain basic modules for introducing you to the most important concepts of machine learning, that of the model (used to fit data), the optimizer (used to "train" the model) and the notion of a "cost function" (a measure of how well a model fits data). We will largely demonstrate these key concepts using the simplest machine learning models: linear and logistic regressors.

# Modules

[Linear and logistic regression](https://colab.research.google.com/github/matthewcarbone/Bootcamp/blob/master/Modules/03_Introduction_to_Machine_Learning/01_Linear_Logistic_Regression.ipynb)

# Nice datasets

During interactive sessions with instructors, we recommend the following two datasets for starting your machine learning journey. 

## California Housing

This is nice dataset for **regression** problems. There are a few ways to download this, but do note that the source of the dataset will have an impact on what the data looks like, whether or not outliers are dropped, what columns are called, etc. 

From Sci-kit learn: [California Housing Dataset](https://inria.github.io/scikit-learn-mooc/python_scripts/datasets_california_housing.html)
```python
import pandas as pd
from sklearn.datasets import fetch_california_housing
california_housing = fetch_california_housing(as_frame=True)
data = pd.concat([california_housing["data"], california_housing["target"]], axis=1)
```

From Huggingface Hub (this is what we'll use in the notebook!):
```python
import pandas as pd
df = pd.read_csv("hf://datasets/leostelon/california-housing/housing.csv")
```

> [!NOTE]
> Don't forget to `pip install scikit-learn` or `pip install huggingface_hub` (respectively), as well as `pip install pandas` (in either case), before trying the above code snippets!

## Iris

This is a nice dataset for classification problems: [Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html).
```python
import pandas as pd
from sklearn.datasets import load_iris
iris = load_iris(as_frame=True)
data = pd.concat([iris["data"], iris["target"]], axis=1)
```

