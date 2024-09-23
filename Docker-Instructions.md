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
    



## Run the Docker Compose command

- This will build the Docker image and start the Flask application, accessible at http://localhost:7755

    ```bash
    docker compose up -d
    ```

- This will stop and remove the containers, networks, and volumes created by docker-compose up

    ```bash
    docker compose down
    ```
    
