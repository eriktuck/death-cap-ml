# Foraging for Mushrooms in Random Forests
**A Machine Learning approach to binary classification of mushrooms as poisonous or edible**

Would you join me on a forage for wild mushrooms? When foraging for wild mushrooms, it's critical to accurately identify the species of mushroom you find to distinguish edible mushrooms from poisonous ones. 

There are some distinguishing features that indicate when a mushroom might be poisonous, such as:
- White gills
- Red cap or stem

However, traditional wisdom asserts that you must identify the species of any mushroom you eat. Relying on a few characteristics or other rules of thumb could be fatal! But is that traditional wisdom correct? Could we use Machine Learning to save us some time identifying mushrooms in the field so we can get on with our feast? Is it worth the risk? 

# Environment
To reproduce this workflow, use the provided `environment.yml` file to create a `conda` environment (you should already have Python and `conda` installed on your system).

After cloning this directory to your system, use the following `bash` commands to create and activate the environment:

```bash
conda env create -f environment.yml
conda activate death-cap-ml
```

You must have Jupyter Notebook installed on your system to run this analysis. For installation instructions, consult the documentation [here](https://jupyter.org/).

# Data
This notebook explores the UC Irvine Machine Learning Repository's [Mushroom Dataset](https://archive.ics.uci.edu/dataset/73/mushroom) as expanded by Kaggle in the [Binary Prediction of Poisonous Mushrooms](https://www.kaggle.com/competitions/playground-series-s4e8/data) Playground Series. 

To run this workflow, please download the `train.csv` and `test.csv` files of the Kaggle dataset from the link provided above.

# Workflow
Run either `kaggle_data.ipynb` or `original_data.ipynb` in any order using a Jupyter Notebook.