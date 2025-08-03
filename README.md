# teachable_model_test

Description
This task involves creating an image recognition model using Google Teachable Machine. The model should be trained with at least two classes and then evaluated.


Steps
Train an image recognition model in Teachable Machine using at least two classes.

Export the model in TensorFlow → Keras format (for example: model.h5).

Create a Python script to load the model and predict an image. For example:

Import TensorFlow, Keras, NumPy, and PIL for image handling.
Load the model using keras.models.load_model("model.h5").
Open the image using Image.open("test.jpg").resize((224, 224)).
Convert the image to an array and normalize it with / 255.0.
Use model.predict() to get predictions and np.argmax() to find the predicted class.
Submit the Python script, exported model files, and a screenshot of the model running.
