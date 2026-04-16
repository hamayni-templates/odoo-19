# Odoo 19 — Hamayni Certified Template

## Description
Odoo 19 Community Edition — ERP/CRM open-source complet. Ce template inclut Odoo 19 + PostgreSQL 16.

## Prérequis
- Docker & Docker Compose
- Minimum 2 Go RAM recommandé

## Variables d'environnement
| Variable | Requis | Description | Défaut |
|----------|--------|-------------|--------|
| POSTGRES_DB | Non | Nom de la base | postgres |
| POSTGRES_USER | Non | Utilisateur PostgreSQL | odoo |
| POSTGRES_PASSWORD | **Oui** | Mot de passe PostgreSQL | — |

## Déploiement
```bash
docker-compose up -d
```

Odoo sera accessible sur le port **8069**. Le port **8072** est utilisé pour le longpolling.

## Licence
LGPL v3 — Odoo SA
