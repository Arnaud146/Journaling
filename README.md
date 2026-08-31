# Journal

Une app de journaling minimaliste sous forme de calendrier mensuel.

## Utilisation

Ouvre simplement `index.html` dans ton navigateur — aucune installation, aucun serveur, aucune dépendance.

- **Calendrier mensuel** : navigue avec les flèches `‹` `›` (ou les flèches ← → du clavier).
- **Écrire** : clique sur un jour pour ouvrir l'éditeur. Le bouton « Aujourd'hui » ouvre directement l'entrée du jour.
- **Sauvegarde automatique** : tout est enregistré pendant que tu écris, dans le `localStorage` de ton navigateur. Un point sous un jour indique qu'une entrée existe.
- **Fermer** : `Échap`, la croix, ou un clic en dehors de l'éditeur.

## Données

Les entrées sont stockées localement dans ton navigateur (clé `journal.entries.v1`), au format :

```json
{ "2026-08-31": "Texte de l'entrée…" }
```

Rien ne quitte ton appareil. Attention : vider les données du site dans le navigateur efface le journal.
