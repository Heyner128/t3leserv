### t3leserv


T3leserv est un bot telegram pour générer rapports des vulnerabilités pour une IP  

# Installation

```
git clone https://github.com/m1d0b4n/t3leserv.git && cd t3leserv
```
Ajoutez au fichier .env les variables 

- `TELEGRAM_BOT_TOKEN` : Votre token pour l'API de telegram généré par @BotFather

- `PROXY_URL` : Si le serveur est deployé dérrière un proxy, l'URL finale doit être paramètré avec ce variable

- `CHAT_ID` : L'ID du chat à envoyer le rapport

- `PORT` : Le port de démarrage du serveur Express

- `REDIRECT_URL` : L'URL de redirection pour le ressource  `/track`

```
npm install
```

```
npm start
```

Utilisez un service de proxy reverse comme ngrok ou cloudflare tunnels pour deployer le serveur