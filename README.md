<p>
1•  Que fait la commande git init ?
•	git init est utilisé pour initialiser un nouveau dépôt Git vide. Cela crée un nouveau sous-dossier nommé .git dans le répertoire actuel, qui contient tous les fichiers nécessaires pour suivre les modifications de votre projet.
2•  Expliquez ce que fait git clone.
•	git clone est utilisé pour créer une copie locale d'un dépôt Git distant. Il récupère tous les fichiers, l'historique et les branches du dépôt distant spécifié et crée une copie complète sur votre machine locale.
3•  Quelle est la fonction de git add ?
•	git add est utilisé pour ajouter des modifications à l'index (aussi appelé la "zone de staging") en vue de préparer un commit. Il permet de spécifier quels fichiers ou quels changements dans les fichiers doivent être inclus dans le prochain commit.
4•  Décrivez ce que fait git commit.
•	git commit crée un instantané des modifications qui ont été ajoutées à l'index via git add. Chaque commit est accompagné d'un message descriptif qui indique les changements apportés. Les commits constituent l'historique des modifications dans un projet Git.
5•  Qu'est-ce que git status affiche ?
•	git status affiche l'état actuel du répertoire de travail et de la zone de staging. Il montre quels fichiers ont été modifiés et qui sont prêts à être commités, quels fichiers sont suivis par Git mais non encore mis en staging, et d'autres informations pertinentes comme la branche courante.
6•  À quoi sert git diff ?
•	git diff montre les différences entre les modifications qui ne sont pas encore ajoutées à la zone de staging (git diff) ou entre la zone de staging et le dernier commit (git diff --staged). Cela permet de voir les changements ligne par ligne dans les fichiers.
7•  Comment utilise-t-on git log ?
•	git log affiche l'historique des commits. Par défaut, il liste tous les commits, du plus récent au plus ancien, avec des détails comme l'auteur du commit, la date et l'heure, et le message de commit associé. Il existe de nombreuses options pour filtrer ou formater la sortie de git log.
8•  Que fait git branch ?
•	git branch est utilisé pour lister, créer ou supprimer des branches dans un dépôt Git. Lorsqu'il est utilisé sans arguments, il liste toutes les branches présentes dans le dépôt local. Pour créer une nouvelle branche, on utilise git branch <nom-de-branche>.
9•  Expliquez git checkout.
•	git checkout est une commande polyvalente dans Git. Principalement, elle est utilisée pour naviguer entre les branches existantes (git checkout <nom-de-branche>) ou pour restaurer des fichiers à partir de la zone de staging (git checkout -- <nom-de-fichier>). Elle peut également être utilisée pour créer des nouvelles branches (git checkout -b <nom-de-nouvelle-branche>) et pour passer d'une branche à une autre.
10•  À quoi sert git merge ?
•	git merge est utilisé pour fusionner une branche avec une autre branche active. Il combine les modifications apportées dans la branche spécifiée avec la branche actuelle. Cela crée un nouveau commit qui rassemble les deux histoires de la branche.
11•  Quelle est la différence entre git merge et git rebase ?
•	git merge fusionne les modifications de deux branches en créant un nouveau commit de fusion. En revanche, git rebase déplace les commits d'une branche sur le dessus d'une autre branche, en réécrivant l'historique de la branche. Cela donne un historique linéaire et propre, mais cela modifie l'historique de la branche, ce qui peut poser problème lorsqu'il y a plusieurs contributeurs travaillant sur la même branche.
12•  Comment utilise-t-on git stash ?
•	git stash est utilisé pour enregistrer temporairement les modifications qui ne sont pas prêtes à être commitées. Cela est utile lorsque vous devez passer à une autre tâche rapidement sans vouloir committer vos changements actuels. Pour utiliser git stash, vous exécutez git stash pour mettre en stash vos modifications. Pour appliquer ces modifications plus tard, vous pouvez utiliser git stash apply ou git stash pop pour appliquer et supprimer le stash de la pile.
13•  Que fait git fetch ?
•	git fetch récupère les derniers commits à partir d'un dépôt distant, mais il ne fusionne pas ces modifications avec votre branche locale. Il met à jour les références locales des branches distantes, vous permettant de voir ce qui a été modifié dans le dépôt distant sans effectuer de fusion.

14•  Décrivez l'utilisation de git pull.
•	git pull récupère les derniers commits d'un dépôt distant et fusionne automatiquement ces modifications avec votre branche locale active. C'est essentiellement un raccourci pour git fetch suivi de git merge pour fusionner les modifications récupérées.
15•  Quelle est la fonction de git push ?
•	git push est utilisé pour pousser les commits locaux d'une branche vers un dépôt distant. Cela met à jour le dépôt distant avec vos modifications locales, rendant ainsi votre travail accessible aux autres collaborateurs du projet.
16•  Expliquez ce que fait git remote.
•	git remote permet de gérer les dépôts distants associés à votre projet Git. Cela inclut l'ajout, la suppression et la gestion des références aux dépôts distants. Par exemple, git remote add origin <url-du-depot> lie votre dépôt local à un dépôt distant nommé "origin".
</p>
