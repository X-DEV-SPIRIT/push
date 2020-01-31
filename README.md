## Créez un nouveau référentiel sur la ligne de commande

- `git init`
- `git add .` ou `git add FICHIER`
- `git commit -m "first commit"`
- `git remote add origin URL_GIT`
- `git push origin master`


## Prendre un référentiel existant depuis la ligne de commande

- `git init`
- `git add .` ou `git add FICHIER`
- `git commit -m "first commit"`
- `git remote add origin URL_GIT`
- `git pull origin master`


## Gestion les branch d'un repo

**CREER UNE BRANCH**

- `git branch NOM_DE_BRANCH` (Créer une branche)
- `git checkout -b NOM_DE_BRANCH` (Créer une branche + switch dedans)

**LIST BRANCH**

- `git branch`

**SWITCH BRANCH**

- `git checkout NOM_DE_LA_BRANCH`

**FUSION BRANCH**

- `git merge NOM_DE_LA_BRANCH` (Fusionne la branche mentionné avec la branche courante)

**DELETE BRANCH**

- `git branch -d NOM_DE_LA_BRANCH`


## Remove all commit

**DELETE HISTORY COMMIT**

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

**SIGNATURES**

- `git config commit.gpgsign true`
- `git config --global commit.gpgsign true`
