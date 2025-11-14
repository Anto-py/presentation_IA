# 🚀 Guide d'installation rapide - GitHub Pages

## Étapes pour déployer votre site :

### 1. Créer un nouveau repository sur GitHub
- Allez sur https://github.com/new
- Nommez-le : `chatbot-personality-guide`
- Laissez-le en Public
- Ne pas initialiser avec README (vous l'avez déjà)
- Cliquez sur "Create repository"

### 2. Uploader les fichiers
#### Option A : Via l'interface GitHub
- Sur la page du nouveau repo, cliquez sur "uploading an existing file"
- Glissez-déposez tous les fichiers et dossiers :
  - `index.html`
  - Dossier `css/`
  - Dossier `js/`
  - Dossier `images/`
  - `README.md`
  - `LICENSE`
  - `.gitignore`
- Ajoutez un message de commit : "Initial commit - Chatbot personality guide"
- Cliquez sur "Commit changes"

#### Option B : Via Git en ligne de commande
```bash
# Dans le dossier du projet
git init
git add .
git commit -m "Initial commit - Chatbot personality guide"
git branch -M main
git remote add origin https://github.com/[votre-username]/chatbot-personality-guide.git
git push -u origin main
```

### 3. Activer GitHub Pages
- Dans votre repository, allez dans `Settings` (⚙️)
- Descendez jusqu'à la section `Pages` dans le menu de gauche
- Source : sélectionnez `Deploy from a branch`
- Branch : sélectionnez `main`
- Folder : sélectionnez `/ (root)`
- Cliquez sur `Save`

### 4. Accéder à votre site
- Attendez 2-3 minutes
- Votre site sera accessible à :
  ```
  https://[votre-username].github.io/chatbot-personality-guide/
  ```
- L'URL exacte s'affiche en haut de la section Pages

## 📝 Notes importantes

- Le déploiement initial peut prendre jusqu'à 10 minutes
- Les mises à jour futures sont généralement visibles en 1-2 minutes
- Assurez-vous que le repository est Public
- Le fichier principal doit s'appeler `index.html`

## 🔧 Dépannage

Si le site ne s'affiche pas :
1. Vérifiez que GitHub Pages est bien activé
2. Attendez quelques minutes de plus
3. Videz le cache de votre navigateur (Ctrl+F5)
4. Vérifiez l'orthographe de l'URL
5. Assurez-vous que tous les chemins dans le code sont relatifs

## ✅ Test local avant déploiement

Pour tester localement :
1. Ouvrez simplement `index.html` dans votre navigateur
2. Ou utilisez un serveur local :
   - Extension "Live Server" dans VS Code
   - Python : `python -m http.server 8000`
   - Node.js : `npx http-server`

---

💡 **Astuce** : Activez les Actions dans l'onglet Actions de votre repo pour voir le statut du déploiement.

📧 **Support** : En cas de problème, consultez la [documentation GitHub Pages](https://docs.github.com/pages)
