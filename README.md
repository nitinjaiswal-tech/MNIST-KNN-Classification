# MNIST Handwritten Digit Classification using KNN

A Machine Learning project that classifies handwritten digits (0–9) using the **K-Nearest Neighbors (KNN)** algorithm and the MNIST dataset.

## Project Overview

This project uses machine learning to recognize handwritten digits from image data. The MNIST dataset contains grayscale images of handwritten digits, which are preprocessed and used to train and evaluate a KNN classifier.

## Features

* Loads and processes the MNIST handwritten digit dataset.
* Normalizes pixel values for machine learning.
* Splits data into training and testing sets.
* Trains a K-Nearest Neighbors (KNN) classifier.
* Evaluates the model's classification accuracy.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset

The project uses the **MNIST dataset**, which contains 28 × 28 pixel grayscale images of handwritten digits from 0 to 9.

The dataset is loaded using Scikit-learn's `fetch_openml()` function.

## Methodology

1. Load the MNIST dataset.
2. Convert the target labels to integer values.
3. Normalize image pixel values to the range 0–1.
4. Split the dataset into 80% training data and 20% testing data.
5. Train a KNN classifier with `n_neighbors=3`.
6. Evaluate the model on the test dataset.

## Model Performance

| Metric                  |                    Result |
| ----------------------- | ------------------------: |
| Algorithm               | K-Nearest Neighbors (KNN) |
| Number of Neighbors (K) |                         3 |
| Training/Test Split     |                 80% / 20% |
| Test Accuracy           |                    97.13% |

*Note: Accuracy is based on the current model run and may vary if the dataset, preprocessing, or model settings change.*

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/nitinjaiswal-tech/MNIST-KNN-Classification.git
   ```

2. Navigate to the project folder:

   ```bash
   cd MNIST-KNN-Classification
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `index.ipynb` and run the cells in order.

## Project Structure

```text
MNIST-KNN-Classification/
├── index.ipynb
├── README.md
└── .gitignore
```

## Learning Outcomes

* Understanding a supervised machine learning classification problem.
* Working with image data and pixel normalization.
* Implementing the K-Nearest Neighbors algorithm.
* Splitting data into training and testing sets.
* Evaluating model performance.

## Future Improvements

* Compare different K values to find a better configuration.
* Add precision, recall, and F1-score.
* Visualize the confusion matrix.
* Display incorrectly classified digit images.
* Compare KNN with other classification algorithms.

## Author

**Nitin Jaiswal**

* GitHub: [nitinjaiswal-tech](https://github.com/nitinjaiswal-tech)

---

*This project was developed for learning and practicing machine learning classification techniques.*
