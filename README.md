# Brixly

**Constructeur de sites no-code qui tourne entièrement dans votre navigateur.**
Un fichier · Zéro dépendance · Zéro serveur.

[![License: MIT](https://img.shields.io/badge/License-MIT-7B5EF8.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-3.0-7B5EF8)]()

---

## ✨ Fonctionnalités

- 🧱 **Éditeur par blocs** — glissez-déposez des sections prêtes à l'emploi (hero, features, articles, CTA…)
- 📄 **Multi-pages** — gérez plusieurs pages dans un même projet
- 📁 **Multi-projets** — basculez entre projets, tout est sauvegardé localement
- ✏️ **Éditeur riche** — mode WYSIWYG et mode HTML brut, dans la même interface
- 🔤 **30+ Google Fonts** — panel typographique avec suggestions de combinaisons
- 🎨 **Palette & CSS** — éditeur de couleurs + injection de CSS personnalisé
- 🖼 **Gestionnaire d'assets** — glissez des images, compression WebP automatique
- 📰 **Système d'articles** — catégories, tags, slug, image à la une, extrait
- 🌐 **Favicons** — importez un ZIP favicon.io directement
- 📱 **Aperçu responsive** — desktop, tablette, mobile
- 📤 **Export HTML** — téléchargez un fichier HTML propre et autonome
- 📥 **Import** — chargez un HTML existant ou un projet JSON
- 💾 **Zéro backend** — tout est sauvegardé dans le localStorage

## 🚀 Démarrage rapide

Aucune installation requise.

1. Téléchargez [`index.html`](../../releases/latest)
2. Ouvrez-le dans votre navigateur
3. Commencez à construire

> Compatible Chrome, Firefox, Safari, Edge (versions récentes).

## 🏗 Architecture

Brixly est un fichier HTML unique (~6 500 lignes) sans aucune dépendance externe ni framework JavaScript. Il exploite :

- **localStorage** pour la persistance des projets
- **Canvas API** pour la compression d'images côté client (WebP automatique)
- **Google Fonts** pour le chargement dynamique des polices
- **iframe sandboxé** pour le rendu isolé du canvas d'édition

## 📸 Aperçu

> *(Ajoutez ici une capture d'écran ou un GIF de l'interface)*

## 🗺 Roadmap

- [ ] Export multi-pages (ZIP)
- [ ] Thèmes prédéfinis au démarrage
- [ ] Historique undo/redo global
- [ ] Mode sombre pour les pages exportées
- [ ] Templates de projets

## 🤝 Contribution

Les contributions sont les bienvenues !

1. Forkez le repo
2. Créez une branche (`git checkout -b feature/ma-feature`)
3. Commitez (`git commit -m 'feat: ajouter X'`)
4. Poussez (`git push origin feature/ma-feature`)
5. Ouvrez une Pull Request

## 📄 Licence

Distribué sous licence **MIT** — voir [`LICENSE`](LICENSE).

---

<div align="center">
  Fait avec ❤️ — un seul fichier pour tout construire.
</div>
