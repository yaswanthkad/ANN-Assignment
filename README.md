# ANN-Assignment
Explanation of ANN for Customer Churn Prediction
Data Preparation: A synthetic dataset is generated to simulate customer churn behavior. The data is split into training and testing sets.

Feature Scaling: Standardization is applied to ensure that all features contribute equally during training and improve model convergence.

Model Architecture: A simple Artificial Neural Network (ANN) is created using the Sequential model. It contains:

Two hidden layers with ReLU activation to capture complex patterns.

One output layer with sigmoid activation to produce a probability for binary classification (churn or not).

Compilation:

Loss Function: binary_crossentropy is used for binary classification tasks.

Optimizer: adam optimizer adapts the learning rate for efficient training.
Metrics: Accuracy is used to measure model performance.

Training: The model is trained over multiple epochs, using validation data to monitor performance and detect overfitting or underfitting.Metrics: Accuracy is used to measure model performance.

Training: The model is trained over multiple epochs, using validation data to monitor performance and detect overfitting or underfitting.
Training Output Insights
Loss: Represents error; should decrease over time.

Accuracy: Shows how many predictions are correct; should increase over time.

Validation Metrics: Help detect if the model generalizes well.

Model Behavior
Good Learning: Training and validation accuracy improve, loss decreases.

Overfitting: Training accuracy is high, but validation accuracy is low.

Underfitting: Both training and validation accuracy are low; model too simple or insufficient training.

