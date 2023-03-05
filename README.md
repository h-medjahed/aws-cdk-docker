# Docker AWS CDK
Containerised AWS CDK to ensure consistent local development.

## Build
Run this command:
    docker compose build

## Usage
Start docker container in the background:

    docker compose up -d

SSH into your docker container:

    docker compose run -it --rm aws-cdk /bin/bash

Check CDK is installed (it should result in some cdk help)

    cdk
