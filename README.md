## Iris Dataset Analysis

This project explores the classic Iris flower dataset using Python and machine learning techniques. The main work is contained in the Jupyter notebook `Iris.ipynb`, which loads the dataset, checks data quality, applies preprocessing, and performs clustering with K-Means.

## Project goal

The notebook is designed to:

- load and inspect the dataset,
- confirm there are no missing values,
- verify class distribution across the three Iris species,
- remove the non-feature `Id` column,
- standardize the feature values,
- cluster the data into three groups using K-Means,
- evaluate the clustering quality with silhouette and Davies-Bouldin scores,
- compare the cluster labels with the actual species labels.

## Dataset

The dataset is stored in `Iris.csv` and contains 150 observations of Iris flowers. Each row includes:

- `Id`
- `SepalLengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`
- `Species`

The species categories are:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

 Files in this project

- `Iris.ipynb` — main analysis notebook
- `Iris.csv` — dataset used for the project
- `.venv` — Python virtual environment for local dependencies

 Technologies used

- Python
- pandas
- scikit-learn
- matplotlib
- Jupyter Notebook

 How to run

1. Open the project folder.
2. Activate the virtual environment in `.venv`.
3. Start Jupyter Notebook or VS Code notebook support.
4. Open `Iris.ipynb`.
5. Run the cells in order.


## Notes

This project is a beginner-friendly example of exploratory data analysis and unsupervised machine learning. It demonstrates how to work with a real-world dataset, prepare features for modeling, and evaluate clustering performance.
