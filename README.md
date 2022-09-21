# Stock Prophet - Week 12 MLOps Assignment

Deploying a basic time series model for stock prices on an AWS EC2 instance.

To run predictions, run the following command in your terminal:

curl \
--header "Content-Type: application/json" \
--request POST \
--data '{"ticker":"MSFT", "days":7}' \
http://13.58.209.140:8000/predict

To view the API documentation and run the predict function interactively, visit http://13.58.209.140:8000/docs .
