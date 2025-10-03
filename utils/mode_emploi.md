# Envoi de mails via l'API Brevo


## Créer la clé et la stocker

0. Créer un compte
1. Aller sur le site brevo.com
2. Paramètres
3. SMTP et API
4. Clés API et MCP
5. Générer une nouvelle clé API
6. Copier la clé
7. Aller sur Onyxia
8. Secrets --> Créer un secret
9. Ajouter une variable avec comme nom "brevo" et comme valeur la clé qui vient d'être copiée

## Envoyer un mail avec du code python
1. Regarder api_brevo.py dans le dossier utils/ (modifier l'email à qui envoyer le message)
2. Créer un fichier .env et le remplir :
```{.env}
TOKEN_BREVO='insérer sa clé'
EMAIL_BREVO='insérer le mail avec lequel le compte Brevo a été créé'
```
3. Installer les requirements.txt (ou les ajouter à vos requirements.txt de votre projet)
4. Dans le terminal, lancer python utils/api_brevo.py
