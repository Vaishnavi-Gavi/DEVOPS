# DEV Project

A simple web application served using Nginx.

## Description

This project contains a basic HTML page that displays a welcome message for DEVOPS.

## Files

- `index.html`: The main HTML page.
- `Dockerfile`: Docker configuration to build an Nginx image with the HTML page.
- `.github/workflows/deploy.yml`: GitHub Actions workflow for deployment.

## Running Locally

To run the application locally using Docker:

```bash
docker build -t dev-app .
docker run -p 80:80 dev-app
```

Then, open your browser to `http://localhost`.

## Deployment

The project is configured for deployment via GitHub Actions as defined in `.github/workflows/deploy.yml`.
