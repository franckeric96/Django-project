# Django-project
**__comment créer son prmier projet django__**
-----------------------------------------

1. Créer son environnement virtuel et on l'active
==================================================
* Sur MAC: python -m venv venv
          source venv/bin/activate 
* Sur Window:python -m venv venv 
            venv/Script/activate 

2. Installer djanjo:
====================
* pip install django== " version qui nous intérest "

3. Créer son projet en effectuant:
==================================
* django-admin startproject nameproject

4. Exécuter la commande suivante pour lancer la prémière fois le projet
=======================================================================
* python manage.py runserver  

5. Faire la mise à jour pour créer la partie administration
==========================================================
* python manage.py migrate

6. Créer l'administration
========================
* python manage.py createsuperuser
