## Save un référentiel

- `git add .` ou `git add FICHIER`
- `git commit [ -S ] -m "first commit"`
- `git push origin master`


## Créez un nouveau référentiel sur la ligne de commande

- `git init`
- `git add .` ou `git add FICHIER`
- `git commit [ -S ] -m "first commit"`
- `git remote add origin URL_GIT`
- `git push origin master`


## Prendre un référentiel existant depuis la ligne de commande

- `git init`
- `git remote add origin URL_GIT`
- `git pull origin master`


## Gerer les branches d'un repository

**CREER UNE BRANCH**

- `git branch NOM_DE_BRANCH` (Créer une branche)
- `git checkout -b NOM_DE_BRANCH` (Créer une branche + switch dedans)

**LIST BRANCH**

- `git branch`

**SEARCH BRANCH**

- `git fetch`

**SWITCH BRANCH**

- `git checkout NOM_DE_LA_BRANCH`

**FUSION BRANCH**

- `git merge NOM_DE_LA_BRANCH` (Fusionne la branche mentionné avec la branche courante)

**DELETE BRANCH**

- `git branch -d NOM_DE_LA_BRANCH`


## Supprimé les commit

- `git checkout --orphan temp_branch`
- `git add -A`
- `git commit -am "Le premier commit"`
- `git branch -D master`
- `git branch -m master`
- ` git push -f origin master`


## Configuration

**USERNAME**

- `git config --global user.name "USERNAME"`

**EMAIL**

- `git config --global user.email "EMAIL"`

**NAME & PASSWORD**

- `git config --global credential.helper store`

**SIGNATURES**

- `git config commit.gpgsign true`
- `git config --global commit.gpgsign true`
