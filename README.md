# Tâches du jour

Petite application web pour valider depuis son téléphone les tâches à faire chaque jour, avec de quoi se motiver à les faire vraiment.

## Fonctionnalités

- **Valider** : appuyer sur une tâche la coche (l'heure est notée). Appuyer de nouveau annule.
- **Remise à zéro chaque jour**, historique conservé.
- **Écran principal** : nombre de tâches restantes et réalisées en très grand, et message qui s'adapte à l'heure. Après 19 h, alerte « Ta série est en jeu » avec le temps restant avant minuit.
- **Écran verrouillé** : l'appli reprend la photo de ton fond d'écran actuel (choisie une fois dans la galerie) et y ajoute un grand bandeau en verre flouté listant les tâches faites (cochées, barrées) et à faire, la progression et la série. Un raccourci iOS l'applique à l'écran verrouillé, à la demande ou à chaque tâche cochée. Sans photo, six fonds de couleur au choix.
- **Style** : inspiré des applis Apple (listes groupées, police et couleurs système, anneau de progression façon Forme) ; suit le mode clair ou sombre du téléphone.
- **Séries** : jours d'affilée où tout est fait, record, et série par tâche (🔥).
- **Points et niveaux** : +10 par tâche, +20 par journée complète, +5 par jour de série.
- **Trophées** à débloquer (3, 7, 14, 30, 100 jours de suite, 100 tâches, tout fini avant 10 h…).
- **Confettis et vibration** quand la journée est complète.
- **Ma motivation** : une phrase personnelle affichée en haut de l'écran.
- **Pastille sur l'icône** avec le nombre de tâches restantes (appli installée, si le téléphone le permet).
- Fonctionne hors connexion. Les données restent sur le téléphone, avec export/import en JSON.

## Mise en ligne (une seule fois)

1. Ouvrir dans le navigateur (pas l'appli GitHub) : https://github.com/emeuniermobile-bit/Claude-taches-quotidiennes/settings/pages
2. **Source : Deploy from a branch**, branche `claude/daily-task-validation-tool-vpm1lf`, dossier `/ (root)`, puis **Save**.
3. Après 1 à 2 minutes, l'appli est disponible à l'adresse
   **https://emeuniermobile-bit.github.io/Claude-taches-quotidiennes/**

## Installer sur le téléphone

- **iPhone** : ouvrir l'adresse dans **Safari** → bouton **Partager** → **Sur l'écran d'accueil**.
- **Android** : ouvrir l'adresse dans **Chrome** → menu **⋮** → **Installer l'application**.

## Afficher les tâches sur l'écran verrouillé (iPhone)

Une seule fois, dans l'app **Raccourcis** : créer un raccourci nommé **Écran Tâches** avec deux actions :

1. **Obtenir le presse-papiers**
2. **Définir le fond d'écran** : écran verrouillé uniquement, « Afficher l'aperçu » désactivé.

Ensuite, dans l'appli : « Choisir ma photo de fond d'écran » (la même photo que ton fond actuel), puis « Mettre à jour l'écran verrouillé » (ou activer la mise à jour automatique).
Sur Android : « Enregistrer l'image » puis la définir comme fond d'écran de verrouillage.
