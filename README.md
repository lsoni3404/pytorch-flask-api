# pytorch-flask-api
This repo contains a sample code to show how to create a Flask API server by deploying our PyTorch model.
# Setup on your machine
Make sure you have python-3 installed on your machine.

Install the dependencies:

      pip install -r requirements.txt
Run the Flask server:

	FLASK_ENV=development FLASK_APP=app.py flask run
From another tab, send the image file in a request:

	curl -X POST -F file=@cat_pic.jpeg http://localhost:5000/predict
#License
The mighty MIT license. Please check LICENSE for more details.
