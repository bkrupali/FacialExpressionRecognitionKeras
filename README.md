# FacialExpressionRecognitionKeras
Facial Expression Recognition in Keras

A convolutional neural network with 4 convolution layers and 2 fully connected layers to predict 7 types of facial expressions.
Uses Adam as the optimizer, categorical crossentropy as the loss function, and accuracy as the evaluation metric.

Training and Evaluating Model
Using ModelCheckpoint() to save the weights associated with the higher validation accuracy.
Observe live training loss and accuracy plots in Jupyter Notebook for Keras.

Saving and Serializing Model as JSON String
Using to_json(), which uses a JSON string, to store the model architecture.

Creating a Flask App to Serve Predictions
Using open-source code from "Video Streaming with Flask Example" to create a flask app to serve the model's prediction images directly to a web interface.

Creating a Class to Output Model Predictions
Creating a FacialExpressionModel class to load the model from the JSON file, load the trained weights into the model, and predict facial expressions.

HTML Template for the Flask App
A basic template in HTML to create the layout for the Flask app.

Using Model to Recognize Facial Expressions in Videos
Running the main.py script to create the Flask app and serve the model's predictions to a web interface.
Apply the model to saved videos on disk.
