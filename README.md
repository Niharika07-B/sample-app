# Sample App

This is a simple Go-based application deployed using Docker and Google Cloud.

## Overview

This project showcases a basic Go application with Docker and Google Cloud deployment pipelines. It includes configuration files for building and deploying the app in both development and production environments.

## Files

- **Dockerfile**: Used to build a Docker image for the app.
- **cloudbuild-dev.yaml**: Configuration for deploying the app in a development environment.
- **cloudbuild.yaml**: Configuration for deploying the app in a production environment.
- **main.go**: The main Go application file that runs the application.

## Technologies

- **Go**: The programming language used for the application.
- **Docker**: Used to containerize the app.
- **Google Cloud**: Used for cloud deployment and Continuous Integration/Continuous Deployment (CI/CD).

## Learning Resources

I learned how to build and deploy this application from the Google Cloud Skills Boost platform.

## Getting Started

To run this application locally:

1. Build the Docker image:
   ```bash
   docker build -t sample-app .
   ```

2. Run the Docker container:
   ```bash
   docker run -p 8080:8080 sample-app
   ```

3. Visit `http://localhost:8080` to see the app in action.

## Contributing

Feel free to fork the repository and submit pull requests for any improvements.

## License

This project is open-source and available under the MIT License.

---

