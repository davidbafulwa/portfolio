# 🧑‍💻 Portfolio — Daniel Bafulwa

Site portfolio personnel de **Daniel Bafulwa**, développeur Django (Python), étudiant en
Licence Informatique (2ᵉ année).

**100 % autonome** : HTML + CSS + JavaScript écrits à la main, **aucune requête externe**
(rien ne charge depuis Internet). Il fonctionne :

- ouvert directement comme un fichier (`index.html`),
- avec un simple serveur local,
- ou hébergé où tu veux.

## Ce que ça change (zéro dépendance)

| Avant (CDN / hébergement) | Maintenant (autonome) |
|---|---|
| Tailwind CSS via `cdn.tailwindcss.com` | CSS écrit à la main (aucun téléchargement) |
| Polices Google Fonts | Polices système de l'appareil |
| Formulaire Netlify (besoin d'hébergement) | Formulaire `mailto:` — ouvre la messagerie du visiteur |

Aucune ressource ne charge depuis Internet : la page s'affiche même **sans connexion**.

## Sections

- **Accueil** — présentation, technologies clés
- **Statistiques** — chiffres clés du projet phare
- **À propos** — bio + parcours (formation, projet tutoré)
- **Compétences** — backend, données & API, frontend & outils
- **Projets** — SILIMU (réservation de transport lacustre) avec captures d'écran
- **Contact** — formulaire `mailto:` + coordonnées

## Ouvrir le site

```bash
python3 -m http.server 8000
# ou double-cliquer sur index.html
```

## Personnalisation

- Coordonnées à mettre à jour dans « Contact » : `davidbafulwa@gmail.com`, la localisation et le compte GitHub.
- Université/école à renseigner dans la section **Parcours** si souhaité.
- Captures d'écran du projet dans `images/` (générées depuis l'application réelle).
- Fichier de déploiement Netlify éventuel : `netlify.toml` (facultatif, ignoré en local).