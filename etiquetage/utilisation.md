Rendez-vous dans l'onglet `Commandes > Colissimo - Étiquetage` pour générer vos documents d'expédition.

## Interface

Le module vous propose une interface similaire à l'onglet `Commandes > Commandes` de PrestaShop.  
Chaque ligne représentant une commande Colissimo, avec les informations clients, d'adresse et les documents disponibles
pour l'impression.  
De nombreux filtres sont également disponibles.

![Interface étiquetage](/../_media/interface-etiquetage.png)

## Génération d'étiquettes

Pour générer uniquement une étiquette pour une commande, vous pouvez cliquer sur le bouton `Générer` en bout de ligne.

![Générer une étiquette](/../_media/generer-etiquette.png)

Sinon, sélectionnez les commandes pour lesquelles vous souhaitez générer une étiquette puis cliquer sur
`Générer étiquett(e)` dans les actions groupées en bas du tableau des commandes.

![Générer plusieurs étiquettes](/../_media/generer-etiquettes.png)

> [!NOTE]
> Une commande ayant déjà une étiquette ne pourra pas en avoir une nouvelle même si vous sélectionnez la commande et
> cliquez sur `Générer étiquette(s)`.

## Imprimer les étiquettes

Il est possible d'imprimer les étiquettes une par une en cliquant sur le bouton `Imprimer` en fin de ligne de la
commande.

![Button d'impression d'une étiquette](/../_media/imprimer-etiquette.png)

Le plus efficace étant de pouvoir imprimer toutes les étiquettes d'un seul coup!  
Pour cela,il suffira de sélectionner les commandes (un raccourci existe dans les actions groupées pour sélectionner
toutes les commandes d'un coup) et de cliquez sur `Imprimer étiquette(s)` dans les actions groupées.

![Button d'impression d'une étiquette](/../_media/imprimer-etiquettes.png)

## Imprimer le formulaire de douane CN23

Si vous avez sélectionné le mode d'impression `PDF A4 (pour imprimante classique)` dans la configuration du module,
alors le formulaire de douane CN23 sera disponible dans le PDF lors de l'impression de l'étiquette en 4 exemplaires.

Dans le cas où vous avez sélectionné le mode d'impression `PDF 10x15cm (pour imprimante thermique / Datamax)`, il y aura
un bouton en plus sur la ligne de la commande vous permettant d'imprimer le formulaire CN23 à part (car il ne peut pas
être sorti sur imprimante thermique avec les étiquettes d'expédition).

![Button d'impression du formulaire CN23](/../_media/CN23.png)

## Imprimer le bordereau de remise

De la même manière que pour l'impression des étiquettes d'expédition, sélectionnez les commandes que vous souhaitez voir
apparaître sur le bordereau de remise, puis dans les actions groupées cliquez sur `Imprimer le bordereau de fin de
journée`.

![Bordereau de fin de journée](/../_media/bordereau-fin-journee.png)

> [!WARNING]
> Le nombre de commandes sur un bordereau de remise est limité, généralement, une centaine de commande au maximum.  
> Si vous rencontrez une erreur dût à un trop grand nombre de commandes alors vous devrez générer plusieurs bordereaux
> de remise.