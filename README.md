# fakeapi

## Installation et lancement

#### 1. npm install -g json-server
#### 2. json-server --watch db.json
<br>

#### Le serveur est disponible sur http://localhost:3000
<br>

## Requêtes HTTP
<br>

### POST
#### Connexion avec le compte suivant : 

##### http://localhost:3000/users
```
username: admin
password: admin
``` 
### GET
#### Obtenir la liste des employés
##### http://localhost:3000/employees

<br>

### POST
#### Créer un employé
##### http://localhost:3000/employees
##### avec en paramètres de la requête POST :

``` 
{
    "first_name": "xxx",
    "last_name": "xxx",
    "email": "xxx",
}
```

### PUT
#### Modifier un employé avec son id
##### http://localhost:3000/employees/{id}
<br>

### DELETE
#### Supprimer un employé avec son id
##### http://localhost:3000/employees/{id}


