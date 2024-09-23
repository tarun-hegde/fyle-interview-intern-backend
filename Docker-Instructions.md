# Running with docker

## Build image

- Build the docker image using following command

    ```bash
    docker build -t flask-app .
    ```

## Run the Docker container:

- This will start the Flask application, and it will be accessible at http://localhost:7755.

    ```bash 
    docker run -p 7755:7755 flask-app
    ```
    



## Run container

- Use the docker compose command to run the container as follows

    ```bash
    docker compose up -d
    ```