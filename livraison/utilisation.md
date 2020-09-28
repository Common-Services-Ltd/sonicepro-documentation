## Gestion des grilles tarifaires des transporteurs

Le module propose une tarification automatique basée sur l'offre Colissimo Privilège. Si vous ne souhaitez pas l'utiliser
alors il faudra mettre en place vos grilles tarifaires manuellement, en respectant quelques règles pour que vos
transporteurs reflêtent bien l'offre Colissimo.

Il est donc important de bien configurer les prix par transporteurs et par zones si vous désirez appliquer un prix
différent pour chacun des pays de l’offre Colissimo.

Il faudra disposer de neuf (9) zones :

* Colissimo Zone 0 (FR) pour la France
* Colissimo Zone 1 (BE, LU, NL, DE, MC) pour la Belgique, le Luxembourg, les Pays-Bas, l’Allemagne et Monaco
* Colissimo Zone 2 (GB, ES, PT, AT, IE, IT) pour le Royaume-Uni, l’Espagne, le Portugal, l’Autriche, l'Irlande et l'Italie
* Colissimo Zone 3 (DK, EE, HU, LV, LT, PL, CZ, SK, SI, SE, CH) pour le Danemark, l’Estonie, la Hongrie, la Lettonie, la Lituanie, la Pologne, la République Tchèque, la Slovaquie, la Slovénie, la Suède et la Suisse
* Colissimo Zone 4 (BG, CY, HR, FI, GR, IS, MT, NO, RO, ES-PM, ES-CN, ES-CE, ES-ML) pour la Bulgarie, Chypre, la Croatie, la Finlande, la Grèce, l'Islande, Malte, la Norvège, la Roumanie, les îles Balèares (Espagne), les îles Canaries (Espagne), Ceuta (Espagne) et Melilla (Espagne)
* Colissimo Zone 5 (AU, CA, CN, KR, US, HK, IN, IL, JP, RU, SG, TH, VN) pour l'Australie, le Canada, la Chine, la Corée du Sud, les États-Unis, Hong Kong, l'Inde, le Japon, la Russie, Singapore, la Thaïlande et le Vietnam
* Colissimo Zone 6 (GP, BL, SM, MQ, RE, GY, GF, YT, PM) pour la Guadeloupe, Saint-Barthélemy, Saint-Martin, la MArtinique, la Réunion, la Guyane, la Guyane Française, Mayotte et Saint-Pierre-et-Miquelon
* Colissimo Zone 7 (NC, PF, WF, TF, AQ) pour la Nouvelle-Calédonie, la Polynésie Française, Wallis et Futuna, Terres australes et antarctiques françaises, et l'Antarctiques
* Colissimo Zone 8 pour toutes les autres destinations

Vous devez créer ces zones dans l'onglet `International > Zones Géographique`, il faudra ensuite modifier chaque pays
pour les faire rentrer dans leur zone respective.

## Mise en place des frais de port

Pour chaque transporteur du module, assignez le bon tarif en fonction de la zone et du poids.  
Pour plus d'information, vous pouvez vous référer [aux tarifs du contrat Colissimo Privilège](https://www.colissimo.entreprise.laposte.fr/fr/system/files/imagescontent/docs/TARIF-2020-PRIVILEGE-FR.pdf)
ou sinon appliquer vos propres tarifs personnalisés.

> [!TIP]
> Pour désactiver une tranche, vous pouvez mettre le prix à `-1`, le module interprétera cela comme une instruction de
> désactivation du transporteur pour cette tranche de prix/poids.