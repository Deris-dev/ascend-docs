# Démarrage

Bienvenue dans l’aventure avec le bot ! Cette page vous guide étape par étape pour ajouter le bot à votre serveur Discord et commencer à l’utiliser.

Assurez-vous d’avoir les permissions nécessaires sur votre serveur avant de commencer !

## Étape 1 : Invitation du bot

1. Cliquez sur ce lien pour inviter le bot : [Lien d’invitation du bot](https://discord.com/oauth2/authorize?client_id=1312924786451812413\&permissions=275146722497\&integration_type=0\&scope=applications.commands+bot).
2. Sélectionnez le serveur sur lequel vous souhaitez ajouter le bot (vous devez avoir la permission "Gérer le serveur").
3. Cliquez sur **Continuer**, puis vérifiez les autorisations demandées par le bot.
4. Cliquez sur **Autoriser** pour ajouter le bot à votre serveur.
5. Complétez la vérification CAPTCHA si nécessaire.

## Étape 2 : Configuration de base

Une fois le bot ajouté, il sera en ligne sur votre serveur. Voici les premières choses à faire pour le configurer :

1. **Configurer les permissions** :
   * Assurez-vous que le bot a les permissions nécessaires pour gérer les rôles et les messages.
   * Placez le rôle du bot au-dessus des autres rôles pour qu’il puisse attribuer les rangs.
2. **Lancer la configuration initiale** :\
   Utilisez la commande suivante pour configurer le bot rapidement :
   * `/settings > Rangs > Créer les rôles` : Crée automatiquement les rôles de rang pour votre serveur.

{% hint style="success" %}
Le bot ne demande pas la permission "**Administrateur**". Assurez-vous donc que le bot **ait** la permission "**Voir le Salon**" dans les salons où le bot doit **comptabiliser** les RP.
{% endhint %}

## Étape 3 : Vérifiez les paramètres importants

* Configurez les salons essentiels avec `/settings` :
  * [**Salon de notifications**](configuration/salon-de-notifications.md) : Choisissez où les notifications de rank up seront envoyées.
  * [**Salon d’événement**](configuration/salon-devenement.md) : Définissez le salon pour les notifications d’événements.
  * [**Salon de logs**](configuration/salon-des-logs.md) : Configurez où seront affichés les logs des RP gagnés et perdus.
* Définissez un **rôle d’événement** si nécessaire via `/settings`.

## Étape 4 : Explorez les commandes

Voici quelques commandes utiles pour bien démarrer :

* `/check` : Vérifiez vos RP, votre rang et vos limites quotidiennes.
* `/leaderboard` : Consultez les classements.

### **Ai-je besoin de permissions spéciales pour ajouter le bot ?**

Oui, vous devez avoir la permission "Gérer le serveur" sur Discord pour inviter le bot.

### **Le bot peut-il être utilisé sur plusieurs serveurs ?**

Oui, vous pouvez inviter le bot sur autant de serveurs que vous souhaitez.

### **Que faire si le bot ne fonctionne pas ?**

* Vérifiez que le bot a les permissions nécessaires.
* Assurez-vous qu’il est en ligne.
* Si le problème persiste, contactez le support via le serveur officiel du bot.

### **Puis-je modifier les paramètres après l’ajout ?**

Bien sûr, vous pouvez modifier les paramètres à tout moment via les commandes `/settings`.
