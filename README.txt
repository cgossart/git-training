TP2 � D�marrage du projet
Objectif
Le projet �tant d�marr�, les premi�res id�es vont-�tre versionn�es pour voir leur �volution et
permettre de retracer les diff�rentes id�es.
1. Premi�re id�e
� Cr�er � la racine un fichier README.txt contenant une description du projet (texte de
pr�sentation de ce TP) ainsi que TODO.txt contenant quelques id�es :
Sites � scanner :
- voyages-sncf.com
- ryanair.com
- eurolines.fr
- eurostar.com
Couleurs de l'application :
Rouge sur fond vert
Titre de l'application :
Resaspi
� Indexer les fichiers TODO.txt et README.txt
� Gr�ce � la commande git status v�rifier que les deux fichiers sont � �tre commit�s
2. Validation des id�es
� Afin de s�parer l'ajout des deux fichiers dans deux commits diff�rents, supprimer
TODO.txt de l'index actuel puis commiter
? Titre : "Initialisation du projet"
? Contenu : "Ajout du fichier README.txt d�crivant le projet"
� Puis re-indexer le fichier TODO.txt et commiter
? Titre : "D�finition des t�ches � effectuer"
? Contenu : "Cr�ation du fichier TODO.txt listant toutes les t�ches actuellement pr�vues
pour le projet"
� V�rifier que les deux fichiers sont biens commit�s dans deux commits diff�rents avec la
commande git log
3. Retour vers le premier commit
� Afin de pr�parer la cr�ation des futures branches, dont une pour g�rer la todolist, remontez
au commit initial avec la commande git checkout et le hash du premier commit qui est
accessible depuis le log (attention � l'ordre des commits affich�s par la commande git log)
� Lister le contenu du dossie

Les t�ches techniques � effectuer sont dans le
fichier TODO.txt
