Auteurs : Jérôme SAUVÉ, Alexandre MAINTIER
Date : 23/03/2025

Pour convertir notre fichier .md en .html :
    cat src/part/sem1.md src/part/interpart.md src/part/sem2.md src/part/interpart.md src/part/sem3.md src/part/interpart.md src/part/sem4.md > src/part/rapport.md
    télécharger pandoc
    utiliser la commande pandoc src/part/rapport.md -o src/rendu/rapport.html -c ./ressources/css/CSS.css -s --toc

Pour convertir notre fichier .html en .pdf :
    utiliser la commande pandoc src/rapport.html -o src/rapport.pdf