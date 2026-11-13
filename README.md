# Keyhome — design system

Design system et maquette d'une application immobilière. Les données (annonces, chiffres, conseillers) sont fictives.

## Contenu

- `tokens/` : tokens de design (JSON et variables CSS).
- `components/` : un dossier par composant (code, styles, README).
- `docs/` : guide de style, principes, règles d'usage.
- `demo/` : page de démo qui assemble les composants.

## Installation

Aucune dépendance. Clonez le repo puis ouvrez `demo/index.html` dans un navigateur :

```bash
git clone https://github.com/claireLDN/keyhome.git
cd keyhome
open demo/index.html   # ou ouvrez le fichier directement
```

La police DM Sans est chargée depuis Google Fonts dans `demo/index.html`.

## Utilisation des tokens

Importez `tokens/tokens.css` avant les styles des composants, puis utilisez les variables (`var(--color-primary)`, `var(--radius-card)`, etc.).

## Accessibilité

Chaque composant respecte les contrastes WCAG AA, reste utilisable au clavier et affiche un focus visible.

## Visuels

La démo utilise des photos dans `demo/img/` (cartes d'annonce, fiche bien, bandeau d'accueil). Toutes proviennent de [Pexels](https://www.pexels.com/) sous la licence Pexels (usage libre).

| Fichier (`demo/img/`) | Photographe |
|---|---|
| `hero-alex-staudinger.jpg / .webp` | Alex Staudinger |
| `card-appartement-lumineux.webp` | Jakub Zerdzicki |
| `card-maison-de-ville.webp` | Daniel Ledesma |
| `card-studio.webp` | David Riand |
| `card-maison-terrain.webp` | Eric Poussin |
| `card-loft.webp` | Egor Komarov |
| `card-villa.webp` | Yasir Gurbuz |
| `gallery-principale.webp` | Paparazzi Ratzfatzzi |
| `gallery-thumb-1.webp` | Arnaud Vigne |
| `gallery-thumb-2.webp` | Arnaud Vigne |
| `gallery-thumb-3.webp` | Volker Thimm |
| `gallery-thumb-4.webp` | Volker Thimm |

## Licence

MIT, voir `LICENSE`.
