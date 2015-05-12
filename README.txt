TP2 – Démarrage du projet
Objectif
Le projet étant démarré, les premières idées vont-être versionnées pour voir leur évolution et
permettre de retracer les différentes idées.
1. Première idée
• Créer à la racine un fichier README.txt contenant une description du projet (texte de
présentation de ce TP) ainsi que TODO.txt contenant quelques idées :
Sites à scanner :
- voyages-sncf.com
- ryanair.com
- eurolines.fr
- eurostar.com
Couleurs de l'application :
Rouge sur fond vert
Titre de l'application :
Resaspi
• Indexer les fichiers TODO.txt et README.txt
• Grâce à la commande git status vérifier que les deux fichiers sont à être commités
2. Validation des idées
• Afin de séparer l'ajout des deux fichiers dans deux commits différents, supprimer
TODO.txt de l'index actuel puis commiter
? Titre : "Initialisation du projet"
? Contenu : "Ajout du fichier README.txt décrivant le projet"
• Puis re-indexer le fichier TODO.txt et commiter
? Titre : "Définition des tâches à effectuer"
? Contenu : "Création du fichier TODO.txt listant toutes les tâches actuellement prévues
pour le projet"
• Vérifier que les deux fichiers sont biens commités dans deux commits différents avec la
commande git log
3. Retour vers le premier commit
• Afin de préparer la création des futures branches, dont une pour gérer la todolist, remontez
au commit initial avec la commande git checkout et le hash du premier commit qui est
accessible depuis le log (attention à l'ordre des commits affichés par la commande git log)
• Lister le contenu du dossie

Les tâches techniques à effectuer sont dans le
fichier TODO.txt
