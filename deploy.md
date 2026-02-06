# Rapport de déploiement - [Hazza]
## Liens
- **Application en ligne :** 
    - https://happy-project.osc-fr1.scalingo.io/
- **Dépôt de code :** 
    - https://github.com/Khaled-Hazza/Happy

## Prérequis techniques
- **PHP 8.4**
- Composer installé
- Un compte Scalingo.com
## Fichier de configuration CI
- .github/workflows/ci.yaml
## Procédure de déploiement pas à pas
- creation de app 

## ajout de variable d'environment 
- APP_ENV = prod
- APP_SECRET = echo bin2hex(random_bytes(16))