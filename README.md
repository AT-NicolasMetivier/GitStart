# GitStart

Premirere journée de formation Git.



## Aide pour l'utilisation de GIT.



1. Aller sur le site de GitHub.
(github.com)

2. Créer un compte ou se connecter.

3. Créer un nouveau répertoire (new repository).


Créer un nouveau répertoire en ligne de commande.
--------------------------------------------------------------------
	1. Créer un répertoire qui va contenir un projet.
	(mkdir "MonProjet")

	2. Se placer dans le projet.
	(cd "MonProjet")

	3. Créer du contenu dans le projet.
	(echo "# MonProjet" >> README.md)

	4. Initialiser le Git local, la base de fichiers.
	(git init)

	5. Mettre à jour la révision (modification réalisé en le moment T0 et T1)
	(git add README.md OU git add .)

	6. Ajouter la révision dans la base de fichier. (Valider l'ajout des révisions.)
	(git commit -a -m "Ceci est un commentaire et il est obligatoire de le mettre 
	lorsqu'un COMMIT est réalisé. Il permet de decrire les modifications que 
	comporte la révision.")

	7. On connecte notre Git local (la base de fichier locale) au site de GitHub (la base de fichier distante).
	(git remote add origin https://github.com/VotreNomUtilisateurGitHub/MonProjet.git)

	8. On upload (on pousse) le contenu de la base de fichier local sur la base de fichiers distant (Local -> Distant).
	(git push -u origin master)

