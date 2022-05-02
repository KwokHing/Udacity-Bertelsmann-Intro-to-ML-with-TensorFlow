## Supervised Learning Project: Finding Donors for CharityML

This project requires Python 3.x and the following Python libraries installed:

- `NumPy`
- `Pandas`
- `matplotlib`
- `scikit-learn`

Recommended to install [Anaconda](https://www.anaconda.com/products/distribution), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. Alternatively, you can make use of [Google Colaboratory](https://colab.research.google.com/), which allows you to write and execute Python codes in your browser.

**Code**

You will also be required to use the included `visuals.py` Python file and the `census.csv` dataset file to run the notebook. 

**Data**

The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). The datset was donated by Ron Kohavi and Barry Becker, after being published in the article _"Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid"_. You can find the article by Ron Kohavi [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf)

**Features**

* `age`: continuous. 
* `workclass`: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked. 
* `education`: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool. 
* `education-num`: continuous. 
* `marital-status`: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse. 
* `occupation`: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces. 
* `relationship`: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried. 
* `race`: Black, White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other. 
* `sex`: Female, Male. 
* `capital-gain`: continuous. 
* `capital-loss`: continuous. 
* `hours-per-week`: continuous. 
* `native-country`: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

**Target Variable**

* `income`: Income Class (<=50K, >50K)

## Getting started
Run `finding_donors.ipynb` on a jupyter notebook environment, or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://githubtocolab.com/KwokHing/Udacity-Bertelsmann-Intro-to-ML-with-TensorFlow/blob/main/Finding%20Donors%20for%20CharityML/finding_donors.ipynb)
