Lors de l'installation du module, un nouvel onglet `Colissimo - Étiquetage` est ajouté dans le menu `Commandes` de
PrestaShop.  
C'est dans ce menu que vous pourrez générer vos étiquettes et imprimer les différents documents d'expédition.

Dans la configuration du module, rendez-vous dans l'onglet `Étiquetage` pour configurer les différents aspects de votre
gestion d'étiquetage.

## Identifiants API

Afin de pouvoir accéder au web service Livraison de Colissimo et ainsi récupérer vos points de retrait en
front-office, il est impératif de renseigner votre identifiant et mot de passe dans la configuration du module.

Afin de recevoir vos identifiants et accéder au web service, il vous faut contacter votre interlocuteur commercial
Colissimo et souscrire à [**contrat Web Service d’Affranchissement**](https://www.colissimo.entreprise.laposte.fr/fr/system/files/imagescontent/docs/spec_ws_affranchissement.pdf).  
Vous recevrez vos identifiants par email et il ne vous restera plus qu’à les utiliser dans la configuration du module.

> [!WARNING]
> Vos identifiants de connexion au back-office Colissimo Entreprise ne font pas office d’identifiants pour ce
module.

## Adresse

Il s'agit de votre adresse d'expédition, c'est votre adresse qui apparaitra sur l'étiquette en tant qu'expéditeur.

## Statut après la création de l'étiquette

Si vous le souhaitez, vous pouvez changer automatiquement le status de vos commandes une fois l'étiquette générée, pour
`Préparation en cours` ou `Expédié` par exemple.  
Sélectionnez ce statut ici et indiquez si vous souhaitez informer le client du changement de statut de la commande (si
le statut en question possède un email).

## Pays d'origine

Lors de la génération du bordereau de douane CN23, il faut indiquer l'origine des produits de la commande.  
Vous pouvez au choix :

* forcer à France
* utiliser l'adresse du fournisseur
* utiliser l'adresse de la marque

## Code tarifaire par défaut

Il s'agit du numéro tarifaire par défaut correspondant à vos articles.  
Il est recommandé d'en renseigné un au cas où vous n'auriez pas encore renseigné le code tarifaire de l'un de vos
produits. 

> [!NOTE]
> Depuis 1988, la Communauté européenne a, après nombre d’États dans le monde, adopté le Système Harmonisé (SH) de
> désignation des marchandises pour les envois commerciaux. Ce « numéro tarifaire » à 6 chiffres permet d’identifier de
> manière unique et dans le monde entier tous les objets physiques. Il est un des trois éléments permettant d’établir la
> taxation en douane, avec le montant des frais de port et l’origine de la marchandise.
>
> Pour permettre un traitement rapide des opérations douanières à l’arrivée dans le pays de destination, il est ainsi
> recommandé aux entreprises d’indiquer le numéro tarifaire de la marchandise envoyée.  
> Dans les échanges postaux, seule l’indication du numéro tarifaire à 6 chiffres constitue une obligation pour les
> entreprises expéditrices.
>
> Où se procurer le numéro tarifaire ?
> * Se rapprocher des cellules de douane de sa région pour des envois réguliers
> * Se rendre sur le site de la douane française : https://pro.douane.gouv.fr/prodouane.asp (dans l’encyclopédie tarifaire RITA, consulter la nomenclature)
>
> Un tutoriel expliquant comment récupérer le numéro tarifaire sur le site de la douane française est
> [disponible ici](https://documentation.common-services.com/sonice_etiquetage/international/).

## Numéro EORI

Tout professionnel communautaire (UE) souhaitant réaliser des envois en dehors de l’UE, devra déposer une demande
d'identification pour récupérer son numéro EORI.  
Ce numéro communautaire unique vise à sécuriser les échanges commerciaux entrant et sortant de l’UE.

Ce numéro apparaitra sur vos formulaires de douane CN23.

## Format des étiquettes

Le module propose 2 formats d'impression PDF :

* PDF A4 pour les imprimantes laser classique, sur papier autocollant A4
* PDF 10x15cm pour les imprimantes thermiques comme la Datamax fournit par Colissimo (autres modèles et marques d'imprimante sont compatibles)

## Date de dépôt estimée

Nombre de jours séparant la génération de l'étiquette et la remise du colis à Colissimo.  
Il s'agit d'une estimation, si vous n'êtes pas sûre, vous pouvez laisser sur `1 jour` par défaut.

## Choix du retour colis

Choisir ici la politique de retour à appliquer pour les expédition hors de France.  
Par défaut, laisser à `Ne pas retourner (Toutes les destinations)`.