# MP VISUAL — e-portfolio de Marlon Pavid

Site statique (HTML + CSS + JS, sans build), hébergé sur Vercel.

- `index.html` : le site complet
- `assets/` : images, mockups des projets, CV en PDF, polices

**Mettre à jour :** modifier ou remplacer les fichiers ici sur GitHub → Vercel republie automatiquement.
Réglages Vercel : Framework « Other », pas de commande de build, dossier racine `./`.

## SEO
- Adresse du site : constante `https://mp-visual-portfolio.vercel.app` dans `index.html` (canonical, Open Graph, JSON-LD), `robots.txt` et `sitemap.xml`.
  Avec un domaine perso : remplacer cette adresse partout par `https://tondomaine.ch`.
- Données structurées : bloc `application/ld+json` (ProfilePage + Person) dans le `<head>`.
