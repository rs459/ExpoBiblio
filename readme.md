# expoBiblio

## Projet

expoBiblio est une application expo, qui reprend l'api symfony biblio avec une branche dédiée au projet, 100 livres ont été ajouté avec la libraire faker.

il y a deux repertoires, un pour le back symfony, et un autre pour l'application Expo, chaque repertoire est un repository Git.

Ce dépôt sert de dépôt parent pour deux sous-modules : `appExpoBiblio` et `bibliotheque-projet-backend`.

## Démarrage

Pour configurer et lancer le projet, suivez ces étapes :

1. **Cloner le dépôt :**

    ```bash
    git clone --recurse-submodules https://github.com/rs459/expoBiblio.git
    cd expoBiblio
    ```

    Si vous avez cloné sans `--recurse-submodules`, vous pouvez les initialiser après coup :

    ```bash
    git submodule update --init --recursive
    ```

2. **Naviguez vers le répertoire `bibliotheque-projet-backend` et suivez ses instructions :**

    ```bash
    cd bibliotheque-projet-backend
    # Référez-vous au fichier README.md dans bibliotheque-projet-backend pour les instructions de configuration spécifiques (par exemple, installation des dépendances, démarrage du serveur).
    ```

    **Attention le back-end étant utilisé pour plusieurs projet, il a une branche spécifique nommée appExpoBiblio**

3. **Naviguez vers le répertoire `appExpoBiblio` et suivez ses instructions :**

    ```bash
    cd ../appExpoBiblio
    # Référez-vous au fichier README.md dans appExpoBiblio pour les instructions de configuration spécifiques (par exemple, installation des dépendances, démarrage du serveur de développement).
    ```

En suivant ces étapes, vous aurez les composants backend et frontend d'expoBiblio configurés et prêts à être exécutés.
