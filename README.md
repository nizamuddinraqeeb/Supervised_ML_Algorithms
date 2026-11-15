# Supervised Machine Learning Algorithms

A collection of Jupyter notebooks exploring supervised machine learning through implementations built with **NumPy** and models from **scikit-learn**.

The project covers regression and classification, with a focus on understanding the calculations behind model training as well as using established machine learning libraries.

## Project Contents

| Notebook | Description | Approach |
|---|---|---|
| `Manual_SLR_Algorithm.ipynb` | Implements simple linear regression, including the cost function, gradient calculation, gradient descent, and prediction. | NumPy / Python |
| `MLR_Numpy_only.ipynb` | Implements multiple linear regression with a cost function, gradients, gradient descent, and predictions. | NumPy |
| `MLR_ScikitLearn.ipynb` | Trains a multiple linear regression model on the housing dataset using `LinearRegression`. Includes one-hot encoding, a train/test split, and an actual-vs-predicted plot. | scikit-learn |
| `logistic_regression_algorithm.ipynb` | Implements binary logistic regression components: sigmoid, logistic cost, gradients, gradient descent, and threshold-based predictions. Uses a small example dataset defined in the notebook. | NumPy |
| `decision_tree.ipynb` | Trains and visualizes a decision tree classifier using the species dataset. Includes preprocessing, a stratified train/test split, and accuracy evaluation. | scikit-learn |

## Datasets

The repository includes these CSV files:

- `housing.csv` — used by `MLR_ScikitLearn.ipynb` to predict `median_house_value`.
- `species.csv` — used by `decision_tree.ipynb` to classify `Species`.

The logistic regression and NumPy multiple linear regression notebooks currently define their example data directly in the notebooks.

## Requirements

- Python 3.9 or later
- NumPy
- pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

Install the Python dependencies:

```bash
python -m pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Open the notebook you want to run. Keep the CSV files in the same directory as the notebooks, as the notebooks read them using relative filenames (`housing.csv` and `species.csv`).

## Running the Notebooks

1. Clone or download this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Launch Jupyter Notebook from the project directory.
4. Open a notebook and run its cells from top to bottom.

## Concepts Practiced

- Linear regression (simple and multiple)
- Logistic regression
- Decision tree classification
- Cost functions and gradients
- Gradient descent
- Feature preprocessing and one-hot encoding
- Train/test splitting
- Model prediction and basic evaluation
- Decision tree visualization
- Actual-vs-predicted visualization

## Project Scope

This is a learning and practice project. The notebooks demonstrate selected implementations and workflows; they are not intended to be a complete collection of all supervised learning algorithms or production-ready machine learning pipelines.

Some notebooks use manually implemented algorithms to make the underlying steps easier to study, while others use scikit-learn estimators.

## Contributions

Suggestions, corrections, and improvements are welcome. You can open an issue or submit a pull request.

