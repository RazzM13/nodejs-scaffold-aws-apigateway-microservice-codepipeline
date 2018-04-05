# A pipeline for building the [nodejs-scaffold-aws-apigateway-microservice](https://github.com/RazzM13/nodejs-scaffold-aws-apigateway-microservice) APIGateway microservice, based off of the [scaffold-aws-microservices-codepipeline](https://github.com/RazzM13/scaffold-aws-microservices-codepipeline) scaffold.

# Installation
To install this pipeline you will need to complete the following steps:
1) Download this project locally and install it's dependencies:
```
git clone --depth 1 https://github.com/RazzM13/nodejs-scaffold-aws-apigateway-microservice-codepipeline.git
cd nodejs-scaffold-aws-apigateway-microservice-codepipeline
npm install
```
2) Obtain a GitHub personal access token from [here](https://github.com/settings/tokens) and then replace the `******` from the `config.yaml` file with your own.
3) Then you just need to deploy the pipeline by executing:
```
npm install-codepipeline
```
