## Innitialisation & Depot d'un GIT

**[ STEP 1 : INNITIALISE ]**
- `git init`

**[ STEP 2 : ADD GIT ( Screen ) ]**
- `git add NOM_DU_FICHIER` (Pour un fichier) 
- `git add .` (pour tout le projet)
- `git add *.log` (pour tout les fichier .log)

**[ STEP 3 : COMMIT GIT ( Sauvegarde ) ]**
- `git commit -m "DESC_DE_LA_MODIF"`

**[ STEP 4 : GIT ADD REPOSITORY ]**
- `git remote add origin URL_REPOSITORY` (ajoute un répertoire distant)

**[ STEP 5 : PUSH IN REPOSITORY ]**
- `git push origin NAME_BRANCH` (Envoie sur le repertoire)

## Configuration Compte GIT

**[ USERNAME ]**
- `git config --global user.name "USERNAME"`

**[ EMAIL ]**
- `git config --global user.email "EMAIL"`

## Gestion des branch

**[ CREATE BRANCH ]**
- `git branch NOM_DE_BRANCH` (Créer une branche)
- `git checkout -b NOM_DE_BRANCH` (Créer une branche + switch dedans)

**[ LIST BRANCH ]**
- `git branch`

**[ SWITCH BRANCH ]**
- `git checkout NOM_DE_LA_BRANCH`

**[ FUSION BRANCH ]**
- `git merge NOM_DE_LA_BRANCH` (Fusionne la branche mentionné avec la branche courante)

**[ DELETE BRANCH ]**
- `git branch -d NOM_DE_LA_BRANCH`

## Récupére un repertoire

**[ PULL IN REPOSITORY ]**
- `git pull origin NAME_BRANCH` (Récupére le repertoire)

## Remove all commit

**[ DELETE HISTORY COMMIT ]**
- `git checkout --orphan temp_branch`
- `git add -A`
- `git commit -am "Le premier commit"`
- `git branch -D master`
- `git branch -m master`
- ` git push -f origin master`