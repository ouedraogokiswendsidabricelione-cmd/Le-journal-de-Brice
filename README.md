# ZoodoGreen

Une PWA éducative et gamifiée qui aide les jeunes à mieux trier, recycler et protéger l'environnement au Burkina Faso.

## Lancer le projet

L'application est volontairement légère et ne nécessite aucune dépendance. Utilisez un serveur HTTP local (le service worker ne fonctionne pas en ouvrant directement le fichier) :

```bash
python3 -m http.server 4173
```

Puis ouvrez [http://localhost:4173](http://localhost:4173). Sur Android, ouvrez cette adresse depuis un navigateur puis utilisez « Ajouter à l'écran d'accueil ».

## Fonctionnalités V1

- Pages Accueil, Apprendre, Quiz, Défis et Profil avec navigation inférieure adaptée au mobile.
- Quiz avec feedback immédiat, XP, niveaux et redémarrage.
- Défis validables et progression de profil persistées dans `localStorage`.
- Manifest et service worker pour l'installation PWA et l'utilisation hors ligne après la première visite.
- Données de classement locales, isolées dans `app.js`, prêtes à être remplacées par une source distante lors de l'ajout de comptes et d'une base de données.
