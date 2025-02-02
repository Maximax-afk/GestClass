# Projet Django - Gestion des Cours  

## 📌 Description  
Ce projet est une application Django permettant de gérer des cours, et ajouter un IA si le professeur est absent. Il comprend une structure de base, mais certains éléments sont encore en cours de finalisation.  

## 📌 Installation  
1. **Cloner le projet**  
   ```bash
   git clone https://github.com/ton-user/ton-projet.git
   cd ton-projet

2. Créer un environnement virtuel
python -m venv env
env\Scripts\activate  # Sur Windows

3. Installer les dépendances (même si les requirements.txt ne figurent pas dans le projet)
pip install django

4. Lancer l'app
python manage.py migrate
python manage.py runserver

 Le projet contient encore des erreurs et certaines fonctionnalités ne sont pas terminées.
Voici les principaux problèmes :
-Templates HTML manquants.
-Erreurs dans settings.py et urls.py qui empêchent le bon fonctionnement.
-Base de données SQLite incluse mais migrations à refaire.

Lors de la création du projet, j’ai rencontré des problèmes techniques qui m’ont empêché de finaliser toutes les fonctionnalités. Cependant, voici la structure de base du projet. Merci de votre compréhension:
GestCours/
│── db.sqlite3
│── manage.py
│── requirements.txt
│── GestCours/
│   │── __init__.py
│   │── settings.py
│   │── urls.py
│   │── asgi.py
│   │── wsgi.py
│── cours/
│   │── __init__.py
│   │── models.py
│   │── views.py
│   │── urls.py
│   │── admin.py
│   │── migrations/
│── templates/
│   │── base.html
│   │── index.html
│── static/
│   │── css/
│   │── js/
│   │── images/
│── README.md
│── .gitignore
  
Voici mon projet Django en l’état actuel. J’ai rencontré des difficultés techniques qui m’ont empêché de le finaliser complètement, mais j’ai structuré le projet et fourni un README expliquant les erreurs et les améliorations 

Je suis conscient que certaines fonctionnalités ne sont pas complètes, mais j’ai fait de mon mieux pour rendre un travail structuré malgré les contraintes.  

Merci pour votre compréhension.  

Cordialement,  
Andrianjafimanana Mahery Thierry  
L3IRD1, SE20220105  











