# JARVIS - Votre Assistant AI en Python

JARVIS est un assistant personnel intelligent développé en Python, capable de reconnaître la parole, de répondre en français, et d'effectuer diverses tâches telles que la recherche d'informations, la génération de code, l'amélioration de code existant, et plus encore.

## Fonctionnalités

- **Reconnaissance vocale** : Interprète les commandes vocales en français.
- **Météo** : Fournit les informations météorologiques pour une ville donnée.
- **Génération de code** : Génère du code basé sur une instruction fournie.
- **Amélioration de code** : Améliore ou optimise le code existant.
- **Recherche d'informations** : Trouve des informations en ligne et les résume.
- **Affichage d'images** : Montre des images basées sur des requêtes spécifiques.

## Prérequis

- Python 3.x
- Bibliothèques Python : `requests`, `speech_recognition`, `pyttsx3`, `openai`, `BeautifulSoup`, `cryptography`, `colorama`, `PIL`

## Installation

### Clonage du Dépôt

Clonez le dépôt GitHub :

git clone [URL_DU_REPO]

Installation des Dépendances
Avant de lancer JARVIS, assurez-vous d'installer les dépendances nécessaires. Ceci peut être fait en exécutant la commande suivante dans le dossier du projet :

[ pip install -r requirements.txt ]

Le fichier requirements.txt inclut les bibliothèques suivantes :
- elevenlabslib==0.6.0
- openai==0.27.6
- SpeechRecognition==3.10.0
- pyaudio==0.2.13

Configuration
Fichier de Clés API (clef.txt)
Vous devez créer un fichier clef.txt contenant vos clés API personnelles. Voici le format attendu :

-----------------------------------------------

elevenlabs ==> VOTRE_CLE_ELEVENLABS
chat gpt ==> VOTRE_CLE_CHATGPT
openweather ==> VOTRE_CLE_OPENWEATHER
google_cse_cx ==> VOTRE_CLE_GOOGLE_CSE_CX
google_cse ==> VOTRE_CLE_GOOGLE_CSE

-----------------------------------------------
Cryptage des Clés
Pour plus de sécurité, vous pouvez crypter vos clés API :

Utilisez Fernet pour crypter les clés et stockez les clés cryptées dans encrypted_keys.txt.
Stockez la clé de cryptage dans un fichier séparé (keys/crypto_key.key).
Utilisation
Pour lancer JARVIS, exécutez :


python jarvis.py
Suivez les instructions à l'écran pour interagir avec JARVIS.

Contribution
Les contributions à ce projet sont les bienvenues. Veuillez suivre les bonnes pratiques de développement et de codage.




