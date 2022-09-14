# Heart Disease Prediction Data Science Project
Data science project on accurately classifying heart disease in patients based on three datasets.

### Python code and more detailed analysis of the dataset can be found in the [heartdisease-prediction.ipynb](/heartdisease-prediction.ipynb) Jupyter Notebook.

## Heart disease datasets used
- UCI Cleveland
- Statlog
- Framingham

Data from these datasets were combined and cleaned for missing or nonsensical values, leaving a total of 756 records from the original 918.

## Classification models used
- Linear Regression
- Decision Trees
- Multi-Layer Perceptron

Training and prediction were performed using the **sklearn** Python library.

## Confusion matrix results based on 80-20 train-test split for each model
![confusion matrix results](/confusion-matrix-results.png)
The multi-layer perception (artificial neural network) yielded the highest accuracy in classifying heart disease in this testing.
