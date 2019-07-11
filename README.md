# Hot Dog Or No Hot Dog Using Tensorflow 

This project is a real world example of the hot dog or not hot dog app featured in the TV show, [Silicon Valley](https://youtu.be/ACmydtFDTGs). A convolutional neural net is the model used for image classifcation, which is created using the Tensorflow estimator API. The model is trained using raw jpg images of hotdogs and food items that are not hotdogs. The model is deployed to Google Cloud AI Platform and the included Flask app can get online predictions from the model. 

# Getting Started

Start by cloning this [git repo](https://github.com/samkahr/hotdog_cnn.git) to a local directory (use the git clone command).

If you would like to see the details of how the model is trained, please refer to the Hotdog.ipynb file, where the model is created, trained and example predictions are returned from the model. 

To run the example Flask app and get online predictions from any jpg image, follow these steps:

* `cd CNN_flask_demo`
* `pip install -r requirements.txt`
* `python main.py`

# Example

Once the flask app is running you should see the following screen

![Screenshot](screenshots/hotdog_blank.png)

If the uploaded image is a hotdog, the app should return the following

![Screenshot](screenshots/hotdog.png)

If a hotdog is not detected, the app should return the following

![Screenshot](screenshots/not_hotdog.png)

# Technology used

* Tensorflow
* Google Cloud AI Platform
* Jupyter Notebook
* Python
* Flask
