# e-Animal

Plateforme web de mise en relation entre propriétaires d'animaux
et services animaliers (vétérinaires, professionnels du secteur).

## Fonctionnalités
- Authentification sécurisée des utilisateurs (JWT)
- Publication et gestion d'annonces liées aux animaux
- Gestion des profils d'animaux (espèces, races) et des vétérinaires
- Upload et gestion des photos
- API REST documentée (Swagger via FastAPI)

## Stack technique
- Back-end : FastAPI (Python), SQLModel, MySQL, JWT (python-jose)
- Front-end : React
- Communication : API REST

## Installation
### Back-end
​```bash
cd zoo_back
pip install -r requirements.txt
uvicorn main:app --reload
​```
API disponible sur http://localhost:8000 — documentation sur http://localhost:8000/docs

### Front-end
​```bash
cd zoo_front
npm install
npm run dev
​```

## Auteur
Jérôme GBOSSA
