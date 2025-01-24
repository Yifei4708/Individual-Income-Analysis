# Individual-Income-Analysis ML

Neural networks

A neural network-based binary classification model designed to predict whether an individual's income exceeds $50K annually. The analysis utilizes the Adult dataset, applying data preprocessing, handling class imbalance, and optimizing the model using cross-validation. The final performance is evaluated using a confusion matrix and classification metrics. 

Model Architecture ○ The neural network model consists of an input layer that processes the scaled features. It includes two hidden layers: the first layer has 64 neurons with ReLU activation and a dropout rate of 30%, while the second layer has 32 neurons with ReLU activation and a dropout rate of 20%. The output layer contains a single neuron with a sigmoid activation function, designed for binary classification tasks. The model optimization is carried out using the binary cross-entropy loss function. Training incorporates early stopping to prevent overfitting, with a batch size of 32 and a maximum of 50 epochs. Cross-Validation Results ○ Mean Cross-Validation Accuracy: 0.87. ○ Standard Deviation: 0 (indicating consistent performance across folds). Final model evaluation ○ Classification Report: ■ Precision: High precision (87%) for predicting >50K, indicating relatively few false positives. ■ Recall: High recall (88%) for predicting >50K, showing the model effectively identifies the positive class. ■ F1-Score: 0.87, balancing precision and recall for the >50K class.

