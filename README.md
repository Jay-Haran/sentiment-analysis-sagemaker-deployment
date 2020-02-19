# Sentiment Analysis SageMaker Deployment

This project covers the implementation and deployment of a model which interacts with a simple front-end html website, responding live to whether a user submitted movie review is positive or negative. The model implemented was an RNN architecture implemented using PyTorch and trained on the IMDB dataset. The model was deployed using Amazon Sagemaker and the aim of completing this project was to gain familiarity with the entire lifecyle of a machine learning project.

The pipeline uses AWS API Gateway and AWS Lambda functions. The application architecture diagram is shown below.

![Web app Diagram](./Web&#32;App&#32;Diagram.svg) 

You can find the original code without solutions in the original [Udacity SageMaker Deployment repository](https://github.com/udacity/sagemaker-deployment).

## Setup instructions
Please see the [original README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks). For the solutions only clone this repository:

```
cd SageMaker
git clone https://github.com/jayharan/sagemaker-sentiment-analysis
exit
```

## Web app final result

The final project will be executed in a simple html page which can be deployed anywhere. 

You will see the following:

![Web app example](./webapp.gif) 

