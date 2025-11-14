# Guide des Chatbots IA - Quel assistant te correspond ?

Une interface interactive pour découvrir quel chatbot IA correspond le mieux à votre personnalité et vos besoins.

## 🎯 Objectif

Ce projet propose une approche originale pour présenter les différents chatbots IA du marché en les associant à des profils de personnalité. L'idée est d'aider les utilisateurs à choisir l'assistant qui leur correspond le mieux selon leur façon de travailler et de penser.

## ✨ Caractéristiques

- **Interface interactive** : Cliquez sur chaque carte pour découvrir les détails
- **Design moderne** : Interface responsive avec animations fluides
- **9 chatbots présentés** :
  - ChatGPT (OpenAI)
  - Gemini (Google)
  - Claude (Anthropic)
  - Mistral AI
  - Perplexity AI
  - Copilot (Microsoft)
  - DuckDuckGo AI Chat
  - HuggingChat (Hugging Face)
  - Option "Autre" pour les profils atypiques

## 🚀 Déploiement

### GitHub Pages

1. Fork ou clonez ce repository
2. Allez dans Settings > Pages
3. Sélectionnez "Deploy from a branch"
4. Choisissez la branche `main` et le dossier `/ (root)`
5. Sauvegardez et attendez quelques minutes
6. Votre site sera accessible à : `https://[votre-username].github.io/[nom-du-repo]/`

### Local

```bash
# Cloner le repository
git clone https://github.com/[votre-username]/chatbot-personality-guide.git

# Ouvrir index.html dans votre navigateur
# Ou utiliser un serveur local comme Live Server dans VS Code
```

## 📁 Structure du projet

```
chatbot-personality-guide/
├── index.html          # Page principale
├── css/
│   └── style.css      # Styles de l'application
├── js/
│   └── script.js      # Logique JavaScript
├── images/            # Logos des chatbots
│   ├── chatgpt.png
│   ├── claude.png
│   ├── gemini.jpeg
│   ├── mistral.png
│   ├── perplexity.png
│   ├── copilot.jpeg
│   ├── duckduckgo.png
│   └── huggingchat.png
└── README.md          # Documentation
```

## 🎨 Personnalisation

### Modifier les descriptions

Éditez le fichier `index.html` pour changer les textes de chaque chatbot :

```html
<p class="description-quote">« Votre citation personnalisée »</p>
<p class="description-profile">Votre profil cible</p>
```

### Ajouter un nouveau chatbot

1. Ajoutez l'image dans le dossier `images/`
2. Dupliquez une carte existante dans `index.html`
3. Modifiez les informations (titre, description, lien)
4. Ajoutez une classe CSS si nécessaire dans `style.css`

### Modifier les couleurs

Les couleurs principales sont définies dans `css/style.css` :

```css
/* Gradient de fond */
body {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

/* Couleur d'accent */
.chatbot-card:hover {
    border-color: #667eea;
}
```

## 🔧 Technologies utilisées

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- JavaScript vanilla
- Design responsive

## 📱 Compatibilité

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Responsive (mobile, tablette, desktop)
- ✅ Support tactile

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commit vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 🙏 Remerciements

- Logos et marques appartiennent à leurs propriétaires respectifs
- Inspiré par la diversité des approches en IA conversationnelle

---

**Note** : Ce projet est à but éducatif et n'est pas affilié aux entreprises mentionnées.
