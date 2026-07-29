# cristal-backend

cristal-backend service

## Stack
- Langage : ${{ values.language }}
- CI/CD : Tekton → Harbor → ArgoCD
- Plateforme : DxP

## Démarrage rapide
```bash
# Cloner le repo
git clone <repo-url>
cd cristal-backend

# Lancer en local
docker build -t cristal-backend .
docker run -p 8080:8080 cristal-backend
```
