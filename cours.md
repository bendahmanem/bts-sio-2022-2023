### Dev web 

Ceci est une commande : 
``` bash
    mkdir test
```

Ceci est du code : 
``` javascript
const test = 'Hello World';
```



Le depot Git ou repository est le dossier qui contient les donnees que l'on souhaite versionner. On y trouve un dossier cache `.git/`.

La commande :
```
git init 
```
permet d'initialiser un depot Git. Elle retourne : 
```
Initialized empty Git repository in C:/Users/porta/Programmation/BTS/.git/
```


Pour verifier l'etat de votre depot Git utiliser la commande : 
```
 git status 
```




`git init`: Permet d'initialiser un depot git local dans le repertoire courant. Cela se traduit par la presence d'un dossier cache `.git/` a la racine du depot.

L'edition ou l'ajout de fichier dans ce repo sera detecte par Git, pour le visualiser dans le terminal on utilise la commande : 

```
    git status
```
une modification

Avant de sauvegarder les modifications, il faut ajouter les modifications que l'on souhaite sauvegarder avec la commande : 
```
    git add <nom de fichier>
```

La sauvegarde s'effectue ensuite avec la commande: 

```
 git commit -m "message de commit"
```
