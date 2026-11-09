# Em Cima — Batucada

PWA responsive de démonstration pour organiser les événements, les réponses de présence, le covoiturage et les ressources d'une batucada.

## Lancer localement

Servez le dossier avec un serveur HTTP (requis pour le service worker et l’installation PWA) :

```bash
python3 -m http.server 8000
```

Puis ouvrez http://localhost:8000. L’application peut ensuite être installée depuis le menu du navigateur compatible.

## Fonctionnalités incluses

- Interface mobile-first en français, thème noir, jaune et blanc, navigation fixe à 7 onglets et prise en compte des encoches / zones système.
- Événements de présence par type, filtres, réponses Oui/Non, sélection d’instrument, comptes de réponses, commentaires, réactions, liens Google Maps et édition admin.
- Gestion des annonces, membres et demandes d’inscription en attente, sondages, newsletter, répertoire et covoiturage.
- Préférences et contenu de démonstration enregistrés dans le stockage local du navigateur ; cache hors ligne de l’interface via le service worker.

## Important : confidentialité et comptes

Cette version est un prototype front-end. Les rôles, données, permissions et approbations sont stockés localement dans le navigateur : ce n’est **pas** une authentification sécurisée et les changements ne sont pas synchronisés avec les autres membres. Pour une vraie application privée multi-utilisateurs, il faut ajouter un serveur et une base de données, l’authentification, des règles d’autorisation côté serveur, une gestion sécurisée des médias et une politique de sauvegarde. Ne publiez pas de données personnelles dans cette démo.
