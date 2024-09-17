[Getting started]
(https://docs.getpelican.com/en/3.1.1/getting_started.html)

Lancer Pelican :
.\env\Scripts\activate

Regarder si il y a de nouveaux fichiers :
pelican content

Lancer le site web :
pelican -l

Regarder le site web :
[http://127.0.0.1:8000](http://127.0.0.1:8000)

# Installer un thème :

1. cloner le depot git du theme dans le dossier du projet
2. ajouter le nom du theme dans le fichier pelicanconf.py
3. exectuter la commande :
   `pelican-themes --install ./pelican-blue-master --verbose`
