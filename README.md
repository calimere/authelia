# authelia

Ci-dessous la commande à lancer pour générer les mots de passe pour le compte

docker run authelia/authelia:latest authelia crypto hash generate argon2 --password 'XXXXXX'
