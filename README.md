# Julie — installeurs

Application desktop **Julie** d'Orawa Films : l'assistante qui fait le point avec chaque
collaborateur quatre fois par jour (09h15, 11h30, 15h00, 17h30), par écrit ou à la voix.

## Installer Julie

1. Télécharger **`Julie-Setup-<version>.exe`** depuis la [dernière version](https://github.com/ORAWAPROD/julie-releases/releases/latest).
2. Lancer l'installeur (installation en un clic, sans droits administrateur).
3. À la première ouverture, saisir l'identifiant du poste, le prénom de l'occupant et la **clé
   API fournie par la direction**.

Windows peut afficher « Windows a protégé votre ordinateur » tant que l'installeur n'est pas
signé : *Informations complémentaires* → *Exécuter quand même*.

## Mises à jour

Les postes installés vérifient ce dépôt au démarrage puis toutes les 6 heures, et téléchargent
les nouvelles versions en arrière-plan. Dans Julie : roue dentée → *Paramètres* →
*Rechercher les mises à jour* / *Mettre à jour maintenant*.

## Sécurité

Ce dépôt ne contient que les installeurs. Aucune clé ni donnée n'y figure : chaque poste saisit sa
clé API, chiffrée localement par le système (DPAPI / Keychain). Le code source est dans un dépôt
privé.
