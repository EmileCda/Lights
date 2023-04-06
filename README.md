# Lights

# Cahier des charges

## Préparation

    1. Créer une classe Lights
    2. Lui ajouter 4 attributs boolean : light_A, light_B, light_C et light_D représentant 4 lumières éteintes par défaut
    3. Ajouter une méthode pour chaque lampe toggle_A, toggle_B, etc... inversant sa valeur
    4. Ajouter la méthode toString retournant une chaine du style : "A: Off / B: On etc..."
    5. Ajouter une méthode all_on retorunatn true si toutes les lampes sont allumées

## Utilisation

    6. Créer une classe Interface contenant une unique méthode statique run
    7. Cette méthode run demande au joueur d'entrer le nom d'une commande (chaine de caractère)
    8. On déclenchera une Commande en fonction de ce qu'a entré l'utilistateur, et ce jusqu'à ce que toutes les lampes soient allumées

    9. Créer une classe Commandes contenant un ensemble de méthodes statique dont
        9.1 La méthode "bambi" qui toggle A et C
        9.2 La méthode "peterpan" qui toggle B et C
        9.3 La méthode "shrek" qui toggle A, B et D

    10. Chaque entrée de l'utilisateur déclenche la commande associée (Commandes.shrek() par exemple)

# Intallation

1. Cloner le repository
2. compiler le programme : `javac Main.java`
3. lancer le programme : `java Main`

# Ce programme a été créé avec les versions de java suivantes

```sh
javac --version

javac 19.0.2
```

```sh
java --version

java 19.0.2 2023-01-17
Java(TM) SE Runtime Environment (build 19.0.2+7-44)
Java HotSpot(TM) 64-Bit Server VM (build 19.0.2+7-44, mixed mode, sharing)

```

# Sinon (pas d'installation)

1. récuperer dist/Lights.jar
1. exécuter la commande suivante : `java -jar Lights.jar`
