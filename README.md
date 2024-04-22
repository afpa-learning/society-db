# Base de données d'apprentissage

Ce dépôt contient la correction des exercices portant sur la base de données "society" utilisée en formation à l'Afpa.

Vous y retrouverez :
- les fichiers de configuration Docker ;
- les scripts de création de base de données (plusieurs branches sont disponibles suivant le SBGDR souhaité) ;
- les solutions aux exercices de requêtage.


## Déploiement de la base de données Docker

Pour déployer la base de données en local, exécutez la commande suivante :
```bash
docker compose -d
```

Veillez à faire attention au conflits de ports.
Modifiez la redirection de port en fonction.

## Acccès à la BDD "society"

Connexion via phpMyAdmin : [http://localhost:8080/index.php](http://localhost:8080/index.php)

Utilisateur : **app_user**
Mot de passe : **supersecured**

Vous pouvez également vous connecter en utilisant un client de BDD tel que :
- [DBeaver](https://dbeaver.io/) -> pour l'installation avec [winget](https://winget.run/pkg/dbeaver/dbeaver)
- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)