Lors de l'installation du module, tous les transporteurs Colissimo sont créés sur la boutique.  
Rendez-vous dans l'onglet `Livraison` pour configurer les différents aspects de vos nouveaux transporteurs Colissimo.

## Identifiants API

Afin de pouvoir accéder au web service Livraison de Colissimo et ainsi récupérer vos points de retrait en
front-office, il est impératif de renseigner votre identifiant et mot de passe dans la configuration du module.

Afin de recevoir vos identifiants et accéder au web service, il vous faut contacter votre interlocuteur commercail
Colissimo et souscrire à [**un contrat professionnel Colissimo Domicile et Points de Retrait**](https://www.colissimo.entreprise.laposte.fr/system/files/imagescontent/docs/spec_ws_livraison.pdf).  
Vous recevrez vos identifiants par email et il ne vous restera plus qu’à les utiliser dans la configuration du module.

> [!WARNING]
> Vos identifiants de connexion au back-office Colissimo Entreprise ne font pas office d’identifiants pour ce
module.

## Utiliser les tarifs de Colissimo

Cette option vous permet d'activer la tarification automatique des transporteurs Colissimo du module.  

Si `désactivé`, vous devrez configurer vous même la grille tarifaire de tous les transporteurs Colissimo du module.

Si `activé`, le module utilisera [les tarifs du contrat Colissimo Privilège](https://www.colissimo.entreprise.laposte.fr/fr/system/files/imagescontent/docs/TARIF-2020-PRIVILEGE-FR.pdf)
pour les transporteurs Colissimo.

Vous aurez toujours la possibilité de limiter les transporteurs Colissimo du module en activant ou désactivant une zone
de livraison dans la grille tarifaire du transporteur, en modifiant les dimensions ou le poids maximum du transporteurs,
etc.

> [!NOTE]
> Lors du passage d'une commande, le module vérifie que le transporteur est compatible avec le pays de destination de
la commande, et filtre automatiquement les transporteurs Colissimo non compatibles.

## Utiliser le calcul de Poids Volumétrique

Le module calculera les frais de port en fonction du poids volumétrique du colis (pour l'Outre-Mer et l'International
uniquement).

Le poids volumétrique est calculé en multipliant les 3 dimensions en centimètre de votre colis, et en divisant le
résultat par 5000: `(L x l x h) / 5000`.

> [!NOTE]
> Le module applique le tarif correspondant au poids volumétrique, si ce dernier est supérieur au poids réel du colis.

Un calculateur de poids volumétrique est [disponible dans votre espace Colissimo Entreprise](https://www.colissimo.entreprise.laposte.fr/fr/poids-volumetrique).

## Assurance Ad-Valorem

En activant cette option, toutes vos expéditions dépassant le montant saisi seront assurées au prix de vente lors de la
génération de l'étiquette.

Pour déterminer le montant de l'assurance Ad-Valorem, le module utilise le prix d'achat (champ `wholesale_price` de
PrestaShop) des produits du panier.
