Ceci est mon premier repo avec  GitHub

J'ai testé direct :

$ git clone https://github.com/Laurent-Gi/Test-Git-GitHub (je n'ai pas mis de destination rep)
Il m'a créé un répertoire rep = Test-Git-GitHub (Comme le repository créé sur GitHub)

équivalent de :
---------------
$ mkdir rep
$ cd rep
$ git init
$ git remote add origin https://github.com/Laurent-Gi/Test-Git-GitHub
$ git pull origin master
$ cd ..

Ce fichier va être repéré lors du prochain :
$ git status

YES :::: la réponse :::
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md.txt

nothing added to commit but untracked files present (use "git add" to track)

$ git add . (ou git add README.md)

$ git commit -m "Ajout du README"

ET POUR AVOIR QUELQUE CHOSE DANS GITHUB : IL FAUT FAIRE LE PUSH

$ git push origin master

(Linux me manque... je vais me créer une machine virtuelle !!!)
