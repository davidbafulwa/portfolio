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
- **Nouveautés** — apports récents de SILIMU (billet de fidélité, confirmation
  d'e-mail des comptes, fiabilisation des envois, correction d'une erreur 500)
- **Contact** — formulaire `mailto:` + coordonnées

## Chiffres annoncés sur la page

Les compteurs de la section « Statistiques » sont volontairement taken sur des
valeurs vérifiables et non fragiles : 1 application en production, 238 tests
automatisés, 10 lignes lacustres couvertes, 7 ports desservis.

Les nb de traversées programmées changent tous les jours, puisque le serveur
replanifie les départs en continu : les afficher donnerait un chiffre faux dès le
lendemain.

## À jour au 1ᵉʳ octobre 2026

- Django **5.2**, pas 4.x.
- Base de données : **SQLite** en exploitation. Le réglage PostgreSQL est écrit et
  prêt pour un hébergement, mais n'est pas actif — le projet Supabase annoncé
  précédemment n'a jamais été créé, l'affirmation a donc été retirée.
- Tailwind CSS est chargé par CDN sur SILIMU (et non compilé), tandis que ce
  portfolio est entièrement autonome.

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