# Docker_Basics

-	Create a Dockerfile for a Python application that runs a simple script (app.py) that prints "Hello, DevOps Intern!"
-	Build and run the Docker image locally.
-	Share the steps to build, run, and stop the container.

## Steps
1. Create a `Dockerfile` as shown in [Dockerfile](./Dockerfile);
2. Create a Python script `app.py` as shown in [app.py](./app.py);
3. Build the Docker image:
   ```bash
   docker build -t python-app .
4. Run the container:
    ```bash
   docker run --name python-container python-app

note: Using python:3.9-slim in the Dockerfile, the container automatically stops after script execution.
