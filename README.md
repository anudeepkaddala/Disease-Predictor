Disease Predictor


Overview:

This project is a disease predictor that utilizes machine learning algorithms to predict the likelihood of a person having a certain disease based on input features such as symptoms, medical history, and demographic information.

Installation:
To install the necessary dependencies, you can use the following command:

pip install -r requirements.txt

This will install the required Python packages listed in the requirements.txt file, including:

numpy
scikit-learn
scipy
pickle-mixin
flask

Folder Structure:

Datasets: Contains datasets used for training and testing the machine learning model.
model_training: Folder consisting of scripts and notebooks for training machine learning models.
prediction_models: Folder consisting of serialized model files (.sav) used for predictions.
static: Contains static files of bootstrap and image files for the web application.
templates: Contains HTML templates used by the Flask application for rendering web pages.
app.py: Main Flask application file responsible for handling web requests and serving the web application.
details.py: Python module containing functions for processing input data and making predictions.
requirements.txt: File listing the required Python packages and their versions.


Usage:
To use the disease predictor, follow these steps:

Ensure that you have installed all dependencies as mentioned in the Installation section.
Run the Flask web application using the following command:

python app.py

Once the application is running, navigate to the provided URL in your web browser.
Input the required information such as symptoms, medical history, and demographic details.
Click on the "Predict" button to get the prediction result.



Model Training:
The machine learning model used for prediction is trained using a dataset containing labeled instances of patients with and without the disease. The training process involves preprocessing the data, selecting appropriate features, and training the model using algorithms available in the scikit-learn library.

The trained model is then serialized using the pickle module and saved to a file (.sav) in the prediction_models folder. This file is loaded by the Flask application at runtime to make predictions.

Contributing:
Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request on the GitHub repository.

License:
This project is licensed under the MIT License.