# Problem Statement

Build a linear regression model using scikit learn in boston data to predict 'Price' based on other dependent variable.

### code to load the data:

    import numpy as np
    import pandas as pd
    import scipy.stats as stats
    import matplotlib.pyplot as plt
    import sklearn
    from sklearn.datasets import load_boston
    boston = load_boston()
    bos = pd.DataFrame(boston.data)
