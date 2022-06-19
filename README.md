# Fintech-Module-12-Challenge


# Credit Risk Classification

In this project the taks will be to count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

## Technologies

This project leverages Python 3.9.7 ((default, Sep 16 2021, 16:59:28) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32) with the following packages:
 
* [python](https://www.python.org/) - Official documentation for Python 3.10.5. 
  
* [numpy](https://numpy.org/doc/stable/) - Source repository. 
NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.

* [pandas](https://pandas.pydata.org/docs/) - Source repository. 
pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

* [pathlib](https://docs.python.org/3/library/pathlib.html) - Source repository. 
The pathlib module offers classes representing filesystem paths with semantics appropriate for different operating systems. Path classes are divided between pure paths, which provide purely computational operations without I/O, and concrete paths, which inherit from pure paths but also provide I/O operations.

* [scikit-learn](https://github.com/scikit-learn/scikit-learn) - scikit-learn is a Python module for machine learning built on top of SciPy and is distributed under the 3-Clause BSD license.

* [jupyterlab](https://jupyterlab.readthedocs.io/en/stable/user/urls.html#managing-workspaces-ui) - For information about the jupyter lab remote workspace hosted by a local computer.

---

## Installation Guide

Before running the application first install the following dependencies.

```
# Install the required libraries
conda install -c conda-forge imbalanced-learn
conda install -c conda-forge pydotplus
```

# Import the required libraries and dependencies
```
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

```
---

## Usage

The detailed instructions are divided into the following parts:

Use the RandomOverSampler module from the imbalanced-learn library to resample the data. Be sure to confirm that the labels have an equal number of data points.

Use the LogisticRegression classifier and the resampled data to fit the model and make predictions.

1. Evaluate the model’s performance by doing the following:
2. Calculate the accuracy score of the model.
3. Generate a confusion matrix.
4. Print the classification report.

    Answer the following question: How well does the logistic regression model, fit with oversampled data, predict both the 0 (healthy loan) and 1 (high-risk loan) labels?


---

## Contributors

Gerald Cortright and Berkeley Fintech support staff
---

## License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
