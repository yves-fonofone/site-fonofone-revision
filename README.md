# Site Fonofone — version révisée

Site statique (HTML + CSS, sans JavaScript) construit par **Jekyll**, le générateur intégré à GitHub Pages.

## Organisation

| Dossier / fichier | Contenu |
|---|---|
| `index.html` et les autres `.html` | Pages du site (en-tête `---` + contenu) |
| `_activites/` | **Une fiche d'activité par fichier `.md`** |
| `modeles/activite.md` | Modèle à copier pour une nouvelle activité |
| `_layouts/` | Gabarits : `default` (en-tête + pied de page), `page`, `activite` |
| `_includes/` | Morceaux réutilisés : menu, pied de page, tuiles d'activités |
| `_data/menu.yml` | Liens du menu principal |
| `style.css` | Toute la mise en forme |
| `images/`, `documents/` | Images et PDF |

## Créer une activité

Voir la page **Créer une activité** du site, ou : *Add file → Create new file* dans `_activites/`, puis copier `modeles/activite.md`.

## Mise en ligne

*Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`*.
Le site est alors publié à `https://yves-fonofone.github.io/site-fonofone-revision/`.
