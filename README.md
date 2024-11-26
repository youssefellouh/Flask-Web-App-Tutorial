# Flask Web App Tutorial 🌐

Ce projet est une application web de base utilisant Flask, conçue pour illustrer les concepts fondamentaux d'un projet Flask structuré.

## 📖 Aperçu du projet

Cette application comprend des fonctionnalités de base comme :
- Authentification (connexion et inscription)
- Une page d'accueil personnalisée
- Un design minimal avec HTML et JavaScript

Lien du projet : [Flask Web App Tutorial](https://github.com/youssefellouh/Flask-Web-App-Tutorial)

---

## 🔧 Prérequis

- Python 3.8 ou version ultérieure
- pip (Python Package Installer)

---

## 🚀 Installation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/youssefellouh/Flask-Web-App-Tutorial.git
2. Accédez au répertoire du projet :
```bash
cd Flask-Web-App-Tutorial
```
3. Installez les dépendances nécessaires :
``` bash
pip install -r requirements.txt
```
## ▶️ Exécution de l'application
1. Lancez l'application :
``` bash
python main.py

```
2.Ouvrez votre navigateur et accédez à :
```bash
http://127.0.0.1:5000
```
## 📂 Structure du projet
```bash
Flask-Web-App-Tutorial/
├── main.py              # Fichier principal pour lancer l'application
├── README.md            # Documentation du projet
├── requirements.txt     # Dépendances Python
└── website/             # Répertoire principal de l'application
    ├── __init__.py      # Initialisation de l'application Flask
    ├── auth.py          # Gestion des routes d'authentification
    ├── models.py        # Modèles de base de données
    ├── views.py         # Routes principales
    ├── static/          # Fichiers statiques (JS, CSS, images)
    │   └── index.js
    └── templates/       # Fichiers HTML
        ├── base.html
        ├── home.html
        ├── login.html
        └── sign_up.html
```

