# Tâches du jour

Petite application web pour valider depuis son téléphone les tâches à faire chaque jour, avec de quoi se motiver à les faire vraiment.

## Fonctionnalités

- **Ajouter une tâche** : bouton « Nouvelle tâche » en bas de l'écran. Une fiche simple :
  - **Quand ?** Aujourd'hui, Cette semaine ou Ce mois-ci ;
  - **Répéter** : désactivé = à faire une seule fois dans ce délai ; activé = revient tous les jours, toutes les semaines (chaque lundi) ou tous les mois (le 1er) ;
  - **Importance** : Normale, Importante, Urgente.
- **Valider** : appuyer sur une tâche la coche. Le bouton ⓘ permet de la modifier ou de la supprimer.
- **Sections** : En retard (tâches uniques non faites à temps), Aujourd'hui, Cette semaine, Ce mois-ci. Les tâches non faites sont en haut, triées par importance. Une tâche unique faite disparaît à la fin de sa période.
- **Écran principal** : tâches du jour restantes et réalisées en grand, avancement de la semaine et du mois, message qui s'adapte (urgences, soirée, série en jeu).
- **Notification permanente** : la liste des tâches à faire (🔴 urgentes, 🟠 importantes), qui reste sur l'écran verrouillé jusqu'à ce qu'on la balaie. Elle sonne une fois par jour, se met à jour sans bruit à chaque tâche cochée, et revient à l'ouverture de l'appli si elle a été effacée.
- **Style** : inspiré des applis Apple (listes groupées, police et couleurs système, anneau de progression façon Forme) ; suit le mode clair ou sombre du téléphone.
- **Séries** : jours d'affilée où tout est fait, record, et série par tâche (🔥).
- **Points et niveaux** : +10 par tâche (+5 importante, +10 urgente), +20 par journée complète, +5 par jour de série.
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

## Activer la notification

Dans l'appli installée : section **Notification** → activer **Notification permanente** et autoriser les notifications.
Sur iPhone, l'appli doit être ouverte depuis son icône sur l'écran d'accueil (iOS 16.4 ou plus récent).
