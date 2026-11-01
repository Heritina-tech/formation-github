# Exercice 03 - Branches, merge et pull request

## 1. Lister les branches

```bash
git branch
```

## 2. Créer une branche ( Collaborator)

```bash
git switch -c feature_a
```

Ajoutez un paragraphe dans `index.html`, sous le `<h1>` :

```html
<p>J'apprends Git et GitHub.</p>
```

```bash
git add index.html   # ou git add .
git commit -m "Ajout d'un paragraphe"
git push -u origin feature_a
```

## 3. Fusionner la branche (merge)

```bash
git switch main
git merge feature_a
git push
git branch -d feature_a
git push origin --delete feature_a
```

## 4. Pull request

```bash
git switch -c feature_b
```

Ajoutez un lien dans `index.html` :

```html
<a href="https://github.com/">Mon GitHub</a>
```

```bash
git add index.html
git commit -m "Ajout d'un lien"
git push -u origin feature_b
```

Sur GitHub :

1. Cliquez sur **Compare & pull request**.
2. Cliquez sur **Create pull request**.
3. Cliquez sur **Merge pull request**, puis sur **Confirm merge**.

Puis récupérez le résultat :

```bash
git switch main
git pull
```
