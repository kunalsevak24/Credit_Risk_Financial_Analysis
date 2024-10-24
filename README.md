# Credit_Risk_Financial_Analysis

Explanation
Input Layer:

The Input layer is used as the first layer in the model to specify the input shape.
This avoids the warning message and follows best practices.
Model Compilation:

The model is compiled with the Adam optimizer and binary cross-entropy loss, suitable for binary classification.
Model Training:

The model is trained for 10 epochs with a batch size of 32.
The training process includes validation data to monitor the model's performance on unseen data.
Model Evaluation:

The model's performance is evaluated on the validation set, and the loss and accuracy are printed.
Visualization:

The training and validation accuracy and loss are plotted to visualize the model's performance over epochs.
This complete process demonstrates how to build, train, and evaluate a neural network model for credit risk prediction using synthetic financial data.

Model Compilation:

The model.compile method is used to configure the model for training.
optimizer='adam' specifies the Adam optimizer.
loss='binary_crossentropy' specifies the loss function for binary classification.
metrics=['accuracy'] specifies that accuracy should be monitored during training.
Training the Model:

The model.fit method is used to train the model.
The training data (X_train, y_train) and validation data (X_val, y_val) are passed to the method.
The model is trained for 10 epochs with a batch size of 32.
Evaluating the Model:

The model.evaluate method is used to evaluate the model's performance on the validation set.
The loss and accuracy on the validation set are printed.
Visualizing Training History:

The training and validation accuracy and loss are plotted to visualize the model's performance over epochs.
