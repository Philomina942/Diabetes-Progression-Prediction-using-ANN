# Diabetes Progression Prediction using ANN

## About the Project

This project uses an Artificial Neural Network (ANN) to predict diabetes progression using the Diabetes dataset available in Scikit-learn. The model is built using TensorFlow and Keras.

## Objective

The main objective is to build and evaluate an ANN model and understand how different model architectures affect prediction performance.

## Dataset

- **Source:** Scikit-learn
- **Dataset:** Diabetes dataset
- **Input features:** 10
- **Target:** Diabetes progression (a continuous numerical value)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow and Keras

## Steps Followed

1. Imported the required libraries.
2. Loaded the Diabetes dataset.
3. Checked for missing values.
4. Performed exploratory data analysis (EDA).
5. Visualized feature distributions and correlations.
6. Split the dataset into training and testing sets.
7. Standardized the input features.
8. Built an ANN model.
9. Trained the model and visualized the training loss.
10. Evaluated the model using MSE and R² score.
11. Built a second ANN with more hidden layers and neurons.
12. Compared the performance of both models.

## Model Results

| Model | MSE | R² Score |
|---|---:|---:|
| Original ANN | 2840.52 | 0.4639 |
| Improved ANN | 2936.59 | 0.4457 |

The Original ANN performed better because it achieved a lower MSE and a higher R² score than the Improved ANN.

## Conclusion

In this project, I learned how to load and preprocess a dataset, perform EDA, build an ANN, and evaluate its performance. I also compared two ANN architectures and found that adding more hidden layers and neurons did not improve the results in this experiment.

## How to Run

1. Download or clone this repository.
2. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
3. Run the notebook cells in order.

## Author

Created as part of the Deep Learning Module End Assignment.
