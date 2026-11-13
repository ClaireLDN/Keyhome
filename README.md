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

Les visuels de la démo sont des aplats de couleur, sans photo. Aucune photo n'est fournie dans ce repo.

## Licence

MIT, voir `LICENSE`.
