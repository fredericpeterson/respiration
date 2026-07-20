# Souffle — PWA de respiration guidée

## Installer sur ton téléphone (sans hébergement)
1. Ouvre `index.html` dans le navigateur de ton téléphone (envoie-toi le fichier par mail/Drive, ou héberge-le comme ci-dessous pour un lien stable).
2. **iPhone (Safari)** : bouton Partager → "Sur l'écran d'accueil".
3. **Android (Chrome)** : menu ⋮ → "Ajouter à l'écran d'accueil" / "Installer l'application".

## Héberger sur GitHub Pages (recommandé, comme tes autres trackers)
1. Crée un nouveau dossier dans ton repo `fredericpeterson.github.io`, par exemple `respiration/`.
2. Dépose ces 4 fichiers dedans : `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`.
3. Push sur GitHub. L'app sera accessible à `https://fredericpeterson.github.io/respiration/`.
4. Ouvre ce lien sur ton téléphone et installe-le comme au-dessus — l'icône et le mode plein écran (sans barre de navigateur) fonctionneront automatiquement.

## Notes techniques
- Le service worker (`sw.js`) met l'app en cache pour un fonctionnement hors-ligne après la première visite.
- Les polices Google Fonts nécessitent une connexion la première fois ; ensuite elles sont mises en cache par le navigateur.
- La voix (synthèse vocale) dépend des voix installées sur l'appareil — pas de connexion nécessaire pour ça.
