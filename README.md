# ArduinoBot

**Assistant pédagogique interactif pour l'apprentissage d'Arduino et de Codecraft au collège**

---

## Présentation

ArduinoBot est un chatbot éducatif conçu pour accompagner les élèves de collège (11-15 ans) dans leur apprentissage de la programmation avec la carte **Arduino Uno** et le logiciel **Codecraft** (programmation par blocs).

Il couvre les thèmes suivants :
- Les **capteurs** : lumière, distance, température, son, boutons...
- Les **actionneurs** : LED, buzzer, moteurs, servomoteurs...
- La **carte Arduino Uno** : broches numériques, analogiques, PWM, alimentation...
- Le logiciel **Codecraft** : blocs de programmation, setup/loop, variables, conditions, boucles...

---

## Fonctionnalités

- Conversation interactive avec un assistant pédagogique spécialisé
- Suggestions de questions rapides par thème
- Historique de conversation conservé pendant la session
- Interface moderne et responsive (desktop et mobile)
- Mode sombre par défaut pour un confort visuel optimal

---

## Utilisation

### 1. Obtenir une clé API Google Gemini

1. Rendez-vous sur [Google AI Studio](https://aistudio.google.com/apikey)
2. Connectez-vous avec un compte Google
3. Cliquez sur **"Create API key"**
4. Copiez la clé générée

### 2. Lancer ArduinoBot

1. Téléchargez le fichier `index.html` depuis ce dépôt
2. Ouvrez-le avec un navigateur web moderne (Chrome, Firefox, Edge)
3. Collez votre clé API dans le champ prévu à cet effet
4. Commencez à poser vos questions !

> La clé API est stockée localement dans votre navigateur et n'est jamais transmise à des serveurs tiers.

---

## Structure du projet

```
Arduibot/
├── README.md          # Ce fichier de documentation
├── index.html         # Interface principale du chatbot
├── LICENSE            # Licence MIT
└── .gitignore         # Fichiers à ignorer par Git
```

---

## Technologies utilisées

- **HTML5 / CSS3** - Structure et style de l'interface
- **JavaScript (Vanilla)** - Logique du chatbot et communication API
- **Google Gemini API** - Modèle de langage pour les réponses (gemini-2.0-flash-lite)
- **Google Fonts** - Polices Space Mono et Nunito

---

## Pour les enseignants

Ce projet est conçu pour être utilisé en classe de technologie au collège. L'enseignant peut :
- Lancer le chatbot sur son poste pour aider les élèves
- Guider les élèves vers des questions pertinentes via les suggestions
- Utiliser les réponses comme support pédagogique

---

## Licence

Ce projet est distribué sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

## Auteur

Développé par **blanchardromain-cyber** pour le Collège.
