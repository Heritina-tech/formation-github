# Exercice 01 - Créer un dépôt et faire un commit

## 1. Créer un dépôt

Créez un nouveau dépôt sur GitHub, par exemple `test_github`, en cochant **Add a README file**.

## 2. Cloner le dépôt

```bash
git clone https://github.com/<votre-pseudo>/test_github.git
cd test_github
```

## 3. Premier projet simple : `index.html`

Créez un fichier `index.html` dans le dossier :

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Premier pas</title>
</head>
<body>
  <h1>Mon premier projet sur GitHub</h1>
</body>
</html>
```

## 4. Commit et push

```bash
git status
git add index.html
git commit -m "Ajout de index.html"
git push
```

---

Exercice suivant : [02-modifier-et-pull](../02-modifier-et-pull/README.md)
