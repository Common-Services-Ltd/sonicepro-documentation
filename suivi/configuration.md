Lors de l'installation du module, un nouvel onglet `Colissimo - Suivi` est ajouté dans le menu `Commandes` de
PrestaShop.  
C'est dans ce menu que vous pourrez l'avancement de la livraison de vos commandes.

Dans la configuration du module, rendez-vous dans l'onglet `Suivi` pour configurer les différents aspects de votre
gestion du suivi de colis.

## Identifiants API

Afin de pouvoir accéder au web service Livraison de Colissimo et ainsi récupérer vos points de retrait en
front-office, il est impératif de renseigner votre identifiant et mot de passe dans la configuration du module.

Afin de recevoir vos identifiants et accéder au web service, il vous faut contacter votre interlocuteur commercial
Colissimo et souscrire à [**contrat Web Service de Suivi Colis**](https://www.colissimo.entreprise.laposte.fr/system/files/imagescontent/docs/spec_ws_suivi.pdf).  
Vous recevrez vos identifiants par email et il ne vous restera plus qu’à les utiliser dans la configuration du module.

> [!WARNING]
> Vos identifiants de connexion au back-office Colissimo Entreprise ne font pas office d’identifiants pour ce
module.

## Statut de commande "Expédié"

Il s'agit du statut pour lequel la commande sera mise à jour lorsque le web service de suivi de colis Colissimo indique
que la commande est en cours de livraison.

## Statut de commande "Livré"

Il s'agit du statut pour lequel la commande sera mise à jour lorsque le web service de suivi de colis Colissimo indique
que la commande est livré.

## Tache planifiée

Il s'agit de la tache planifiée à mettre en place sur votre serveur pour assurer le suivi de vos colis à intervalle
régulier.  
Il convient généralement de faire un suivi de colis toutes les 6 heures, mais cet intervalle reste à votre convenance.

> [!TIP]
> Si n'avez pas les connaissances suffisantes ou de webmaster pour mettre en place la tache planifiée sur votre serveur
> alors vous pouvez utiliser un service tier, par exemple [cron-job.org](https://cron-job.org).