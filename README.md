# Transcompiler
Compilateur qui utilise la puissance du modèle GPT-3.5 d'OpenAI pour transformer le langage naturel en code
Transcompilateur
Création d'une app avec streamlit , flask, qui permet d'éxecuter du code grace l'api de open ai

Table des matières Installation Configuration de la base de données Configuration de l'API OpenAI Environnement virtuel Contribution Licence Installation Donnez ici des instructions générales pour installer votre projet.

Configuration de la base de données Exécuter le fichier transcompiler.sql dans une base de données MySQL adaptée. Aller dans le dossier config/ et ouvrir le fichier config.py. Renseigner les informations nécessaires pour votre clé OpenAI et les informations de votre base de données. Configuration de l'API OpenAI Indiquez ici toutes les étapes spécifiques pour configurer l'API OpenAI, si elles ne sont pas déjà couvertes dans la section précédente.

Environnement virtuel Installer votre environnement virtuel :

bash Copy code python -m venv .venv Activer l'environnement virtuel :

bash Copy code .venv/Scripts/activate Après avoir activé l'environnement virtuel et installé les dépendances nécessaires,

créez un fichier requirements.txt : pip install -r requirements.txt

bash Copy code pip freeze > requirements.txt Contribution Expliquez comment d'autres développeurs peuvent contribuer à votre projet s'ils le souhaitent.

Licence Indiquez la licence sous laquelle votre projet est publié, par exemple, MIT, GPL, etc.
