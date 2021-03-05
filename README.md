# Recensioni Film

Piattaforma nella quale si può visualizzare e votare film prelevati da [http://www.omdbapi.com](http://www.omdbapi.com/).
Ogni utente può votare una sola volta uno stesso film e visualizzare la classifica con con la media dei voti degli altri utenti.
Il frontend è realizzato in react.

# API

L'applicativo è hostato su EC2 tramite l'utilizzo di un container di docker, il database è hostato su RDS.
Le istanze di EC2 e RDS vengono create con Terraform.
