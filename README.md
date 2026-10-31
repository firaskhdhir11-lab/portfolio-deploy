# TP2 — Déploiement d'un Portfolio Next.js avec Coolify et Forgejo

## 1. Objectif du TP

L'objectif de ce TP est de mettre en place une plateforme de déploiement
automatisé pour une application Portfolio développée avec Next.js et Express.

La solution utilise :
- **Forgejo** : hébergement du code source Git.
- **Coolify** : gestion et déploiement des applications.
- **Traefik** : reverse proxy et routage HTTP.
- **Docker** : conteneurisation des applications.

## 2. Environnement de travail

| Composant | Configuration |
|---|---|
| Système | Ubuntu 26.04.1 LTS |
| Docker | 29.1.3 |
| Coolify | v4.5.3 |
| Forgejo | Image version 17 |
| Serveur | VM Ubuntu |
| Adresse IP utilisée | 192.168.10.129 |

## 3. Installation de Coolify

Installation de Coolify avec la commande :

```bash
curl -fsSL https://cdn.coollabs.io/coolify/install.sh | sudo bash
