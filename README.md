### Breast Cancer Detection Jupyter Notebook

This Jupyter notebook demonstrates how to use machine learning to detect breast cancer using the sklearn and TensorFlow libraries.

#### Libraries
The following libraries are imported:

- pandas
- numpy
- sklearn.datasets
- sklearn.model_selection
- matplotlib.pyplot
- tensorflow
- keras

#### Data
The breast cancer dataset from sklearn is loaded and stored in a pandas DataFrame. The DataFrame is then split into training and testing sets. The training data is standardized using a StandardScaler.

#### Model
A neural network model is created using the Keras Sequential API. The model has three hidden layers with 20, 10, and 2 units, respectively. The input layer has 30 units, and the output layer has 2 units. The model is compiled using the Adam optimizer, sparse categorical crossentropy loss function, and accuracy metric.

#### Training
The model is trained on the training data for 10 epochs. The accuracy and loss are plotted during training.

#### Evaluation
The model is evaluated on the test data. The loss and accuracy are printed.

#### Prediction
A new data point is created and standardized. The model is used to predict the label of the new data point. The predicted label is printed.

#### Conclusion
This Jupyter notebook demonstrates how to use machine learning to detect breast cancer. The model achieved an accuracy of 96% on the test data.
