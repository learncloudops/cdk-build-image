## AWS CodeBuild image for CDK

This Docker image builds the toolset for building serverless (and other) applications with the Amazon Cloud Developer Toolkit.

### Contents

_Base Image_: amazon/aws-lambda-python:3.9

The image has the following tools installed.

- Python 3.9.13
- Node 16.17.0
- NPM 8.15.0
- Pipenv 2022.8.19
- Pip 22.0.4
- CDK Version 2.37.1

Source available [here](https://github.com/learncloudops/cdk-build-image)