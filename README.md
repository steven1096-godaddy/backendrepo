# Simple FastAPI Backend Containerized Application

## Overview

This repository contains a simple Fast API application. 

The application image will be built and run locally with Docker & Docker Compose. 

In the Cloud, it will use Github as version control & as a trigger to build and store the app image in Amazon Elastic Container Registry (ECR).
The app will run on the the Elastic Container Service (ECS) using the Fargate platform.
