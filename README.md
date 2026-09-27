# Tâches du jour

Petite application web pour valider depuis son téléphone les tâches à faire chaque jour, avec de quoi se motiver à les faire vraiment.

## Fonctionnalités

- **Valider** : appuyer sur une tâche la coche (l'heure est notée). Appuyer de nouveau annule.
- **Remise à zéro chaque jour**, historique conservé.
- **Écran principal** : nombre de tâches restantes et réalisées en très grand, et message qui s'adapte à l'heure. Après 19 h, alerte « Ta série est en jeu » avec le temps restant avant minuit.
- **Écran verrouillé** : notification permanente « 2 restantes · 1 réalisée » avec la liste des tâches à faire, mise à jour à chaque tâche cochée.
- **Style** : noir, ivoire et or, typographie Cormorant Garamond ; suit le mode clair ou sombre du téléphone.
- **Séries** : jours d'affilée où tout est fait, record, et série par tâche (🔥).
- **Points et niveaux** : +10 par tâche, +20 par journée complète, +5 par jour de série.
- **Trophées** à débloquer (3, 7, 14, 30, 100 jours de suite, 100 tâches, tout fini avant 10 h…).
- **Poussière d'or et vibration** quand la journée est complète.
- **Ma motivation** : une phrase personnelle affichée en haut de l'écran.
- **Rappels** : un bouton ajoute deux rappels quotidiens (matin et soir) dans l'agenda du téléphone.
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

Ensuite, dans l'appli : « Ajouter les rappels à mon agenda » pour recevoir une notification chaque jour.
