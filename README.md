# 🔐 Générateur Sécurisé

Un générateur de mots de passe et de noms d'utilisateur sécurisés avec interface moderne et effet Matrix.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Fonctionnalités

### 🔑 Générateur de Mots de Passe
- **Cryptographie sécurisée** : Utilisation de `crypto.getRandomValues()`
- **Personnalisation complète** : Longueur de 8 à 32 caractères
- **Options flexibles** : Majuscules, minuscules, chiffres, symboles
- **Indicateur de force** : Analyse en temps réel de la robustesse
- **Copie en un clic** : Bouton de copie intégré

### 👤 Générateur de Noms d'Utilisateur
- **4 styles de génération** :
  - Adjectif + Nom (ex: BravePhoenix)
  - Nom + Adjectif (ex: PhoenixBrave)
  - Fantaisie (ex: Eldrithar)
  - Technologique (ex: CyberNova)
- **Options personnalisables** : Ajout de chiffres et underscores
- **Indicateur d'originalité** : Évaluation de l'unicité du pseudo

### 🎨 Design & Interface
- **Effet Matrix animé** : Arrière-plan dynamique avec caractères en cascade
- **Glassmorphism** : Interface moderne avec effet de verre
- **Effet néon bleu** : Textes illuminés pour une meilleure visibilité
- **Icônes Font Awesome** : Design professionnel
- **Responsive** : Compatible tous appareils

## 🚀 Démo en ligne

[Voir la démo](https://johan-agouni.github.io/secure-password-generator/)

## 📸 Captures d'écran

### Page d'accueil
![Accueil](screenshots/accueil.png)

### Générateur de mots de passe
![Mot de passe](screenshots/password.png)

### Générateur de pseudos
![Pseudo](screenshots/username.png)

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Animations, glassmorphism, effets néon
- **JavaScript (Vanilla)** : Logique de génération sécurisée
- **Font Awesome 6.5.1** : Icônes modernes
- **Crypto API** : Génération cryptographiquement sécurisée

## 📦 Installation

### Cloner le repository
```bash
git clone https://github.com/Johan-Agouni/secure-password-generator.git
cd secure-password-generator
```

### Lancer le projet

Ouvrez simplement `accueil.html` dans votre navigateur, ou utilisez un serveur local :
```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (http-server)
npx http-server

# Avec PHP
php -S localhost:8000
```

Puis accédez à `http://localhost:8000`

## 📁 Structure du projet
```
secure-password-generator/
│
├── accueil.html          # Page d'accueil
├── index.html            # Générateur de mots de passe
├── index2.html           # Générateur de noms d'utilisateur
├── style.css             # Styles principaux
├── script.js             # Logique JavaScript
├── image/
│   └── Image acceuil.png # Image de fond
└── README.md             # Documentation
```

## 🔒 Sécurité

- ✅ **Génération côté client uniquement** : Aucune donnée n'est envoyée à un serveur
- ✅ **Crypto.getRandomValues()** : Utilisation de l'API de cryptographie du navigateur
- ✅ **Aucun stockage** : Les mots de passe ne sont jamais sauvegardés
- ✅ **Open source** : Code totalement transparent et vérifiable

## 💡 Utilisation

### Générer un mot de passe sécurisé

1. Choisissez la longueur désirée (8-32 caractères)
2. Sélectionnez les types de caractères (majuscules, minuscules, chiffres, symboles)
3. Cliquez sur "Générer un mot de passe"
4. Copiez le résultat en un clic

### Générer un nom d'utilisateur unique

1. Choisissez un style de génération
2. Ajoutez des chiffres ou underscores (optionnel)
3. Cliquez sur "Générer un nom d'utilisateur"
4. Copiez votre nouveau pseudo

## 🎯 Conseils de sécurité

- 🔐 Utilisez un mot de passe différent pour chaque compte
- 🔄 Changez vos mots de passe régulièrement (tous les 3-6 mois)
- ✅ Privilégiez des mots de passe d'au moins 16 caractères
- 🛡️ Activez l'authentification à deux facteurs (2FA) quand possible
- 💾 Utilisez un gestionnaire de mots de passe pour les stocker

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche (`git checkout -b feature/amelioration`)
3. Commit vos changements (`git commit -m 'Ajout d'une fonctionnalité'`)
4. Push vers la branche (`git push origin feature/amelioration`)
5. Ouvrir une Pull Request

## 📝 TODO / Améliorations futures

- [ ] Ajouter un historique des mots de passe générés (temporaire)
- [ ] Implémenter un générateur de phrases de passe (passphrase)
- [ ] Ajouter plus de styles de noms d'utilisateur
- [ ] Créer une extension navigateur
- [ ] Ajouter un mode sombre/clair
- [ ] Support multilingue (EN, ES, DE)

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 👨‍💻 Auteur

**Johan Agouni**

- GitHub: [@Johan-Agouni](https://github.com/Johan-Agouni)
- Portfolio: [Votre site web]
- LinkedIn: [Votre profil LinkedIn]

## 🌟 Remerciements

- Font Awesome pour les icônes
- Inspiration du film Matrix pour l'effet d'arrière-plan
- La communauté open source

---

⭐ **Si ce projet vous a été utile, n'hésitez pas à lui donner une étoile !** ⭐
