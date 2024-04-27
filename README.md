# git-hacking-nasa

## Partie 1 : Configuration et Premier Commit
1. **Créer un nouveau dossier pour votre projet et l'initialiser avec Git :**
   ```bash
   mkdir tutoriel-git-drole
   cd tutoriel-git-drole
   git init
   ```

2. **Créer le fichier HTML initial et le valider sur la branche principale (main) :**
   - Écrire le contenu HTML de votre fichier (le copier de la version1)
   - Valider dans la branche principale.
   ```bash
   git add index.html
   git commit -m "Commit initial avec configuration standard"
   ```

# Partie 2 : Branch "nasanothacked"
1. **Créer et passer à la branche 'nasanothacked' :**
   ```bash
   git checkout -b nasanothacked
   ```

2. **Faire des modifications drôles sans pirater la NASA (par exemple, changer l'image de fond pour la fusée) :**
   - Modifier le fichier HTML et CSS.
   - Valider les changements.
   ```bash
   git add index.html
   git commit -m "Fond avec fusée dessinée, NASA non piratée"
   ```

### Partie 3 : Branch "nasahacked"
1. **Revenir à la branche principale et créer la branche 'nasahacked' :**
   ```bash
   git checkout main
   git checkout -b nasahacked
   ```

2. **Faire des modifications indiquant que la NASA a été piratée (par exemple, ajouter un alien dansant) :**
   - Modifier le fichier HTML pour inclure des éléments amusants comme un alien dansant (le copier de la version2).
   - Valider les changements.
   ```bash
   git add index.html
   git commit -m "Alien dansant ajouté, NASA piratée!"
   ```

### Partie 4 : Pousser sur GitHub
- **Ajouter le dépôt distant et pousser toutes les branches :**
   ```bash
   git remote add origin [URL de votre dépôt]
   git push -u origin main
   git push origin nasanothacked
   git push origin nasahacked
   ```

### Conclusion : Comparer les Branches
- **Utiliser `git log`, `git diff`, et `git checkout` pour explorer et présenter les différences entre les branches.**
- **Discutons de l'importance des branches dans la gestion de projets et comment elles permettent de tester différentes fonctionnalités de manière isolée.**
