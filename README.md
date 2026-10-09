# Git and Docker Starter Application

This repository contains a small Python web application used to practice Git, GitHub, and Docker workflows.

## Application

The application listens on port 8000 and returns a text response when accessed over HTTP.

## Verification

The running application should be verified using an HTTP request to port 8000.

## Usage

Build Docker Image:

docker build -t git-docker-app:test . 

Run Application:

docker run --rm -p 8000:8000 git-docker-app:test

Then access application at http://localhost:8000
