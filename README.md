# Sèdo

**La parole devient trace.**

Sèdo est un logiciel de dictée vocale médicale. Vous maintenez une touche, vous parlez, vous relâchez : le texte s'écrit là où se trouve votre curseur, dans votre logiciel métier, votre messagerie ou votre traitement de texte.

- **Tout reste sur votre ordinateur.** La voix est transcrite sur place ; aucun son ni aucun texte n'est envoyé sur Internet.
- **Vocabulaire médical.** Plus de 44 000 termes, organisés par spécialité, et l'apprentissage de vos propres mots.
- **Ponctuation dictée.** « virgule », « point », « à la ligne », « nouveau paragraphe », parenthèses.

## Télécharger

> Version d'essai : Sèdo est encore en cours de mise au point.

| Votre ordinateur | Fichier |
|---|---|
| Mac à puce Apple (M1, M2, M3, M4) | [Télécharger la dernière version](https://github.com/Thieum21/sedo/releases/latest/download/Sedo-mac-puce-apple.dmg) |
| Mac Intel | bientôt |
| Windows | bientôt |

Pour savoir quel Mac vous avez : menu Pomme → « À propos de ce Mac ». Si la ligne « Puce » indique Apple M1, M2, M3 ou M4, prenez la version « puce Apple ».

## Installer sur Mac

1. Ouvrez le fichier `.dmg` téléchargé et glissez **Sèdo** dans le dossier **Applications**.
2. Ouvrez Sèdo depuis Applications. Au premier lancement, macOS affiche un avertissement, car l'application n'est pas encore signée auprès d'Apple : allez dans **Réglages Système → Confidentialité et sécurité**, descendez jusqu'au message concernant Sèdo et cliquez sur **Ouvrir quand même**.
3. Accordez les autorisations demandées : **Microphone**, **Accessibilité** et **Surveillance de l'entrée** (pour la touche de dictée et l'écriture au curseur). Quittez puis relancez Sèdo.
4. Au premier démarrage, Sèdo télécharge son modèle de reconnaissance vocale (environ 1,6 Go, une seule fois). C'est le seul moment où une connexion Internet est nécessaire.

Sèdo n'a pas de fenêtre principale : son icône se trouve dans la barre de menus, en haut de l'écran.

## Prise en main

*Pour un premier utilisateur sur Mac. Tout se passe sur votre ordinateur : aucune dictée, aucun texte ne quitte le poste.*

### Dicter

- Cliquez dans n'importe quel champ de texte (logiciel médical, mail, traitement de texte), **maintenez la touche Option droite (⌥ à droite de la barre d'espace)**, parlez, **relâchez**. Le texte apparaît sous le curseur une seconde plus tard.
- Parlez à votre rythme habituel, sans détacher les mots. Sèdo a été réglé pour la dictée médicale rapide.
- **Dictez la ponctuation** : « point », « virgule », « deux points », « à la ligne », « nouveau paragraphe », « point d'interrogation », « ouvrir la parenthèse / fermer la parenthèse », « tiret ». Sans rien dicter, Sèdo met un point à la fin et une majuscule au début.
- Les nombres, unités et doses s'écrivent seuls : « hémoglobine à dix virgule huit grammes par décilitre » → *hémoglobine à 10,8 g/dL* ; « tension quatorze sur sept » → *14/7* ; « trente-neuf semaines d'aménorrhée » → *39 SA*.
- Un mot médical mal reconnu ? **Corrigez-le à la main dans le texte** : Sèdo le remarque et vous propose de l'apprendre (bulle « L'apprendre ? »). Une fois appris, il ne se trompe plus. Vous pouvez aussi sélectionner le passage corrigé et appuyer sur **Ctrl + Alt + C**.

### Les trois pièges du début

1. **Rien ne s'affiche ?** Vérifiez que le curseur clignote bien dans un champ de texte avant d'appuyer ; que le micro n'est pas pris par une autre application (visioconférence, autre dictée) ; et qu'aucune **bulle de compte rendu** n'est restée ouverte (voir ci-dessous). Le bouton **« Dernières dictées… »** du panneau montre ce que Sèdo a entendu et ce qu'il a inséré.
2. **Un mot seul ou un mot très court** peut passer inaperçu : préférez une phrase, même brève.
3. **Relâchez la touche après le dernier mot**, pas pendant : Sèdo attend une demi-seconde de silence pour fermer la dictée.

### Comptes rendus types (pour les comptes rendus répétitifs)

- Dites **seulement** « compte rendu type césarienne » (ou « CRO césarienne », « consultation de néphrologie »…) : une **bulle** s'ouvre, qui liste les rubriques à dicter et celles déjà remplies.
- Dictez ensuite rubrique par rubrique, en plusieurs fois si vous voulez : « anesthésiste docteur Martin », « poids trois mille deux cent cinquante grammes », « pertes sanguines cinq cents »… La bulle coche au fur et à mesure.
- Dites **« terminé »** (ou cliquez le bouton de la bulle) : le compte rendu complet, mis en forme, est collé sous le curseur.
- **Important** : tant que la bulle est ouverte, toute dictée est ajoutée au compte rendu et *rien n'est collé* (une notification vous le rappelle). Pour dicter autre chose, fermez la bulle avec sa croix.
- Vos propres trames (Réglages › Gabarits) se créent à partir d'un de vos comptes rendus existants.

### Reformuler une phrase hésitante

Sélectionnez le passage et appuyez sur **Ctrl + Alt + F** (ou menu de l'icône › *Reformuler la sélection*). Sèdo retire les hésitations, répétitions et faux départs, corrige les accords, et vous montre l'original à côté de la proposition : vous retouchez, puis **Remplacer**. Rien n'est jamais remplacé sans votre clic, et les nombres, côtés, négations et termes médicaux sont vérifiés. Le premier appel télécharge le modèle de langage (une fois, environ 1 Go).

### Pour que Sèdo apprenne votre voix (dix minutes, à faire une fois)

Menu de l'icône › **Réglages › Dictée › « Lecture d'entraînement »** : lisez le texte proposé à voix haute (cochez « Lecture longue (10 min) » pour le meilleur résultat). Sèdo mesure ses erreurs sur votre voix et apprend les mots qu'il a mal entendus. Le rapport reste sur votre Mac.

### Raccourcis

| Action | Raccourci |
|---|---|
| Dicter (maintenir) | Option droite |
| Dictée longue, mains libres | Deux appuis rapides sur Option droite ; un appui pour terminer |
| Relire la sélection corrigée | Ctrl + Alt + C |
| Reformuler la sélection | Ctrl + Alt + F |
| Apprendre un mot | Ctrl + Alt + A |
| Annuler la dictée en cours | Échap |

Les raccourcis Ctrl + Alt + D / L / M / K choisissent le style (phrase courte, texte long, mail, courrier).

### Signaler un problème

Panneau › **« Signaler un problème… »** : décrivez ce qui s'est passé en une phrase, cochez si vous voulez joindre les trois dernières dictées (elles s'affichent pour que vous les relisiez : données de patients possibles), puis « Préparer le courriel ». Un message s'ouvre dans Mail, le rapport est joint (version, machine, réglages, sans donnée de patient) ; relisez et envoyez.

*Sèdo est en développement actif : cette page est mise à jour à chaque version. Version du document : 0.5.179.*

## Confidentialité

Sèdo ne collecte rien. Vos dictées, votre profil et votre vocabulaire personnel restent dans un dossier de votre ordinateur.
