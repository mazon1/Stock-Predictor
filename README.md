<p align = "center" draggable=”false” ><img src="https://user-images.githubusercontent.com/37101144/161836199-fdb0219d-0361-4988-bf26-48b0fad160a3.png" 
     width="200px"
     height="auto"/>
</p>

# Deployment of Stock Prediction Model as a RESTful API using FastAPI and AWS EC2
This project aims to deploy a Stock Prediction Model as a RESTful API using FastAPI, a modern, fast (high-performance) web framework for building APIs with Python. The API will be deployed on an AWS EC2 instance.

# Requirements
Python 3.7 or higher
FastAPI
Uvicorn
Requests
AWS EC2 Instance

# Installation
Clone the repository
Install the required packages using pip install -r requirements.txt
Run the API using uvicorn main:app --host 0.0.0.0 --port 8000

# API Endpoints
/ - Returns the API status and usage instructions
/predict - Accepts a POST request with a JSON payload containing the stock data to be used for the prediction. Returns a JSON response containing the predicted stock price.
Deployment

# Launch an AWS EC2 instance.
Install the necessary packages on the EC2 instance.
Copy the project files to the EC2 instance.
Start the API using uvicorn main:app --host 0.0.0.0 --port 8000 on the EC2 instance.
Test the API using a client such as curl or Postman.

# Credits
This project was developed by Uchenna Mgbaja and is licensed under the MIT License.