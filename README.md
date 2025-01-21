# netdisco-links-2csv

Extrait les données de liens entre éléments réseau depuis la base
de donnée du service [netdisco](https://netdisco.org/). Génère un fichier CSV.

## dependances

Si lança de la machine netdisco, les deps devraient être satisfaite. Sinon:

```shell
$ sudo apt install libdbi-perl libdb-pg-perl
```

## utilisation

La plus simple, en root depuis la machine hébergeant la BDD netdisco (s'assurer
que l'utilisateur postgres à les autorisations correctes pour executer le 
script)

```shell
# sudo -i -u postgres /bin/netdisco-links-2csv > links.csv
```

