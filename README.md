# ARPAB Project Docker Compose

Questo repository contiene la configurazione Docker Compose per il progetto ARPAB, che include sia il backend che il frontend.

## Prerequisiti

- Docker
- Docker Compose

## Configurazione

1. Clona questo repository:

    ```sh
    git clone https://github.com/SteCard/arpab-docker-compose.git
    cd arpab-docker-compose
    ```

2. Clona il repository del backend:

    ```sh
    git clone https://github.com/SteCard/arpab-app-Api.git
    ```

3. Clona il repository del frontend:

    ```sh
    git clone https://github.com/aysenurtutal/arpab-app-frontend-.git (master branch)
    ```

4. Costruisci e avvia i container:

    ```sh
    docker-compose up --build
    ```

## Accedi ai servizi

- **Frontend**: http://localhost:5000
- **Backend**: http://localhost:3001
- **phpMyAdmin**: http://localhost:8080
