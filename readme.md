# expoBiblio

## Projet

expoBiblio est une application expo, qui reprend l'api symfony biblio avec une branche dédiée au projet, 100 livres ont été ajouté avec la libraire faker.

il y a deux repertoires, un pour le back symfony, et un autre pour l'application Expo, chaque repertoire est un repository Git.

This repository serves as a parent repository for two submodules: `expoBiblio-frontend` and `expoBiblio-backend`.

## Getting Started

To set up and run the project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone --recurse-submodules https://github.com/your-username/expoBiblio.git
    cd expoBiblio
    ```

    If you cloned without `--recurse-submodules`, you can initialize them afterwards:

    ```bash
    git submodule update --init --recursive
    ```

2. **Navigate to the `expoBiblio-backend` directory and follow its instructions:**

    ```bash
    cd expoBiblio-backend
    # Refer to the README.md in expoBiblio-backend for specific setup instructions (e.g., installing dependencies, running the server).
    ```

3. **Navigate to the `expoBiblio-frontend` directory and follow its instructions:**

    ```bash
    cd ../expoBiblio-frontend
    # Refer to the README.md in expoBiblio-frontend for specific setup instructions (e.g., installing dependencies, running the development server).
    ```

By following these steps, you will have both the backend and frontend components of `expoBiblio` set up and ready to run.
