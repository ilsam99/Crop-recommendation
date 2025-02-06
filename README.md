# Crop-recommendation
Overview

This project leverages Artificial Neural Networks (ANNs) and AWS SageMaker to optimize crop selection and fertilizer use based on real-time soil data. The system is designed to help farmers make data-driven decisions, improving yield and resource efficiency.

Features

Real-time soil data processing (NPK levels, temperature, pH, humidity)

Artificial Neural Network (ANN) model for crop recommendation

AWS SageMaker deployment for scalability and performance

API Gateway & AWS Lambda for handling real-time predictions

AWS SNS notifications for farmers

System Architecture

Sensors collect soil data.

Data is sent to AWS Lambda via API Gateway.

The ANN model in SageMaker processes the data.

The model predicts the best crop and optimal fertilizer use.

Results are sent to farmers via AWS SNS (email/SMS).

Technologies Used

Machine Learning: ANN (Artificial Neural Network)

Cloud Platform: AWS SageMaker, AWS Lambda, API Gateway, AWS SNS

Programming Language: Python

Frameworks: TensorFlow/Keras, NumPy, Pandas, Scikit-learn

Deployment: AWS SageMaker Endpoint
