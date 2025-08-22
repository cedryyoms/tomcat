# Rôle: Tomcat

## Présentation

Ce rôle Ansible a pour objectif d'automatiser l'installation, la configuration et la mise en service d'Apache Tomcat sur des systèmes Linux


## Prérequis

Votre projet doit contenir des fichiers KEY et CRT au nom du serveur dans le dossier files/ssl/NOMDUSERVEUR(.key,.crt). Les fichiers Key doivent être cryptés.

```bash
ansible-vault encrypt 
```

## Paramètres

### Inventaire

* inventory_staging_ip: Point de terminaison NFS qui contient le partage /staging

### Voutes

Aucun

### Global
Aucun

### Environnement

```yaml
env4: # Code à 4 lettres de l'environnement.
env3: # Code à 3 lettres de l'environnement.
env2: # Code à 2 lettres de l'environnement.

# Configuration générale de l'environnement
env_alias:
 

```yaml

### Défauts

La liste des ports à ouvrir sur le parfeu.
